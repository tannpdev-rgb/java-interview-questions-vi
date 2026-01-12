# câu hỏi phỏng vấn java

Các câu hỏi phỏng vấn Java thường gặp

### Mục lục

<!-- TOC_START -->
| Không. | Câu hỏi |
| --- | --------- |
| 1 | [Sự khác biệt giữa JVM, JRE và JDK là gì?](#what-are-the-differences-between-jvm-jre-and-jdk) |
| 2 | [Tại sao Java là ngôn ngữ độc lập với nền tảng](#why-java-is-platform-independent-language) |
| 3 | [JVM hoạt động như thế nào](#how-does-jvm-works) |
| 4 | [Các tính năng chính của Java là gì](#what-are-the-main-features-of-java) |
| 5 | [public static void main là gì?](#what-is-public-static-void-main) |
| 6 | [Nhóm hằng số chuỗi là gì](#what-is-string-constant-pool) |
| 7 | [Tại sao chuỗi là bất biến](#why-strings-are-immutable) |
| 8 | [Sự khác biệt giữa StringBuffer và StringBuilder](#what-is-the-difference-between-stringbuffer-and-stringbuilder) |
| 9 | [Tầm quan trọng của phương thức hashCode() và Equals() là gì](#what-is-the-importance-of-hashcode-and-equals-methods) |
| 10 | [Sự khác biệt giữa các trường hợp ngoại lệ được kiểm tra và không được kiểm tra là gì](#what-is-the-difference-between-checked-and-unchecked-expceptions) |
| 11 | [Các lớp bao bọc là gì](#what-are-wrapper-classes) |
| 12 | [Tại sao java không phải là ngôn ngữ hướng đối tượng thuần túy](#why-java-is-not-pure-object-oriented-language) |
| 13 | [Sự khác biệt giữa lớp trừu tượng và giao diện](#what-is-the-difference-between-abstract-class-and-interface) |
| 14 | [Giao diện điểm đánh dấu là gì](#what-are-marker-interfaces) |
| 15 | [Bộ sưu tập trong Java là gì?](#what-are-collections-in-java) |
| 16 | [Sự khác biệt giữa danh sách mảng và vector là gì?](#what-are-the-differences-between-arraylist-and-vector) |
| 17 | [Phương pháp hoàn thiện là gì? Làm thế nào để bạn ghi đè nó?](#what-is-finalize-method-how-do-you-override-it) |
| 18 | [Sự khác biệt giữa giao diện so sánh và giao diện so sánh là gì](#what-is-the-difference-between-the-comparable-and-comparator-interfaces) |
| 19 | [Lớp bên trong là gì](#what-is-an-inner-class) |
| 20 | [Sự khác biệt giữa cuối cùng, cuối cùng và hoàn thiện() trong Java là gì?](#what-is-the-difference-between-final-finally-and-finalize-in-java) |
| 21 | [Sự khác biệt giữa phương thức '==' và bằng () là gì?](#what-is-the-difference-between--and-equals-method) |
| 22 | [Nạp chồng phương thức và ghi đè phương thức là gì?](#what-is-method-overloading-and-method-overriding) |
| 23 | [Sự khác biệt giữa HashMap và Hashtable là gì?](#what-is-the-difference-between-hashmap-and-hashtable) |
| 24 | [Sự khác biệt giữa ArrayList và LinkedList là gì?](#what-is-the-difference-between-arraylist-and-linkedlist) |
| 25 | [API phản chiếu Java là gì?](#what-is-java-reflection-api) |
| 26 | [Các loại vùng nhớ khác nhau được JVM phân bổ là gì?](#what-are-the-different-types-of-memory-areas-allocated-by-jvm) |
| 27 | [Sự khác biệt giữa ném và ném là gì?](#what-is-the-difference-between-throw-and-throws) |
| 28 | [Lớp singleton là gì và làm thế nào để tạo một lớp?](#what-is-a-singleton-class-and-how-to-create-one) |
| 29 | [Các tính năng API luồng Java 8 là gì?](#what-are-java-8-stream-api-features) |
| 30 | [Sự khác biệt giữa các trình vòng lặp không nhanh và không an toàn là gì?](#what-is-the-difference-between-fail-fast-and-fail-safe-iterators) |
| 31 | [Sự khác biệt giữa quá trình và chủ đề là gì?](#what-is-the-difference-between-process-and-thread) |
| 32 | [Các cách khác nhau để tạo một luồng trong Java là gì?](#what-are-the-different-ways-to-create-a-thread-in-java) |
| 33 | [Đồng bộ hóa trong Java là gì?](#what-is-synchronization-in-java) |
| 34 | [Bế tắc là gì và làm thế nào để tránh nó?](#what-is-deadlock-and-how-to-avoid-it) |
| 35 | [Từ khóa dễ bay hơi trong Java là gì?](#what-is-the-volatile-keyword-in-java) |
| 36 | [Từ khóa tạm thời trong Java là gì?](#what-is-the-transient-keyword-in-java) |
| 37 | [Tuần tự hóa và giải tuần tự hóa là gì?](#what-is-serialization-and-deserialization) |
| 38 | [Giao diện chức năng trong Java là gì?](#what-are-functional-interfaces-in-java) |
| 39 | [Biểu thức lambda trong Java là gì?](#what-are-lambda-expressions-in-java) |
| 40 | [Lớp tùy chọn trong Java 8 là gì?](#what-is-optional-class-in-java-8) |
| 41 | [Sự khác biệt giữa Bộ sưu tập và Bộ sưu tập là gì?](#what-is-the-difference-between-collection-and-collections) |
| 42 | [Sự khác biệt giữa Bộ và Danh sách là gì?](#what-is-the-difference-between-set-and-list) |
| 43 | [Sự khác biệt giữa HashSet và TreeSet là gì?](#what-is-the-difference-between-hashset-and-treeset) |
| 44 | [Vấn đề kim cương trong Java là gì?](#what-is-the-diamond-problem-in-java) |
| 45 | [Tiêm phụ thuộc là gì?](#what-is-dependency-injection) |
| 46 | [Sự khác biệt giữa bản sao nông và bản sao sâu là gì?](#what-is-the-difference-between-shallow-copy-and-deep-copy) |
| 47 | [Các mẫu thiết kế trong Java là gì?](#what-are-design-patterns-in-java) |
| 48 | [Mẫu thiết kế nhà xưởng là gì?](#what-is-the-factory-design-pattern) |
| 49 | [Mẫu thiết kế của người xây dựng là gì?](#what-is-the-builder-design-pattern) |
| 50 | [Sự khác biệt giữa bộ nhớ Heap và Stack là gì?](#what-is-the-difference-between-heap-and-stack-memory) |
| 51 | [Thu gom rác trong Java là gì?](#what-is-garbage-collection-in-java) |
| 52 | [Các loại trình thu gom rác khác nhau trong Java là gì?](#what-are-the-different-types-of-garbage-collectors-in-java) |
| 53 | [Sự khác biệt giữa các phương thức wait() và sleep() là gì?](#what-is-the-difference-between-wait-and-sleep-methods) |
| 54 | [Sự khác biệt giữa thông báo() và thông báoAll() là gì?](#what-is-the-difference-between-notify-and-notifyall) |
| 55 | [Lớp bất biến là gì và làm thế nào để tạo một lớp?](#what-is-an-immutable-class-and-how-to-create-one) |
| 56 | [Sự khác biệt giữa String, StringBuilder và StringBuffer là gì?](#what-is-the-difference-between-string-stringbuilder-and-stringbuffer) |
| 57 | [Sự khác biệt giữa các biến tĩnh và biến thể là gì?](#what-is-the-difference-between-static-and-instance-variables) |
| 58 | [Mục đích của từ khóa super là gì?](#what-is-the-purpose-of-the-super-keyword) |
| 59 | [Mục đích của từ khóa này là gì?](#what-is-the-purpose-of-the-this-keyword) |
| 60 | [Generics trong Java là gì?](#what-are-generics-in-java) |
| 61 | [Xóa kiểu trong Java Generics là gì?](#what-is-type-erasure-in-java-generics) |
<!-- TOC_END -->

<!-- QUESTIONS_START -->

1. ### Sự khác biệt giữa JVM, JRE và JDK là gì?

   Sự khác biệt chính giữa JVM, JRE và JDK được liệt kê bên dưới,

   **JVM:** Máy ảo Java (JVM) là một máy trừu tượng cung cấp môi trường thời gian chạy để thực thi Java ByteCode. tức là, Nó là một phần của Môi trường chạy thi hành Java (JRE) và chịu trách nhiệm chuyển đổi mã byte thành mã có thể đọc được bằng máy. JVM phụ thuộc vào nền tảng nhưng nó diễn giải mã byte độc ​​lập với nền tảng. Kết quả là các ứng dụng Java có thể chạy trên các nền tảng và hệ điều hành khác nhau.

   **JRE:** Môi trường chạy thi hành Java (JRE) là gói cài đặt cung cấp Máy ảo Java (JVM), thư viện lớp và các thành phần khác để chạy chương trình hoặc ứng dụng Java trên bất kỳ máy nào.

   **JDK:** Bộ công cụ phát triển Java (JDK) là bộ công cụ phát triển phần mềm dùng để phát triển và thực thi các chương trình Java. Nó bao gồm các công cụ để phát triển, giám sát và gỡ lỗi các chương trình java, cùng với JRE để thực thi các chương trình tương ứng đó.

   Biểu diễn bằng hình ảnh của ba thành phần này trông như sau,

   <img src="images/JVM_JRE_JDK.png" width="400" Height="400" />

   **[⬆ Quay lại đầu trang](#table-of-contents)**

2. ### Tại sao Java là ngôn ngữ độc lập với nền tảng

   Java là ngôn ngữ độc lập với nền tảng vì các chương trình java được biên dịch thành mã byte có thể chạy trên bất kỳ thiết bị hoặc hệ điều hành nào có Máy ảo Java (JVM). Điều này có thể thực hiện được nhờ khả năng "Viết một lần, chạy mọi nơi"(WORA) của JVM. Vì lý do này, bạn có thể viết chương trình Java trên một nền tảng như máy Windows và sau đó chạy chương trình đó trên một nền tảng khác như máy macOS hoặc Linux mà không cần thực hiện bất kỳ sửa đổi nào đối với mã.

   Sơ đồ dưới đây giải thích tính năng độc lập nền tảng của Java,

   ![Screenshot](images/JavaIndependent.png)

   **[⬆ Quay lại đầu trang](#table-of-contents)**

3. ### JVM hoạt động như thế nào

   JVM (Máy ảo Java) là một công cụ thời gian chạy trừu tượng để chạy các ứng dụng java. Nó là một phần của Môi trường chạy thi hành Java (JRE) để thực thi mã byte được tạo bởi trình biên dịch java. JVM mang đến hành vi WORA (Viết một lần đọc mọi nơi) trong đó bạn có thể viết chương trình java trên một hệ thống và dự kiến ​​sẽ chạy trên mọi hệ thống hỗ trợ java mà không cần bất kỳ sửa đổi nào. Khi biên dịch tệp .java thành tệp .class (chứa mã byte), tệp .class sẽ thực hiện một số bước được mô tả bởi JVM.

   JVM bao gồm ba thành phần chính:

   1. Hệ thống con Trình nạp lớp
   2. Vùng dữ liệu/ vùng nhớ thời gian chạy
   3. Động cơ thực thi

   Hãy hiểu kiến ​​trúc JVM bao gồm ba thành phần trên,

   ![Screenshot](images/JVMArchitecture.png)

   1. **Hệ thống con trình nạp lớp:** Trình nạp lớp có trách nhiệm tải động các tệp lớp vào JVM trong thời gian chạy. Lớp đầu tiên được nạp vào bộ nhớ thường là lớp chứa `main` phương pháp. Hệ thống con này thực hiện ba hoạt động chính.

      1. **Đang tải:** Là một phần của bước này, trình nạp lớp sẽ đọc tệp .class và tạo mã byte tương ứng. Thông tin quan trọng sau đây của tệp lớp sẽ được lưu trong vùng phương thức của JVM.

         1. Tên lớp đủ điều kiện (FQCN) của lớp được tải.
         2. Lớp cha mẹ ngay lập tức.
         3. Thông tin về các biến, phương pháp và sửa đổi
         4. .class có liên quan đến Lớp, Giao diện hay Enum hay không.

         JVM cũng tạo một đối tượng thuộc loại **Class** (có sẵn từ gói **java.lang**) để thể hiện tệp trong bộ nhớ heap. Nhưng nó sẽ chỉ được tạo vào lần đầu tiên khi tệp lớp được tải vào JVM. Đối tượng này rất hữu ích cho các nhà phát triển để có được thông tin về cấp lớp.

      2. **Liên kết:** Liên kết là quá trình lấy một lớp hoặc giao diện và kết hợp nó vào trạng thái thời gian chạy của máy ảo Java, chuẩn bị cho nó thực thi. Nó bao gồm các bước sau:

         1. **Xác minh:** Giai đoạn này đảm bảo tính chính xác của `.class` tệp bằng cách kiểm tra xem tệp có được định dạng đúng hay không và mã được tạo bởi trình biên dịch hợp lệ hay không. Nếu xác thực không thành công, bạn sẽ nhận được `java.lang.VerifyError` thông qua **ByteCodeVerifier**.

         2. **Chuẩn bị:** Trong bước này, JVM phân bổ bộ nhớ cho tất cả các biến tĩnh trong các lớp/giao diện và gán chúng với các giá trị mặc định.

         3. **Giải pháp:** Trong bước này, tất cả các tham chiếu tượng trưng đến các lớp hoặc giao diện được thay thế bằng vị trí bộ nhớ thực của chúng. Sự chuyển đổi này được gọi là **Liên kết động**.

      3. **Khởi tạo:** Đây là giai đoạn cuối cùng của quá trình tải lớp, trong đó tất cả các biến tĩnh được thay thế bằng giá trị ban đầu của chúng và khối tĩnh được thực thi.

   Có ba trình nạp lớp tích hợp sẵn trong Java:

   1. **Bootstrap ClassLoader:** Đây là trình nạp lớp gốc và thường được biểu diễn dưới dạng rỗng. Nó tải các thư viện java cốt lõi nằm trong thư mục <JAVA_HOME>/jmods như `java.lang`, `java.util` v.v. Trình nạp lớp này được viết bằng mã gốc không giống như các trình nạp lớp khác.

   2. **Trình tải lớp nền tảng:** Trình tải lớp này chịu trách nhiệm tải các lớp nền tảng chẳng hạn như API nền tảng Java SE, các lớp triển khai của chúng và các lớp thời gian chạy dành riêng cho JDK. Ví dụ: các lớp nền tảng như `java.net.http`, `java.sql`, `org.graalvm.compile`(JDK cụ thể).

   3. **Trình nạp lớp hệ thống/ứng dụng:** Trình nạp lớp này chịu trách nhiệm tải tất cả các lớp được định cấu hình từ đường dẫn lớp. Đường dẫn lớp có thể chứa các lớp từ các thư mục, tệp JAR, v.v.

   Các trình nạp lớp ở trên tuân theo hệ thống phân cấp của trình nạp lớp để đảm bảo cơ chế ủy nhiệm. Điều đó có nghĩa là, nếu lớp được tải và trình nạp lớp ứng dụng không tìm thấy nó, thì yêu cầu sẽ được ủy quyền lên trình tải lớp ứng dụng nền tảng. Nhưng thậm chí nó không được tìm thấy bởi trình nạp lớp nền tảng, sau đó ủy quyền tiếp tục cho trình nạp lớp Bootstrap.

   **Lưu ý:** Ngoài các trình nạp lớp tích hợp sẵn ở trên, bạn cũng có thể tạo trình nạp lớp do người dùng xác định của riêng mình để đảm bảo tính độc lập của ứng dụng. Ví dụ: máy chủ web Tomcat sử dụng phương pháp này (WebAppClassLoader) để đảm bảo rằng các ứng dụng web khác nhau sẽ tải và tách biệt các lớp/lọ.

   2. **Vùng dữ liệu thời gian chạy/vùng bộ nhớ:**

      Các vùng dữ liệu thời gian chạy chủ yếu được chia thành năm thành phần,

      1. **Phương thức:** Vùng phương thức lưu trữ thông tin ở cấp độ lớp bên dưới,

         1. Tham chiếu ClassLoader
         2. Nhóm hằng số thời gian chạy
         3. Dữ liệu trường như tên, loại, công cụ sửa đổi, thuộc tính, v.v. của từng trường.
         4. Dữ liệu phương thức như tên, kiểu trả về, bộ sửa đổi, thuộc tính, loại tham số, v.v. của từng trường.
         5. Dữ liệu của hàm tạo như các loại tham số và thứ tự của chúng cho mỗi hàm tạo.

      Đây là tài nguyên được chia sẻ và chỉ có một vùng phương thức có sẵn cho mỗi JVM.

      2. **Heap:** Đây là vùng dữ liệu thời gian chạy trong đó tất cả các đối tượng và các biến thể hiện tương ứng của chúng được lưu trữ. Vùng heap được tạo khi khởi động JVM và chỉ có một vùng heap cho mỗi JVM.

      3. **Ngăn xếp:** Mỗi luồng được tạo trong JVM, một ngăn xếp thời gian chạy riêng biệt cũng được tạo cùng lúc. Các biến cục bộ, lệnh gọi phương thức và kết quả trung gian được lưu trữ trong vùng ngăn xếp này. Nhưng nếu luồng yêu cầu kích thước ngăn xếp lớn hơn kích thước có sẵn, JVM sẽ đưa ra `StackOverflow` lỗi.

      Đối với mỗi lệnh gọi phương thức, một khung ngăn xếp được tạo trong vùng bộ nhớ ngăn xếp và nó sẽ bị hủy khi quá trình thực thi phương thức hoàn tất. Mỗi khung ngăn xếp được chia thành ba phần.

      1. **Biến cục bộ:** Đối với mỗi khung, tất cả biến cục bộ và giá trị của chúng được lưu trữ ở định dạng mảng.
      2. **Ngăn xếp toán hạng:** Trong mỗi khung, các biến và toán tử cần thiết cho các phép toán được lưu trữ trong ngăn xếp LIFO.
      3. **Dữ liệu khung:** Khu vực này chứa tất cả các tham chiếu tượng trưng liên quan đến độ phân giải nhóm không đổi và dữ liệu trả về của phương thức. Nó cũng được sử dụng để lưu trữ một tham chiếu đến bảng ngoại lệ có tất cả thông tin liên quan đến khối bắt trong trường hợp có ngoại lệ.

      **Lưu ý:** Vùng ngăn xếp không phải là tài nguyên được chia sẻ.

      4. **Thanh ghi PC:** JVM hỗ trợ nhiều luồng cùng lúc và mỗi luồng có các thanh ghi PC riêng biệt. Các thanh ghi này được sử dụng để lưu trữ địa chỉ của lệnh JVM hiện đang được thực thi. Sau khi hoàn thành lệnh hiện tại, thanh ghi PC sẽ được cập nhật với lệnh tiếp theo.

      5. **Ngăn xếp phương thức gốc:** Ngăn xếp này được sử dụng để chứa thông tin liên quan đến các phương thức gốc được viết bằng C, C++ và Assembly.

   3. **Công cụ thực thi:** Công cụ thực thi chịu trách nhiệm thực thi mã byte được tải vào JVM. Nó giao tiếp với các bộ nhớ dữ liệu thời gian chạy khác nhau của JVM trong quá trình thực thi. Sau khi chương trình thực thi xong, bộ nhớ trong vùng dữ liệu thời gian chạy sẽ được giải phóng.

      Nó chứa ba thành phần chính để thực thi các tệp lớp.

      1. **Trình thông dịch:** Trình thông dịch đọc và thực thi từng dòng lệnh mã byte để chuyển đổi thành các lệnh ngôn ngữ máy tương ứng. Ưu điểm chính của trình thông dịch là tải và thực thi mã rất nhanh với tốc độ nhanh hơn. Nhưng bất cứ khi nào nó thực thi lặp đi lặp lại cùng một khối mã, trình thông dịch sẽ thực thi lặp đi lặp lại. Vì vậy, trình thông dịch không thể tối ưu hóa thời gian chạy trong trường hợp thực thi mã lặp lại.

      2. **Trình biên dịch JIT:** Just-In-Time Compiler (Trình biên dịch JIT) được ra mắt nhằm khắc phục những nhược điểm của trình thông dịch, đặc biệt là với việc thực thi mã lặp đi lặp lại. Trình biên dịch JIT có thể ghi nhớ các đoạn khối mã lặp lại và chúng sẽ được lưu dưới dạng mã gốc trong bộ đệm. Bất cứ khi nào trình biên dịch JIT đọc lại cùng một khối mã, nó sẽ sử dụng mã gốc được lưu trong bộ đệm.

      Trình biên dịch JIT đã chia thành các thành phần sau,

      1. **Trình tạo mã trung gian:** Nó tạo mã trung gian.
      2. **Trình tối ưu hóa mã:** Nó tối ưu hóa mã trung gian để có hiệu suất tốt hơn.
      3. **Trình tạo mã mục tiêu:** Nó chuyển đổi mã trung gian thành mã máy gốc.
      4. **Profiler:** Điều này được sử dụng để xác định các Điểm phát sóng (tức là các phương thức thực thi liên tục) và thay thế các điểm phát sóng bằng mã gốc tương ứng.

      5. **Bộ thu gom rác:** Bộ thu gom rác(GC) chịu trách nhiệm thu thập và loại bỏ các đối tượng không được tham chiếu khỏi vùng heap. Tính năng quản lý bộ nhớ này được sử dụng để lấy lại bộ nhớ chưa sử dụng và tạo không gian trống cho các đối tượng mới hơn. Điều này xảy ra trong hai giai đoạn:

         1. **Mark:** Ở bước này, GC xác định các đối tượng không sử dụng trong bộ nhớ
         2. **Quét:** Là một phần của bước này, GC sẽ loại bỏ các đối tượng được xác định ở giai đoạn trước.

   4. **Giao diện gốc Java (JNI):** JNI được sử dụng làm cầu nối giữa lệnh gọi phương thức java và thư viện gốc được viết bằng C, C++, v.v. Đôi khi, cần phải gọi mã gốc cho phần cứng được gạch chân cụ thể.
   5. **Thư viện phương thức gốc:** Đây là tập hợp các thư viện gốc (C/C++/Assembly) được yêu cầu bởi công cụ thực thi. Các thư viện này được tải thông qua JNI và được biểu diễn dưới dạng `.dll` hoặc `.so` tập tin.

   **[⬆ Quay lại đầu trang](#table-of-contents)**

4. ### Các tính năng chính của Java là gì

   Java có nhiều tính năng quan trọng khiến nó trở nên độc đáo trong số các ngôn ngữ lập trình phổ biến. Một số tính năng đó là:

   1. **Đơn giản:** Java là ngôn ngữ lập trình đơn giản và dễ hiểu mà không có bất kỳ sự phức tạp nào không giống như các ngôn ngữ lập trình trước đó.
      Một số lý do cho sự đơn giản là: 1. Nó dựa trên C++ giúp các nhà phát triển mới dễ dàng học nó một cách nhanh chóng. 2. Java không hỗ trợ con trỏ (không giống như C hoặc C++) vì tính phức tạp và các lỗ hổng bảo mật của nó. Ngoài ra, nạp chồng toán tử không tồn tại trong Java. 3. Không cần phải loại bỏ các đối tượng không được tham chiếu vì việc này sẽ được Bộ thu gom rác tự động xử lý.

   2. **Hướng đối tượng:** Java là ngôn ngữ lập trình hướng đối tượng (OOPS), có nghĩa là mọi thứ trong Java đều được thể hiện bằng các loại lớp và đối tượng khác nhau. OOPS này là một phương pháp giúp đơn giản hóa việc phát triển và bảo trì phần mềm bằng cách thực hiện theo các tính năng dưới đây.

      1. Trừu tượng
      2. đóng gói
      3. Kế thừa
      4. Đa hình

   3. **Di động:** Java có tính di động vì mã byte được tạo trên một máy có thể được đưa tới bất kỳ nền tảng nào để thực thi.

   4. **Nền tảng độc lập:** Trình biên dịch java chuyển đổi mã nguồn thành mã byte và sau đó JVM thực thi mã byte để tạo đầu ra. Nếu bạn biên dịch một chương trình java trên hệ điều hành cụ thể (giả sử là Windows), thì chương trình đó có thể chạy trên bất kỳ nền tảng nào khác (Windows, Linux hoặc Mac) với JVM dành riêng cho nền tảng đó. Đây là lý do tại sao chúng tôi gọi Java là ngôn ngữ độc lập với nền tảng.

   5. **Mạnh mẽ:** Java mạnh mẽ với nhiều biện pháp bảo vệ an toàn để đảm bảo mã đáng tin cậy. Nó có những người bảo vệ an toàn bên dưới,

      1. Nó có khả năng xử lý việc chấm dứt chương trình bất ngờ thông qua tính năng xử lý ngoại lệ.
      2. Nó cung cấp khả năng quản lý bộ nhớ mạnh mẽ thông qua Garbage Collector từ JVM, thu thập tất cả các biến và đối tượng không sử dụng để giải phóng không gian bộ nhớ. Trong khi đó ở các ngôn ngữ lập trình trước đó, lập trình viên hoàn toàn chịu trách nhiệm phân bổ và giải phóng không gian bộ nhớ.

   6. **Bảo mật:** Java cực kỳ an toàn nhờ có nhiều tính năng khác nhau được liệt kê bên dưới,

      1. Không có con trỏ rõ ràng. Vì vậy, bạn không thể truy cập mảng ngoài giới hạn. Nếu bạn vẫn cố truy cập vào một mảng, nó sẽ hiển thị một `ArrayIndexOutOfBound` Ngoại lệ. Vì vậy, không thể khai thác trong Java với các lỗi bảo mật như hỏng ngăn xếp hoặc tràn bộ đệm.
      2. Các chương trình chạy trong môi trường bảo mật (JVM) độc lập với hệ điều hành (OS).
      3. Java có trình xác minh mã byte để kiểm tra các khối mã xem có bất kỳ mã bất hợp pháp nào vi phạm quyền truy cập vào các đối tượng hay không.

   7. **Phân phối:** Java hỗ trợ tạo các ứng dụng phân tán bằng cách sử dụng Lệnh gọi phương thức từ xa (RMI) và Đậu Java doanh nghiệp. Các chương trình java được phân phối dễ dàng trên một hoặc nhiều hệ thống thông qua kết nối internet.

   8. **Đa luồng:** Java hỗ trợ tính năng đa luồng, cho phép thực thi đồng thời một số phần của chương trình để tận dụng tối đa CPU. Điều này có thể thực hiện được thông qua nhiều luồng chạy chương trình cùng một lúc.

   9. **Biên dịch và phiên dịch:** Nó cung cấp cả việc biên dịch và giải thích các chương trình. Các chương trình được biên dịch bởi trình biên dịch trước tiên và mã byte được tạo sẽ được diễn giải.

   10. **Hiệu suất cao:** Mã byte Java gần giống với mã gốc nên chạy nhanh hơn các ngôn ngữ lập trình được diễn giải thông thường khác. Tất nhiên, nó không nhanh bằng các ngôn ngữ được biên dịch như C hoặc C++. JVM cũng sử dụng trình biên dịch JIT cho phép đạt hiệu suất cao thông qua các tính năng bên dưới.
   11. Phương thức nội tuyến
   12. Loại bỏ mã chết
   13. Loại bỏ kiểm tra null
   14. Gấp liên tục

   **[⬆ Quay lại đầu trang](#table-of-contents)**

5. ### public static void main là gì?

   các `main()` phương thức này đóng vai trò là điểm khởi đầu để JVM bắt đầu thực thi chương trình Java. tức là JVM không thực thi mã nếu không có phương thức chính trong mã. Chữ ký của phương thức chính phải tuân theo mẫu cụ thể để JVM nhận ra nó là điểm vào. Vì đây là một phương thức quan trọng của Java nên bạn cần có sự hiểu biết đúng đắn về chữ ký của nó một cách chi tiết.

   Chữ ký của phương thức chính để hiển thị "Hello World" trông như bên dưới,

   ```java
   public static void main(String[] args) {
        System.out.println("Hello World");
   }
   ```

   Khi `java.exe` phân tích dòng lệnh, nó tạo ra một mảng String mới và gọi phương thức main(). Hãy mô tả từng từ trong câu lệnh,

   1. Công khai: Công cụ sửa đổi truy cập công khai có thể truy cập được ở mọi nơi và nó cho phép JVM có thể gọi nó từ bên ngoài lớp vì nó không có trong lớp hiện tại. Nếu không, bạn sẽ nhận được thông báo lỗi "Không tìm thấy phương thức chính trong lớp".

   2. Tĩnh: Từ khóa tĩnh này được sử dụng để thực hiện `main()` phương thức này làm phương thức liên quan đến lớp để JVM có thể gọi nó mà không cần khởi tạo lớp. Nó cũng hữu ích để tránh việc sử dụng bộ nhớ không cần thiết với đối tượng chỉ để gọi phương thức chính.

   3. Void: Từ khóa void được sử dụng để chỉ định rằng một phương thức không trả về bất cứ thứ gì. Vì phương thức main() không trả về bất cứ thứ gì nên kiểu trả về của nó là void. Khi phương thức chính kết thúc, chương trình java cũng chấm dứt.

   4. Chính: Tên phương thức "chính" là mã định danh mà JVM tìm kiếm làm điểm bắt đầu của chương trình Java.

   5. String[] args: Đây là một mảng các chuỗi lưu trữ các đối số được truyền bởi dòng lệnh trong khi khởi động chương trình.

   **Lưu ý:** Bạn có thể tạo bất kỳ số lượng phương thức chính nào thông qua các tính năng nạp chồng. tức là, Nhiều phương thức chính có thể được tạo với các tham số khác nhau.

   **[⬆ Quay lại đầu trang](#table-of-contents)**

6. ### Nhóm hằng chuỗi là gì

   Nhóm hằng chuỗi là một không gian lưu trữ đặc biệt bên trong vùng bộ nhớ heap nơi lưu trữ các chuỗi ký tự. Nó còn được gọi là **String pool** hoặc **String Intern Pool**. Điều này được duy trì riêng bởi lớp String và nó trống theo mặc định. Bất cứ khi nào bạn tạo một đối tượng chuỗi mới, JVM sẽ kiểm tra sự hiện diện của đối tượng chuỗi trong nhóm chuỗi. Nếu giá trị chuỗi đã có sẵn thì tham chiếu đối tượng tương tự sẽ được chia sẻ với biến, nếu không thì một chuỗi mới sẽ được tạo trong nhóm với tham chiếu biến được lưu trữ trong vùng ngăn xếp.

   **[⬆ Quay lại đầu trang](#table-of-contents)**

7. ### Tại sao chuỗi không thể thay đổi

   Chuỗi là bất biến, điều đó có nghĩa là nội dung của đối tượng chuỗi không thể sửa đổi sau khi tạo. tức là khi bạn cố gắng thay đổi chuỗi, nó sẽ tạo ra một chuỗi mới. Do hành vi này, trạng thái bên trong của chuỗi vẫn giữ nguyên trong suốt quá trình thực thi chương trình. Đặc tính bất biến này giúp mang lại lợi ích cho bộ nhớ đệm, bảo mật, đồng bộ hóa và hiệu suất.

   **[⬆ Quay lại đầu trang](#table-of-contents)**

8. ### Sự khác biệt giữa StringBuffer và StringBuilder là gì

   Chuỗi là một lớp bất biến để biểu diễn chuỗi ký tự. Java cũng cung cấp phiên bản có thể thay đổi của lớp String thông qua StringBuffer và StringBuilder. Mặc dù cả hai lớp này đều có thể thay đổi được nhưng có nhiều điểm khác biệt giữa StringBuffer và StringBuilder.

   Một số khác biệt chính ở dạng bảng:

   | Bộ đệm chuỗi | StringBuilder |
   | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
   | StringBuffer được giới thiệu trong phiên bản Java 1.0 | StringBuilder được giới thiệu trong phiên bản Java 1.5 |
   | StringBuffer được đồng bộ hóa (luồng an toàn). Điều đó có nghĩa là hai hoặc nhiều luồng không thể gọi các phương thức của StringBuffer cùng một lúc | StringBuilder không được đồng bộ hóa (không an toàn cho luồng). Điều đó có nghĩa là hai hoặc nhiều luồng có thể gọi các phương thức của StringBuilder cùng một lúc. |
   | Do đồng bộ hóa nên StringBuffer chậm hơn StringBuilder | StringBuilder nhanh hơn StringBuffer vì sẽ không có bất kỳ kiểm tra sơ bộ nào cho nhiều luồng |

   **[⬆ Quay lại đầu trang](#table-of-contents)**

9. ### Tầm quan trọng của phương thức hashCode() và Equals() là gì

   Vì cả hai `equals()` Và `hashCode()` các phương thức có sẵn trong lớp Object (tức là Java.lang.object), mọi lớp java đều được triển khai mặc định các phương thức bằng và hashCode. Các phương thức này phối hợp với nhau để xác minh xem hai đối tượng có cùng giá trị hay không.

   **1. bằng:** `equals()` phương pháp được sử dụng để so sánh sự bình đẳng của hai Đối tượng. Theo mặc định, việc triển khai của chúng sẽ so sánh danh tính của đối tượng. Lớp đối tượng được xác định `equals()` phương pháp như sau,

   ```java
   public boolean equals(Object obj) {
       return (this == obj);
   }
   ```

   Có một số quy tắc cần phải được tuân theo để sử dụng phương thức bằng:

   1. **Phản xạ:** Với mọi vật x, `x.equals(x)` nên quay lại `true`.
   2. **Đối xứng:** Với hai đối tượng x và y bất kỳ, `x.equals(y)` nên quay lại `true` nếu và chỉ khi `y.equals(x)` trả lại `true`.
   3. **Transitive:** Đối với nhiều đối tượng x, y và z, `if x.equals(y)` trả lại `true` Và `y.equals(z)` trả lại `true`, sau đó `x.equals(z)` nên quay lại `true`.
   4. **Nhất quán:** Đối với hai đối tượng x và y bất kỳ, nhiều lệnh gọi `x.equals(y)` sẽ trả về kết quả tương tự (`true` hoặc `false`), trừ khi bất kỳ thuộc tính đối tượng nào được sửa đổi đang được sử dụng trong triển khai phương thức bằng().

   **2. mã băm:** `hashCode()` phương thức trả về giá trị mã băm số nguyên của đối tượng. Phương thức này phải được ghi đè trong mọi lớp ghi đè `equals()` phương pháp. Hợp đồng chung của hashCode là:

   1. Trong khi thực thi ứng dụng, nhiều lời gọi của `hashCode()` trên đối tượng sẽ trả về cùng một giá trị nguyên, trừ khi thuộc tính đối tượng được sử dụng trong `equals()` phương pháp đang được sửa đổi.
   2. Trong quá trình thực thi ứng dụng nhiều lần, hashCode của đối tượng có thể thay đổi.
   3. Nếu hai đối tượng bằng nhau dựa trên `equals()` phương thức, thì mã băm của đối tượng của chúng phải giống nhau.
   4. Nếu hai đối tượng không bằng nhau dựa trên `equals()` phương thức, giá trị mã băm của chúng có thể bằng hoặc không bằng nhau.

   Cùng nhau thực hiện các `equals()` Và `hashCode()` nên tuân theo những quy tắc này.

   1. Nếu như `x.equals(y)` là đúng thì `x.hashCode() === y.hashCode()` phải luôn luôn đúng.
   2. Nếu như `x.hashCode() === y.hashCode()` là đúng thì không cần thiết phải như vậy `x.equals(y)` luôn đúng.

   **[⬆ Quay lại đầu trang](#table-of-contents)**

10. ### Sự khác biệt giữa các trường hợp ngoại lệ được kiểm tra và không được kiểm tra là gì

    Một ngoại lệ là một sự kiện làm gián đoạn quá trình thực hiện chương trình thông thường. Có hai loại ngoại lệ,

    1. Đã kiểm tra ngoại lệ
    2. Ngoại lệ không được kiểm tra

    Cấu trúc phân cấp của các ngoại lệ được phân loại như dưới đây,

    ![Screenshot](images/CheckedVsUncheckedException.png)

    Các ngoại lệ được kiểm tra tại thời điểm biên dịch được gọi là ngoại lệ được kiểm tra. Nếu một số mã bên trong một phương thức ném ra ngoại lệ đã kiểm tra này, thì bạn cần xử lý (hoặc bắt) ngoại lệ đó bằng cách sử dụng khối **try/catch** hoặc khai báo trong chữ ký phương thức bằng từ khóa **thows**.

    Một số trường hợp ngoại lệ được kiểm tra phổ biến là,

    1. IOException
    2. Tệp không tìm thấy ngoại lệ
    3. LớpNotFoundNgoại lệ
    4. Ngoại lệ bị gián đoạn
    5. Ngoại lệ SQL
    6. Phân tích ngoại lệ

    Ví dụ: lớp sau có hai phương thức ném check(`FileNotFoundException`) ngoại lệ từ hàm tạo FileInputStream. Điều này là do truy cập vào tệp đầu vào không tồn tại. Bạn có thể xử lý chúng bằng cách sử dụng khối try/catch hoặc khai báo từ khóa thos trong chữ ký phương thức.

    ```java
        import java.io.*;

        class MyCheckedExceptions {

            private void methodWithTryCatch() {
                    File file = new File("non_existing_file.txt");
                    try {
                        FileInputStream stream = new FileInputStream(file);
                    } catch (FileNotFoundException e) {
                        e.printStackTrace();
                    }
            }

            private void methodWithThrows() throws FileNotFoundException {
                    File file = new File("non_existing_file.txt");
                    FileInputStream stream = new FileInputStream(file);
            }

        }
    ```

    Trong khi đó, các ngoại lệ không được kiểm tra tại thời điểm biên dịch được gọi là ngoại lệ không được kiểm tra. Tất cả các ngoại lệ trong Lỗi và RuntimeException đều nằm trong các ngoại lệ không được kiểm tra.

    Một số trường hợp ngoại lệ không được kiểm tra phổ biến là,

    1. NullPointerNgoại lệ
    2. ArrayIndexOutOfBoundsNgoại lệ
    3. Ngoại lệ số học
    4. SốĐịnh dạngNgoại lệ
    5. Bất hợp phápThreadStateException

    Ví dụ: phương thức sau không có bất kỳ lỗi nào trong thời gian biên dịch. Nhưng nó sẽ ném `ArithmeticException` trong thời gian chạy vì chia cho số 0.

    ```java
    class MyUncheckedException {

        private void divideByZero() {
    	    int a = 1;
    	    int b = 0;
    	    int result = a / b;
        }

    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

11. ### Lớp bao bọc là gì

    Các lớp Wrapper cung cấp cơ chế chuyển đổi các kiểu nguyên thủy thành các kiểu đối tượng và ngược lại. Vì Java là ngôn ngữ lập trình hướng đối tượng và nhiều API cũng như thư viện trong Java yêu cầu các đối tượng thay vì các kiểu nguyên thủy. Ví dụ: cấu trúc dữ liệu trong khung bộ sưu tập, các lớp tiện ích từ `java.utils.*`,quá trình nhân bản, Tuần tự hóa, Đồng bộ hóa, v.v. yêu cầu loại đối tượng.

    Bảng sau biểu thị các nguyên hàm và các lớp bao bọc tương ứng của chúng.

    | Kiểu dữ liệu nguyên thủy | Lớp bao bọc |
    | ------------------- | ------------- |
    | thay đổi | Trao đổi |
    | ngắn | Ngắn |
    | int | Số nguyên |
    | phao | Phao |
    | đôi | Đôi |
    | dài | Dài |
    | boolean | Boolean |
    | char | Nhân vật |

    Bạn có thể sử dụng `.valueOf` các phương thức từ các lớp trình bao bọc để chuyển đổi kiểu nguyên thủy thành kiểu đối tượng và cách tương tự các phương thức của lớp trình bao bọc như `intValue`, `doubleValue` vv được sử dụng để chuyển đổi lớp bao bọc thành kiểu nguyên thủy. Nhưng quá trình thủ công này có thể được tự động hóa.

    1. **hộp thư tự động**

    Việc tự động chuyển đổi nguyên thủy thành đối tượng (lớp trình bao bọc tương ứng) được gọi là **autoboxing**. Ví dụ sau đây minh họa cách chuyển đổi hoạt động,

    ```java
    public class AutoboxingDemo{
        public static void main(String args[]){
            int num = 10;
            Integer x = Integer.valueOf(num); // Converting primitive int into Integer explicitly
            Integer y = num; // Autoboxing without explicit conversion

            System.out.println("x = "+ x + " y " + y);
        }
    }
    ```

    2. **mở hộp**
       Việc tự động chuyển đổi lớp trình bao bọc thành lớp gốc được gọi là **unboxing**. Ví dụ sau minh họa cả chuyển đổi thủ công và tự động,

    ```java
    public class UnboxingDemo{
       public static void main(String args[]){
           Integer num = new Integer(3);
           int x = num.intValue(); //Converting Integer to int explicitly
           int y = num; //Unboxing without manual conversion

           System.out.println("x ="+ x + "y = "+y);
       }
    }
    ```

    **Lưu ý:** Các tính năng tự động đóng hộp và mở hộp này có sẵn từ phiên bản JDK1.5 trở đi.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

12. ### Tại sao java không phải là ngôn ngữ hướng đối tượng thuần túy

    Java không phải là ngôn ngữ lập trình hướng đối tượng hoàn toàn vì hai lý do chính.

    1. Nó hỗ trợ các kiểu dữ liệu nguyên thủy như int, byte, long, short, v.v., không phải là đối tượng. Mặc dù bạn có thể chuyển đổi các kiểu dữ liệu nguyên thủy thành các đối tượng bằng cách sử dụng các lớp trình bao bọc, nhưng điều đó không làm cho Java trở thành ngôn ngữ hướng đối tượng thuần túy. Bởi vì các đối tượng này ban đầu không được liên kết với Java và bên trong nó sử dụng các hoạt động như Unboxing và Autoboxing. Điều đó có nghĩa là ngay cả khi bạn sử dụng các lớp trình bao bọc, nó vẫn sử dụng các kiểu nguyên thủy để tính toán.

    2. Cả biến và phương thức tĩnh đều có thể được truy cập mà không cần sử dụng đối tượng. Thay vào đó, chúng được liên kết với các lớp, điều này đi ngược lại nguyên tắc hướng đối tượng trong đó mọi thứ phải là một đối tượng.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

13. ### Sự khác biệt giữa lớp trừu tượng và giao diện là gì

    Cả lớp trừu tượng và giao diện đều được sử dụng để xác định hợp đồng trong lập trình hướng đối tượng. Nhưng có một số khác biệt chính giữa chúng như được hiển thị bên dưới,

    | Lớp trừu tượng | Giao diện |
    | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
    | các `abstract` từ khóa được sử dụng để khai báo lớp trừu tượng và nó có thể được mở rộng bằng cách sử dụng `extends` từ khóa | các `interface` từ khóa được sử dụng để khai báo giao diện và nó chỉ có thể mở rộng giao diện khác.                     |
    | Lớp trừu tượng chứa các phương thức trừu tượng và không trừu tượng | Giao diện chỉ có thể có các phương thức trừu tượng. Nhưng có thể có các phương thức mặc định và tĩnh từ Java8 trở đi |
    | Nó hỗ trợ các biến cuối cùng, không phải cuối cùng, tĩnh và không tĩnh | Nó chỉ hỗ trợ các biến cuối cùng và tĩnh.                                                                       |
    | Nó không hỗ trợ đa kế thừa | Giao diện hỗ trợ đa kế thừa |
    | Nó có thể có các công cụ sửa đổi quyền truy cập như công khai, được bảo vệ và riêng tư cho các phương thức và thuộc tính của chúng | Nó chỉ có thể có quyền truy cập công khai |

    **Lưu ý:** Cả lớp Trừu tượng và giao diện đều không thể khởi tạo được.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

14. ### Giao diện điểm đánh dấu là gì

    Giao diện điểm đánh dấu là các giao diện không có bất kỳ trường, phương thức hoặc hằng số nào bên trong nó. Chúng còn được gọi là giao diện trống hoặc giao diện thẻ. Ví dụ về giao diện điểm đánh dấu là giao diện Serializable, Cloneable và Remote. Mục đích của giao diện điểm đánh dấu là cung cấp thông tin loại thời gian chạy về một đối tượng cho JVM và Trình biên dịch. Chúng chủ yếu được sử dụng trong phát triển API và trong các framework như Spring để cung cấp thông tin bổ sung cho lớp.

    Một số giao diện đánh dấu tích hợp thường được sử dụng là:

    1. **Có thể nhân bản:** Nó có sẵn ở `java.lang` bưu kiện. Nếu chúng ta cố gắng sao chép một đối tượng không triển khai giao diện điểm đánh dấu này, JVM sẽ đưa ra một `CloneNotSupportedException`. tức là, Giao diện điểm đánh dấu này được sử dụng làm tín hiệu/chỉ báo cho JVM rằng việc gọi `Object.clone()` phương pháp.
    2. **Có thể tuần tự hóa:** Nó có sẵn ở `java.io` bưu kiện. Khi chúng tôi cố gắng ghi một đối tượng vào luồng đầu ra bằng cách sử dụng `ObjectOutputStream.writeObject()` phương thức mà không triển khai giao diện điểm đánh dấu này, JVM sẽ đưa ra một ngoại lệ có tên `NotSerializableException`.
    3. **Điều khiển từ xa:** Nó có sẵn ở `java.rmi` bưu kiện. Một đối tượng từ xa có thể được truy cập từ một máy khác khi và chỉ khi lớp đó đã triển khai giao diện đánh dấu này. Nếu không, nó sẽ ném ngoại lệ có tên `RemoteException`.

    Ví dụ: giao diện điểm đánh dấu có thể nhân bản trông như bên dưới,

    ```java
    public interface Cloneable {
       // nothing here
    }
    ```

    và lớp sinh viên sau đây triển khai giao diện Cloneable để tạo một bản sao đối tượng của sinh viên.

    ```java
    import java.lang.*;

    class Student implements cloneable {

        String name = null;
        int age = 0;

        Student(String name, int age) {
            this.name = name;
            this.age = age;
        }

        @Override
        protected Object clone() throws CloneNotSupportedException {
            return super.clone();
        }

        public static void main(String[] args) {

            Student s1 = new Student("Sudheer", 30);
            //Create clone of s1 object
            try {
                Student s2 = s1.clone();
            } catch (Exception e) {
                System.out.println(s2.toString());
            }
        }
    }

    ```

    Ngoài ra còn có các lựa chọn thay thế cho giao diện điểm đánh dấu.

    1. **Cờ nội bộ:** Chúng có thể được sử dụng thay cho giao diện điểm đánh dấu để biểu thị bất kỳ hoạt động cụ thể nào.
    2. **Chú thích:** Chúng được sử dụng làm thẻ để thể hiện siêu dữ liệu được đính kèm với các lớp, giao diện hoặc phương thức nhằm biểu thị thông tin bổ sung mà JVM yêu cầu.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

15. ### Bộ sưu tập trong Java là gì?

    Bộ sưu tập trong Java là một khung hợp nhất cung cấp kiến ​​trúc để lưu trữ và thao tác một nhóm đối tượng.

    các `java.util.*` gói chứa các lớp và giao diện sau cho khung Bộ sưu tập.

    ![Screenshot](images/CollectionsHierarchy.png)

    **[⬆ Quay lại đầu trang](#table-of-contents)**

16. ### Sự khác biệt giữa danh sách mảng và vectơ là gì?

    Cả Vector và ArrayList đều sử dụng mảng có thể thay đổi kích thước linh hoạt làm cấu trúc dữ liệu nội bộ của chúng và triển khai giao diện Danh sách. Nhưng có một số khác biệt giữa chúng như được liệt kê dưới đây,

    | Danh sách mảng | Vectơ |
    | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
    | Cấu trúc dữ liệu này là một phần của khung Bộ sưu tập, được giới thiệu trong JDK 1.2 | Đây là lớp kế thừa |
    | Mức tăng công suất của ArrayList là 50% nếu số phần tử vượt quá kích thước hiện tại | Mức tăng công suất của Vector là 100% nếu số phần tử vượt quá kích thước hiện tại |
    | Nó không được đồng bộ hóa theo mặc định. Điều đó có nghĩa là nhiều luồng có thể truy cập đồng thời.    | Nó được đồng bộ hóa theo mặc định. Điều đó có nghĩa là mỗi lần chỉ có một luồng có thể truy cập nó.          |
    | Nó khá nhanh vì không được đồng bộ hóa | Nó khá chậm do đồng bộ hóa |
    | ArrayList sử dụng giao diện Iterator để duyệt qua các phần tử.                          | Vector sử dụng cả giao diện Iterator và Enumeration để duyệt qua các phần tử.     |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

17. ### Phương thức hoàn thiện là gì? Làm thế nào để bạn ghi đè nó?

    các `finalize()` là một phương thức từ lớp Object được sử dụng để thực hiện hoạt động dọn dẹp trước khi hủy bất kỳ đối tượng nào. Phương thức này được trình thu thập rác gọi ra cho các hoạt động dọn dẹp như đóng các tài nguyên được liên kết với một đối tượng (kết nối cơ sở dữ liệu hoặc kết nối mạng). Quá trình này được gọi là **hoàn thiện** và nó giúp JVM tối ưu hóa trong bộ nhớ.

    Nó là một phương thức protected của lớp Object với cú pháp như sau:

    ```java
    protected void finalize() throws Throwable{}
    ```

    Vì Object là siêu lớp của tất cả các lớp java nên phương thức hoàn thiện có sẵn cho mọi lớp java. Đó là lý do tại sao người thu gom rác có thể gọi `finalize()` phương thức trên bất kỳ đối tượng java nào.

    Phương thức này có phần triển khai trống bên trong lớp Object. Nếu lớp của bạn có hoạt động dọn dẹp, bạn cần ghi đè phương thức này. Ví dụ sau đây minh họa cách ghi đè phương thức hoàn thiện và gọi phương thức này một cách rõ ràng.

    ```java
    import java.lang.*;

    public class finalizeDemo {

        protected void finalize() throws Throwable {
                try {

                    System.out.println("Inside finalize() method of finalizeDemo class");
                }
                catch (Throwable e) {

                    throw e;
                }
                finally {

                    System.out.println("Calling finalize method of the Object(super) class");

                    super.finalize();
                }
        }

        public static void main(String[] args) throws Throwable {
            finalizeDemo fd = new finalizeDemo();
            fd.finalize();
        }
    }
    ```

    Tuyên bố `super.finalize()` được gọi bên trong khối cuối cùng để đảm bảo việc thực thi nó ngay cả trong trường hợp ngoại lệ.

    **Lưu ý:** Trình thu gom rác gọi `finalize()` phương thức chỉ một lần trên bất kỳ đối tượng nào.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

18. ### Sự khác biệt giữa giao diện so sánh và giao diện so sánh là gì

    Java cung cấp các giao diện Comparable và Comparator để sắp xếp tập hợp các đối tượng, nhưng chúng phục vụ các mục đích khác nhau và được sử dụng trong các tình huống khác nhau. 

    **Có thể so sánh:**
    Giao diện Comparable có khả năng so sánh một đối tượng với một đối tượng khác cùng loại. Lớp cần so sánh các thể hiện của nó phải thực hiện `java.lang.Comparable` giao diện.
    Nó có thể được sử dụng để cung cấp **cách sắp xếp duy nhất**. Điều đó có nghĩa là các đối tượng có thể được sắp xếp dựa trên một thành viên dữ liệu duy nhất. Ví dụ: đối tượng Nhân viên có thể được sắp xếp dựa trên các thuộc tính đơn lẻ như id, tên, tuổi, v.v.

    Nếu lớp triển khai giao diện Comparable, nó sẽ biết cách sắp xếp các đối tượng vì chính lớp đó đã triển khai phương thức so sánh. Kiểu sắp xếp này được gọi là **sắp xếp mặc định hoặc tự nhiên**. Lớp có thể so sánh đối tượng của nó bằng cách ghi đè phương thức so sánh với cú pháp như dưới đây:

    ```java
    class T implements Comparable<T> {
        @Override
        public int compareTo(T t) {
            // comparison logic goes here
        }
    }
    ```

    Ví dụ: nhóm nhân viên được sắp xếp dựa trên thuộc tính tên của họ bằng giao diện Comparable như sau

    ```java
    import java.util.*;

    class Employee implements Comparable<Employee> {
        private final String id;
        private final String name;
        private final int age;
        
        public Employee(String id, String name, int age) {
            this.id = id;
            this.name = name;
            this.age = age;
        }
        
        @Override
        public int compareTo(final Employee employee) {
            return this.name.compareTo(employee.name);
        }
        
        public String getId() { return this.id; }
        
        public String getName() { return this.name; }
        
        public int getAge() { return this.age; }
        
        @Override
        public String toString() {
            return String.format("ID: %s | Name: %s | Age: %d", id, name, age);
        }
    }

    public class Main {
        public static void main(String[] args) {
            List<Employee> employees = new ArrayList<>();

            employees.add(new Employee("3", "John", 32));
            employees.add(new Employee("1", "James", 27));
            employees.add(new Employee("2", "Jackson", 22));
            
            Collections.sort(employees);

            employees.forEach(employee -> 
                                System.out.println(employee.toString()));
        }
    }
    ```

    **Bộ so sánh:**

    Bộ so sánh là một giao diện chức năng được sử dụng để sắp xếp các đối tượng và nó cung cấp **nhiều chuỗi sắp xếp** trong đó các đối tượng được sắp xếp dựa trên nhiều thành viên dữ liệu. Giao diện này có sẵn như là một phần của `java.util` bưu kiện.  Ví dụ: đối tượng Nhân viên có thể được sắp xếp dựa trên nhiều thuộc tính như id, tên, tuổi, v.v.

    Bộ so sánh được sử dụng để sắp xếp thứ tự tùy chỉnh khi lớp không biết về logic sắp xếp. Bộ so sánh có thể được tạo bằng cách sử dụng biểu thức lambda chấp nhận hai đối tượng cùng loại và trả về một giá trị số nguyên (tức là 1, 0, -1) dựa trên thứ tự với cú pháp như hiển thị bên dưới,

    ```java
     Comparator<T> comparator = (T t1, T t2) -> { 
        //comparison logic 
     }
    ```

    Bạn có thể tạo nhiều lớp riêng biệt (thực hiện giao diện Comparator) để so sánh giữa các thành viên khác nhau. Comparator cung cấp phương thức so sánh () có thể được ghi đè để tùy chỉnh logic so sánh. Ví dụ: nhóm nhân viên được sắp xếp dựa trên dữ liệu id và tuổi của các thành viên mặc dù lớp Nhân viên đã ghi đè phương thức so sánh.

    ```java
    public static void sortById(List<Employee> employees) {
        Comparator<Employee> idComparator = (Employee e1, Employee e2) -> {
            return e1.getId().compareTo(e2.getId());
        };
        
        employees.sort(idComparator);
    }
    
    public static void sortByAge(List<Employee> employees) {
        Comparator<Employee> ageComparator = (Employee e1, Employee e2) -> {
            return e1.getAge() - e2.getAge();
        };
        
        employees.sort(ageComparator);
    }
    ```

    Trong ví dụ trên, idComparator và ageComparator đã được tạo để thực hiện sắp xếp tùy chỉnh. Những bộ so sánh này cần được chuyển làm đối số cho phương thức sắp xếp.
    
    **Lưu ý:** Nên sử dụng biểu thức lambda để tạo Bộ so sánh vì đây là một giao diện chức năng (chính xác là một phương thức trừu tượng).


    **[⬆ Quay lại đầu trang](#table-of-contents)**

19. ### Lớp bên trong là gì

   Lớp bên trong là lớp được định nghĩa bên trong một lớp khác. Các lớp bên trong được sử dụng để nhóm các lớp một cách hợp lý chỉ được sử dụng ở một nơi, tăng khả năng đóng gói và làm cho mã dễ đọc và dễ bảo trì hơn. Java hỗ trợ bốn loại lớp bên trong:

   1. **Lớp bên trong thành viên (Lớp lồng nhau không tĩnh):** Một lớp được xác định bên trong một lớp khác mà không có công cụ sửa đổi tĩnh. Nó có quyền truy cập vào tất cả các thành viên của lớp bên ngoài, bao gồm cả các thành viên riêng tư.

   ```java
   class Outer {
       private int data = 30;
       
       class Inner {
           void display() {
               System.out.println("Data: " + data);
           }
       }
       
       public static void main(String[] args) {
           Outer outer = new Outer();
           Outer.Inner inner = outer.new Inner();
           inner.display();
       }
   }
   ```

   2. **Lớp lồng nhau tĩnh:** Một lớp tĩnh được xác định bên trong một lớp khác. Nó chỉ có thể truy cập các thành viên tĩnh của lớp bên ngoài.

   ```java
   class Outer {
       static int data = 30;
       
       static class StaticNested {
           void display() {
               System.out.println("Data: " + data);
           }
       }
       
       public static void main(String[] args) {
           Outer.StaticNested nested = new Outer.StaticNested();
           nested.display();
       }
   }
   ```

   3. **Lớp bên trong cục bộ:** Một lớp được xác định trong một phương thức. Nó có thể truy cập các biến cục bộ là cuối cùng hoặc cuối cùng một cách hiệu quả.

   ```java
   class Outer {
       void display() {
           final int num = 23;
           
           class LocalInner {
               void print() {
                   System.out.println("Number: " + num);
               }
           }
           
           LocalInner inner = new LocalInner();
           inner.print();
       }
   }
   ```

   4. **Lớp bên trong ẩn danh:** Một lớp không có tên, được dùng để khởi tạo các đối tượng bằng một số tính năng bổ sung nhất định, chẳng hạn như các phương thức ghi đè.

   ```java
   abstract class Animal {
       abstract void sound();
   }
   
   class Test {
       public static void main(String[] args) {
           Animal dog = new Animal() {
               void sound() {
                   System.out.println("Bark");
               }
           };
           dog.sound();
       }
   }
   ```

   **[⬆ Quay lại đầu trang](#table-of-contents)**

20. ### Sự khác biệt giữa cuối cùng, cuối cùng và hoàn thiện() trong Java là gì?

   Các điều khoản `final`, `finally`, Và `finalize()` trong Java trông giống nhau nhưng phục vụ các mục đích hoàn toàn khác nhau.

   1. **cuối cùng** → Nó là **công cụ sửa đổi** được sử dụng cho các biến, phương thức và lớp.  
      - MỘT `final` biến không thể được gán lại sau khi khởi tạo.  
      - MỘT `final` phương thức không thể bị ghi đè trong các lớp con.  
      - MỘT `final` lớp học không thể được mở rộng.  

   2. **cuối cùng** → Đó là một **khối** được sử dụng trong **xử lý ngoại lệ** để thực thi mã quan trọng như đóng tệp, giải phóng kết nối, v.v.  
      - các `finally` khối thực thi **bất kể** có xảy ra ngoại lệ hay không.  

   3. **finalize()** → Đó là một **phương thức** được định nghĩa trong `Object` lớp mà **Garbage Collector** gọi trước khi hủy một đối tượng.  
      - Hiện nay nó hiếm khi được sử dụng vì thời gian thu gom rác không thể đoán trước được.

   **Ví dụ:**

   ```java
   public class FinalExample {
       final int VALUE = 100;

       public final void display() {
           System.out.println("Final method");
       }

       public static void main(String[] args) {
           try {
               System.out.println("Inside try block");
           } finally {
               System.out.println("Inside finally block");
           }
       }

       @Override
       protected void finalize() throws Throwable {
           System.out.println("Finalize method called");
       }
   }
   ```

   **[⬆ Quay lại đầu trang](#table-of-contents)**

21. ### Sự khác biệt giữa phương thức '==' và bằng() là gì?
    
    Cả hai phương thức **==** và **.equals()** đều được sử dụng để so sánh các đối tượng, nhưng chúng hoạt động theo những cách khác nhau:

    1. **== (So sánh tham khảo):** `==` toán tử so sánh địa chỉ bộ nhớ (tham chiếu) của hai đối tượng. Nó trở lại `true` nếu cả hai tham chiếu đều trỏ đến cùng một đối tượng trong bộ nhớ.

    2. **.equals() (So sánh nội dung):** `.equals()` phương thức so sánh nội dung hoặc giá trị thực tế của hai đối tượng. Theo mặc định, nó hoạt động như `==`, nhưng nó có thể được ghi đè để cung cấp logic so sánh tùy chỉnh.

    ```java
    public class ComparisonExample {
        public static void main(String[] args) {
            String s1 = new String("Hello");
            String s2 = new String("Hello");
            String s3 = s1;
            
            // == compares references
            System.out.println(s1 == s2);      // false (different objects)
            System.out.println(s1 == s3);      // true (same reference)
            
            // equals() compares content
            System.out.println(s1.equals(s2)); // true (same content)
            System.out.println(s1.equals(s3)); // true (same content)
        }
    }
    ```

    | == Toán tử | Phương thức bằng() |
    |-------------|-----------------|
    | So sánh các tham chiếu đối tượng | So sánh nội dung đối tượng |
    | Không thể ghi đè | Có thể bị ghi đè |
    | Hoạt động với các đối tượng và nguyên thủy | Chỉ hoạt động với các đối tượng |
    | Trả về true nếu cùng một vị trí bộ nhớ | Trả về true nếu nội dung giống nhau |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

22. ### Nạp chồng phương thức và ghi đè phương thức là gì?

    Nạp chồng phương thức và ghi đè phương thức là hai khái niệm quan trọng trong Java cho phép đa hình.

    ** Nạp chồng phương thức (Đa hình thời gian biên dịch):**
    Quá tải phương thức xảy ra khi nhiều phương thức trong cùng một lớp có cùng tên nhưng khác tham số (số lượng, loại hoặc thứ tự tham số khác nhau). Kiểu trả về có thể giống hoặc khác nhau.

    ```java
    class Calculator {
        // Method with two int parameters
        int add(int a, int b) {
            return a + b;
        }
        
        // Overloaded method with three int parameters
        int add(int a, int b, int c) {
            return a + b + c;
        }
        
        // Overloaded method with double parameters
        double add(double a, double b) {
            return a + b;
        }
    }
    ```

    **Ghi đè phương thức (Đa hình thời gian chạy):**
    Ghi đè phương thức xảy ra khi một lớp con cung cấp cách triển khai cụ thể của một phương thức đã được xác định trong lớp cha của nó. Phương thức phải có cùng tên, kiểu trả về và tham số.

    ```java
    class Animal {
        void sound() {
            System.out.println("Animal makes a sound");
        }
    }
    
    class Dog extends Animal {
        @Override
        void sound() {
            System.out.println("Dog barks");
        }
    }
    
    class Cat extends Animal {
        @Override
        void sound() {
            System.out.println("Cat meows");
        }
    }
    ```

    | Quá tải phương thức | Ghi đè phương thức |
    |--------------------|-------------------|
    | Tên phương thức giống nhau, tham số khác nhau | Cùng tên phương thức, cùng tham số |
    | Xảy ra trong cùng một lớp | Xảy ra giữa lớp cha và lớp con |
    | Đa hình thời gian biên dịch | Đa hình thời gian chạy |
    | Kiểu trả về có thể khác | Kiểu trả về phải giống nhau hoặc hiệp biến |
    | Công cụ sửa đổi quyền truy cập có thể là bất kỳ | Không thể giảm công cụ sửa đổi quyền truy cập |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

23. ### Sự khác biệt giữa HashMap và Hashtable là gì?

    Cả HashMap và Hashtable đều được sử dụng để lưu trữ các cặp khóa-giá trị trong Java, nhưng chúng có một số điểm khác biệt quan trọng:

    | HashMap | Bảng băm |
    |---------|-----------|
    | Không được đồng bộ hóa (không an toàn cho luồng) | Đã đồng bộ hóa (an toàn theo luồng) |
    | Cho phép một khóa null và nhiều giá trị null | Không cho phép khóa hoặc giá trị null |
    | Được giới thiệu trong Java 1.2 | Lớp kế thừa từ Java 1.0 |
    | Nhanh hơn do không đồng bộ hóa | Chậm hơn do chi phí đồng bộ hóa |
    | Iterator bị lỗi nhanh | Điều tra viên không nhanh chóng thất bại |
    | Mở rộng lớp Bản đồ trừu tượng | Mở rộng lớp Từ điển |
    | Được ưu tiên cho các ứng dụng đơn luồng | Có thể được sử dụng trong các ứng dụng đa luồng |

    ```java
    import java.util.*;

    public class MapComparison {
        public static void main(String[] args) {
            // HashMap example
            HashMap<String, Integer> hashMap = new HashMap<>();
            hashMap.put("One", 1);
            hashMap.put(null, 0);        // Allows null key
            hashMap.put("Two", null);    // Allows null value
            
            // Hashtable example
            Hashtable<String, Integer> hashtable = new Hashtable<>();
            hashtable.put("One", 1);
            // hashtable.put(null, 0);   // Throws NullPointerException
            // hashtable.put("Two", null); // Throws NullPointerException
        }
    }
    ```

    **Lưu ý:** Đối với các hoạt động an toàn theo luồng, hãy ưu tiên `ConcurrentHashMap` qua `Hashtable` vì nó cung cấp hiệu suất tốt hơn thông qua khóa cấp phân khúc.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

24. ### Sự khác biệt giữa ArrayList và LinkedList là gì?

    Cả ArrayList và LinkedList đều triển khai giao diện Danh sách nhưng khác nhau về đặc tính hiệu suất và triển khai nội bộ của chúng.

    | Danh sách mảng | Danh sách liên kết |
    |-----------|------------|
    | Sử dụng mảng động trong nội bộ | Sử dụng danh sách liên kết đôi trong nội bộ |
    | Tốt hơn cho việc lưu trữ và truy cập dữ liệu (O(1) cho get) | Tốt hơn cho việc thao tác dữ liệu (O(1) để thêm/xóa ở cuối) |
    | Thao tác chậm hơn khi cần chuyển số | Thao tác nhanh hơn, không cần dịch chuyển |
    | Chỉ triển khai giao diện Danh sách | Triển khai giao diện List và Deque |
    | Hiệu quả bộ nhớ hơn | Thêm chi phí bộ nhớ (lưu trữ các tài liệu tham khảo trước/tiếp theo) |
    | Tốt cho truy cập ngẫu nhiên | Tốt cho truy cập tuần tự |

    ```java
    import java.util.*;

    public class ListComparison {
        public static void main(String[] args) {
            // ArrayList - better for random access
            ArrayList<String> arrayList = new ArrayList<>();
            arrayList.add("A");
            arrayList.add("B");
            arrayList.get(0);  // O(1) - fast random access
            
            // LinkedList - better for frequent insertions/deletions
            LinkedList<String> linkedList = new LinkedList<>();
            linkedList.add("A");
            linkedList.addFirst("B");  // O(1) - fast insertion at beginning
            linkedList.removeLast();   // O(1) - fast removal at end
        }
    }
    ```

    **Khi nào nên sử dụng:**
    - Sử dụng **ArrayList** khi bạn cần truy cập thường xuyên vào các phần tử theo chỉ mục
    - Sử dụng **Danh sách liên kết** khi bạn cần chèn/xóa thường xuyên, đặc biệt là ở đầu hoặc giữa danh sách

    **[⬆ Quay lại đầu trang](#table-of-contents)**

25. ### API phản chiếu Java là gì?

    Java Reflection API là một tính năng mạnh mẽ cho phép các chương trình kiểm tra và sửa đổi hành vi của các lớp, giao diện, phương thức và trường trong thời gian chạy. Nó là một phần của `java.lang.reflect` bưu kiện.

    **Các khả năng chính của Reflection:**
    1. Kiểm tra thuộc tính lớp khi chạy
    2. Tạo đối tượng một cách linh hoạt
    3. Gọi các phương thức trong thời gian chạy
    4. Truy cập và sửa đổi các trường riêng tư
    5. Nhận thông tin về hàm tạo, phương thức và trường

    ```java
    import java.lang.reflect.*;

    class Person {
        private String name;
        public int age;
        
        public Person() {}
        
        public Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
        
        private void privateMethod() {
            System.out.println("Private method called");
        }
        
        public void display() {
            System.out.println("Name: " + name + ", Age: " + age);
        }
    }

    public class ReflectionDemo {
        public static void main(String[] args) throws Exception {
            // Get Class object
            Class<?> clazz = Person.class;
            
            // Get class name
            System.out.println("Class: " + clazz.getName());
            
            // Get all declared methods
            Method[] methods = clazz.getDeclaredMethods();
            for (Method method : methods) {
                System.out.println("Method: " + method.getName());
            }
            
            // Create instance dynamically
            Constructor<?> constructor = clazz.getConstructor(String.class, int.class);
            Person person = (Person) constructor.newInstance("John", 25);
            
            // Access private field
            Field nameField = clazz.getDeclaredField("name");
            nameField.setAccessible(true);
            nameField.set(person, "Jane");
            
            // Invoke method
            Method displayMethod = clazz.getMethod("display");
            displayMethod.invoke(person);
        }
    }
    ```

    **Các trường hợp sử dụng:** Các khung như Spring, Hibernate, JUnit sử dụng Reflection rộng rãi để chèn phần phụ thuộc, ánh xạ ORM và thực thi thử nghiệm.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

26. ### Các loại vùng nhớ khác nhau được JVM phân bổ là gì?

    JVM phân bổ bộ nhớ ở các vùng khác nhau để thực thi chương trình hiệu quả. Các vùng nhớ chính là:

    1. **Vùng phương thức (Metaspace):**
       - Lưu trữ dữ liệu cấp lớp như cấu trúc lớp, dữ liệu phương thức và nhóm hằng số thời gian chạy
       - Được chia sẻ giữa tất cả các chủ đề
       - Được tạo trong quá trình khởi động JVM

    2. **Diện tích vùng heap:**
       - Lưu trữ tất cả các đối tượng và các biến thể hiện của chúng
       - Được chia sẻ giữa tất cả các chủ đề
       - Được quản lý bởi Garbage Collector
       - Được chia thành Thế hệ trẻ (không gian Eden, Người sống sót) và Thế hệ cũ

    3. **Diện tích ngăn xếp:**
       - Mỗi luồng có ngăn xếp riêng
       - Lưu trữ các biến cục bộ, lệnh gọi phương thức và kết quả một phần
       - Chứa các khung ngăn xếp cho mỗi lần gọi phương thức
       - Bộ nhớ được tự động cấp phát/giải phóng

    4. **Thanh ghi PC (Bộ đếm chương trình):**
       - Mỗi luồng có thanh ghi PC riêng
       - Lưu trữ địa chỉ của lệnh JVM hiện đang thực thi
       - Cập nhật sau mỗi lần thực hiện lệnh

    5. **Ngăn xếp phương thức gốc:**
       - Chứa thông tin phương thức gốc
       - Mỗi luồng có ngăn xếp phương thức gốc riêng
       - Được sử dụng cho các phương thức được viết bằng các ngôn ngữ khác ngoài Java (C, C++)

    ```
    JVM Memory Structure:
    ┌─────────────────────────────────────────────┐
    │              Method Area (Metaspace)         │
    │  (Class data, Method data, Constant pool)   │
    ├─────────────────────────────────────────────┤
    │                  Heap Area                   │
    │  ┌─────────────────┬─────────────────────┐  │
    │  │ Young Generation│   Old Generation    │  │
    │  │ (Eden,Survivor) │                     │  │
    │  └─────────────────┴─────────────────────┘  │
    ├─────────────────────────────────────────────┤
    │  Stack │  Stack  │  Stack  │ ... (per thread)│
    ├─────────────────────────────────────────────┤
    │  PC Reg│  PC Reg │  PC Reg │ ... (per thread)│
    ├─────────────────────────────────────────────┤
    │  Native│ Native  │ Native  │ ... (per thread)│
    └─────────────────────────────────────────────┘
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

27. ### Sự khác biệt giữa ném và ném là gì?

    Cả hai `throw` Và `throws` được sử dụng trong xử lý ngoại lệ nhưng phục vụ các mục đích khác nhau.

    **ném:**
    - Được sử dụng để ném một ngoại lệ một cách rõ ràng
    - Được sử dụng bên trong thân phương thức
    - Chỉ có thể ném một ngoại lệ tại một thời điểm
    - Tiếp theo là một trường hợp ngoại lệ

    **ném:**
    - Được sử dụng để khai báo các ngoại lệ mà một phương thức có thể đưa ra
    - Được sử dụng trong chữ ký phương thức
    - Có thể khai báo nhiều ngoại lệ
    - Tiếp theo là tên lớp ngoại lệ

    ```java
    import java.io.*;

    public class ThrowVsThrows {
        
        // Using throws - declares that method may throw an exception
        public void readFile(String filename) throws FileNotFoundException, IOException {
            FileReader file = new FileReader(filename);
            BufferedReader reader = new BufferedReader(file);
            String line = reader.readLine();
            reader.close();
        }
        
        // Using throw - explicitly throws an exception
        public void validateAge(int age) {
            if (age < 0) {
                throw new IllegalArgumentException("Age cannot be negative");
            }
            if (age < 18) {
                throw new ArithmeticException("Not eligible to vote");
            }
            System.out.println("Eligible to vote");
        }
        
        // Combining throw and throws
        public void processData(String data) throws CustomException {
            if (data == null) {
                throw new CustomException("Data cannot be null");
            }
            // Process data
        }
    }

    class CustomException extends Exception {
        public CustomException(String message) {
            super(message);
        }
    }
    ```

    | ném | ném |
    |-------|--------|
    | Được sử dụng để ném một ngoại lệ | Dùng để khai báo một ngoại lệ |
    | Nội dung phương thức bên trong | Trong chữ ký phương thức |
    | Không thể ném nhiều ngoại lệ | Có thể khai báo nhiều ngoại lệ |
    | Tiếp theo là ví dụ | Tiếp theo là tên lớp |
    | Các trường hợp ngoại lệ đã được kiểm tra phải được phát hiện | Tuyên truyền ngoại lệ cho người gọi |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

28. ### Lớp singleton là gì và cách tạo một lớp như thế nào?

    Lớp Singleton là mẫu thiết kế đảm bảo chỉ có một phiên bản của lớp được tạo trong suốt vòng đời của ứng dụng. Nó cung cấp một điểm truy cập toàn cầu vào trường hợp đó.

    **Đặc điểm chính:**
    - Nhà xây dựng riêng để ngăn chặn việc khởi tạo trực tiếp
    - Phương thức tĩnh để lấy phiên bản duy nhất
    - Biến tĩnh để giữ phiên bản đơn

    **Các cách khác nhau để tạo Singleton:**

    1. **Khởi tạo háo hức:**
    ```java
    public class EagerSingleton {
        private static final EagerSingleton instance = new EagerSingleton();
        
        private EagerSingleton() {}
        
        public static EagerSingleton getInstance() {
            return instance;
        }
    }
    ```

    2. **Khởi tạo lười biếng:**
    ```java
    public class LazySingleton {
        private static LazySingleton instance;
        
        private LazySingleton() {}
        
        public static LazySingleton getInstance() {
            if (instance == null) {
                instance = new LazySingleton();
            }
            return instance;
        }
    }
    ```

    3. **Singleton an toàn theo luồng (Khóa kiểm tra hai lần):**
    ```java
    public class ThreadSafeSingleton {
        private static volatile ThreadSafeSingleton instance;
        
        private ThreadSafeSingleton() {}
        
        public static ThreadSafeSingleton getInstance() {
            if (instance == null) {
                synchronized (ThreadSafeSingleton.class) {
                    if (instance == null) {
                        instance = new ThreadSafeSingleton();
                    }
                }
            }
            return instance;
        }
    }
    ```

    4. **Bill Pugh Singleton (Phương pháp hay nhất):**
    ```java
    public class BillPughSingleton {
        private BillPughSingleton() {}
        
        private static class SingletonHelper {
            private static final BillPughSingleton INSTANCE = new BillPughSingleton();
        }
        
        public static BillPughSingleton getInstance() {
            return SingletonHelper.INSTANCE;
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

29. ### Tính năng API luồng Java 8 là gì?

    API luồng Java 8 cung cấp một cách tiếp cận chức năng để xử lý các bộ sưu tập đối tượng. Các luồng hỗ trợ các hoạt động tuần tự và song song trên dữ liệu.

    **Các tính năng chính:**
    1. **Đánh giá lười biếng:** Các thao tác trung gian không được thực thi cho đến khi thao tác đầu cuối được gọi
    2. **Đường ống:** Các hoạt động có thể được xâu chuỗi lại với nhau
    3. **Lặp lại nội bộ:** Luồng xử lý việc lặp lại nội bộ
    4. **Xử lý song song:** Thực hiện song song dễ dàng với `parallelStream()`

    **Hoạt động truyền phát chung:**

    ```java
    import java.util.*;
    import java.util.stream.*;

    public class StreamDemo {
        public static void main(String[] args) {
            List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
            
            // filter - filters elements based on condition
            List<Integer> evenNumbers = numbers.stream()
                .filter(n -> n % 2 == 0)
                .collect(Collectors.toList());
            // Result: [2, 4, 6, 8, 10]
            
            // map - transforms elements
            List<Integer> squares = numbers.stream()
                .map(n -> n * n)
                .collect(Collectors.toList());
            // Result: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
            
            // reduce - combines elements
            int sum = numbers.stream()
                .reduce(0, (a, b) -> a + b);
            // Result: 55
            
            // sorted - sorts elements
            List<Integer> sorted = numbers.stream()
                .sorted(Comparator.reverseOrder())
                .collect(Collectors.toList());
            
            // distinct - removes duplicates
            List<Integer> unique = Arrays.asList(1, 1, 2, 2, 3).stream()
                .distinct()
                .collect(Collectors.toList());
            // Result: [1, 2, 3]
            
            // limit and skip
            List<Integer> limited = numbers.stream()
                .skip(2)
                .limit(5)
                .collect(Collectors.toList());
            // Result: [3, 4, 5, 6, 7]
            
            // anyMatch, allMatch, noneMatch
            boolean hasEven = numbers.stream().anyMatch(n -> n % 2 == 0);
            boolean allPositive = numbers.stream().allMatch(n -> n > 0);
            
            // findFirst, findAny
            Optional<Integer> first = numbers.stream().findFirst();
            
            // count
            long count = numbers.stream().filter(n -> n > 5).count();
            
            // forEach
            numbers.stream().forEach(System.out::println);
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

30. ### Sự khác biệt giữa vòng lặp không nhanh và vòng lặp không an toàn là gì?

    Các trình vòng lặp trong Java có thể được phân loại là không nhanh hoặc không an toàn dựa trên hành vi của chúng khi bộ sưu tập cơ bản được sửa đổi trong quá trình lặp.

    **Trình lặp nhanh không thành công:**
    - Ném `ConcurrentModificationException` nếu bộ sưu tập được sửa đổi trong quá trình lặp
    - Hoạt động trên bộ sưu tập gốc
    - Ví dụ: các trình vòng lặp ArrayList, HashMap, HashSet
    - Công dụng `modCount` để phát hiện sửa đổi

    ```java
    import java.util.*;

    public class FailFastExample {
        public static void main(String[] args) {
            List<String> list = new ArrayList<>();
            list.add("A");
            list.add("B");
            list.add("C");
            
            Iterator<String> iterator = list.iterator();
            while (iterator.hasNext()) {
                String element = iterator.next();
                if (element.equals("B")) {
                    list.remove(element); // Throws ConcurrentModificationException
                }
            }
        }
    }
    ```

    **Trình lặp không an toàn:**
    - Không ném ngoại lệ nếu bộ sưu tập được sửa đổi trong quá trình lặp
    - Hoạt động trên một bản sao/bản sao của bộ sưu tập
    - Ví dụ: các trình vòng lặp CopyOnWriteArrayList, ConcurrentHashMap
    - Thêm chi phí bộ nhớ do sao chép

    ```java
    import java.util.concurrent.*;
    import java.util.*;

    public class FailSafeExample {
        public static void main(String[] args) {
            CopyOnWriteArrayList<String> list = new CopyOnWriteArrayList<>();
            list.add("A");
            list.add("B");
            list.add("C");
            
            Iterator<String> iterator = list.iterator();
            while (iterator.hasNext()) {
                String element = iterator.next();
                if (element.equals("B")) {
                    list.remove(element); // No exception thrown
                }
            }
            System.out.println(list); // [A, C]
        }
    }
    ```

    | Thất bại nhanh | Không an toàn |
    |-----------|-----------|
    | Ném ConcurrentModificationException | Không có ngoại lệ ném |
    | Hoạt động trên bộ sưu tập gốc | Hoạt động trên bản sao của bộ sưu tập |
    | Ít chi phí bộ nhớ hơn | Thêm chi phí bộ nhớ |
    | ArrayList, HashMap, HashSet | CopyOnWriteArrayList, ConcurrentHashMap |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

31. ###Sự khác biệt giữa tiến trình và luồng là gì?

    Một tiến trình và một luồng đều là các đơn vị thực thi, nhưng chúng khác nhau đáng kể về đặc điểm và cách sử dụng.

    **Quá trình:**
    - Chương trình thực thi độc lập với không gian bộ nhớ riêng
    - Chứa ít nhất một chủ đề (luồng chính)
    - Có không gian địa chỉ, vùng heap, ngăn xếp và tài nguyên hệ thống riêng
    - Các tiến trình được cách ly với nhau
    - Giao tiếp giữa các quá trình (IPC) đắt tiền

    **Chủ đề:**
    - Đơn vị thực thi nhẹ trong một quy trình
    - Chia sẻ không gian bộ nhớ với các luồng khác trong cùng tiến trình
    - Có ngăn xếp riêng nhưng chia sẻ đống với các luồng khác
    - Các luồng trong một tiến trình có thể giao tiếp trực tiếp
    - Chuyển đổi ngữ cảnh giữa các luồng nhanh hơn

    ```java
    public class ProcessVsThread {
        public static void main(String[] args) {
            // Creating a new process
            try {
                ProcessBuilder pb = new ProcessBuilder("notepad.exe");
                Process process = pb.start(); // Creates a new process
            } catch (Exception e) {
                e.printStackTrace();
            }
            
            // Creating a new thread
            Thread thread = new Thread(() -> {
                System.out.println("Thread running: " + Thread.currentThread().getName());
            });
            thread.start(); // Creates a new thread within the same process
        }
    }
    ```

    | Quy trình | Chủ đề |
    |---------|--------|
    | Trọng lượng nặng | Trọng lượng nhẹ |
    | Không gian bộ nhớ riêng | Không gian bộ nhớ dùng chung |
    | Chuyển ngữ cảnh chậm hơn | Chuyển đổi ngữ cảnh nhanh hơn |
    | Bị cô lập khỏi các quy trình khác | Có thể giao tiếp với các chủ đề khác |
    | Cần nhiều tài nguyên hơn | Ít tốn tài nguyên hơn |
    | Sự cố quy trình không ảnh hưởng đến người khác | Sự cố chủ đề có thể ảnh hưởng đến toàn bộ quá trình |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

32. ### Có những cách nào khác nhau để tạo một luồng trong Java?

    Có nhiều cách để tạo một luồng trong Java:

    **1. Mở rộng lớp Thread:**
    ```java
    class MyThread extends Thread {
        @Override
        public void run() {
            System.out.println("Thread running: " + Thread.currentThread().getName());
        }
    }

    // Usage
    MyThread thread = new MyThread();
    thread.start();
    ```

    **2. Triển khai giao diện Runnable:**
    ```java
    class MyRunnable implements Runnable {
        @Override
        public void run() {
            System.out.println("Runnable running: " + Thread.currentThread().getName());
        }
    }

    // Usage
    Thread thread = new Thread(new MyRunnable());
    thread.start();
    ```

    **3. Sử dụng biểu thức Lambda (Java 8+):**
    ```java
    Thread thread = new Thread(() -> {
        System.out.println("Lambda thread running");
    });
    thread.start();
    ```

    **4. Triển khai giao diện Callable (trả về kết quả):**
    ```java
    import java.util.concurrent.*;

    class MyCallable implements Callable<Integer> {
        @Override
        public Integer call() throws Exception {
            return 42;
        }
    }

    // Usage
    ExecutorService executor = Executors.newSingleThreadExecutor();
    Future<Integer> future = executor.submit(new MyCallable());
    Integer result = future.get(); // Gets the result
    executor.shutdown();
    ```

    **5. Sử dụng ExecutorService:**
    ```java
    ExecutorService executor = Executors.newFixedThreadPool(5);
    
    executor.execute(() -> {
        System.out.println("Task executed by: " + Thread.currentThread().getName());
    });
    
    executor.submit(() -> {
        return "Task completed";
    });
    
    executor.shutdown();
    ```

    | Phương pháp | Trả về giá trị | Có Thể Mở Rộng Lớp Khác | Xử lý ngoại lệ |
    |--------|--------------|------------------------|-------------------|
    | Lớp chủ đề | Không | Không | Chỉ bỏ chọn |
    | Có thể chạy được | Không | Có | Chỉ bỏ chọn |
    | Có thể gọi được | Có | Có | Đã kiểm tra và bỏ chọn |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

33. ### Đồng bộ hóa trong Java là gì?

    Đồng bộ hóa là một cơ chế đảm bảo mỗi lần chỉ có một luồng có thể truy cập tài nguyên được chia sẻ. Nó ngăn ngừa tình trạng chạy đua và đảm bảo an toàn cho luồng.

    **Các loại đồng bộ hóa:**

    **1. Phương pháp đồng bộ hóa:**
    ```java
    class Counter {
        private int count = 0;
        
        public synchronized void increment() {
            count++;
        }
        
        public synchronized int getCount() {
            return count;
        }
    }
    ```

    **2. Khối được đồng bộ hóa:**
    ```java
    class Counter {
        private int count = 0;
        private final Object lock = new Object();
        
        public void increment() {
            synchronized (lock) {
                count++;
            }
        }
    }
    ```

    **3. Đồng bộ hóa tĩnh:**
    ```java
    class StaticCounter {
        private static int count = 0;
        
        public static synchronized void increment() {
            count++;
        }
    }
    ```

    **Ví dụ minh họa nhu cầu đồng bộ hóa:**
    ```java
    class BankAccount {
        private int balance = 1000;
        
        // Without synchronization - race condition possible
        public void withdraw(int amount) {
            if (balance >= amount) {
                System.out.println(Thread.currentThread().getName() + " is withdrawing");
                balance -= amount;
                System.out.println("Balance after withdrawal: " + balance);
            }
        }
        
        // With synchronization - thread safe
        public synchronized void safeWithdraw(int amount) {
            if (balance >= amount) {
                System.out.println(Thread.currentThread().getName() + " is withdrawing");
                balance -= amount;
                System.out.println("Balance after withdrawal: " + balance);
            }
        }
    }
    ```

    **Những điểm chính:**
    - Mọi đối tượng trong Java đều có khóa (màn hình) nội tại
    - Mỗi lần chỉ có một luồng có thể giữ khóa
    - Đồng bộ hóa có thể gây ra chi phí hiệu suất
    - Ưu tiên các khối được đồng bộ hóa hơn các phương pháp được đồng bộ hóa để kiểm soát chi tiết hơn

    **[⬆ Quay lại đầu trang](#table-of-contents)**

34. ### Bế tắc là gì và làm thế nào để tránh nó?

    Bế tắc là tình huống trong đó hai hoặc nhiều luồng bị chặn vĩnh viễn, mỗi luồng chờ luồng kia giải phóng khóa.

    **Ví dụ bế tắc:**
    ```java
    public class DeadlockExample {
        private static final Object lock1 = new Object();
        private static final Object lock2 = new Object();
        
        public static void main(String[] args) {
            Thread thread1 = new Thread(() -> {
                synchronized (lock1) {
                    System.out.println("Thread 1: Holding lock1");
                    try { Thread.sleep(100); } catch (InterruptedException e) {}
                    
                    synchronized (lock2) {
                        System.out.println("Thread 1: Holding lock1 and lock2");
                    }
                }
            });
            
            Thread thread2 = new Thread(() -> {
                synchronized (lock2) {
                    System.out.println("Thread 2: Holding lock2");
                    try { Thread.sleep(100); } catch (InterruptedException e) {}
                    
                    synchronized (lock1) {
                        System.out.println("Thread 2: Holding lock2 and lock1");
                    }
                }
            });
            
            thread1.start();
            thread2.start();
        }
    }
    ```

    **Cách tránh bế tắc:**

    **1. Thứ tự khóa - Luôn lấy khóa theo cùng thứ tự:**
    ```java
    // Fixed version - both threads acquire locks in same order
    Thread thread1 = new Thread(() -> {
        synchronized (lock1) {
            synchronized (lock2) {
                // work
            }
        }
    });

    Thread thread2 = new Thread(() -> {
        synchronized (lock1) {  // Same order as thread1
            synchronized (lock2) {
                // work
            }
        }
    });
    ```

    **2. Sử dụng tryLock khi hết thời gian chờ:**
    ```java
    import java.util.concurrent.locks.*;

    ReentrantLock lock1 = new ReentrantLock();
    ReentrantLock lock2 = new ReentrantLock();

    public void safeMethod() {
        boolean gotLock1 = false;
        boolean gotLock2 = false;
        try {
            gotLock1 = lock1.tryLock(1, TimeUnit.SECONDS);
            gotLock2 = lock2.tryLock(1, TimeUnit.SECONDS);
            if (gotLock1 && gotLock2) {
                // Do work
            }
        } catch (InterruptedException e) {
            e.printStackTrace();
        } finally {
            if (gotLock1) lock1.unlock();
            if (gotLock2) lock2.unlock();
        }
    }
    ```

    **3. Tránh các khóa lồng nhau**
    **4. Sử dụng thời gian chờ khóa**
    **5. Tránh giữ ổ khóa trong thời gian dài**

    **[⬆ Quay lại đầu trang](#table-of-contents)**

35. ### Từ khóa dễ bay hơi trong Java là gì?

    các `volatile` từ khóa trong Java được sử dụng để chỉ ra rằng giá trị của một biến có thể được sửa đổi bởi các luồng khác nhau. Nó đảm bảo khả năng hiển thị các thay đổi trên các luồng và ngăn biến lưu vào bộ nhớ đệm.

    **Các tính năng chính:**
    1. **Chế độ hiển thị:** Những thay đổi được thực hiện bởi một luồng sẽ được hiển thị ngay lập tức đối với các luồng khác
    2. **Tính nguyên tử:** Các thao tác đọc và ghi trên các biến dễ bay hơi là nguyên tử (đối với các biến nguyên thủy)
    3. **Không có bộ nhớ đệm:** Biến luôn được đọc từ bộ nhớ chính, không phải từ bộ đệm CPU

    ```java
    public class VolatileExample {
        private volatile boolean running = true;
        
        public void stop() {
            running = false;
        }
        
        public void run() {
            while (running) {
                // Do work
            }
            System.out.println("Stopped");
        }
        
        public static void main(String[] args) throws InterruptedException {
            VolatileExample example = new VolatileExample();
            
            Thread worker = new Thread(() -> example.run());
            worker.start();
            
            Thread.sleep(1000);
            example.stop(); // This change will be visible to the worker thread
        }
    }
    ```

    **Không biến động:**
    ```java
    // Without volatile, the worker thread might never see the change
    // because it may read from its local cache
    private boolean running = true; // Thread may cache this value
    ```

    **Dễ bay hơi và được đồng bộ hóa:**
    | dễ bay hơi | đồng bộ |
    |----------|--------------|
    | Chỉ đảm bảo khả năng hiển thị | Đảm bảo khả năng hiển thị và tính nguyên tử |
    | Không chặn | Nguyên nhân chặn |
    | Không thể sử dụng cho các phép toán phức hợp | Có thể bảo vệ hoạt động ghép |
    | Ít chi phí hơn | Thêm chi phí |

    **Lưu ý:** Dễ bay hơi không phù hợp cho các hoạt động kết hợp như `count++`. Sử dụng `AtomicInteger` hoặc `synchronized` cho những trường hợp như vậy.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

36. ### Từ khóa tạm thời trong Java là gì?

    các `transient` từ khóa trong Java được sử dụng để chỉ ra rằng một trường không nên được tuần tự hóa khi đối tượng được chuyển đổi thành luồng byte.

    **Trường hợp sử dụng:**
    - Dữ liệu nhạy cảm như mật khẩu
    - Các trường được tính toán/dẫn xuất
    - Các trường không thể tuần tự hóa
    - Dữ liệu cục bộ

    ```java
    import java.io.*;

    class User implements Serializable {
        private static final long serialVersionUID = 1L;
        
        private String username;
        private transient String password;  // Will not be serialized
        private transient int loginCount;   // Will not be serialized
        
        public User(String username, String password) {
            this.username = username;
            this.password = password;
            this.loginCount = 0;
        }
        
        @Override
        public String toString() {
            return "User{username='" + username + "', password='" + password + 
                   "', loginCount=" + loginCount + "}";
        }
    }

    public class TransientDemo {
        public static void main(String[] args) {
            User user = new User("john", "secret123");
            user.loginCount = 5;
            System.out.println("Before serialization: " + user);
            
            // Serialize
            try (ObjectOutputStream oos = new ObjectOutputStream(
                    new FileOutputStream("user.ser"))) {
                oos.writeObject(user);
            } catch (IOException e) {
                e.printStackTrace();
            }
            
            // Deserialize
            try (ObjectInputStream ois = new ObjectInputStream(
                    new FileInputStream("user.ser"))) {
                User deserializedUser = (User) ois.readObject();
                System.out.println("After deserialization: " + deserializedUser);
                // Output: User{username='john', password='null', loginCount=0}
            } catch (IOException | ClassNotFoundException e) {
                e.printStackTrace();
            }
        }
    }
    ```

    **Những điểm chính:**
    - Các trường tạm thời nhận giá trị mặc định sau khi khử lưu lượng (null cho đối tượng, 0 cho số, sai cho boolean)
    - Các trường tĩnh không được tuần tự hóa bất kể từ khóa tạm thời
    - Có thể kết hợp với readObject/writeObject tùy chỉnh cho các tình huống phức tạp

    **[⬆ Quay lại đầu trang](#table-of-contents)**

37. ### Tuần tự hóa và giải tuần tự hóa là gì?

    **Nối tiếp** là quá trình chuyển đổi trạng thái của đối tượng thành luồng byte. **Khử tuần tự** là quá trình ngược lại - chuyển đổi luồng byte trở lại thành một đối tượng.

    **Tại sao phải tuần tự hóa?**
    - Duy trì trạng thái đối tượng vào tệp/cơ sở dữ liệu
    - Gửi đối tượng qua mạng
    - Đối tượng sao chép sâu
    - Đối tượng bộ nhớ đệm

    ```java
    import java.io.*;

    class Employee implements Serializable {
        private static final long serialVersionUID = 1L;
        
        private String name;
        private int id;
        private transient double salary; // Not serialized
        
        public Employee(String name, int id, double salary) {
            this.name = name;
            this.id = id;
            this.salary = salary;
        }
        
        @Override
        public String toString() {
            return "Employee{name='" + name + "', id=" + id + ", salary=" + salary + "}";
        }
    }

    public class SerializationDemo {
        public static void main(String[] args) {
            Employee emp = new Employee("John", 101, 50000);
            
            // Serialization
            try (ObjectOutputStream oos = new ObjectOutputStream(
                    new FileOutputStream("employee.ser"))) {
                oos.writeObject(emp);
                System.out.println("Object serialized successfully");
            } catch (IOException e) {
                e.printStackTrace();
            }
            
            // Deserialization
            try (ObjectInputStream ois = new ObjectInputStream(
                    new FileInputStream("employee.ser"))) {
                Employee deserializedEmp = (Employee) ois.readObject();
                System.out.println("Deserialized: " + deserializedEmp);
            } catch (IOException | ClassNotFoundException e) {
                e.printStackTrace();
            }
        }
    }
    ```

    **Xê-ri tùy chỉnh:**
    ```java
    class CustomSerializable implements Serializable {
        private String data;
        private transient String sensitiveData;
        
        private void writeObject(ObjectOutputStream oos) throws IOException {
            oos.defaultWriteObject();
            // Encrypt and write sensitive data
            oos.writeObject(encrypt(sensitiveData));
        }
        
        private void readObject(ObjectInputStream ois) 
                throws IOException, ClassNotFoundException {
            ois.defaultReadObject();
            // Decrypt sensitive data
            sensitiveData = decrypt((String) ois.readObject());
        }
        
        private String encrypt(String data) { return data; } // Placeholder
        private String decrypt(String data) { return data; } // Placeholder
    }
    ```

    **Quan trọng:** Luôn khai báo `serialVersionUID` để duy trì khả năng tương thích trong quá trình khử lưu huỳnh.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

38. ### Giao diện chức năng trong Java là gì?

    Giao diện chức năng là giao diện chứa chính xác một phương thức trừu tượng. Chúng là nền tảng cho các biểu thức lambda trong Java 8.

    **Đặc điểm chính:**
    - Có chính xác một phương thức trừu tượng
    - Có thể có nhiều phương thức mặc định và tĩnh
    - Có thể chú thích bằng `@FunctionalInterface`
    - Được sử dụng làm loại mục tiêu cho biểu thức lambda

    ```java
    @FunctionalInterface
    interface Calculator {
        int calculate(int a, int b);
        
        // Default method - allowed
        default void print(String msg) {
            System.out.println(msg);
        }
        
        // Static method - allowed
        static void info() {
            System.out.println("Calculator interface");
        }
    }

    public class FunctionalInterfaceDemo {
        public static void main(String[] args) {
            // Using lambda expression
            Calculator add = (a, b) -> a + b;
            Calculator multiply = (a, b) -> a * b;
            
            System.out.println("Sum: " + add.calculate(5, 3));      // 8
            System.out.println("Product: " + multiply.calculate(5, 3)); // 15
        }
    }
    ```

    **Giao diện chức năng tích hợp (java.util.function):**

    ```java
    import java.util.function.*;

    public class BuiltInFunctionalInterfaces {
        public static void main(String[] args) {
            // Predicate - takes input, returns boolean
            Predicate<Integer> isEven = n -> n % 2 == 0;
            System.out.println(isEven.test(4)); // true
            
            // Function - takes input, returns output
            Function<String, Integer> length = s -> s.length();
            System.out.println(length.apply("Hello")); // 5
            
            // Consumer - takes input, returns nothing
            Consumer<String> printer = s -> System.out.println(s);
            printer.accept("Hello"); // prints Hello
            
            // Supplier - takes nothing, returns output
            Supplier<Double> random = () -> Math.random();
            System.out.println(random.get()); // random number
            
            // BiFunction - takes two inputs, returns output
            BiFunction<Integer, Integer, Integer> add = (a, b) -> a + b;
            System.out.println(add.apply(5, 3)); // 8
            
            // UnaryOperator - takes input, returns same type
            UnaryOperator<Integer> square = n -> n * n;
            System.out.println(square.apply(5)); // 25
            
            // BinaryOperator - takes two inputs of same type, returns same type
            BinaryOperator<Integer> max = (a, b) -> a > b ? a : b;
            System.out.println(max.apply(5, 3)); // 5
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

39. ### Biểu thức lambda trong Java là gì?

    Biểu thức Lambda là các hàm ẩn danh cung cấp một cách ngắn gọn để triển khai các giao diện chức năng. Được giới thiệu trong Java 8, chúng cho phép lập trình hàm trong Java.

    **Cú pháp:**
    ```
    (parameters) -> expression
    (parameters) -> { statements; }
    ```

    **Ví dụ:**

    ```java
    import java.util.*;
    import java.util.function.*;

    public class LambdaExamples {
        public static void main(String[] args) {
            // No parameters
            Runnable runnable = () -> System.out.println("Hello Lambda!");
            runnable.run();
            
            // One parameter (parentheses optional)
            Consumer<String> consumer = s -> System.out.println(s);
            consumer.accept("Hello");
            
            // Multiple parameters
            BiFunction<Integer, Integer, Integer> add = (a, b) -> a + b;
            System.out.println(add.apply(5, 3));
            
            // With type declarations
            BiFunction<Integer, Integer, Integer> multiply = 
                (Integer a, Integer b) -> a * b;
            
            // Multiple statements (braces required)
            BiFunction<Integer, Integer, Integer> calculate = (a, b) -> {
                int sum = a + b;
                int product = a * b;
                return sum + product;
            };
            
            // With Collections
            List<String> names = Arrays.asList("John", "Jane", "Bob", "Alice");
            
            // forEach with lambda
            names.forEach(name -> System.out.println(name));
            
            // Method reference (shorthand for lambda)
            names.forEach(System.out::println);
            
            // Sorting with lambda
            names.sort((s1, s2) -> s1.compareTo(s2));
            
            // Using Comparator method reference
            names.sort(String::compareTo);
            
            // Filtering with streams
            List<String> filtered = names.stream()
                .filter(name -> name.startsWith("J"))
                .collect(Collectors.toList());
            
            // Mapping with streams
            List<Integer> lengths = names.stream()
                .map(name -> name.length())
                .collect(Collectors.toList());
        }
    }
    ```

    **Tham khảo phương pháp:**
    ```java
    // Static method reference
    Function<String, Integer> parseInt = Integer::parseInt;

    // Instance method reference
    String str = "Hello";
    Supplier<Integer> length = str::length;

    // Constructor reference
    Supplier<ArrayList<String>> listSupplier = ArrayList::new;
    ```

    **Những lợi ích:**
    - Mã ngắn gọn và dễ đọc
    - Cho phép lập trình chức năng
    - Hỗ trợ tốt hơn cho xử lý song song
    - Giảm mã soạn sẵn

    **[⬆ Quay lại đầu trang](#table-of-contents)**

40. ### Lớp tùy chọn trong Java 8 là gì?

    các `Optional` class là một đối tượng chứa có thể chứa hoặc không chứa giá trị khác null. Nó giúp tránh `NullPointerException` và làm cho việc xử lý null rõ ràng hơn.

    **Tạo tùy chọn:**
    ```java
    import java.util.Optional;

    public class OptionalDemo {
        public static void main(String[] args) {
            // Creating Optional
            Optional<String> empty = Optional.empty();
            Optional<String> name = Optional.of("John");
            Optional<String> nullable = Optional.ofNullable(null);
            
            // Checking if value present
            System.out.println(name.isPresent());     // true
            System.out.println(empty.isPresent());    // false
            System.out.println(empty.isEmpty());      // true (Java 11+)
            
            // Getting value
            String value = name.get();  // Returns "John"
            // String error = empty.get(); // Throws NoSuchElementException
            
            // Safe access with orElse
            String defaultName = empty.orElse("Unknown");  // "Unknown"
            
            // orElseGet - lazy evaluation
            String lazyDefault = empty.orElseGet(() -> computeDefault());
            
            // orElseThrow
            String required = name.orElseThrow(() -> 
                new IllegalArgumentException("Name is required"));
            
            // ifPresent - execute if value exists
            name.ifPresent(n -> System.out.println("Name: " + n));
            
            // ifPresentOrElse (Java 9+)
            name.ifPresentOrElse(
                n -> System.out.println("Found: " + n),
                () -> System.out.println("Not found")
            );
        }
        
        static String computeDefault() {
            return "Computed Default";
        }
    }
    ```

    **Tùy chọn với Luồng:**
    ```java
    public class OptionalStreams {
        public static void main(String[] args) {
            Optional<String> name = Optional.of("  John  ");
            
            // map - transform value
            Optional<Integer> length = name.map(String::length);
            
            // Chaining operations
            String result = name
                .map(String::trim)
                .map(String::toUpperCase)
                .orElse("UNKNOWN");
            System.out.println(result);  // "JOHN"
            
            // filter - conditional
            Optional<String> filtered = name
                .filter(n -> n.trim().length() > 3);
            
            // flatMap - for nested Optionals
            Optional<Optional<String>> nested = Optional.of(Optional.of("Hello"));
            Optional<String> flat = nested.flatMap(o -> o);
        }
    }
    ```

    **Các phương pháp hay nhất:**
    ```java
    class UserService {
        // Return Optional for methods that may not find a result
        public Optional<User> findById(int id) {
            User user = database.find(id);
            return Optional.ofNullable(user);
        }
        
        // Don't use Optional for fields or parameters
        // Bad: private Optional<String> name;
        // Good: private String name; // can be null
        
        // Don't use Optional.get() without checking
        // Bad: optional.get()
        // Good: optional.orElse(default) or optional.ifPresent(...)
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

41. ### Sự khác biệt giữa Bộ sưu tập và Bộ sưu tập là gì?

    `Collection` Và `Collections` là hai khái niệm khác nhau trong Java thường bị nhầm lẫn.

    **Bộ sưu tập (Giao diện):**
    - Nó là một giao diện gốc trong Khung sưu tập Java
    - Nằm ở `java.util` bưu kiện
    - Đại diện cho một nhóm đối tượng được gọi là các phần tử
    - Được mở rộng theo giao diện Danh sách, Bộ và Hàng đợi

    **Bộ sưu tập (Lớp tiện ích):**
    - Nó là một lớp tiện ích cung cấp các phương thức tĩnh cho các hoạt động thu thập
    - Nằm ở `java.util` bưu kiện
    - Chứa các phương pháp sắp xếp, tìm kiếm, xáo trộn, đảo ngược, v.v.
    - Không thể khởi tạo được (tất cả các phương thức đều tĩnh)

    ```java
    import java.util.*;

    public class CollectionVsCollections {
        public static void main(String[] args) {
            // Collection - interface used to create a collection
            Collection<String> collection = new ArrayList<>();
            collection.add("Apple");
            collection.add("Banana");
            collection.add("Cherry");
            
            // Collections - utility class with static methods
            List<String> list = new ArrayList<>(collection);
            
            // Sorting using Collections utility
            Collections.sort(list);
            System.out.println("Sorted: " + list);
            
            // Reverse the list
            Collections.reverse(list);
            System.out.println("Reversed: " + list);
            
            // Shuffle the list
            Collections.shuffle(list);
            System.out.println("Shuffled: " + list);
            
            // Find min and max
            System.out.println("Min: " + Collections.min(list));
            System.out.println("Max: " + Collections.max(list));
            
            // Create unmodifiable collection
            List<String> unmodifiable = Collections.unmodifiableList(list);
            
            // Create synchronized collection
            List<String> syncList = Collections.synchronizedList(new ArrayList<>());
        }
    }
    ```

    | Bộ sưu tập | Bộ sưu tập |
    |------------|-------------|
    | Giao diện | Lớp tiện ích |
    | Dùng để đại diện cho một nhóm đối tượng | Cung cấp các phương thức tĩnh cho hoạt động |
    | Có thể thực hiện được | Không thể khởi tạo |
    | Hệ thống phân cấp gốc của Bộ sưu tập | Lớp trợ giúp cho các hoạt động Bộ sưu tập |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

42. ### Sự khác biệt giữa Tập hợp và Danh sách là gì?

    Cả Set và List đều là các giao diện trong Java Collections Framework, nhưng chúng có các đặc điểm khác nhau:

    | Danh sách | Đặt |
    |------|-----|
    | Cho phép các phần tử trùng lặp | Không cho phép các phần tử trùng lặp |
    | Duy trì thứ tự chèn | Có thể duy trì trật tự hoặc không (tùy vào việc thực hiện) |
    | Các phần tử có thể được truy cập theo chỉ mục | Không có quyền truy cập dựa trên chỉ mục |
    | Cho phép nhiều giá trị null | Cho phép tối đa một giá trị null (HashSet, LinkedHashSet) |
    | Triển khai: ArrayList, LinkedList, Vector | Triển khai: HashSet, LinkedHashSet, TreeSet |

    ```java
    import java.util.*;

    public class ListVsSet {
        public static void main(String[] args) {
            // List - allows duplicates, maintains order
            List<String> list = new ArrayList<>();
            list.add("Apple");
            list.add("Banana");
            list.add("Apple");  // Duplicate allowed
            list.add(null);
            list.add(null);     // Multiple nulls allowed
            System.out.println("List: " + list);  // [Apple, Banana, Apple, null, null]
            System.out.println("Element at index 1: " + list.get(1));  // Index access
            
            // Set - no duplicates
            Set<String> hashSet = new HashSet<>();
            hashSet.add("Apple");
            hashSet.add("Banana");
            hashSet.add("Apple");  // Duplicate ignored
            hashSet.add(null);     // Only one null allowed
            System.out.println("HashSet: " + hashSet);  // Order not guaranteed
            
            // LinkedHashSet - maintains insertion order
            Set<String> linkedHashSet = new LinkedHashSet<>();
            linkedHashSet.add("Cherry");
            linkedHashSet.add("Apple");
            linkedHashSet.add("Banana");
            System.out.println("LinkedHashSet: " + linkedHashSet);  // [Cherry, Apple, Banana]
            
            // TreeSet - sorted order, no nulls
            Set<String> treeSet = new TreeSet<>();
            treeSet.add("Cherry");
            treeSet.add("Apple");
            treeSet.add("Banana");
            System.out.println("TreeSet: " + treeSet);  // [Apple, Banana, Cherry]
        }
    }
    ```

    **Khi nào nên sử dụng:**
    - Sử dụng **Danh sách** khi bạn cần duy trì thứ tự chèn và cho phép trùng lặp
    - Sử dụng **Set** khi bạn chỉ cần lưu trữ các phần tử duy nhất

    **[⬆ Quay lại đầu trang](#table-of-contents)**

43. ### Sự khác biệt giữa HashSet và TreeSet là gì?

    Cả HashSet và TreeSet đều triển khai giao diện Set nhưng có các đặc điểm và triển khai nội bộ khác nhau:

    | Bộ băm | Bộ cây |
    |---------|---------|
    | Sử dụng HashMap nội bộ | Sử dụng TreeMap (Cây đỏ-đen) nội bộ |
    | Không duy trì trật tự nào | Duy trì các phần tử theo thứ tự được sắp xếp (tự nhiên) |
    | Cho phép một phần tử null | Không cho phép phần tử null |
    | O(1) để thêm, xóa, chứa | O(log n) để thêm, xóa, chứa |
    | Sử dụng hashCode() và bằng() | Sử dụng CompareTo() hoặc Comparator |
    | Hiệu suất tốt hơn cho các hoạt động cơ bản | Tốt hơn khi cần sắp xếp thứ tự |

    ```java
    import java.util.*;

    public class HashSetVsTreeSet {
        public static void main(String[] args) {
            // HashSet - no ordering, allows null
            Set<Integer> hashSet = new HashSet<>();
            hashSet.add(30);
            hashSet.add(10);
            hashSet.add(20);
            hashSet.add(null);  // Allowed
            hashSet.add(10);    // Duplicate ignored
            System.out.println("HashSet: " + hashSet);  // Order not guaranteed
            
            // TreeSet - sorted order, no null
            Set<Integer> treeSet = new TreeSet<>();
            treeSet.add(30);
            treeSet.add(10);
            treeSet.add(20);
            // treeSet.add(null);  // Throws NullPointerException
            System.out.println("TreeSet: " + treeSet);  // [10, 20, 30] - sorted
            
            // TreeSet with custom Comparator (descending order)
            Set<Integer> descendingSet = new TreeSet<>(Collections.reverseOrder());
            descendingSet.add(30);
            descendingSet.add(10);
            descendingSet.add(20);
            System.out.println("Descending TreeSet: " + descendingSet);  // [30, 20, 10]
            
            // TreeSet with custom objects
            Set<Person> personSet = new TreeSet<>(Comparator.comparing(Person::getName));
            personSet.add(new Person("John", 25));
            personSet.add(new Person("Alice", 30));
            personSet.add(new Person("Bob", 20));
            System.out.println("Person TreeSet: " + personSet);
        }
    }

    class Person {
        private String name;
        private int age;
        
        public Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
        
        public String getName() { return name; }
        public int getAge() { return age; }
        
        @Override
        public String toString() {
            return name + "(" + age + ")";
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

44. ### Vấn đề kim cương trong Java là gì?

    Vấn đề kim cương là sự mơ hồ nảy sinh trong đa kế thừa khi một lớp kế thừa từ hai lớp mà cả hai đều kế thừa từ một siêu lớp chung. Nó được gọi là "kim cương" vì hình dạng của sơ đồ thừa kế.

    **Vấn đề:**
    ```
           A
          / \
         B   C
          \ /
           D
    ```
    Nếu lớp D kế thừa từ cả B và C, đồng thời cả B và C đều ghi đè một phương thức từ A, thì D nên sử dụng phiên bản nào?

    **Giải pháp của Java:**
    Java không cho phép đa kế thừa với các lớp để tránh vấn đề kim cương. Tuy nhiên, với các giao diện Java 8+ có các phương thức mặc định, tình huống tương tự có thể xảy ra:

    ```java
    interface A {
        default void display() {
            System.out.println("Display from A");
        }
    }

    interface B extends A {
        @Override
        default void display() {
            System.out.println("Display from B");
        }
    }

    interface C extends A {
        @Override
        default void display() {
            System.out.println("Display from C");
        }
    }

    // Diamond problem with interfaces
    class D implements B, C {
        // Must override to resolve ambiguity
        @Override
        public void display() {
            // Can choose which interface method to call
            B.super.display();  // Calls B's display
            // or
            // C.super.display();  // Calls C's display
            // or provide own implementation
            System.out.println("Display from D");
        }
    }

    public class DiamondProblem {
        public static void main(String[] args) {
            D d = new D();
            d.display();
        }
    }
    ```

    **Quy tắc giải quyết trong Java:**
    1. **Lớp chiến thắng giao diện:** Nếu một lớp kế thừa một phương thức từ cả siêu lớp và giao diện, thì phương thức lớp đó sẽ được ưu tiên
    2. **Loại phụ thắng:** Phương thức mặc định của giao diện cụ thể hơn được chọn thay vì phương thức ít cụ thể hơn
    3. **Độ phân giải rõ ràng:** Nếu vẫn còn mơ hồ, lớp phải ghi đè rõ ràng và chỉ định phương thức nào sẽ sử dụng

    ```java
    class Parent {
        void show() {
            System.out.println("Parent show");
        }
    }

    interface MyInterface {
        default void show() {
            System.out.println("Interface show");
        }
    }

    // Class method wins over interface default method
    class Child extends Parent implements MyInterface {
        // No override needed - Parent's show() is used automatically
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

45. ### Nội dung phụ thuộc là gì?

    Dependency Insert (DI) là một mẫu thiết kế được sử dụng để triển khai Đảo ngược điều khiển (IoC). Nó cho phép tạo các đối tượng phụ thuộc bên ngoài một lớp và cung cấp các đối tượng đó cho một lớp theo nhiều cách khác nhau.

    **Lợi ích của việc tiêm phụ thuộc:**
    1. Khớp nối lỏng lẻo giữa các lớp
    2. Kiểm tra đơn vị dễ dàng hơn (phụ thuộc giả)
    3. Khả năng sử dụng lại mã tốt hơn
    4. Bảo trì dễ dàng hơn và linh hoạt hơn

    **Các loại chèn phụ thuộc:**

    1. **Tiêm hàm tạo:**
    ```java
    // Dependency
    interface MessageService {
        void sendMessage(String message);
    }

    class EmailService implements MessageService {
        @Override
        public void sendMessage(String message) {
            System.out.println("Email sent: " + message);
        }
    }

    class SMSService implements MessageService {
        @Override
        public void sendMessage(String message) {
            System.out.println("SMS sent: " + message);
        }
    }

    // Constructor Injection
    class NotificationService {
        private final MessageService messageService;
        
        // Dependency injected through constructor
        public NotificationService(MessageService messageService) {
            this.messageService = messageService;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    2. **Tiêm Setter:**
    ```java
    class NotificationService {
        private MessageService messageService;
        
        // Dependency injected through setter
        public void setMessageService(MessageService messageService) {
            this.messageService = messageService;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    3. **Chèn giao diện:**
    ```java
    interface MessageServiceInjector {
        void injectMessageService(MessageService service);
    }

    class NotificationService implements MessageServiceInjector {
        private MessageService messageService;
        
        @Override
        public void injectMessageService(MessageService service) {
            this.messageService = service;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    **Ví dụ sử dụng:**
    ```java
    public class DIExample {
        public static void main(String[] args) {
            // Create dependencies
            MessageService emailService = new EmailService();
            MessageService smsService = new SMSService();
            
            // Inject dependencies
            NotificationService notifier1 = new NotificationService(emailService);
            notifier1.notify("Hello via Email!");
            
            NotificationService notifier2 = new NotificationService(smsService);
            notifier2.notify("Hello via SMS!");
        }
    }
    ```

    **Lưu ý:** Các khung như Spring cung cấp tính năng chèn phụ thuộc tự động bằng cách sử dụng các chú thích như `@Autowired`, `@Inject`.

    **[⬆ Quay lại đầu trang](#table-of-contents)**

46. ###Sự khác biệt giữa bản sao nông và bản sao sâu là gì?

    Khi sao chép các đối tượng trong Java, có hai loại bản sao: bản sao nông và bản sao sâu.

    **Bản sao nông:**
    - Tạo một đối tượng mới nhưng sao chép các tham chiếu đến các đối tượng lồng nhau
    - Những thay đổi đối với các đối tượng lồng nhau sẽ ảnh hưởng đến cả hai bản sao
    - Hành vi mặc định của `clone()` phương pháp

    **Bản sao sâu:**
    - Tạo một đối tượng mới và sao chép đệ quy tất cả các đối tượng lồng nhau
    - Những thay đổi đối với các đối tượng lồng nhau không ảnh hưởng đến bản gốc
    - Yêu cầu thực hiện thủ công

    ```java
    import java.util.ArrayList;
    import java.util.List;

    class Address implements Cloneable {
        String city;
        
        public Address(String city) {
            this.city = city;
        }
        
        @Override
        protected Address clone() throws CloneNotSupportedException {
            return (Address) super.clone();
        }
        
        @Override
        public String toString() {
            return city;
        }
    }

    class Person implements Cloneable {
        String name;
        Address address;
        List<String> hobbies;
        
        public Person(String name, Address address, List<String> hobbies) {
            this.name = name;
            this.address = address;
            this.hobbies = hobbies;
        }
        
        // Shallow Copy
        public Person shallowCopy() throws CloneNotSupportedException {
            return (Person) super.clone();
        }
        
        // Deep Copy
        public Person deepCopy() throws CloneNotSupportedException {
            Person cloned = (Person) super.clone();
            cloned.address = this.address.clone();  // Clone nested object
            cloned.hobbies = new ArrayList<>(this.hobbies);  // Create new list
            return cloned;
        }
        
        @Override
        public String toString() {
            return "Person{name='" + name + "', address=" + address + ", hobbies=" + hobbies + "}";
        }
    }

    public class CopyExample {
        public static void main(String[] args) throws CloneNotSupportedException {
            List<String> hobbies = new ArrayList<>();
            hobbies.add("Reading");
            
            Person original = new Person("John", new Address("New York"), hobbies);
            
            // Shallow Copy
            Person shallowCopy = original.shallowCopy();
            
            // Deep Copy
            Person deepCopy = original.deepCopy();
            
            // Modify nested objects
            original.address.city = "Los Angeles";
            original.hobbies.add("Gaming");
            
            System.out.println("Original: " + original);
            System.out.println("Shallow Copy: " + shallowCopy);  // Address changed!
            System.out.println("Deep Copy: " + deepCopy);        // Address unchanged
        }
    }
    ```

    | Sao chép nông | Bản sao sâu |
    |--------------|-----------|
    | Sao chép tài liệu tham khảo đối tượng | Sao chép các đối tượng thực tế |
    | Các đối tượng lồng nhau được chia sẻ | Các đối tượng lồng nhau là độc lập |
    | Nhanh hơn và ít bộ nhớ hơn | Chậm hơn và nhiều bộ nhớ hơn |
    | Những thay đổi ảnh hưởng đến cả hai bản | Những thay đổi bị cô lập |
    | Hành vi clone() mặc định | Yêu cầu triển khai tùy chỉnh |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

47. ### Các mẫu thiết kế trong Java là gì?

    Các mẫu thiết kế là các giải pháp có thể tái sử dụng cho các vấn đề thường gặp trong thiết kế phần mềm. Chúng đại diện cho các phương pháp hay nhất và cung cấp các mẫu để giải quyết các thách thức về thiết kế.

    **Các loại mẫu thiết kế:**

    1. **Mẫu sáng tạo** - Xử lý các cơ chế tạo đối tượng
       - Singleton
       - Phương pháp xuất xưởng
       - Nhà máy trừu tượng
       - Người xây dựng
       - Nguyên mẫu

    2. **Mẫu cấu trúc** - Xử lý thành phần đối tượng
       - Bộ chuyển đổi
       - Cầu
       - tổng hợp
       - Người trang trí
       - mặt tiền
       - Hạng ruồi
       - ủy quyền

    3. **Mô hình hành vi** - Xử lý tương tác với đối tượng
       - Chuỗi trách nhiệm
       - Yêu cầu
       - Trình vòng lặp
       - Người hòa giải
       - vật lưu niệm
       - Người quan sát
       - Tình trạng
       - Chiến lược
       - Phương pháp mẫu
       - khách truy cập

    **Ví dụ về các mẫu thiết kế phổ biến:**

    ```java
    // 1. SINGLETON - Only one instance
    public class Singleton {
        private static Singleton instance;
        private Singleton() {}
        public static synchronized Singleton getInstance() {
            if (instance == null) {
                instance = new Singleton();
            }
            return instance;
        }
    }

    // 2. FACTORY - Creates objects without exposing creation logic
    interface Animal {
        void speak();
    }
    class Dog implements Animal {
        public void speak() { System.out.println("Woof!"); }
    }
    class Cat implements Animal {
        public void speak() { System.out.println("Meow!"); }
    }
    class AnimalFactory {
        public static Animal createAnimal(String type) {
            return switch (type.toLowerCase()) {
                case "dog" -> new Dog();
                case "cat" -> new Cat();
                default -> throw new IllegalArgumentException("Unknown animal");
            };
        }
    }

    // 3. OBSERVER - One-to-many dependency
    interface Observer {
        void update(String message);
    }
    class NewsSubscriber implements Observer {
        private String name;
        public NewsSubscriber(String name) { this.name = name; }
        public void update(String message) {
            System.out.println(name + " received: " + message);
        }
    }

    // 4. STRATEGY - Family of interchangeable algorithms
    interface PaymentStrategy {
        void pay(int amount);
    }
    class CreditCardPayment implements PaymentStrategy {
        public void pay(int amount) {
            System.out.println("Paid $" + amount + " with Credit Card");
        }
    }
    class PayPalPayment implements PaymentStrategy {
        public void pay(int amount) {
            System.out.println("Paid $" + amount + " with PayPal");
        }
    }

    // 5. DECORATOR - Add behavior dynamically
    interface Coffee {
        double getCost();
        String getDescription();
    }
    class SimpleCoffee implements Coffee {
        public double getCost() { return 2.0; }
        public String getDescription() { return "Simple Coffee"; }
    }
    class MilkDecorator implements Coffee {
        private Coffee coffee;
        public MilkDecorator(Coffee coffee) { this.coffee = coffee; }
        public double getCost() { return coffee.getCost() + 0.5; }
        public String getDescription() { return coffee.getDescription() + ", Milk"; }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

48. ###Mẫu thiết kế nhà xưởng là gì?

    Mẫu thiết kế nhà máy là một mẫu sáng tạo cung cấp giao diện để tạo các đối tượng mà không chỉ định các lớp chính xác của chúng. Nó ủy quyền logic khởi tạo cho các lớp con hoặc các phương thức xuất xưởng.

    **Các loại mẫu nhà máy:**

    1. **Nhà máy đơn giản (Phương pháp nhà máy tĩnh):**
    ```java
    interface Shape {
        void draw();
    }

    class Circle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Circle");
        }
    }

    class Rectangle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Rectangle");
        }
    }

    class Triangle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Triangle");
        }
    }

    // Simple Factory
    class ShapeFactory {
        public static Shape createShape(String shapeType) {
            if (shapeType == null) {
                return null;
            }
            return switch (shapeType.toUpperCase()) {
                case "CIRCLE" -> new Circle();
                case "RECTANGLE" -> new Rectangle();
                case "TRIANGLE" -> new Triangle();
                default -> throw new IllegalArgumentException("Unknown shape: " + shapeType);
            };
        }
    }

    public class SimpleFactoryDemo {
        public static void main(String[] args) {
            Shape circle = ShapeFactory.createShape("CIRCLE");
            circle.draw();
            
            Shape rectangle = ShapeFactory.createShape("RECTANGLE");
            rectangle.draw();
        }
    }
    ```

    2. **Mẫu phương thức nhà máy:**
    ```java
    // Product interface
    interface Vehicle {
        void drive();
    }

    class Car implements Vehicle {
        @Override
        public void drive() {
            System.out.println("Driving a car");
        }
    }

    class Motorcycle implements Vehicle {
        @Override
        public void drive() {
            System.out.println("Riding a motorcycle");
        }
    }

    // Creator abstract class
    abstract class VehicleFactory {
        // Factory method
        public abstract Vehicle createVehicle();
        
        public void deliverVehicle() {
            Vehicle vehicle = createVehicle();
            System.out.println("Delivering vehicle...");
            vehicle.drive();
        }
    }

    class CarFactory extends VehicleFactory {
        @Override
        public Vehicle createVehicle() {
            return new Car();
        }
    }

    class MotorcycleFactory extends VehicleFactory {
        @Override
        public Vehicle createVehicle() {
            return new Motorcycle();
        }
    }

    public class FactoryMethodDemo {
        public static void main(String[] args) {
            VehicleFactory carFactory = new CarFactory();
            carFactory.deliverVehicle();
            
            VehicleFactory motorcycleFactory = new MotorcycleFactory();
            motorcycleFactory.deliverVehicle();
        }
    }
    ```

    **Những lợi ích:**
    - Sự kết nối lỏng lẻo giữa người sáng tạo và sản phẩm
    - Nguyên tắc trách nhiệm duy nhất - mã tạo ở một nơi
    - Nguyên tắc mở/đóng - dễ dàng thêm loại sản phẩm mới
    - Kiểm tra đơn vị dễ dàng hơn với các đối tượng giả

    **[⬆ Quay lại đầu trang](#table-of-contents)**

49. ### Mẫu thiết kế của người xây dựng là gì?

    Mẫu thiết kế Builder là một mẫu sáng tạo tách biệt việc xây dựng một đối tượng phức tạp khỏi cách trình bày của nó. Nó cho phép xây dựng các đối tượng theo từng bước và tạo ra các cách biểu diễn khác nhau bằng cách sử dụng cùng một quy trình xây dựng.

    **Khi nào nên sử dụng:**
    - Khi đối tượng có nhiều tham số tùy chọn
    - Khi việc tạo đối tượng bao gồm nhiều bước
    - Khi bạn muốn các đối tượng bất biến với nhiều trường

    ```java
    // Product class with many fields
    class Computer {
        // Required parameters
        private final String processor;
        private final int ram;
        
        // Optional parameters
        private final int storage;
        private final boolean hasGraphicsCard;
        private final boolean hasBluetooth;
        private final boolean hasWifi;
        private final String operatingSystem;
        
        private Computer(ComputerBuilder builder) {
            this.processor = builder.processor;
            this.ram = builder.ram;
            this.storage = builder.storage;
            this.hasGraphicsCard = builder.hasGraphicsCard;
            this.hasBluetooth = builder.hasBluetooth;
            this.hasWifi = builder.hasWifi;
            this.operatingSystem = builder.operatingSystem;
        }
        
        // Getters
        public String getProcessor() { return processor; }
        public int getRam() { return ram; }
        public int getStorage() { return storage; }
        public boolean hasGraphicsCard() { return hasGraphicsCard; }
        public boolean hasBluetooth() { return hasBluetooth; }
        public boolean hasWifi() { return hasWifi; }
        public String getOperatingSystem() { return operatingSystem; }
        
        @Override
        public String toString() {
            return "Computer{" +
                "processor='" + processor + '\'' +
                ", ram=" + ram + "GB" +
                ", storage=" + storage + "GB" +
                ", graphicsCard=" + hasGraphicsCard +
                ", bluetooth=" + hasBluetooth +
                ", wifi=" + hasWifi +
                ", OS='" + operatingSystem + '\'' +
                '}';
        }
        
        // Static Builder class
        public static class ComputerBuilder {
            // Required parameters
            private final String processor;
            private final int ram;
            
            // Optional parameters with default values
            private int storage = 256;
            private boolean hasGraphicsCard = false;
            private boolean hasBluetooth = true;
            private boolean hasWifi = true;
            private String operatingSystem = "Windows";
            
            // Constructor with required parameters
            public ComputerBuilder(String processor, int ram) {
                this.processor = processor;
                this.ram = ram;
            }
            
            // Builder methods for optional parameters
            public ComputerBuilder storage(int storage) {
                this.storage = storage;
                return this;
            }
            
            public ComputerBuilder graphicsCard(boolean hasGraphicsCard) {
                this.hasGraphicsCard = hasGraphicsCard;
                return this;
            }
            
            public ComputerBuilder bluetooth(boolean hasBluetooth) {
                this.hasBluetooth = hasBluetooth;
                return this;
            }
            
            public ComputerBuilder wifi(boolean hasWifi) {
                this.hasWifi = hasWifi;
                return this;
            }
            
            public ComputerBuilder operatingSystem(String operatingSystem) {
                this.operatingSystem = operatingSystem;
                return this;
            }
            
            // Build method to create the final object
            public Computer build() {
                return new Computer(this);
            }
        }
    }

    public class BuilderPatternDemo {
        public static void main(String[] args) {
            // Building a gaming computer
            Computer gamingPC = new Computer.ComputerBuilder("Intel i9", 32)
                .storage(1000)
                .graphicsCard(true)
                .bluetooth(true)
                .wifi(true)
                .operatingSystem("Windows 11")
                .build();
            
            System.out.println("Gaming PC: " + gamingPC);
            
            // Building a basic computer with defaults
            Computer basicPC = new Computer.ComputerBuilder("Intel i3", 8)
                .build();
            
            System.out.println("Basic PC: " + basicPC);
            
            // Building a Mac
            Computer mac = new Computer.ComputerBuilder("Apple M2", 16)
                .storage(512)
                .operatingSystem("macOS")
                .build();
            
            System.out.println("Mac: " + mac);
        }
    }
    ```

    **Những lợi ích:**
    - Mã có thể đọc được với chuỗi phương thức (giao diện trôi chảy)
    - Các đối tượng bất biến có thể được tạo dễ dàng
    - Sự tách biệt rõ ràng giữa xây dựng và thể hiện
    - Tránh mô hình chống xây dựng kính thiên văn

    **[⬆ Quay lại đầu trang](#table-of-contents)**

50. ### Sự khác biệt giữa bộ nhớ Heap và Stack là gì?

    Bộ nhớ Java được chia thành hai khu vực chính: Heap và Stack. Hiểu được sự khác biệt của chúng là rất quan trọng để quản lý bộ nhớ.

    | Bộ nhớ ngăn xếp | Bộ nhớ đống |
    |--------------|-------------|
    | Lưu trữ các lệnh gọi phương thức và biến cục bộ | Lưu trữ các đối tượng và biến thể hiện |
    | Cấu trúc LIFO (Vào sau ra trước) | Không có thứ tự cụ thể |
    | An toàn cho luồng (mỗi luồng có ngăn xếp riêng) | Được chia sẻ giữa tất cả các chủ đề |
    | Cấp phát/giải phóng bộ nhớ là tự động | Được quản lý bởi Người thu gom rác |
    | Kích thước cố định (có thể gây ra StackOverflowError) | Kích thước động (có thể gây ra OutOfMemoryError) |
    | Truy cập nhanh hơn | Truy cập chậm hơn |
    | Lưu trữ các giá trị nguyên thủy và tham chiếu | Lưu trữ các đối tượng thực tế |

    ```java
    public class MemoryExample {
        // Instance variable - stored in Heap
        private int instanceVar = 10;
        
        // Static variable - stored in Method Area (part of Heap in modern JVMs)
        private static int staticVar = 20;
        
        public void demonstrate() {
            // Local primitive - stored in Stack
            int localPrimitive = 30;
            
            // Local reference - reference in Stack, object in Heap
            String localString = new String("Hello");
            
            // Object created in Heap
            Person person = new Person("John", 25);
            
            // Array - reference in Stack, array object in Heap
            int[] numbers = new int[5];
        }
        
        public static void main(String[] args) {
            // Reference 'obj' in Stack, object in Heap
            MemoryExample obj = new MemoryExample();
            obj.demonstrate();
            
            // Recursive call can cause StackOverflowError
            // recursiveMethod(); // Uncomment to see StackOverflowError
        }
        
        public static void recursiveMethod() {
            recursiveMethod(); // Infinite recursion - StackOverflowError
        }
    }

    class Person {
        String name;  // Reference in Heap, String object in Heap
        int age;      // Primitive stored in Heap (as part of object)
        
        Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
    }
    ```

    **Hình dung bộ nhớ:**
    ```
    STACK                          HEAP
    ┌─────────────────┐            ┌─────────────────────────────────┐
    │ main() frame    │            │                                 │
    │  obj (reference)│──────────► │  MemoryExample object           │
    │                 │            │    instanceVar = 10             │
    ├─────────────────┤            │                                 │
    │ demonstrate()   │            ├─────────────────────────────────┤
    │  localPrimitive │            │                                 │
    │  = 30           │            │  String object "Hello"          │
    │  localString ───│──────────► │                                 │
    │  person ────────│──────────► │  Person object                  │
    │  numbers ───────│──────────► │    name (ref) ──► "John"        │
    └─────────────────┘            │    age = 25                     │
                                   │                                 │
                                   │  int[5] array                   │
                                   └─────────────────────────────────┘
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

51. ### Thu gom rác trong Java là gì?

    Garbage Collection (GC) là một tính năng quản lý bộ nhớ tự động trong Java nhằm xác định và loại bỏ các đối tượng không còn được sử dụng, giải phóng bộ nhớ heap cho các đối tượng mới.

    **Cách hoạt động của bộ sưu tập rác:**

    1. **Giai đoạn đánh dấu:** GC xác định những đối tượng nào vẫn có thể truy cập được (đang sử dụng)
    2. **Giai đoạn quét:** GC loại bỏ các đối tượng không thể tiếp cận
    3. **Giai đoạn thu gọn (tùy chọn):** GC nén các đối tượng còn lại để giảm phân mảnh

    **Khi nào một đối tượng đủ điều kiện cho GC?**
    - Khi không có tài liệu tham khảo trỏ đến nó
    - Khi tham chiếu được đặt thành null
    - Khi tham chiếu được gán lại
    - Khi đối tượng đi ra khỏi phạm vi

    ```java
    public class GarbageCollectionDemo {
        
        public static void main(String[] args) {
            // Object created - not eligible for GC
            Object obj1 = new Object();
            
            // Reference set to null - obj1's object eligible for GC
            obj1 = null;
            
            // Object reassignment - first object eligible for GC
            Object obj2 = new Object();
            obj2 = new Object();  // First object now eligible for GC
            
            // Objects in method scope
            createObjects();
            // After method returns, local objects are eligible for GC
            
            // Request garbage collection (not guaranteed to run immediately)
            System.gc();
            // or
            Runtime.getRuntime().gc();
        }
        
        static void createObjects() {
            Object localObj = new Object();
            // localObj goes out of scope when method returns
        }
    }

    // Using finalize() - deprecated but shows GC callback
    class MyObject {
        private String name;
        
        public MyObject(String name) {
            this.name = name;
            System.out.println(name + " created");
        }
        
        @Override
        protected void finalize() throws Throwable {
            System.out.println(name + " is being garbage collected");
            super.finalize();
        }
    }

    // Demonstrating object eligibility
    class GCEligibility {
        public static void main(String[] args) throws InterruptedException {
            // Island of isolation - objects reference each other but unreachable
            MyObject a = new MyObject("A");
            MyObject b = new MyObject("B");
            
            // Create circular reference
            // a.partner = b;
            // b.partner = a;
            
            // Both become eligible for GC (island of isolation)
            a = null;
            b = null;
            
            // Request GC
            System.gc();
            Thread.sleep(1000);  // Give GC time to run
        }
    }
    ```

    **Các thế hệ vùng heap của JVM:**
    ```
    ┌────────────────────────────────────────────────────────────┐
    │                          HEAP                              │
    ├─────────────────────────────┬──────────────────────────────┤
    │     Young Generation        │      Old Generation          │
    │  ┌───────┬───────┬───────┐  │      (Tenured)               │
    │  │ Eden  │  S0   │  S1   │  │                              │
    │  │       │(From) │ (To)  │  │   Long-lived objects         │
    │  │ New   │       │       │  │                              │
    │  │objects│Survivor Spaces│  │                              │
    │  └───────┴───────┴───────┘  │                              │
    └─────────────────────────────┴──────────────────────────────┘
    ```

    **Quy trình GC:**
    1. Các đối tượng mới được phân bổ trong không gian Eden
    2. Khi Eden đầy, Minor GC xảy ra
    3. Các vật thể sống sót di chuyển đến không gian Survivor
    4. Các đối tượng tồn tại qua nhiều GC nhỏ sẽ chuyển sang Thế hệ cũ
    5. Khi Thế hệ cũ đầy, GC chính (GC đầy đủ) xảy ra

    **Tùy chọn JVM GC:**
    ```bash
    # Set heap size
    java -Xms256m -Xmx1024m MyApp
    
    # Choose garbage collector
    java -XX:+UseG1GC MyApp          # G1 Garbage Collector
    java -XX:+UseParallelGC MyApp    # Parallel GC
    java -XX:+UseZGC MyApp           # Z Garbage Collector (Java 11+)
    
    # GC logging
    java -Xlog:gc* MyApp             # Java 9+
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

52. ### Các loại trình thu gom rác khác nhau trong Java là gì?

    Java cung cấp một số triển khai thu gom rác, mỗi triển khai được tối ưu hóa cho các tình huống khác nhau:

    **1. Bộ thu gom rác nối tiếp (-XX:+UseSerialGC)**
    - Sử dụng một luồng để thu gom rác
    - Tốt nhất cho các ứng dụng đơn luồng
    - Gây ra sự tạm dừng "stop-the-world"
    - Thích hợp cho các ứng dụng nhỏ với đống nhỏ

    **2. Bộ thu gom rác song song (-XX:+UseParallelGC)**
    - Sử dụng nhiều luồng để thu gom rác
    - Còn được gọi là "bộ thu thông lượng"
    - GC mặc định trong Java 8
    - Tốt cho các ứng dụng đa luồng yêu cầu thông lượng cao

    **3. Máy thu gom rác G1 (-XX:+UseG1GC)**
    - Chia heap thành các vùng
    - Được thiết kế cho các đống lớn (> 4GB)
    - GC mặc định từ Java 9 trở đi
    - Cân bằng thông lượng và độ trễ
    - Thời gian tạm dừng có thể dự đoán được

    **4. Máy thu gom rác Z (-XX:+UseZGC)**
    - Được giới thiệu trong Java 11
    - Độ trễ cực thấp (<10ms thời gian tạm dừng)
    - Xử lý đống từ 8MB đến 16TB
    - Thu gom rác đồng thời

    **5. Người thu gom rác Shenandoah (-XX:+UseShenandoahGC)**
    - Trình thu gom rác có thời gian tạm dừng thấp
    - Thực hiện nén đồng thời
    - Có sẵn trong OpenJDK

    ```java
    public class GCDemo {
        public static void main(String[] args) {
            // Check current garbage collector
            java.lang.management.GarbageCollectorMXBean gc;
            for (java.lang.management.GarbageCollectorMXBean bean : 
                    java.lang.management.ManagementFactory.getGarbageCollectorMXBeans()) {
                System.out.println("GC Name: " + bean.getName());
                System.out.println("Collection Count: " + bean.getCollectionCount());
                System.out.println("Collection Time: " + bean.getCollectionTime() + "ms");
            }
        }
    }
    ```

    **Tùy chọn JVM cho GC:**
    ```bash
    # Serial GC
    java -XX:+UseSerialGC -jar app.jar

    # Parallel GC
    java -XX:+UseParallelGC -XX:ParallelGCThreads=4 -jar app.jar

    # G1 GC
    java -XX:+UseG1GC -XX:MaxGCPauseMillis=200 -jar app.jar

    # ZGC
    java -XX:+UseZGC -jar app.jar
    ```

    | Loại GC | Tốt nhất cho | Tạm dừng thời gian | Thông lượng |
    |---------|----------|------------|------------|
    | Nối tiếp | Ứng dụng nhỏ | Cao | Thấp |
    | Song song | Ứng dụng thông lượng | Trung bình | Cao |
    | G1 | Đống lớn | Thấp-Trung bình | Trung bình-Cao |
    | ZGC | Độ trễ thấp | Rất Thấp | Trung bình |

    **[⬆ Quay lại đầu trang](#table-of-contents)**

53. ### Sự khác biệt giữa phương thức wait() và sleep() là gì?

    Cả hai `wait()` Và `sleep()` được sử dụng để tạm dừng thực thi luồng, nhưng chúng có những khác biệt đáng kể:

    | chờ đợi() | ngủ() |
    |--------|---------|
    | Được định nghĩa trong lớp Đối tượng | Được xác định trong lớp Thread |
    | Nhả khóa/màn hình | Không nhả khóa |
    | Phải được gọi từ ngữ cảnh được đồng bộ hóa | Có thể được gọi từ bất cứ đâu |
    | Có thể được đánh thức bằng cách thông báo()/notifyAll() | Không thể đánh thức (trừ ngắt) |
    | Được sử dụng để liên lạc giữa các luồng | Được sử dụng để giới thiệu độ trễ |
    | Phương pháp dụ | Phương pháp tĩnh |

    ```java
    public class WaitVsSleep {
        private static final Object lock = new Object();
        
        public static void main(String[] args) {
            // Demonstrating sleep()
            Thread sleepThread = new Thread(() -> {
                System.out.println("Sleep thread starting...");
                try {
                    Thread.sleep(2000);  // Sleeps for 2 seconds
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
                System.out.println("Sleep thread woke up!");
            });
            
            // Demonstrating wait()
            Thread waitThread = new Thread(() -> {
                synchronized (lock) {
                    System.out.println("Wait thread starting...");
                    try {
                        lock.wait(2000);  // Waits for 2 seconds or until notified
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                    System.out.println("Wait thread woke up!");
                }
            });
            
            // Notify thread
            Thread notifyThread = new Thread(() -> {
                try {
                    Thread.sleep(1000);  // Wait 1 second
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
                synchronized (lock) {
                    System.out.println("Notifying...");
                    lock.notify();  // Wakes up the waiting thread
                }
            });
            
            sleepThread.start();
            waitThread.start();
            notifyThread.start();
        }
    }
    ```

    **Những điểm chính:**
    - `wait()` được sử dụng để phối hợp giữa các chủ đề
    - `sleep()` được sử dụng để tạm dừng thực hiện trong một thời gian cụ thể
    - Luôn gọi `wait()` bên trong một khối được đồng bộ hóa
    - `wait()` có thể bị gián đoạn bởi `notify()` trước khi hết thời gian

    **[⬆ Quay lại đầu trang](#table-of-contents)**

54. ### Sự khác biệt giữa thông báo() và thông báoAll() là gì?

    Cả hai `notify()` Và `notifyAll()` là các phương thức trong lớp Object được sử dụng để đánh thức các luồng đang chờ trên màn hình của đối tượng.

    | thông báo() | thông báoAll() |
    |----------|-------------|
    | Chỉ đánh thức một chủ đề đang chờ | Đánh thức tất cả các chủ đề đang chờ |
    | Chủ đề nào được đánh thức không được đảm bảo | Tất cả các chủ đề đều cạnh tranh để giành khóa |
    | Hiệu quả hơn khi chỉ cần một luồng cần tiến hành | An toàn hơn khi nhiều luồng có thể cần tài nguyên |
    | Có thể gây ra tình trạng đói luồng | Không bị đói nhưng tốn nhiều chi phí hơn |

    ```java
    public class NotifyVsNotifyAll {
        private static final Object lock = new Object();
        private static boolean resourceAvailable = false;
        
        public static void main(String[] args) throws InterruptedException {
            // Create multiple waiting threads
            for (int i = 1; i <= 3; i++) {
                final int threadNum = i;
                new Thread(() -> {
                    synchronized (lock) {
                        while (!resourceAvailable) {
                            System.out.println("Thread " + threadNum + " waiting...");
                            try {
                                lock.wait();
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        System.out.println("Thread " + threadNum + " got the resource!");
                    }
                }).start();
            }
            
            Thread.sleep(1000);  // Let all threads start waiting
            
            // Using notify() - wakes only ONE thread
            synchronized (lock) {
                System.out.println("\nCalling notify()...");
                resourceAvailable = true;
                lock.notify();  // Only one thread wakes up
            }
            
            Thread.sleep(1000);
            
            // Reset and demonstrate notifyAll()
            resourceAvailable = false;
            
            // Create more waiting threads
            for (int i = 4; i <= 6; i++) {
                final int threadNum = i;
                new Thread(() -> {
                    synchronized (lock) {
                        while (!resourceAvailable) {
                            System.out.println("Thread " + threadNum + " waiting...");
                            try {
                                lock.wait();
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        System.out.println("Thread " + threadNum + " got the resource!");
                    }
                }).start();
            }
            
            Thread.sleep(1000);
            
            // Using notifyAll() - wakes ALL threads
            synchronized (lock) {
                System.out.println("\nCalling notifyAll()...");
                resourceAvailable = true;
                lock.notifyAll();  // All threads wake up
            }
        }
    }
    ```

    **Khi nào nên sử dụng:**
    - Sử dụng `notify()` khi chỉ có một luồng có thể tiếp tục (ví dụ: một tài nguyên)
    - Sử dụng `notifyAll()` khi nhiều luồng có thể tiếp tục hoặc khi điều kiện thay đổi

    **[⬆ Quay lại đầu trang](#table-of-contents)**

55. ### Lớp bất biến là gì và cách tạo lớp đó như thế nào?

    Lớp bất biến là lớp mà các thể hiện của nó không thể sửa đổi sau khi tạo. Khi một đối tượng được tạo, trạng thái của nó sẽ không đổi trong suốt vòng đời của nó.

    **Lợi ích của tính bất biến:**
    - An toàn cho luồng mà không cần đồng bộ hóa
    - Có thể được chia sẻ và lưu trữ một cách an toàn
    - Tốt cho các khóa băm (hashCode không bao giờ thay đổi)
    - Dễ dàng lý luận hơn

    **Quy tắc tạo lớp bất biến:**
    1. Khai báo lớp như `final`
    2. Tạo tất cả các trường `private` Và `final`
    3. Không cung cấp phương thức setter
    4. Khởi tạo tất cả các trường thông qua hàm tạo
    5. Thực hiện sao chép sâu cho các đối tượng có thể thay đổi
    6. Trả về bản sao của các đối tượng có thể thay đổi trong getters

    ```java
    import java.util.ArrayList;
    import java.util.Collections;
    import java.util.List;

    // Immutable class example
    public final class ImmutablePerson {
        private final String name;
        private final int age;
        private final List<String> hobbies;
        
        public ImmutablePerson(String name, int age, List<String> hobbies) {
            this.name = name;
            this.age = age;
            // Deep copy of mutable object
            this.hobbies = new ArrayList<>(hobbies);
        }
        
        public String getName() {
            return name;
        }
        
        public int getAge() {
            return age;
        }
        
        // Return unmodifiable copy to prevent modification
        public List<String> getHobbies() {
            return Collections.unmodifiableList(hobbies);
        }
        
        // Method that appears to modify but returns new instance
        public ImmutablePerson withAge(int newAge) {
            return new ImmutablePerson(this.name, newAge, this.hobbies);
        }
        
        @Override
        public String toString() {
            return "ImmutablePerson{name='" + name + "', age=" + age + 
                   ", hobbies=" + hobbies + "}";
        }
    }

    // Usage
    class ImmutableDemo {
        public static void main(String[] args) {
            List<String> hobbies = new ArrayList<>();
            hobbies.add("Reading");
            hobbies.add("Gaming");
            
            ImmutablePerson person = new ImmutablePerson("John", 25, hobbies);
            System.out.println("Original: " + person);
            
            // Original list modification doesn't affect the object
            hobbies.add("Cooking");
            System.out.println("After modifying original list: " + person);
            
            // Cannot modify returned list
            // person.getHobbies().add("Swimming"); // Throws UnsupportedOperationException
            
            // Create new instance with different age
            ImmutablePerson olderPerson = person.withAge(30);
            System.out.println("New person: " + olderPerson);
            System.out.println("Original unchanged: " + person);
        }
    }
    ```

    **Bản ghi Java (Java 14+):**
    ```java
    // Records are immutable by default
    public record Person(String name, int age) {
        // Automatically generates constructor, getters, equals, hashCode, toString
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

56. ### Sự khác biệt giữa String, StringBuilder và StringBuffer là gì?

    Cả ba đều được sử dụng để xử lý các chuỗi trong Java, nhưng chúng có các đặc điểm khác nhau:

    | Tính năng | Chuỗi | StringBuilder | Bộ đệm chuỗi |
    |---------|--------|---------------|--------------|
    | Khả năng biến đổi | Bất biến | Có thể thay đổi | Có thể thay đổi |
    | An toàn chủ đề | Chủ đề an toàn (không thay đổi) | Không an toàn theo chủ đề | An toàn chủ đề (đồng bộ hóa) |
    | Hiệu suất | Nối chậm hơn | Nhanh nhất | Chậm hơn StringBuilder |
    | Lưu trữ | Bể dây | Đống | Đống |
    | Kể từ | Java 1.0 | Java 1.5 | Java 1.0 |

    ```java
    public class StringComparison {
        public static void main(String[] args) {
            // String - immutable
            String str = "Hello";
            str = str + " World";  // Creates new String object
            System.out.println("String: " + str);
            
            // StringBuilder - mutable, not thread-safe
            StringBuilder sb = new StringBuilder("Hello");
            sb.append(" World");  // Modifies same object
            System.out.println("StringBuilder: " + sb);
            
            // StringBuffer - mutable, thread-safe
            StringBuffer sbuf = new StringBuffer("Hello");
            sbuf.append(" World");  // Modifies same object
            System.out.println("StringBuffer: " + sbuf);
            
            // Performance comparison
            long startTime, endTime;
            
            // String concatenation (slow)
            startTime = System.currentTimeMillis();
            String s = "";
            for (int i = 0; i < 100000; i++) {
                s += "a";
            }
            endTime = System.currentTimeMillis();
            System.out.println("String time: " + (endTime - startTime) + "ms");
            
            // StringBuilder (fast)
            startTime = System.currentTimeMillis();
            StringBuilder sb2 = new StringBuilder();
            for (int i = 0; i < 100000; i++) {
                sb2.append("a");
            }
            endTime = System.currentTimeMillis();
            System.out.println("StringBuilder time: " + (endTime - startTime) + "ms");
            
            // StringBuffer (moderate)
            startTime = System.currentTimeMillis();
            StringBuffer sbuf2 = new StringBuffer();
            for (int i = 0; i < 100000; i++) {
                sbuf2.append("a");
            }
            endTime = System.currentTimeMillis();
            System.out.println("StringBuffer time: " + (endTime - startTime) + "ms");
        }
    }
    ```

    **Các phương thức phổ biến (StringBuilder/StringBuffer):**
    ```java
    StringBuilder sb = new StringBuilder("Hello");
    sb.append(" World");           // Append
    sb.insert(5, ",");             // Insert at position
    sb.delete(5, 6);               // Delete range
    sb.reverse();                  // Reverse
    sb.replace(0, 5, "Hi");        // Replace range
    String result = sb.toString(); // Convert to String
    ```

    **Khi nào nên sử dụng:**
    - **Chuỗi:** Khi chuỗi không thay đổi nhiều
    - **StringBuilder:** Khi chuỗi thay đổi thường xuyên (đơn luồng)
    - **StringBuffer:** Khi chuỗi thay đổi thường xuyên (đa luồng)

    **[⬆ Quay lại đầu trang](#table-of-contents)**

57. ### Sự khác biệt giữa biến tĩnh và biến thể hiện là gì?

    Các biến tĩnh thuộc về lớp, trong khi các biến thể hiện thuộc về các đối tượng riêng lẻ.

    | Biến tĩnh | Biến thể hiện |
    |-----------------|-------------------|
    | Thuộc lớp | Thuộc đối tượng |
    | Bản sao duy nhất được chia sẻ bởi tất cả các phiên bản | Mỗi phiên bản có bản sao riêng |
    | Khai báo với `static` từ khóa | Tuyên bố mà không có `static` từ khóa |
    | Truy cập qua tên lớp | Truy cập thông qua tham chiếu đối tượng |
    | Bộ nhớ được cấp phát một lần khi tải lớp | Bộ nhớ được cấp phát khi đối tượng được tạo |
    | Được lưu trữ trong Khu vực Phương thức | Được lưu trữ trong Heap |

    ```java
    public class Employee {
        // Static variable - shared by all instances
        private static int employeeCount = 0;
        private static String companyName = "TechCorp";
        
        // Instance variables - unique to each instance
        private int id;
        private String name;
        private double salary;
        
        public Employee(String name, double salary) {
            this.name = name;
            this.salary = salary;
            this.id = ++employeeCount;  // Use static counter
        }
        
        // Static method - can only access static members
        public static int getEmployeeCount() {
            return employeeCount;
        }
        
        public static String getCompanyName() {
            return companyName;
        }
        
        // Instance method - can access both static and instance members
        public void displayInfo() {
            System.out.println("ID: " + id);
            System.out.println("Name: " + name);
            System.out.println("Salary: " + salary);
            System.out.println("Company: " + companyName);  // Accessing static
        }
        
        public static void main(String[] args) {
            // Accessing static variable before creating any object
            System.out.println("Company: " + Employee.companyName);
            System.out.println("Initial count: " + Employee.getEmployeeCount());
            
            // Create instances
            Employee emp1 = new Employee("John", 50000);
            Employee emp2 = new Employee("Jane", 60000);
            Employee emp3 = new Employee("Bob", 55000);
            
            // Each has unique instance variables
            emp1.displayInfo();
            System.out.println();
            emp2.displayInfo();
            
            // Static variable is shared
            System.out.println("\nTotal employees: " + Employee.getEmployeeCount());
            
            // Change static variable - affects all
            Employee.companyName = "NewTechCorp";
            System.out.println("\nAfter company name change:");
            emp1.displayInfo();
            emp2.displayInfo();
        }
    }
    ```

    **Khối tĩnh:**
    ```java
    class StaticDemo {
        static int value;
        
        // Static block - executed once when class loads
        static {
            System.out.println("Static block executed");
            value = 100;
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

58. ### Mục đích của từ khóa super là gì?

    các `super` từ khóa trong Java được dùng để chỉ lớp cha trực tiếp. Nó có ba công dụng chính:

    **1. Truy cập các biến lớp cha:**
    ```java
    class Animal {
        String name = "Animal";
    }

    class Dog extends Animal {
        String name = "Dog";
        
        void displayNames() {
            System.out.println("Child name: " + name);
            System.out.println("Parent name: " + super.name);
        }
    }
    ```

    **2. Gọi các phương thức lớp cha mẹ:**
    ```java
    class Animal {
        void eat() {
            System.out.println("Animal is eating");
        }
    }

    class Dog extends Animal {
        @Override
        void eat() {
            super.eat();  // Call parent method first
            System.out.println("Dog is eating dog food");
        }
    }
    ```

    **3. Gọi hàm tạo của lớp cha:**
    ```java
    class Person {
        String name;
        int age;
        
        Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
    }

    class Employee extends Person {
        String department;
        double salary;
        
        Employee(String name, int age, String department, double salary) {
            super(name, age);  // Call parent constructor (must be first statement)
            this.department = department;
            this.salary = salary;
        }
    }
    ```

    **Ví dụ đầy đủ:**
    ```java
    class Vehicle {
        String brand = "Generic";
        int maxSpeed = 100;
        
        Vehicle() {
            System.out.println("Vehicle constructor");
        }
        
        Vehicle(String brand, int maxSpeed) {
            this.brand = brand;
            this.maxSpeed = maxSpeed;
            System.out.println("Vehicle parameterized constructor");
        }
        
        void start() {
            System.out.println("Vehicle starting...");
        }
        
        void displayInfo() {
            System.out.println("Brand: " + brand + ", Max Speed: " + maxSpeed);
        }
    }

    class Car extends Vehicle {
        String brand = "Car Brand";  // Hides parent variable
        int numDoors;
        
        Car(String brand, int maxSpeed, int numDoors) {
            super(brand, maxSpeed);  // Call parent constructor
            this.numDoors = numDoors;
            System.out.println("Car constructor");
        }
        
        @Override
        void start() {
            super.start();  // Call parent method
            System.out.println("Car engine started!");
        }
        
        void showBrands() {
            System.out.println("Car brand field: " + brand);
            System.out.println("Parent brand field: " + super.brand);
        }
    }

    public class SuperDemo {
        public static void main(String[] args) {
            Car car = new Car("Toyota", 200, 4);
            car.start();
            car.showBrands();
            car.displayInfo();
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

59. ### Mục đích của từ khóa này là gì?

    các `this` từ khóa trong Java đề cập đến phiên bản đối tượng hiện tại. Nó có một số công dụng:

    **1. Phân biệt các biến thể hiện với các tham số:**
    ```java
    class Person {
        String name;
        int age;
        
        Person(String name, int age) {
            this.name = name;  // this.name refers to instance variable
            this.age = age;    // age (right) is the parameter
        }
    }
    ```

    **2. Gọi một hàm tạo khác (Chuỗi hàm tạo):**
    ```java
    class Employee {
        String name;
        int age;
        String department;
        
        Employee() {
            this("Unknown", 0, "General");  // Call parameterized constructor
        }
        
        Employee(String name) {
            this(name, 0, "General");
        }
        
        Employee(String name, int age, String department) {
            this.name = name;
            this.age = age;
            this.department = department;
        }
    }
    ```

    **3. Truyền đối tượng hiện tại làm tham số:**
    ```java
    class Calculator {
        int value;
        
        Calculator(int value) {
            this.value = value;
        }
        
        void display(Calculator calc) {
            System.out.println("Value: " + calc.value);
        }
        
        void show() {
            display(this);  // Pass current object
        }
    }
    ```

    **4. Trả về đối tượng hiện tại (Xâu chuỗi phương thức/Giao diện thông thạo):**
    ```java
    class Builder {
        private String name;
        private int age;
        private String email;
        
        Builder setName(String name) {
            this.name = name;
            return this;  // Return current object for chaining
        }
        
        Builder setAge(int age) {
            this.age = age;
            return this;
        }
        
        Builder setEmail(String email) {
            this.email = email;
            return this;
        }
        
        void build() {
            System.out.println("Name: " + name + ", Age: " + age + ", Email: " + email);
        }
    }

    // Usage with method chaining
    class ThisDemo {
        public static void main(String[] args) {
            new Builder()
                .setName("John")
                .setAge(25)
                .setEmail("john@example.com")
                .build();
        }
    }
    ```

    **5. Tham chiếu Phiên bản lớp hiện tại trong Lớp bên trong:**
    ```java
    class Outer {
        int value = 10;
        
        class Inner {
            int value = 20;
            
            void display() {
                int value = 30;
                System.out.println("Local: " + value);
                System.out.println("Inner: " + this.value);
                System.out.println("Outer: " + Outer.this.value);
            }
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

60. ### Generics trong Java là gì?

    Generics cho phép các loại (lớp và giao diện) trở thành tham số khi xác định lớp, giao diện và phương thức. Chúng cung cấp sự an toàn cho kiểu thời gian biên dịch và loại bỏ nhu cầu truyền.

    **Lợi ích của thuốc gốc:**
    - Nhập an toàn tại thời điểm biên dịch
    - Loại bỏ phôi
    - Khả năng sử dụng lại mã
    - Kích hoạt các thuật toán chung

    **Lớp chung:**
    ```java
    // Generic class with type parameter T
    class Box<T> {
        private T content;
        
        public void set(T content) {
            this.content = content;
        }
        
        public T get() {
            return content;
        }
    }

    // Multiple type parameters
    class Pair<K, V> {
        private K key;
        private V value;
        
        public Pair(K key, V value) {
            this.key = key;
            this.value = value;
        }
        
        public K getKey() { return key; }
        public V getValue() { return value; }
    }
    ```

    **Phương pháp chung:**
    ```java
    class Utilities {
        // Generic method
        public static <T> void printArray(T[] array) {
            for (T element : array) {
                System.out.print(element + " ");
            }
            System.out.println();
        }
        
        // Generic method with return type
        public static <T> T getFirst(List<T> list) {
            return list.isEmpty() ? null : list.get(0);
        }
        
        // Multiple type parameters
        public static <K, V> V getValue(Map<K, V> map, K key) {
            return map.get(key);
        }
    }
    ```

    **Thông số loại giới hạn:**
    ```java
    // Upper bound - T must extend Number
    class NumberBox<T extends Number> {
        private T number;
        
        public NumberBox(T number) {
            this.number = number;
        }
        
        public double doubleValue() {
            return number.doubleValue();
        }
    }

    // Multiple bounds
    class MultiBound<T extends Number & Comparable<T>> {
        private T value;
        
        public int compareTo(T other) {
            return value.compareTo(other);
        }
    }
    ```

    **Ký tự đại diện:**
    ```java
    class WildcardDemo {
        // Unbounded wildcard
        public static void printList(List<?> list) {
            for (Object item : list) {
                System.out.println(item);
            }
        }
        
        // Upper bounded wildcard (read-only)
        public static double sumNumbers(List<? extends Number> list) {
            double sum = 0;
            for (Number n : list) {
                sum += n.doubleValue();
            }
            return sum;
        }
        
        // Lower bounded wildcard (write-only)
        public static void addIntegers(List<? super Integer> list) {
            list.add(1);
            list.add(2);
            list.add(3);
        }
    }
    ```

    **Ví dụ sử dụng:**
    ```java
    public class GenericsDemo {
        public static void main(String[] args) {
            // Generic class usage
            Box<String> stringBox = new Box<>();
            stringBox.set("Hello");
            String str = stringBox.get();  // No cast needed
            
            Box<Integer> intBox = new Box<>();
            intBox.set(100);
            int num = intBox.get();
            
            // Pair
            Pair<String, Integer> pair = new Pair<>("Age", 25);
            System.out.println(pair.getKey() + ": " + pair.getValue());
            
            // Generic method
            Integer[] intArray = {1, 2, 3, 4, 5};
            String[] strArray = {"A", "B", "C"};
            Utilities.printArray(intArray);
            Utilities.printArray(strArray);
            
            // Bounded type
            NumberBox<Integer> numBox = new NumberBox<>(42);
            System.out.println("Double value: " + numBox.doubleValue());
        }
    }
    ```

    **[⬆ Quay lại đầu trang](#table-of-contents)**

61. ### Xóa kiểu trong Java generics là gì?

    Xóa kiểu là quá trình trình biên dịch Java loại bỏ tất cả thông tin kiểu chung trong quá trình biên dịch. Các tham số loại chung được thay thế bằng giới hạn hoặc Đối tượng của chúng và các kiểu ép kiểu được chèn khi cần thiết.

    **Cách thức hoạt động của tính năng Xóa:**

    ```java
    // Before compilation (source code)
    public class Box<T> {
        private T content;
        
        public void set(T content) {
            this.content = content;
        }
        
        public T get() {
            return content;
        }
    }

    // After type erasure (bytecode equivalent)
    public class Box {
        private Object content;
        
        public void set(Object content) {
            this.content = content;
        }
        
        public Object get() {
            return content;
        }
    }
    ```

    **Xóa kiểu giới hạn:**
    ```java
    // Before erasure
    public class NumberBox<T extends Number> {
        private T number;
        
        public double getValue() {
            return number.doubleValue();
        }
    }

    // After erasure - T replaced with Number (its bound)
    public class NumberBox {
        private Number number;
        
        public double getValue() {
            return number.doubleValue();
        }
    }
    ```

    **Phương pháp bắc cầu:**
    Trình biên dịch tạo ra các phương thức cầu nối để duy trì tính đa hình:

    ```java
    class Node<T> {
        public T data;
        
        public void setData(T data) {
            this.data = data;
        }
    }

    class IntegerNode extends Node<Integer> {
        @Override
        public void setData(Integer data) {
            System.out.println("IntegerNode.setData");
            super.setData(data);
        }
    }

    // Compiler generates bridge method:
    // public void setData(Object data) {
    //     setData((Integer) data);  // Calls the actual method
    // }
    ```

    **Ý nghĩa của việc xóa kiểu:**

    ```java
    public class TypeErasureDemo {
        public static void main(String[] args) {
            // 1. Cannot create instances of type parameters
            // T obj = new T();  // Compile error
            
            // 2. Cannot create arrays of parameterized types
            // List<String>[] array = new List<String>[10];  // Compile error
            List<?>[] array = new List<?>[10];  // OK with wildcard
            
            // 3. Cannot use instanceof with parameterized types
            List<String> list = new ArrayList<>();
            // if (list instanceof ArrayList<String>) {}  // Compile error
            if (list instanceof ArrayList<?>) {}  // OK with wildcard
            
            // 4. Runtime type is same regardless of type parameter
            List<String> stringList = new ArrayList<>();
            List<Integer> intList = new ArrayList<>();
            System.out.println(stringList.getClass() == intList.getClass());  // true
            
            // 5. Cannot overload methods that have same erasure
            // void process(List<String> list) {}
            // void process(List<Integer> list) {}  // Compile error - same erasure
        }
        
        // Workaround: Use Class<T> for runtime type information
        public static <T> T createInstance(Class<T> clazz) throws Exception {
            return clazz.getDeclaredConstructor().newInstance();
        }
    }
    ```

    **Tại sao phải gõ Xóa?**
    - Khả năng tương thích ngược với mã tiền generic
    - Không cần hướng dẫn mã byte mới
    - Giảm dung lượng bộ nhớ (không có thông tin loại thời gian chạy)

    **Hạn chế:**
    - Không thể xác định loại chung khi chạy
    - Không thể tạo mảng chung
    - Không thể sử dụng nguyên thủy làm tham số kiểu
    - Không thể bắt hoặc ném các ngoại lệ chung

    **[⬆ Quay lại đầu trang](#table-of-contents)**


<!-- QUESTIONS_END -->
