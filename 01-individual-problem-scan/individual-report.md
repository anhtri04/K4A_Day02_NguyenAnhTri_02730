# 01 — Individual Problem Scan

## Thông tin cá nhân

* Họ và tên: Nguyễn Anh Trí
* Mã học viên: 2730
* Vai trò / bối cảnh: Backend Developer / AI Engineering, định hướng Software Architecture, Cloud và AI Agent
* Công việc/hoạt động thường gặp: phát triển backend, học và thử nghiệm AI/LLM/Agent, tìm hiểu AWS và system architecture, làm các project cá nhân về trading/finance, sử dụng Linux/Omarchy, đạp xe và theo dõi dữ liệu tập luyện.

## Vai trò của tôi trong team

Trong team, tôi giữ vai trò **Team Lead**. Tôi chủ động tìm problem, đưa problem vào thảo luận và chịu trách nhiệm chính trong việc bảo vệ tại sao problem đó đáng để team đào sâu.

Tuy nhiên, tôi không xem việc lead là quyết định thay cho các thành viên khác. Tôi tập trung vào việc đưa ra lập luận, đặt câu hỏi và tạo điều kiện để mọi người challenge lẫn nhau. Với những candidate problem khác, tôi cùng team phân tích actor, workflow, evidence, feasibility và khả năng prototype để xác định vì sao một hướng phù hợp hơn hướng khác.

Tôi cũng đóng vai trò kết nối các thành viên. Khi mỗi người đưa ra một problem khác nhau, tôi giúp gom các ý tưởng có cùng pattern, làm rõ điểm chung và đưa discussion từ “solution nào nghe hay hơn” về “problem nào đáng giải quyết hơn”.

---

## Phase 1 — Scan vấn đề

| # | Lăng kính                          | Problem quan sát được                                                                                                                                               | Ai chịu ảnh hưởng?                             | Dấu hiệu thật / research ngắn                                                                                                                                                                            |
| - | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 | Lặp lại + tốn thời gian            | Khi làm việc với code, developer có thể push code lên để senior review nhưng vẫn còn lỗi format, test, convention hoặc thiếu checklist cơ bản.                      | Intern, junior developer và senior reviewer.   | Đây là workflow tôi thường gặp khi làm software. Một phần review có thể được tự động kiểm tra trước khi bàn giao, nhưng cần xác định đâu là lỗi machine-checkable và đâu vẫn cần senior judgement.       |
| 2 | Lặp lại + tốn thời gian            | Khi học AI/LLM, thông tin nằm rải rác trong documentation, GitHub, paper, blog và video nên khó biết nên học gì trước và đâu là thông tin đáng tin.                 | Developer/AI engineer đang tự học.             | Tôi thường phải chuyển qua nhiều nguồn khi nghiên cứu một topic. Vấn đề không phải thiếu thông tin mà là context switching và khó xác định nguồn nào phù hợp với mục tiêu hiện tại.                      |
| 3 | Tốn thời gian + thông tin phân tán | Khi tìm hiểu AWS architecture, một problem thường liên quan đến nhiều service và trade-off; đọc từng documentation riêng lẻ khó hình thành architecture hoàn chỉnh. | Developer, cloud engineer, người học AWS.      | Một bài toán có thể liên quan đồng thời đến VPC, IAM, networking, storage, security và cost. Tôi thường phải vẽ lại architecture để kết nối các phần kiến thức.                                          |
| 4 | Lặp lại + tốn thời gian            | Dữ liệu trading/finance nằm ở nhiều nguồn khác nhau; để research một mã cổ phiếu phải kết hợp market data, news, company information và các tín hiệu khác.          | Nhà đầu tư cá nhân, người research thị trường. | Đây là workflow tôi quan tâm và từng làm project liên quan. Việc chuyển đổi giữa nhiều nguồn khiến research chậm và khó giữ context.                                                                     |
| 5 | Tốn thời gian                      | Khi một project AI có nhiều agent/tool, developer phải tự theo dõi context, tool call, intermediate result và failure để debug workflow.                            | AI engineer / developer xây agent system.      | Đây là pain tôi gặp trực tiếp khi nghiên cứu Agentic Workflow. Debug agent khác debug CRUD/service thông thường vì reasoning và tool interaction không deterministic hoàn toàn.                          |
| 6 | Lặp lại + tốn thời gian            | Khi sử dụng Linux/Omarchy, một lỗi configuration có thể phải tìm thông tin từ GitHub issue, documentation, forum và config của người khác rồi tự ghép lại.          | Linux user/developer.                          | Tôi gặp các vấn đề configuration và troubleshooting theo kiểu này. Nhiều lỗi không khó về mặt kỹ thuật nhưng tốn thời gian tìm đúng context.                                                             |
| 7 | Tốn thời gian + thiếu feedback     | Dữ liệu đạp xe/training có nhiều metric nhưng khó chuyển thành insight dài hạn nếu chỉ xem từng activity riêng lẻ.                                                  | Người tập endurance/cycling.                   | Một activity có speed, heart rate, cadence, distance và duration nhưng giá trị lớn hơn nằm ở trend qua nhiều buổi tập.                                                                                   |
| 8 | Lặp lại + tốn thời gian            | Thực phẩm trong tủ lạnh bị quên; cùng loại thực phẩm nhưng khác batch nên khó biết batch nào cũ hơn và cần dùng trước.                                              | Gia đình 2–5 người, người mua/nấu ăn.          | Đây là problem tôi nhận ra từ góc nhìn workflow: người dùng biết “còn thực phẩm” nhưng không có timestamp/ID rõ ràng cho từng batch. Nếu đồ mới che đồ cũ, FIFO gần như phụ thuộc hoàn toàn vào trí nhớ. |

**AI đã dùng ở Phase 1:** Tôi dùng AI để mở rộng problem space và challenge các giả định ban đầu. Tôi không lấy danh sách AI tạo ra làm kết luận. Tôi lọc lại dựa trên những workflow tôi thực sự hiểu hoặc có thể quan sát được.

Một insight quan trọng của tôi ở phase này là **không phải problem nào có thể dùng AI cũng nên dùng AI**. Ví dụ code-checking có thể giải bằng rule/CI; một số workflow AWS có thể giải bằng documentation/search tốt hơn là Agent; còn FreshBox có thể bắt đầu bằng sensor + timestamp + rule FIFO.

## Phase 2 — Top 3 Problem Cards

| Rank | Problem                                          | Vì sao chọn                                                                                                | Điều còn chưa chắc                                                                                  |
| ---- | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| 1    | Quên thực phẩm và nhầm các batch trong tủ lạnh   | Pain dễ hình dung, actor rõ, workflow quan sát được và có thể prototype bằng hardware/rule mà chưa cần AI. | Cần đo forgotten-item rate, food waste và mức chấp nhận thao tác của người dùng.                    |
| 2    | Code chưa được kiểm tra đủ trước khi push/review | Gắn trực tiếp với workflow developer và có thể đo số lỗi bị bắt trước review.                              | Cần xác định chính xác phần nào rule/static analysis giải được và phần nào vẫn cần senior.          |
| 3    | Research AI/AWS bị phân mảnh giữa nhiều nguồn    | Đây là pain tôi gặp thường xuyên và liên quan trực tiếp đến việc học kỹ thuật.                             | Khó chứng minh impact định lượng nếu chưa log thời gian/context switching trong quá trình research. |

### Problem Card #1 — FreshBox: quên batch thực phẩm

**Problem 1 câu:** Gia đình thường biết “còn thịt/cá” nhưng không biết batch nào cũ hơn, dẫn đến đồ cũ bị quên và có thể phải bỏ.

**Actor:** Gia đình 2–5 người; người mua, chia và cất thực phẩm.

**Bối cảnh:** Sau khi mua/nhận thêm thực phẩm, đặc biệt khi cùng một loại thực phẩm được đưa vào tủ nhiều lần.

**Current workflow:**

Mua/nhận → chia vào túi/hộp → đặt vào ngăn bất kỳ → nhớ bằng trí nhớ → đồ mới che đồ cũ → phát hiện muộn → bỏ hoặc kiểm tra lại.

**Bottleneck:** Không có timestamp và ID rõ ràng cho từng batch. Nếu yêu cầu người dùng ghi thủ công mọi thứ thì chính thao tác nhập liệu lại trở thành một pain mới.

**Impact:** Khó thực hiện FIFO, dễ quên batch cũ, có thể mua trùng và tăng food waste.

**Success metric (prototype):**

* Forgotten-item rate giảm ≥50%.
* Registration <5 giây/item.
* Batch tracking accuracy ≥90%.
* Người dùng có thể xác định batch cần dùng trước mà không cần nhớ bằng trí nhớ.

**Non-AI alternative:** Rack có vị trí cố định, nhãn ngày và bảng FIFO đơn giản.

**AI hypothesis:** MVP chưa cần AI. Có thể dùng sensor + container ID + timestamp + weight + rule FIFO. Camera/AI recognition chỉ nên được xem là hướng nâng cao nếu prototype cơ bản chứng minh được pain.

**Quick gut:** Workflow + Rule, chưa cần Agent.

```text
CURRENT — người dùng nhớ thủ công

[Mua/nhận]
      ↓
[Cho vào hộp/túi]
      ↓
[Đặt vào tủ]
      ↓
[Tự nhớ ngày/batch]
      ↓
[Đồ mới che đồ cũ]
      ↓
[Phát hiện muộn]


FUTURE — FreshBox hỗ trợ tự động

[Đặt hộp vào rack]
      ↓
[Sensor ghi ID + timestamp]
      ↓
[Theo dõi weight]
      ↓
[FIFO / LED nhắc dùng trước]
      ↓
[Người dùng xác nhận khi cần]

Fallback:
Nếu sensor sai → người dùng sửa batch bằng app/nhãn ngày thủ công.
```

### Problem Card #2 — Pre-push Code Check

**Problem 1 câu:** Developer có thể push code lên senior review trong khi các lỗi có thể kiểm tra tự động như formatting, test hoặc convention chưa được phát hiện.

**Actor:** Intern, junior developer và senior reviewer.

**Bối cảnh:** Trước khi tạo PR hoặc bàn giao code cho reviewer.

**Current workflow:**

Code → tự kiểm tra → push/PR → senior review → phát hiện lỗi cơ bản → developer sửa → review lại.

**Bottleneck:** Một phần thời gian của senior bị dùng để phát hiện những lỗi mà machine có thể kiểm tra trước.

**Impact:** Review cycle dài hơn và developer phải quay lại sửa những lỗi không cần human judgement.

**Success metric:**

* Giảm số lỗi machine-checkable xuất hiện trong PR.
* ≥90% checklist tự động chạy trước khi PR được review.
* Giảm số comment review liên quan đến formatting/test/convention.

**Non-AI alternative:** Git hooks, CI, linter, formatter, static analysis và test pipeline.

**AI hypothesis:** AI chỉ nên xử lý các check cần context hoặc giải thích lỗi; không nên dùng Agent cho những rule deterministic.

```text
CURRENT:
Code → Push → Senior review → Phát hiện lỗi cơ bản → Fix → Review lại

FUTURE:
Code → Automated checks
      ├── Pass → Senior review
      └── Fail → Developer fix → Check lại

AI chỉ tham gia nếu cần giải thích/context mà rule thông thường không đủ.
```

### Problem Card #3 — Fragmented AI/AWS Research

**Problem 1 câu:** Khi nghiên cứu một technical topic, developer phải chuyển qua nhiều nguồn và tự ghép context nên tốn thời gian và dễ mất mạch suy nghĩ.

**Actor:** Developer/AI engineer tự học hoặc research technology mới.

**Bối cảnh:** Học một technology chưa quen hoặc cần giải quyết một architecture problem.

**Current workflow:**

Problem → Google/search → documentation → GitHub → blog/video → thử code → gặp vấn đề → search lại → tự tổng hợp.

**Bottleneck:** Context bị phân tán giữa nhiều nguồn và chất lượng thông tin không đồng đều.

**Impact:** Tăng thời gian research và khó biết khi nào đã có đủ evidence để đưa ra quyết định.

**Success metric:**

* Giảm thời gian tìm được nguồn phù hợp.
* Giảm số lần context switching.
* Có thể trace mỗi technical conclusion về nguồn hoặc experiment tương ứng.

**Non-AI alternative:** Knowledge base, bookmarks, notes và documentation index có cấu trúc.

**AI hypothesis:** AI có thể hỗ trợ search/summarization/context management, nhưng phải giữ source traceability và không được biến generated answer thành source of truth.

```text
CURRENT:
Problem → Search → Docs → GitHub → Blog → Experiment → Search lại → Tổng hợp

FUTURE:
Problem → Structured search
        → Relevant sources
        → AI-assisted synthesis
        → Verify source / experiment
        → Decision
```

---

## Tôi đã bảo vệ candidate nào?

**FreshBox là candidate tôi muốn pitch và bảo vệ nhất.**

Lý do không chỉ là tôi thấy nó “hay”, mà vì nó có một số đặc điểm mà các candidate khác chưa có cùng lúc:

1. Actor tương đối rõ.
2. Workflow hiện tại có thể quan sát.
3. Bottleneck cụ thể: batch + timestamp + FIFO.
4. Có thể tạo prototype nhỏ mà không cần phụ thuộc API hoặc dữ liệu bên thứ ba.
5. Có metric để kiểm chứng.
6. Có thể giải bằng No AI / Rule / Workflow trước khi cần AI.
7. Có thể mở rộng sau nếu prototype chứng minh được value.

Trong quá trình discussion, tôi không chỉ bảo vệ FreshBox mà còn challenge chính problem này: **liệu người dùng có thực sự giảm food waste hay chỉ có một inventory system đẹp hơn?**

Đây là câu hỏi quan trọng vì nếu sensor, rack hoặc container ID khiến người dùng phải thao tác quá nhiều thì solution có thể tạo ra một pain mới lớn hơn pain ban đầu.

## Tôi đã challenge các candidate khác như thế nào?

Tôi tập trung vào bốn câu hỏi:

* **Ai thực sự gặp problem?**
* **Workflow hiện tại diễn ra như thế nào?**
* **Bottleneck nằm ở đâu và có evidence gì?**
* **Có thể prototype và đo được trong scope của team không?**

Ví dụ:

* Với bài toán **student information**, pain có thể thật nhưng cần tích hợp nhiều nguồn và chưa có baseline rõ về thông báo bị bỏ sót.
* Với **tax assistance**, pain có hậu quả rõ nhưng có rủi ro pháp lý và phụ thuộc regulation; không nên để AI tự kết luận nghĩa vụ thuế.
* Với **urban/vehicle tracking**, solution có vẻ hấp dẫn nhưng phụ thuộc data owner, API và privacy.
* Với **code checking**, problem khá rõ nhưng phần lớn có thể giải bằng rule/CI nên Agent không tạo thêm nhiều value.

Nhờ vậy, việc chọn FreshBox không chỉ là “team thích ý tưởng này hơn”, mà là kết quả của việc so sánh **problem clarity + evidence + feasibility + boundary**.

## AI đã dùng ở Phase 2

| Phase        | Tôi dùng AI để làm gì?                   | AI hữu ích ở đâu?                            | AI sai / hời hợt ở đâu?                                                  | Tôi sửa gì bằng nhận định của mình?                           |
| ------------ | ---------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------- |
| Scan         | Gợi ý thêm problem theo nhiều lăng kính. | Mở rộng problem space nhanh.                 | Một số problem nghe hợp lý nhưng không có evidence.                      | Chỉ giữ problem tôi có context hoặc có thể kiểm chứng.        |
| Problem Card | Challenge actor, workflow và metric.     | Giúp phát hiện missing information.          | Có xu hướng đề xuất AI/camera/Agent quá sớm.                             | Tôi đưa MVP về sensor, ID, timestamp và Rule khi phù hợp.     |
| Workflow     | Chuyển mô tả thành flow.                 | Làm bottleneck dễ nhìn hơn.                  | Có xu hướng tự động hóa cả bước human judgement.                         | Giữ human confirmation và fallback.                           |
| Research     | Hỗ trợ tìm các case/solution đã tồn tại. | Giúp biết thị trường đã giải quyết bước nào. | Website/product description không phải lúc nào cũng là evidence về pain. | Phân biệt market signal với evidence cá nhân.                 |
| Comparison   | Challenge các candidate.                 | Giúp tạo checklist so sánh.                  | AI không thể thay team quyết định candidate tốt nhất.                    | Tôi sử dụng actor, workflow, evidence và feasibility để chốt. |
| Decision     | Gợi ý risk và feasibility questions.     | Bổ sung các góc nhìn tôi có thể bỏ sót.      | Có thể làm solution nghe hấp dẫn hơn thực tế.                            | Ưu tiên problem evidence và prototype feasibility.            |

## Self-check

* [x] Có 5+ problems và actor/bối cảnh.
* [x] Có top 3 Problem Cards.
* [x] Có workflow trước/sau, bottleneck, metric và fallback.
* [x] Đã pitch và bảo vệ FreshBox.
* [x] Đã challenge các candidate khác bằng actor, workflow, evidence và feasibility.
* [x] Đã thể hiện vai trò Team Lead trong quá trình convergence.
* [x] Đã phân biệt No AI / Rule / Workflow / Agent thay vì mặc định chọn AI.
* [x] Đã ghi rõ AI hỗ trợ tư duy nhưng không thay thế quyết định của team.
