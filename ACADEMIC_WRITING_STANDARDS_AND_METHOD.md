---
name: academic-writing-standards
description: >
  Reusable standards and working method for writing and revising academic
  manuscripts (journal articles and reviews) in English. Enforces an
  anti-"AI-tell" writing style, citation integrity, scientific-honesty rules,
  and figure/table/heading conventions. Trigger when drafting, revising, or
  auditing a manuscript, a related-work / literature review, or figures and
  captions.
---

# Academic Writing Standards & Method

General, project-independent rules for writing and revising academic manuscripts
in English. Two parts:

1. **Writing standards** — how prose, headings, figures, tables, and citations
   must look.
2. **Working method** — how to respond, verify sources, and avoid overclaiming.

> How to use: paste into a new chat as context, or keep in the repo as the style
> contract. English version first; Vietnamese version below.

---

## Part 1 — Writing standards

### 1.1 Voice and tone
- Academic English in connected sentences with simple vocabulary.
- No first-person pronouns in prose: no *we*, *our*, *us*, *the reader*. Use
  impersonal or passive phrasing ("the proposed detector adapts…", "the
  evaluation compares…").
- No self-referential signposting ("this section evaluates/inspects/presents…").
  Make the subject the content ("The quantitative evaluation compares…"). One
  short roadmap sentence opening a subsection is acceptable.
- No generic claims, no formulaic wording, no repetitive sentence structures.
- Do not write very short sentences as a paragraph, and do not write paragraphs
  of only 1–2 sentences.

### 1.2 Forbidden words and phrases
Do not use in prose (replace with plain wording or delete):

- **Filler / AI-tells:** reflect, ensure, vague, together, explicit, implicit,
  robustness, robust, state, interpretation, heavily, substantial, substantially,
  plausible, rely, solely, adequately, inherently, evidence, effectively,
  essentially, clearly, notably, importantly, crucially, operationally,
  inconsistently.
- **Weak connectors / hedges:** because, rather than, "rather than relying
  exclusively", yet, "worth noting", "plays a key / crucial / vital / central
  role".
- **AI transition words:** Moreover, Furthermore, Conversely, Nonetheless,
  Hence, Additionally. Prefer *and*, *so*, *but*, *still*, or a new sentence.

> Sample replacements: clearly → distinctly; essentially → almost; nonetheless →
> still; "inconsistent between observers" → "subject to variation between
> observers"; "we adopt X" → "X is adopted".

### 1.3 Forbidden punctuation and patterns
- No em dashes (`---`) and no en dashes joining clauses. Use commas, parentheses,
  or split the sentence. (En dashes stay correct for numeric ranges, e.g. page or
  reference ranges.)
- No semicolons.
- No colon followed directly by a space used to introduce prose. (A colon before
  a displayed equation or a formal list is fine.)
- No comma followed directly by a present participle ("…, using X", "…, showing
  Y"). Rewrite as two clauses.
- No arbitrary bold in prose. Bold only where a format requires it (table
  headers, CRediT labels, defined-term leads).

### 1.4 Paragraph and structure
- No inductive "result-first, justify-after" pattern: do not open a paragraph
  with the conclusion and then explain "because… so…". Lead with the observation
  or data, then the conclusion.
- No bullet or numbered lists inside prose. Convert to flowing sentences.
  (Highlights, table notes, and required submission lists are exempt.)
- IMRaD for research papers: Introduction (may fold in related work) → Materials
  and methods → Results and discussion → Conclusions → back matter.
- Do not begin a section with a table or figure; introduce it with text first.

### 1.5 Headings
- Sentence case, not Title Case.
- No abbreviations in headings (spell out at first use).
- Number sections 1, 1.1, 1.1.1. Do not number the abstract. Cross-reference by
  number, never "the text above/below".

### 1.6 Figures and tables
- Every figure and table is cited in the text and numbered by order of appearance.
- No two figures/tables back-to-back with no text between them; no figure left
  alone on an otherwise empty page.
- Caption = short bold title + description; keep detail in the prose, define each
  abbreviation once.
- Numbers and labels inside a figure must be legible; no leftover internal
  code-names.
- Tables: editable text (never an image), no vertical rules, no cell shading,
  notes below the table body, must fit the text width.
- Center figures and tables (small tables look intentional when centered).
- Legend colours must match what actually appears; a legend entry with no
  corresponding mark is an error.

### 1.7 Citations and references
- Numeric citations in square brackets: `[7]`, `[12]–[14]`. Number references in
  order of first appearance. Naming authors in text is fine, but always give the
  number ("Barnaby and Jones [8] obtained…").
- No web links inside manuscript paragraphs. URLs live only in the reference list.
- Reference-list format (Elsevier numbered example): author initials first,
  article title plain, journal abbreviated per LTWA, `vol (year) pages`, DOI as
  `https://doi.org/…`. Mark preprints ("arXiv preprint") and datasets
  (`[dataset]`).
- Remove reference-manager field codes before final submission; plain-text `[n]`
  plus a numbered list is the accepted final form.
- References cited in the abstract are given in full.

### 1.8 Scientific integrity (no overclaiming)
- A visual/model label identifies a symptom or category; it does not confirm a
  causal organism unless an appropriate reference standard was used (expert
  diagnosis, culture isolation, PCR, ELISA).
- High accuracy on a controlled collection is not proof of field performance,
  early detection, severity estimation, or deployment readiness.
- One correct output does not prove another: correct identification does not
  prove correct severity, and correct area/count estimation does not prove
  correct identification.
- Report biological and acquisition variation, and distinguish controlled
  internal testing, internal field-origin testing, independent testing after
  model lock, and operational demonstration without reference labels.
- Do not present a cloud application as a local/on-device system merely because
  it has a mobile user interface.
- State honest limitations (data-leakage risk, un-measured conditions,
  tool-dependent numbers) rather than hiding them.

---

## Part 2 — Working method

### 2.1 Response granularity
- Asked for a paragraph → return only that paragraph, no preamble, unless further
  explanation is requested.
- Asked for a connection between two paragraphs → return one bridge sentence only.
- Asked to fix grammar → make the smallest possible correction.
- Ask a question only when a missing decision would materially change the content.

### 2.2 Literature and citation verification
- Prefer peer-reviewed primary sources.
- For every source, verify it exists, the title and DOI are correct, and it
  supports the exact claim it is cited for.
- Do not put unpublished results or personal communications in the reference
  list; they may be mentioned in text.

### 2.3 Reporting experimental / deployment results
- Report the positive configuration and result for each study first. Do not
  repeat "the study did not report…" after every entry; consolidate missing
  information once, later, in a dedicated discussion.
- Compare only configurations that hold the relevant variables fixed (model,
  runtime/compiler, precision, input size, batch size, thread/accelerator
  setting, timing boundary). Explain why non-comparable numbers cannot form a
  single ranking.
- Keep distinct measures distinct: model-file size vs flash vs activation RAM vs
  peak process RAM; whole-system power vs component-only power; model-only vs
  accelerator-only vs end-to-end vs pipeline timing.

---
---

# Chuẩn viết & phương pháp học thuật (Tiếng Việt)

Quy tắc chung, không phụ thuộc bài cụ thể, dùng để viết và chỉnh sửa bản thảo học
thuật (bài báo và bài review) bằng tiếng Anh. Gồm hai phần: (1) Quy chuẩn viết,
(2) Phương pháp làm việc.

> Cách dùng: dán vào chat mới làm ngữ cảnh, hoặc để trong repo làm "hợp đồng văn
> phong". Bản tiếng Anh ở trên, bản tiếng Việt ở đây.

---

## Phần 1 — Quy chuẩn viết

### 1.1 Giọng văn
- Tiếng Anh học thuật, câu liền mạch, từ vựng đơn giản.
- KHÔNG đại từ nhân xưng trong prose: không *we*, *our*, *us*, *the reader*. Dùng
  câu bị động/vô nhân xưng ("the proposed detector adapts…", "the evaluation
  compares…").
- KHÔNG câu dẫn tự quy chiếu ("this section evaluates/inspects/presents…"). Cho
  chủ ngữ là nội dung ("The quantitative evaluation compares…"). Một câu roadmap
  ngắn mở đầu tiểu mục thì chấp nhận.
- KHÔNG khẳng định chung chung, KHÔNG lối viết công thức/lặp cấu trúc.
- KHÔNG viết câu quá ngắn thành một đoạn, và KHÔNG viết đoạn chỉ 1–2 câu.

### 1.2 Từ và cụm cấm
Không dùng trong prose (thay bằng từ mộc hoặc bỏ):

- **Từ đệm / lộ AI:** reflect, ensure, vague, together, explicit, implicit,
  robustness, robust, state, interpretation, heavily, substantial, substantially,
  plausible, rely, solely, adequately, inherently, evidence, effectively,
  essentially, clearly, notably, importantly, crucially, operationally,
  inconsistently.
- **Connector yếu / rào đón:** because, rather than, "rather than relying
  exclusively", yet, "worth noting", "plays a key/crucial/vital/central role".
- **Từ chuyển ý kiểu AI:** Moreover, Furthermore, Conversely, Nonetheless, Hence,
  Additionally. Ưu tiên *and*, *so*, *but*, *still*, hoặc tách câu mới.

> Ví dụ thay: clearly → distinctly; essentially → almost; nonetheless → still;
> "inconsistent between observers" → "subject to variation between observers";
> "we adopt X" → "X is adopted".

### 1.3 Dấu câu và pattern cấm
- KHÔNG em dash (`---`) và không en dash để nối mệnh đề. Dùng phẩy, ngoặc, hoặc
  tách câu. (En dash vẫn đúng cho khoảng số, ví dụ khoảng trang hay khoảng
  reference.)
- KHÔNG chấm phẩy (semicolon).
- KHÔNG dấu hai chấm + khoảng trắng để mở prose. (Dấu hai chấm trước công thức
  hiển thị hoặc danh sách chính thức thì được.)
- KHÔNG dấu phẩy đi ngay với hiện tại phân từ ("…, using X", "…, showing Y").
  Viết lại thành hai mệnh đề.
- KHÔNG in đậm tùy tiện trong prose. Chỉ bold ở chỗ format bắt buộc (đầu bảng,
  nhãn CRediT, từ định nghĩa).

### 1.4 Đoạn văn và cấu trúc
- KHÔNG lối "kết quả trước, giải thích sau": đừng mở đoạn bằng câu chốt rồi mới
  "vì… nên…". Dẫn từ quan sát/số liệu → kết luận.
- KHÔNG liệt kê gạch đầu dòng/đánh số trong prose. Viết thành câu văn xuôi.
  (Highlights, ghi chú bảng, và danh sách bắt buộc khi nộp thì miễn.)
- IMRaD cho bài nghiên cứu: Introduction (có thể gộp related work) → Materials and
  methods → Results and discussion → Conclusions → back matter.
- KHÔNG mở đầu section bằng bảng/hình; phải có text giới thiệu trước.

### 1.5 Heading
- Sentence case, không Title Case.
- Không viết tắt trong heading (viết đủ ở lần đầu).
- Đánh số mục 1, 1.1, 1.1.1. Không đánh số abstract. Tham chiếu chéo bằng số,
  không nói "phần trên/dưới".

### 1.6 Hình và bảng
- Mọi hình/bảng đều được trích trong text và đánh số theo thứ tự xuất hiện.
- Không đặt 2 hình/bảng liền nhau không có text xen giữa; không để hình đứng trơ
  một mình trên trang trống.
- Caption = tiêu đề ngắn in đậm + mô tả; chi tiết để trong prose, mỗi viết tắt
  định nghĩa một lần.
- Số/nhãn trong hình phải đọc được; không để tên code nội bộ sót lại.
- Bảng: text chỉnh sửa được (không phải ảnh), không kẻ dọc, không tô nền ô, ghi
  chú đặt dưới thân bảng, không tràn khung.
- Căn giữa hình và bảng (bảng nhỏ căn giữa nhìn chủ đích hơn).
- Màu trong legend phải khớp cái thực sự có trong hình; mục legend không có ký
  hiệu tương ứng là lỗi.

### 1.7 Trích dẫn và tài liệu tham khảo
- Trích dẫn dạng số trong ngoặc vuông: `[7]`, `[12]–[14]`. Đánh số reference theo
  thứ tự xuất hiện. Có thể nêu tên tác giả trong câu nhưng luôn kèm số ("Barnaby
  and Jones [8] obtained…").
- Không để link web trong đoạn văn bản; URL chỉ nằm ở danh mục reference.
- Format danh mục (kiểu Elsevier đánh số): tên viết tắt đứng trước, tên bài
  thường, tên tạp chí viết tắt theo LTWA, `vol (year) pages`, DOI dạng
  `https://doi.org/…`. Đánh dấu preprint ("arXiv preprint") và dataset
  (`[dataset]`).
- Bỏ field code của phần mềm quản lý trích dẫn trước khi nộp bản cuối; text thuần
  `[n]` + danh mục đánh số là dạng cuối được chấp nhận.
- Reference trích trong abstract phải ghi đầy đủ.

### 1.8 Liêm chính khoa học (không overclaim)
- Nhãn thị giác/mô hình chỉ nhận diện triệu chứng/loại; không xác nhận tác nhân
  gây bệnh trừ khi có chuẩn tham chiếu phù hợp (chẩn đoán chuyên gia, phân lập
  nuôi cấy, PCR, ELISA).
- Độ chính xác cao trên tập ảnh có kiểm soát không chứng minh hiệu năng ngoài
  đồng, phát hiện sớm, ước lượng mức độ, hay sẵn sàng triển khai.
- Một kết quả đúng không chứng minh kết quả khác: nhận diện đúng không chứng minh
  ước lượng mức độ đúng, và ước lượng diện tích/đếm đúng không chứng minh nhận
  diện đúng.
- Báo cáo biến thiên sinh học và điều kiện thu ảnh; phân biệt test nội bộ có kiểm
  soát, test nguồn-ngoài-đồng nội bộ, test độc lập sau khi khóa mô hình, và trình
  diễn vận hành không có nhãn tham chiếu.
- Không trình bày ứng dụng cloud như hệ thống local/on-device chỉ vì nó có giao
  diện di động.
- Nêu hạn chế trung thực (nguy cơ rò rỉ dữ liệu, điều kiện chưa đo, số liệu phụ
  thuộc công cụ) thay vì che giấu.

---

## Phần 2 — Phương pháp làm việc

### 2.1 Độ chi tiết khi trả lời
- Hỏi một đoạn → trả đúng một đoạn, không rào đón, trừ khi được yêu cầu giải
  thích thêm.
- Hỏi câu nối giữa hai đoạn → trả đúng một câu bridge.
- Hỏi sửa ngữ pháp → sửa nhỏ nhất có thể.
- Chỉ hỏi lại khi thiếu một quyết định sẽ làm thay đổi nội dung một cách đáng kể.

### 2.2 Kiểm chứng tài liệu và trích dẫn
- Ưu tiên nguồn sơ cấp bình duyệt.
- Với mỗi nguồn: kiểm nó có thật, tiêu đề và DOI đúng, và nó hỗ trợ đúng claim mà
  nó được trích.
- Không đưa kết quả chưa công bố hay trao đổi cá nhân vào danh mục reference; có
  thể nhắc trong text.

### 2.3 Báo cáo kết quả thực nghiệm / triển khai
- Báo cáo cấu hình và kết quả tích cực của từng nghiên cứu trước. Đừng lặp "the
  study did not report…" sau mỗi mục; gom thông tin còn thiếu lại một lần, ở phần
  thảo luận riêng.
- Chỉ so sánh các cấu hình giữ cố định các biến liên quan (mô hình,
  runtime/compiler, precision, input size, batch size, thread/accelerator, ranh
  giới đo thời gian). Giải thích vì sao các số không so sánh được không thể xếp
  thành một bảng thứ hạng.
- Giữ các phép đo tách bạch: kích thước file mô hình vs flash vs activation RAM vs
  peak process RAM; công suất toàn hệ vs công suất riêng linh kiện; thời gian
  model-only vs accelerator-only vs end-to-end vs pipeline.
