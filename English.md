# Amazon Web Services Machine Learning - Specialty Experience

## 1. AWS's recommended knowledge and experience:

***Check this link for full details: [click here](https://aws.amazon.com/certification/certified-machine-learning-specialty/)***

> **There are 4 domains within 65 questions in this exam:**
> 1. Data engineering: 20%
> 2. Exploratory data analysis: 24%
> 3. Modeling: 36%
> 4. Machine learning implementation: 20%

* 1-2 years of experience developing, architecting, or running ML/deep learning workloads on the AWS Cloud
* The ability to express the intuition behind basic ML algorithms
* Experience performing basic hyperparameter optimization
* Experience with ML and deep learning frameworks
* The ability to follow model-training best practices
* The ability to follow deployment and operational best practices

## 2. My recommendation:

> ***In my opinion, this certificate consists of 2 big elements***

* Machine learning (building,training,evaluation,deployment)
* AWS services used for implementing everything above inside AWS infrastructure.
* *It will be easier if you are a Machine Learning practioner before, you just need to learn AWS infrastructure.*

> **Me before the certificate**

* 2 years experience in Machine Learning & Deep Learning, but I am not too familiar with data mining, exploratory data analysis because I mainly work on computer vision (of course I've already learned data science before, but maybe at that time I like doing something than learning data so haha, i missed it), thus it's take me a punch of time to review all the knowledge around data as visualization, data insight, evaluation, use case, etc.
* Nearly 4 months of exposure to AWS (actually my knowledge at this time is just limited around S3 for storage, EC2 for training model, and a little bit of IAM for manage user, policy, resouces, etc.), so don't worry, nothing's impossible :D 
* I have reviewed everything while still working in a company for about 3 months, I'm also procrastinative too much so you absolutely can achieve it in a shorter time.

## 3. Documentation:

* **Course AWS Developer - Associate**: to familiar with the basic services of AWS, you do not need to take this certificate but just take it if you want, [youtube](https://www.youtube.com/watch?v=RrKRN9zRBWs) (on youtube, no quiz, no engsub or vietsub anymore since it's to long - 11 hours, but free), or [acloud.guru](https://acloud.guru/learn/aws-certified-developer-associate) (It has fee, also has english subtitle, quiz and hands-on lab, I learnt here because my company pay everything)


* **Course AWS Machine Learning - Specialty**: all knowledge of the main certificate, I studied at [acloud.guru](https://acloud.guru/learn/aws-certified-machine-learning-specialty), but I have figured out another course at [linuxacademy](https://linuxacademy.com/course/aws-certified-machine-learning-specialty/) seem more detailed and also recommended my boss pay this course for other people in company.


* **Developer Guide của các service** & **White paper của AWS**: trong quá trình học và giải đề bạn sẽ cần phải tìm hiểu sâu hơn về các service, nên cứ bí service nào thì lên google tìm documentation của service đó ở trang aws để đọc là được, trong khóa học ở trên người ta cũng sẽ recommend resources thì các bạn cứ down về đọc, mình cũng recommend 1 White paper về Big Data solution on AWS mà mình thấy khá có ích ở [đây](https://docs.aws.amazon.com/whitepapers/latest/building-data-lakes/building-data-lake-aws.html)


* **Practice**: Hãy thử nhiều service nhất có thể để có cảm giác về nó. Hãy chú ý SageMaker vì mọi thứ sẽ xoay quanh rất nhiều về nó. Đừng bỏ qua các hands-on lab nếu gặp chúng nó trong khóa học.


* **Giải đề**: lợi ích của học các course trả phí là nó sẽ có đề thi thử cuối khóa, mình đã giải qua các đề của ***Acloud.guru***(có explanation), ***Whizlab***(có explanation chi tiết, cái này có anh bạn tốt bụng cho mình mượn account) và ***Examtopic*** (cái này đừng tin theo đáp án của nó vì không chính xác đâu, hãy tự tìm hiểu documentation và các tài liệu khác để chọn đáp án, xem discussion của mọi người cho từng câu nữa), nói thật là mình chưa bao giờ pass khi thi thử :D, có thể do ẩu và nôn nóng. Đêm trước khi thi mình vẫn chưa yên tâm nên pay thêm 1 đề của ***Udemy***(cũng có explanation chi tiết) để giải, tất nhiên là cũng fail luôn. Ngoài ra, AWS cũng có đề thi thử 20 câu nhưng tới 40$ khá chát và cũng không có explanation chi tiết nên mình không pay, chỉ giải cái đề thử free của nó thôi - **[link](https://d1.awsstatic.com/training-and-certification/docs-ml/AWS-Certified-Machine-Learning-Specialty_Sample-Questions.pdf)**


* Ngoài ra, sẽ luôn có các service lạ như là AWS Batch, AWS Step Function hoặc Deeplens, DeepRacer, Iot Greengrass, Iot Core, etc. Hãy cố gắng đọc sơ qua để không bị bí những câu dễ dễ của services đó , nhiều khi nó xuất hiện trong những đáp án sai nhưng vì chúng ta không biết về nó nên bị phân tâm. Hãy ôn lại những kiến thức xác suất thống kê như Bernulli distribution, Binomial distribution, Poisson distribution, hệ số tương quan Pearson, ý nghĩa của residual plot, Naive Bayes, Full Bayes, etc. Hầu hết những câu mình bí hoặc không chắc trong đề thi đều là những câu dạng suy luận của xác suất thống kê này, cũng không nhiều, nhưng thà giết nhầm còn hơn bỏ sót chứ đúng không :))))

* Nên đọc thật kĩ câu hỏi và suy luận context khi nào nên dùng các service. 

Ví dụ:

> Giữa Step Function và Batch thì nếu bạn có 1 process đã hoàn chỉnh, bạn muốn chạy phân tán nó trên nhiều resource, có khả năng schedule, manage những công việc đó thì Batch là lựa chọn hoàn hảo. 

> Ngược lại bạn có 1 process trong đầu chưa thực hiện, bạn muốn stack nhiều bước và resource thành một dây chuyền xử lí để thực hiện process đó thì lựa chọn Step Function

Còn rất nhiều kiểu câu hỏi khác, như là kết hợp service như thế nào để hợp lí nhất, rẻ nhất, nhanh nhất, hiệu quả nhất, etc. Hãy giải đề và đọc explanation chi tiết để tự tìm câu trả lời cho mình.

## 4. Đi thi:

* Book phòng: ở aws.training (1 phòng 1 người thôi không phải 2 người :D)
* Đóng 300$.
* Nhớ chọn ESL (tiếng anh là ngôn ngữ thứ 2) để được cộng thêm 30 phút
* Chiến thuật làm bài: thời gian là 3 tiếng 30 phút, giải một lượt hết 65 câu, flag những câu không chắc chắn, sau đó quay lại check kĩ lại những câu chắc chắn (để chắc chắn rằng không mất điểm những câu này), sau đó mới tìm những câu để flag để đọc lại lần nữa và suy luận kĩ hơn. Với mình thì mình flag khoảng 15 câu ở lượt đầu tiên và mình đã dùng hết 3 tiếng rưỡi để check đi check lại được 3 lần cái đề ^^.
* Sau khi nộp bài sẽ có kết quả ngay đậu rớt nhưng không có điểm cụ thể.
* Khoảng 2 ngày sau thì kết quả điểm sẽ trả về ở mail và trang đăng kí thi.


Và đây là kết quả của mình hihi :heart_eyes:

![alt text](images/aws-score.png)


