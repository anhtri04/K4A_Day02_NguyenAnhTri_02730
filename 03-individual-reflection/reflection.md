# 03 — Individual Reflection

## Thông tin cá nhân

* Họ và tên: Nguyễn Anh Trí
* Mã học viên: 2730
* Nhóm: C sủi
* Vai trò: **Team Lead**
* Candidate problem nhóm chọn: **FreshBox — giúp gia đình biết trong tủ lạnh đang có gì, từng batch được cất từ khi nào và món nào nên dùng trước.**

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động                | Tôi đã làm gì?                                                                                                                                                | Kết quả / ảnh hưởng tới nhóm                                                                           |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Scan cá nhân             | Tôi chủ động tìm nhiều problem từ các workflow tôi thực sự gặp: code review, AI/AWS research, trading research và FreshBox.                                   | Nhóm có nhiều candidate để so sánh thay vì bắt đầu trực tiếp từ một solution.                          |
| Tìm problem chính        | Tôi nhận ra FreshBox không chỉ là “smart fridge”, mà có một pain cụ thể hơn: không biết batch nào cũ hơn và nên dùng trước.                                   | Problem được chuyển từ một ý tưởng rộng thành batch tracking + FIFO.                                   |
| Pitch Problem Card       | Tôi trình bày FreshBox theo actor → workflow → bottleneck → impact → metric.                                                                                  | Team có một candidate đủ cụ thể để challenge và đào sâu.                                               |
| Bảo vệ problem           | Tôi giải thích vì sao FreshBox có actor rõ, workflow quan sát được, prototype được và ít phụ thuộc dữ liệu bên ngoài.                                         | Giúp team có cơ sở so sánh FreshBox với các candidate khác.                                            |
| Challenge candidate khác | Tôi đặt câu hỏi về actor, workflow, evidence, feasibility, data dependency và risk.                                                                           | Team loại/thu hẹp những candidate có scope lớn hoặc evidence chưa đủ.                                  |
| Challenge chính FreshBox | Tôi cũng đặt câu hỏi ngược lại: nếu người dùng phải nhập quá nhiều thì solution có tạo thêm pain không? Sensor sai thì ai sửa? Hardware cost có hợp lý không? | Team không chỉ nhìn FreshBox theo hướng “ý tưởng hay” mà bắt đầu quan tâm đến feasibility và fallback. |
| Gom trùng / cluster      | Tôi kết nối các candidate có pattern giống nhau và đưa discussion về problem thay vì solution.                                                                | Team nhìn được các nhóm problem và tránh tranh luận chỉ dựa trên tên ý tưởng.                          |
| Điều phối team           | Tôi kết nối các thành viên, phân chia các hướng research và giúp các phần research quay lại phục vụ decision chung.                                           | Các thành viên có thể đóng góp ở những góc khác nhau nhưng vẫn hội tụ về cùng một problem.             |
| Validation / research    | Tôi hỗ trợ team kiểm tra các solution đã tồn tại và các constraint về data/API/privacy/regulation.                                                            | Team hiểu rõ hơn tại sao một số candidate có risk hoặc scope lớn hơn FreshBox.                         |
| Workflow                 | Tôi giúp làm rõ current workflow và future workflow của FreshBox.                                                                                             | Nhóm xác định được sensor/ID/timestamp/weight và Rule FIFO nằm ở đâu.                                  |
| Rule / Workflow / Agent  | Tôi bảo vệ quan điểm rằng MVP chưa cần Agent hay AI recognition.                                                                                              | Scope được giảm và solution thực tế hơn.                                                               |
| Final decision           | Tôi hỗ trợ team so sánh candidate bằng actor, workflow, evidence, impact và feasibility.                                                                      | Team thống nhất chọn FreshBox thay vì chọn solution chỉ vì dễ làm app.                                 |

### Dấu tay rõ nhất của tôi

Đóng góp rõ nhất của tôi không phải chỉ là **“đưa ra FreshBox”**, mà là biến nó thành một problem mà team có thể **defend và kiểm chứng**.

Tôi cố gắng đưa discussion từ:

> “Ý tưởng này có vẻ hay.”

sang:

> “Ai gặp vấn đề? Hiện tại họ làm thế nào? Bottleneck ở đâu? Có evidence gì? Có thể đo gì? Có thể giải bằng Rule không? Nếu không cần AI thì tại sao phải dùng AI?”

Tôi cũng đóng vai trò kết nối các thành viên để những candidate khác nhau không trở thành những hướng làm việc riêng biệt. Mục tiêu của tôi là giúp team đi đến một quyết định mà mọi người hiểu **tại sao chọn** và quan trọng không kém là **tại sao không chọn các hướng còn lại**.

---

## 2. Bảng dùng AI

| Phase                | Tôi dùng AI để làm gì?                               | AI hữu ích ở đâu?                                           | AI sai / hời hợt ở đâu?                                              | Tôi sửa gì bằng nhận định của mình?                                                  |
| -------------------- | ---------------------------------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Scan                 | Gợi ý thêm problem theo các lăng kính của worksheet. | Mở rộng problem space nhanh.                                | Một số problem chung chung hoặc solution-first.                      | Tôi lọc theo trải nghiệm thật và khả năng kiểm chứng.                                |
| Problem Card         | Challenge actor, workflow, bottleneck và metric.     | Giúp phát hiện phần problem còn mơ hồ.                      | Có xu hướng đưa camera/AI/Agent vào quá sớm.                         | Tôi giữ MVP FreshBox ở sensor + ID + timestamp + weight + Rule FIFO.                 |
| Workflow             | Chuyển mô tả thành current/future workflow.          | Giúp nhìn rõ các bước và bottleneck.                        | AI thường tự động hóa cả bước cần human judgement.                   | Tôi giữ human confirmation và fallback khi sensor sai.                               |
| Research             | Tìm các solution/case đã tồn tại.                    | Giúp team biết market đã giải quyết một phần workflow nào.  | Product website không phải evidence độc lập về pain.                 | Tôi dùng research như context/market signal, không coi nó là proof cho pain cá nhân. |
| Candidate comparison | Gợi ý tiêu chí để so sánh problem.                   | Tạo framework nhanh.                                        | AI không thể tự biết candidate nào phù hợp với team context.         | Tôi tập trung vào actor, workflow, evidence, feasibility và boundary.                |
| Team discussion      | Hỗ trợ tạo câu hỏi challenge.                        | Giúp mở thêm góc nhìn khi discussion bị stuck.              | Nếu dùng nguyên câu trả lời của AI, discussion dễ trở thành generic. | Tôi biến output thành câu hỏi cụ thể cho từng candidate.                             |
| Decision             | Gợi ý risk, feasibility và alternative solution.     | Giúp kiểm tra blind spots.                                  | AI có xu hướng làm solution nghe hấp dẫn hơn problem.                | Tôi ưu tiên evidence và khả năng prototype thay vì độ “thông minh” của solution.     |
| Reflection           | Hỗ trợ structure reflection.                         | Giúp kiểm tra tôi đã cover role, AI usage và learning chưa. | AI không thể tự phản ánh thay cho trải nghiệm của tôi.               | Tôi viết lại dựa trên những quyết định và conflict thực tế trong team.               |

---

## 3. Reflection

### 3.1. Tôi học được gì về việc làm Team Lead?

Trước bài này, tôi thường nghĩ Team Lead chủ yếu là người chia task và đảm bảo mọi người hoàn thành phần việc của mình. Sau bài này, tôi nhận ra một phần quan trọng hơn của việc lead là **giúp team ra quyết định tốt**.

Khi mỗi thành viên đưa ra một problem khác nhau, nếu tôi chỉ chia task thì team vẫn có thể làm việc song song nhưng cuối cùng rất khó hội tụ. Vì vậy, tôi tập trung vào việc đưa discussion về cùng một framework: **actor → workflow → bottleneck → evidence → impact → feasibility**.

Điều này giúp tôi nhận ra rằng Team Lead không nhất thiết phải là người có câu trả lời cho mọi thứ. Quan trọng hơn là phải biết **đặt đúng câu hỏi để team tự tìm ra câu trả lời**.

### 3.2. Tôi đã bảo vệ problem như thế nào?

FreshBox là problem tôi muốn bảo vệ nhất. Nhưng trong quá trình làm, tôi nhận ra bảo vệ một problem không có nghĩa là cố chứng minh rằng mình đúng.

Tôi phải đồng thời tìm lý do để **ủng hộ và phản bác chính problem của mình**.

Ví dụ, tôi có thể nói:

* Actor rõ.
* Workflow dễ quan sát.
* Batch tracking có bottleneck cụ thể.
* Có thể prototype.
* Không cần phụ thuộc API bên ngoài.

Nhưng tôi cũng phải hỏi:

* Người dùng có thực sự giảm food waste không?
* Người dùng có chịu nhập/scan từng item không?
* Sensor sai thì ai sửa?
* Hardware có đắt hơn giá trị mà solution tạo ra không?
* Nếu Rule FIFO đã đủ thì AI có thực sự cần không?

Tôi thấy cách này làm cho việc defend problem đáng tin hơn. Nếu chỉ đưa ra các lý do ủng hộ thì đó giống pitching hơn là validation.

### 3.3. Tôi đã hỗ trợ các thành viên khác như thế nào?

Tôi không muốn việc team lead biến thành việc tôi đưa ra hướng rồi mọi người chỉ làm theo.

Khi các thành viên có những candidate khác nhau, tôi cố gắng tìm phần hợp lý trong từng ý tưởng và hỏi xem chúng có thể giải thích bằng cùng một workflow/problem framework hay không.

Ví dụ, với các bài toán về student information, tax assistance hoặc vehicle tracking, tôi không đơn giản nói rằng “không làm được”. Tôi cùng team phân tích:

* Problem có đủ evidence chưa?
* Data ở đâu?
* Ai sở hữu data?
* Có dependency bên ngoài không?
* Privacy/regulation có ảnh hưởng không?
* Có thể làm prototype trong scope của lab không?
* Có thể đo success không?

Qua đó, việc loại một candidate trở thành một **decision có reasoning**, thay vì preference cá nhân.

### 3.4. Điều tôi học được về AI

Điều quan trọng nhất tôi học được là **AI rất giỏi mở rộng không gian suy nghĩ nhưng không nên được giao quyền quyết định thay mình**.

AI giúp tôi rất nhanh trong việc:

* brainstorm problem;
* generate questions;
* challenge workflow;
* đề xuất metrics;
* tìm alternative solutions;
* structure information.

Nhưng AI cũng có một pattern khá rõ: nó thường làm solution trở nên “thông minh” hơn cần thiết.

Ví dụ với FreshBox, AI rất dễ dẫn đến camera recognition, computer vision, freshness prediction hoặc Agent. Nhưng khi nhìn vào workflow thực tế, MVP có thể chỉ cần:

**ID + timestamp + weight + Rule FIFO.**

Điều này củng cố cho tôi một nguyên tắc:

> **Không bắt đầu bằng “AI có thể làm gì?”, mà bắt đầu bằng “problem cần giải quyết bước nào?”**

Sau đó mới quyết định No AI, Rule, Workflow hay Agent.

### 3.5. Điều tôi sẽ làm khác nếu làm lại

Nếu làm lại, tôi sẽ đầu tư nhiều hơn vào **evidence trước khi defend candidate**.

Đặc biệt với FreshBox, tôi muốn có baseline thực tế:

* Một gia đình quên bao nhiêu item trong một tuần/tháng?
* Bao nhiêu item bị bỏ vì không biết batch cũ?
* Người dùng mất bao lâu để record một item?
* Họ có thực sự sẵn sàng thay đổi cách sắp xếp tủ lạnh không?
* Hardware/sensor có cost bao nhiêu?
* Khi sensor sai, correction workflow mất bao lâu?

Tôi cũng sẽ phân chia research sớm hơn. Thay vì để mỗi thành viên research theo hướng riêng, tôi sẽ tạo một bảng chung với các câu hỏi cần chứng minh và assign owner cho từng câu.

Điều đó sẽ giúp team giảm thời gian research trùng nhau và decision cuối có evidence rõ hơn.

---

## 4. Bài học lớn nhất

Bài học lớn nhất của tôi sau lab này là:

**Team Lead không phải là người có ý tưởng tốt nhất. Team Lead là người giúp team tìm ra lý do tốt nhất để tin hoặc không tin một ý tưởng.**

Trong bài này, tôi có problem tôi muốn bảo vệ, nhưng đồng thời tôi phải giúp team challenge nó. Tôi cũng phải hỗ trợ các thành viên khác đưa problem của họ lên bàn cân một cách công bằng.

Cuối cùng, điều tôi thấy có giá trị nhất không phải chỉ là team chọn FreshBox. Giá trị là team hiểu được **vì sao FreshBox phù hợp hơn trong scope hiện tại**, tại sao một số candidate khác chưa phù hợp, và tại sao MVP chưa cần Agent.

Đây cũng là cách tôi muốn áp dụng vào những project software/AI sau này: **problem trước, evidence sau, workflow tiếp theo, rồi mới chọn technology.**

---

## 5. Tự kiểm cuối bài

* [x] Cá nhân có 5+ problems và Top 3 Problem Cards.
* [x] Đã pitch và bảo vệ FreshBox.
* [x] Đã challenge chính problem của mình thay vì chỉ bảo vệ nó.
* [x] Đã challenge các candidate khác bằng actor, workflow, evidence và feasibility.
* [x] Đã thể hiện rõ vai trò Team Lead.
* [x] Đã hỗ trợ và kết nối các thành viên trong quá trình convergence.
* [x] Reflection có vai trò, cách dùng AI, giới hạn của AI và bài học cá nhân.
* [x] Đã giải thích vì sao MVP dùng Rule/Workflow thay vì mặc định dùng Agent.
* [x] Đã nêu rõ điều tôi sẽ làm khác nếu có thêm thời gian.
