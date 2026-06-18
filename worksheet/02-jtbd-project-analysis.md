---

## artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** Arionear (C2-App-040) — *Closer to Publication*

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. `**Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. `**Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
  `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. `**Project slice` + market context**
2. `**Job executor` + `core JTBD`**
3. **3 `job stories`**
4. `**JTBD lite map` + pain points**
5. `**AI leverage point` + `product hypothesis`**
6. `**Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- **1 nhóm người dùng chính**
- **1 hoàn cảnh / tình huống rõ**
- **1 job cốt lõi**
- **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm là:** Arionear — nền tảng Assisted Editing giúp researcher cải thiện bản thảo LaTeX học thuật với AI (Ario), có Human Gate diff + guardrail chống fabrication
- **Lát cắt tôi chọn để phân tích hôm nay là:** Graduate student / postdoc đang chỉnh sửa bản thảo LaTeX **trước deadline nộp journal** — cần polish văn phong + kiểm tra citation mà không làm sai lệch ý nghĩa khoa học
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là workflow MVP đã code (editor + style agent + citation verifier + diff gate). Không phân tích "sinh bài từ ý tưởng" (Arionear cố ý không làm) hay peer-review response (P2) — tránh viết quá rộng.

### Viết quá rộng vs viết sắc hơn


| Viết quá rộng                        | Viết sắc hơn                                                                                          |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| Giúp researcher dùng AI viết bài báo | Giúp postdoc polish văn phong + verify citation trên bản thảo LaTeX có sẵn trước deadline nộp journal |
| Dùng AI để làm slide                 | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn                           |
| AI cho tuyển dụng                    | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ                                     |


> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**
  > Researcher mất nhiều thời gian chỉnh văn phong học thuật, kiểm tra trích dẫn và sửa LaTeX — đồng thời lo AI generic (ChatGPT) sẽ bịa số liệu hoặc thay đổi claim khoa học nếu dùng không kiểm soát.
2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**
  > Nhà nghiên cứu (graduate student, postdoc, young faculty) đang soạn bản thảo tiếng Anh dạng LaTeX, chuẩn bị nộp journal/conference.
3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**
  > Overleaf + tự sửa tay; hỏi ChatGPT/Copilot (copy-paste đoạn văn, mất context); nhờ đồng nghiệp/biên tập viên đọc; Grammarly (không hiểu học thuật); kiểm tra DOI thủ công trên Google Scholar/CrossRef.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**
  > Graduate student / postdoc viết paper tiếng Anh, thường không phải native speaker, deadline journal gấp, ít kinh nghiệm biên tập học thuật chuyên nghiệp.
2. **Vấn đề xuất hiện trong hoàn cảnh nào?**
  > Sau khi có draft Methods/Results xong, trước 1–2 tuần deadline nộp — cần polish toàn bộ manuscript (intro, abstract, discussion) + đảm bảo citations đúng format và tồn tại thật.
3. **Hiện tại họ đang dùng giải pháp thay thế nào?**
  > Overleaf (soạn + compile); ChatGPT/Claude (copy-paste từng đoạn, không có guardrail); Grammarly Premium; đồng nghiệp đọc feedback; kiểm tra DOI thủ công; thuê language editing service ($200–500/paper).
4. **Vì sao đây là thời điểm đáng giải?**
  > 84% dev/researcher dùng AI tools (Stack Overflow Survey 2024) — nhưng generic AI không có guardrail học thuật, gây lo ngại fabrication. Journal ngày càng yêu cầu AI disclosure. Cần công cụ "AI editor" trong workflow LaTeX, không phải chatbot tách rời manuscript.

### Tóm tắt market context trong 3-4 dòng

> Thị trường: researcher non-native English đang polish bản thảo LaTeX trước deadline nộp journal. Họ đã thử ChatGPT nhưng sợ AI thay đổi claim/số liệu; Overleaf không có AI editing có guardrail; language editing service đắt và chậm. Thời điểm đáng giải vì AI adoption cao nhưng thiếu công cụ "assisted editing" hiểu ngữ cảnh manuscript + có human gate — đúng khoảng trống Arionear nhắm tới.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Graduate student / postdoc đang trực tiếp soạn và chỉnh sửa bản thảo LaTeX của mình
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người ngồi trong editor, bôi đen đoạn cần sửa, Accept/Reject diff, và chịu trách nhiệm nộp bài. PI/advisor có thể influence nhưng không phải daily user. Language editing service là outsourced alternative, không phải executor.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`
- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  

> Cải thiện chất lượng bản thảo học thuật bằng AI editor trong LaTeX workspace trước khi nộp journal

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: AI editor, LaTeX workspace

### Bản chốt

**Core JTBD cuối cùng:**  

> **Nâng chất lượng bản thảo học thuật (văn phong, cấu trúc, trích dẫn) để sẵn sàng nộp tạp chí — mà không làm sai lệch ý nghĩa khoa học hay số liệu gốc**

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories


| #   | Trigger / When                                                                         | Motivation / I want to                                                             | Outcome / so I can                                                                                  | Điều story này cho thấy                                                                       |
| --- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| JS1 | Khi tôi bôi đen một đoạn Discussion viết vội, ngữ pháp lủng củng trước deadline 5 ngày | Tôi muốn có bản chỉnh văn phong học thuật chuẩn mà **giữ nguyên claim và số liệu** | So I can nộp bài mà không sợ reviewer bắt lỗi language hoặc AI đã thay đổi kết quả                  | Product xuất hiện ở **Quick Edit + Style Agent + diff gate** — user phải Accept từng thay đổi |
| JS2 | Khi tôi hoàn thành draft và cần kiểm tra 40+ citations trong `.bib` trước nộp          | Tôi muốn biết citation nào broken/mismatch mà không phải mở từng DOI trên browser  | So I can fix BibTeX nhanh và tránh embarrassment khi reviewer phát hiện reference giả               | Product xuất hiện ở **Citation Verifier** (arXiv → CrossRef → Semantic Scholar)               |
| JS3 | Khi LaTeX compile fail lúc 2h sáng, log lỗi dài và khó hiểu                            | Tôi muốn hiểu lỗi và có gợi ý sửa ngay trong ngữ cảnh file đang mở                 | So I can compile thành công PDF mà không phải tab-out sang Stack Overflow hay ChatGPT (mất context) | Product xuất hiện ở **"Ask Ario to fix"** với compile log + full manuscript context           |


### Tự kiểm nhanh

- Mỗi story là một **tình huống thật**, không phải slogan chung chung
- 3 story không trùng hệt nhau
- Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives


| Alternative hiện tại                           | User đang thuê nó để làm gì?                | Nó làm tốt gì?                                         | Nó fail ở đâu?                                                                                            | Switching cost hiện tại cao hay thấp?                       |
| ---------------------------------------------- | ------------------------------------------- | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| Alt 1: ChatGPT / Claude (copy-paste)           | Polish văn phong, hỏi cấu trúc, debug LaTeX | Nhanh, free/cheap, đa năng                             | Không có manuscript context; không guardrail — có thể bịa số liệu/thay claim; user phải tự so sánh output | **Thấp** — đã quen, chỉ cần mở tab mới                      |
| Alt 2: Overleaf + tự sửa tay                   | Soạn LaTeX, compile PDF, collaborate        | Workflow chuẩn cộng đồng; compile ổn; real-time collab | Không có AI editing; không citation verify; polish language chậm                                          | **Trung bình** — project đã ở Overleaf, migrate có friction |
| Alt 3: Language editing service (AJE, Editage) | Professional polish toàn bộ manuscript      | Chất lượng cao, reviewer-trusted                       | Đắt ($200–500); chậm (3–7 ngày); không tích hợp LaTeX workflow; không verify citation real-time           | **Cao** — đã trả tiền, chờ kết quả                          |


### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  

> ChatGPT copy-paste từng đoạn (vì free + instant) kết hợp Overleaf để compile — chấp nhận rủi ro AI thay đổi claim vì không có alternative tốt hơn ở mức giá 0.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map


| Step     | Trong workflow này user đang cố làm gì?                                           | Hôm nay họ đang dùng gì?                                                 | Friction / pain hiện tại                                                          | Mức đau  |
| -------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | -------- |
| Define   | Xác định section nào cần polish trước (abstract? discussion? toàn bộ?)            | Tự đọc lại draft, hỏi advisor, hoặc theo journal checklist               | Không có framework ưu tiên — user không biết bắt đầu từ đâu khi còn 5 ngày        | Med      |
| Locate   | Tìm đoạn văn / citation / lỗi LaTeX cần sửa trong manuscript dài                  | Scroll trong Overleaf; Ctrl+F; outline thủ công                          | Manuscript 6000+ từ, khó locate weak paragraph hoặc broken cite key               | Med      |
| Prepare  | Chuẩn bị context để gửi cho AI hoặc editor (copy đoạn + surrounding context)      | Copy-paste từng đoạn sang ChatGPT; hoặc gửi cả file cho language service | Mất context khi copy-paste; ChatGPT không thấy `.bib`, figures, toàn bộ structure | **High** |
| Confirm  | Xác nhận suggestion không thay đổi ý nghĩa khoa học trước khi apply               | Đọc lại thủ công từng câu AI suggest; so sánh side-by-side trong 2 tab   | Tốn thời gian; dễ miss subtle change (số liệu, claim); không có diff view chuẩn   | **High** |
| Execute  | Apply thay đổi vào bản thảo LaTeX                                                 | Paste lại vào Overleaf; hoặc accept track changes từ editor service      | LaTeX syntax dễ break khi paste; formatting bị mất; phải compile lại nhiều lần    | Med      |
| Monitor  | Kiểm tra kết quả sau khi sửa (compile OK? citation còn đúng? meaning giữ nguyên?) | Compile PDF; đọc lại; chạy citation check thủ công                       | Không có automated integrity check; user phải tự phát hiện regression             | Med      |
| Modify   | Iteratively sửa lại nếu suggestion chưa đúng                                      | Quay lại ChatGPT hỏi lại; hoặc email editor service                      | Mất context giữa các vòng; không có revision history gắn với từng đoạn            | Med      |
| Conclude | Export final PDF + BibTeX, sẵn sàng submit journal portal                         | Overleaf compile → download PDF; upload lên journal                      | N/A nếu các bước trên đã OK — bước này ít pain nếu manuscript sạch                | Low      |


### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Prepare — mất context khi copy-paste sang AI generic, không có full manuscript + `.bib` trong một workspace  
**Bước đau nhất #2:** Confirm — không có cách nhanh để verify AI suggestion không thay đổi claim/số liệu; so sánh thủ công 2 tab rất chậm

**Vì sao đây là nơi đáng chú ý nhất:**  

> Đây chính xác là khoảng trống Arionear lấp: editor có full LaTeX context + diff gate (L3) + integrity check (L2). Generic ChatGPT mạnh ở Execute (viết nhanh) nhưng fail ở Prepare và Confirm — hai bước quan trọng nhất với academic integrity.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point


| Step              | AI nên giúp bằng cách nào?                                                                                                                                                                     | Vì sao AI hợp ở đây?                                                                                                                            | Rủi ro chính nếu dùng AI                                                                |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Prepare + Confirm | Style Agent đọc **selection + surrounding LaTeX + `.bib` context** → đề xuất polish qua **inline diff**; Integrity Monitor (L2) check numeric drift + semantic containment trước khi show diff | AI hiểu ngữ cảnh manuscript — điều ChatGPT copy-paste không làm được; diff + Accept/Reject giải pain Confirm; guardrail giải rủi ro fabrication | LLM vẫn có thể subtly paraphrase làm lệch claim; L2 threshold cần calibrate theo domain |
| Locate + Monitor  | Citation Verifier batch-check toàn bộ cite keys; Structure Analyzer flag section imbalance; compile error → "Ask Ario to fix" với log context                                                  | Deterministic checks (L1–3 citation) không hallucinate; LLM chỉ dùng cho advisory structure/fix suggestion                                      | Citation L4 (LLM relevance) chưa có — có thể miss "cite đúng nhưng không support claim" |


### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  

> **Prepare → Confirm loop trong editor:** AI đọc full manuscript context, đề xuất thay đổi qua diff có guardrail, user Accept/Reject từng đoạn — thay thế workflow "copy-paste ChatGPT → so sánh thủ công 2 tab".

**Vì sao không phải ở bước khác:**  

> Define/Locate: user judgment, AI chỉ advisory (structure suggestions). Execute: LaTeX compile là deterministic, không cần LLM. Conclude: export PDF đã có. Pain thật nằm ở **chuẩn bị context + xác nhận an toàn** — không phải ở viết nhanh (ChatGPT đã làm tốt).

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **graduate student/postdoc** làm job **nâng chất lượng bản thảo học thuật** tốt hơn ở bước **Prepare + Confirm**,
> bằng cách **Style Agent với full LaTeX context + inline diff + integrity guardrail (L1–L3)**,
> thì họ sẽ chuyển từ **ChatGPT copy-paste + so sánh thủ công** sang **Arionear editor**,
> vì **họ polish nhanh hơn mà không phải lo AI thay đổi claim/số liệu — mọi thay đổi visible và reversible**.

### Tín hiệu sớm nếu hypothesis này đúng

1. User dùng Quick Edit / Style Agent ≥3 lần/session thay vì mở tab ChatGPT
2. Accept rate trên diff suggestions ≥60% (user tin suggestion đủ để apply, không reject hết vì sợ)

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions


| Assumption                                                | Vì sao assumption này rủi ro?                                             | Tôi đang có bằng chứng gì?                                 | Cần validate bằng cách nào tiếp theo?                               |
| --------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------- |
| A1: Job executor là postdoc/GS chỉnh LaTeX trước deadline | PI hoặc lab manager có thể là buyer thực sự; GS chỉ dùng free tier        | Team member là researcher; READMETEMP mô tả user flow      | Interview 5 GS/postdoc: "Ai quyết định tool? Ai ngồi sửa?"          |
| A2: Pain Prepare+Confirm đủ đau để đổi tool               | ChatGPT free đã "đủ tốt" cho nhiều người; họ chấp nhận rủi ro fabrication | Anecdotal từ team; chưa có user research                   | Survey: "Bạn lo gì nhất khi dùng ChatGPT sửa paper?" + frequency    |
| A3: User sẽ migrate từ Overleaf sang Arionear             | Overleaf có network effect (collab, templates); switching cost cao        | Arionear hỗ trợ import Overleaf ZIP                        | Track: bao nhiêu user import ZIP vs tạo mới; retention sau 1 tuần   |
| A4: Integrity guardrail (L2) đủ tin cậy                   | Threshold 0.85 có thể reject valid paraphrase hoặc miss subtle drift      | Code có `check_integrity()` + tests; chưa calibrate domain | Eval dataset 50 đoạn academic: measure false positive/negative rate |
| A5: User tin diff suggestion đủ để Accept                 | Nếu reject rate >80%, AI leverage point vô nghĩa                          | Có L4 revision log API; chưa đủ data production            | Analytics: accept/reject ratio per session; follow-up interview     |


### Assumption nguy hiểm nhất nếu tôi đang sai

> **A3: User sẽ không rời Overleaf** — nếu switching cost quá cao, Arionear chỉ là "nice demo" chứ không phải daily workflow tool. Cần validate sớm: plugin/extension trên Overleaf vs standalone editor.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện


| Ý phản biện tôi nghe được                                                         | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì?                                                                                                                                                |
| --------------------------------------------------------------------------------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| "JTBD của bạn có lẫn 'trích dẫn' — đó là job riêng hay sub-job?"                  | Core JTBD             | **Sửa nhẹ:** tách citation verify thành sub-job riêng trong job map (Locate/Monitor), Core JTBD giữ focus "nâng chất lượng bản thảo" bao quát                       |
| "ChatGPT đã free — vì sao user trả effort migrate sang Arionear?"                 | Alternative + A3      | **Giữ** hypothesis nhưng thêm: giá trị chính là **trust + context**, không phải speed — cần validate A2                                                             |
| "Prepare+Confirm đau nhưng AI có giải được Confirm không? User vẫn phải đọc diff" | AI leverage point     | **Giữ** — diff giảm cognitive load vs 2-tab compare; integrity flag tự động highlight risk thay vì user tự tìm                                                      |
| "Nếu không dùng AI, Arionear còn giá trị không?" (câu khó từ Lab 1 pattern)       | Toàn bộ hypothesis    | **Thành thật:** không — editor + compile + citation verify deterministic vẫn có giá trị, nhưng **không đủ moat** vs Overleaf. AI + guardrail mới là differentiation |


---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- Giữ nguyên `job executor`
- Sửa `job executor`
- Giữ nguyên `core JTBD`
- Sửa `core JTBD`
- Giữ nguyên `AI leverage point`
- Sửa `AI leverage point`
- Giữ nguyên `product hypothesis`
- Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Giữ nguyên executor, JTBD, leverage point và hypothesis. Phản biện bàn làm rõ: (1) citation là sub-job trong map, không cần sửa Core JTBD; (2) moat thật là trust+context, không phải speed — đã reflect trong hypothesis; (3) nếu không có AI, product yếu vs Overleaf — đây là risk cần ghi trong A3, không phải lý do đổi JTBD.

### Version cuối cùng tôi nộp

**Job executor:**  

> Graduate student / postdoc đang trực tiếp soạn và chỉnh sửa bản thảo LaTeX của mình trước deadline nộp journal

**Core JTBD:**  

> Nâng chất lượng bản thảo học thuật (văn phong, cấu trúc, trích dẫn) để sẵn sàng nộp tạp chí — mà không làm sai lệch ý nghĩa khoa học hay số liệu gốc

**2 bước đau nhất trong workflow:**  

> 1. **Prepare** — mất context khi copy-paste sang AI generic
> 2. **Confirm** — không có cách nhanh verify suggestion không thay đổi claim/số liệu

**AI leverage point chính:**  

> Prepare → Confirm loop: Style Agent + full LaTeX context + inline diff + integrity guardrail (L1–L3) — thay workflow ChatGPT copy-paste + so sánh thủ công

**Product hypothesis:**  

> Nếu giúp postdoc polish manuscript ở bước Prepare+Confirm bằng contextual diff có guardrail, họ chuyển từ ChatGPT sang Arionear vì polish nhanh hơn mà không lo fabrication — mọi thay đổi visible và reversible

**Assumption cần validate đầu tiên:**  

> **A3:** User có chịu migrate từ Overleaf không — nếu switching cost quá cao, cả hypothesis sập dù AI leverage point đúng

---

## Checklist trước khi nộp

- Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- Tôi đã phân biệt được `job executor` với buyer / influencer.
- `Core JTBD` của tôi không nhét solution vào câu.
- Tôi đã viết đủ 3 `job stories`.
- Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- Tôi đã ghi rõ `assumptions to validate`.
- Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

### 1. Phỏng vấn nhanh 1 người dùng thật để kiểm job story

**Kế hoạch:** Hỏi 1 postdoc/GS trong lab hoặc cohort AI20K:


| Câu hỏi                                                             | Mục đích                     | Job story nào test                      |
| ------------------------------------------------------------------- | ---------------------------- | --------------------------------------- |
| "Lần gần nhất bạn sửa paper trước deadline, bạn làm gì đầu tiên?"   | Validate workflow thực       | JS1 vs JS2 — polish hay citation trước? |
| "Bạn có dùng ChatGPT sửa paper không? Lo gì nhất?"                  | Validate A2 (pain đủ đau)    | JS1 — fear of fabrication               |
| "Bạn có chịu chuyển từ Overleaf sang tool mới không? Điều kiện gì?" | Validate A3 (switching cost) | Migration assumption                    |


### 2. So sánh alternatives theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn


| Alternative               | Nhanh hơn?             | Rẻ hơn?                  | Tin hơn (academic integrity)?   |
| ------------------------- | ---------------------- | ------------------------ | ------------------------------- |
| ChatGPT copy-paste        | ✅ Rất nhanh            | ✅ Free                   | ❌ Không guardrail               |
| Overleaf + tự sửa         | ❌ Chậm (polish tay)    | ✅ Free tier              | ✅ User kiểm soát 100%           |
| Language editing service  | ❌ 3–7 ngày             | ❌ $200–500               | ✅ Professional, trusted         |
| **Arionear (hypothesis)** | ✅ Nhanh (AI) + context | ✅ Free tier (OpenRouter) | ✅ Diff + guardrail + human gate |


**Kết luận:** Arionear chỉ thắng nếu **tin hơn ChatGPT** ở mức tương đương **nhanh hơn Overleaf** — đúng positioning "assisted editing with integrity", không compete speed với ChatGPT.

### 3. Nếu không dùng AI, project này còn tạo giá trị không?


| Thành phần không cần AI              | Giá trị còn lại                                 | Đủ moat vs Overleaf?               |
| ------------------------------------ | ----------------------------------------------- | ---------------------------------- |
| LaTeX editor + multi-file            | Có — nhưng Overleaf tốt hơn (collab, templates) | ❌ Không                            |
| PDF compile + SyncTeX                | Có — tiện                                       | ❌ Overleaf có                      |
| Citation verify (deterministic L1–3) | Có — unique                                     | ⚠️ Một phần — có thể làm extension |
| Diff gate UI                         | Có — nhưng cần content để diff                  | ❌ Không standalone                 |


**Kết luận thành thật:** Không có AI, Arionear **không đủ moat** để kéo user rời Overleaf. Giá trị differentiation nằm ở **AI + guardrail + context trong editor** — đúng leverage point đã chọn. Nếu AI layer yếu hoặc user không tin guardrail, project cần pivot (ví dụ: Overleaf plugin thay vì standalone editor).

### 4. Expectation shift từ Lab 1 áp dụng cho Arionear


| Bài học Stack Overflow (Lab 1)             | Áp dụng cho Arionear                                                                         |
| ------------------------------------------ | -------------------------------------------------------------------------------------------- |
| Entry point chuyển vào workflow (IDE)      | Arionear đặt AI **trong editor LaTeX**, không tách chatbot — đúng hướng                      |
| Generic AI "đủ tốt" xóa sổ phân khúc basic | ChatGPT free có thể xóa sổ "polish đơn giản" — Arionear phải thắng ở **integrity + context** |
| Moat cũ (network effect) không cứu được    | Overleaf network effect mạnh — Arionear không compete collab, compete **trust layer**        |
| Đừng bolt AI lên entry point cũ            | OverflowAI trên website = sai; Arionear embed AI trong editor = đúng pattern Copilot         |


