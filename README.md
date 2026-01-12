# java-interview-questions (Phiên bản Head First Java Tiếng Việt)

Các câu hỏi phỏng vấn Java thường gặp - Giải thích siêu dễ hiểu, siêu vui vẻ!

### Mục lục

<!-- TOC_START -->
| STT | Câu hỏi |
| --- | ------- |
| 1 | [JVM, JRE và JDK khác nhau thế nào? (Đừng nhầm nữa nhé!)](#jvm-jre-và-jdk-khác-nhau-thế-nào-đừng-nhầm-nữa-nhé) |
| 2 | [Tại sao Java lại "không kén chọn" nền tảng?](#tại-sao-java-lại-không-kén-chọn-nền-tảng) |
| 3 | [JVM hoạt động "ma thuật" thế nào?](#jvm-hoạt-động-ma-thuật-thế-nào) |
| 4 | [Đặc điểm "độc" của Java là gì?](#đặc-điểm-độc-của-java-là-gì) |
| 5 | [public static void main() - Cửa ngõ vào Java là gì?](#public-static-void-main---cửa-ngõ-vào-java-là-gì) |
| 6 | [String Constant Pool - "Kho chứa" chuỗi đặc biệt](#string-constant-pool---kho-chứa-chuỗi-đặc-biệt) |
| 7 | [Tại sao String "cứng đầu" không thay đổi được?](#tại-sao-string-cứng-đầu-không-thay-đổi-được) |
| 8 | [StringBuffer vs StringBuilder - Ai nhanh hơn?](#stringbuffer-vs-stringbuilder---ai-nhanh-hơn) |
| 9 | [hashCode() và equals() - Cặp bài trùng không thể thiếu](#hashcode-và-equals---cặp-bài-trùng-không-thể-thiếu) |
| 10 | [Checked vs Unchecked Exceptions - Lỗi có báo trước và "hổ báo"](#checked-vs-unchecked-exceptions---lỗi-có-báo-trước-và-hổ-báo) |
| 11 | [Wrapper Classes - "Bọc" kiểu nguyên thủy](#wrapper-classes---bọc-kiểu-nguyên-thủy) |
| 12 | [Java không phải OOP "nguyên chất" - Tại sao?](#java-không-phải-oop-nguyên-chất---tại-sao) |
| 13 | [Abstract Class vs Interface - Ai là "ông trùm"?](#abstract-class-vs-interface---ai-là-ông-trùm) |
| 14 | [Marker Interfaces - "Tem nhãn" bí ẩn](#marker-interfaces---tem-nhãn-bí-ẩn) |
| 15 | [Collections trong Java - "Rổ đựng" đối tượng](#collections-trong-java---rổ-đựng-đối-tượng) |
| 16 | [ArrayList vs Vector - Ai mạnh hơn?](#arraylist-vs-vector---ai-mạnh-hơn) |
| 17 | [finalize() - Lời từ biệt của đối tượng](#finalize---lời-từ-biệt-của-đối-tượng) |
| 18 | [Comparable vs Comparator - Sắp xếp kiểu gì?](#comparable-vs-comparator---sắp-xếp-kiểu-gì) |
| 19 | [Inner Class - Lớp lồng trong lớp](#inner-class---lớp-lồng-trong-lớp) |
| 20 | [final, finally, finalize() - Ba thằng "gần giống nhau"](#final-finally-finalize---ba-thằng-gần-giống-nhau) |
| 21 | [== vs equals() - So sánh kiểu gì cho đúng?](#-vs-equals---so-sánh-kiểu-gì-cho-đúng) |
| 22 | [Method Overloading vs Overriding - Ghi đè hay Tải chồng?](#method-overloading-vs-overriding---ghi-đè-hay-tải-chồng) |
| 23 | [HashMap vs Hashtable - Bản đồ của ai?](#hashmap-vs-hashtable---bản-đồ-của-ai) |
| 24 | [ArrayList vs LinkedList - Mảng hay Danh sách liên kết?](#arraylist-vs-linkedlist---mảng-hay-danh-sách-liên-kết) |
| 25 | [Java Reflection API - "Soi" vào bên trong lớp](#java-reflection-api---soi-vào-bên-trong-lớp) |
| 26 | [Các vùng nhớ JVM phân bổ - Bộ nhớ "chia năm xẻ bảy"](#các-vùng-nhớ-jvm-phân-bổ---bộ-nhớ-chia-năm-xẻ-bảy) |
| 27 | [throw vs throws - Ném lỗi thế nào?](#throw-vs-throws---ném-lỗi-thế-nào) |
| 28 | [Singleton Class - Lớp "duy nhất" trên đời](#singleton-class---lớp-duy-nhất-trên-đời) |
| 29 | [Java 8 Stream API - Xử lý dữ liệu "dòng chảy"](#java-8-stream-api---xử-lý-dữ-liệu-dòng-chảy) |
| 30 | [Fail-fast vs Fail-safe Iterators - Lặp lại an toàn?](#fail-fast-vs-fail-safe-iterators---lặp-lại-an-toàn) |
| 31 | [Process vs Thread - Tiến trình hay Luồng?](#process-vs-thread---tiến-trình-hay-luồng) |
| 32 | [Các cách tạo Thread trong Java](#các-cách-tạo-thread-trong-java) |
| 33 | [Synchronization - Đồng bộ hóa "cùng ăn, cùng ngủ"](#synchronization---đồng-bộ-hóa-cùng-ăn-cùng-ngủ) |
| 34 | [Deadlock - Kẹt xe trong lập trình](#deadlock---kẹt-xe-trong-lập-trình) |
| 35 | [volatile - Từ khóa "biến động"](#volatile---từ-khóa-biến-động) |
| 36 | [transient - Từ khóa "tạm thời"](#transient---từ-khóa-tạm-thời) |
| 37 | [Serialization & Deserialization - "Đóng băng" đối tượng](#serialization--deserialization---đóng-băng-đối-tượng) |
| 38 | [Functional Interfaces - Giao diện "hàm số"](#functional-interfaces---giao-diện-hàm-số) |
| 39 | [Lambda Expressions - Hàm ẩn danh "siêu gọn"](#lambda-expressions---hàm-ẩn-danh-siêu-gọn) |
| 40 | [Optional Class - Hộp đựng an toàn](#optional-class---hộp-đựng-an-toàn) |
| 41 | [Collection vs Collections - Khác một chữ, khác cả trời đất](#collection-vs-collections---khác-một-chữ-khác-cả-trời-đất) |
| 42 | [Set vs List - Tập hợp hay Danh sách?](#set-vs-list---tập-hợp-hay-danh-sách) |
| 43 | [HashSet vs TreeSet - Ai nhanh hơn?](#hashset-vs-treeset---ai-nhanh-hơn) |
| 44 | [Diamond Problem - Vấn đề "kim cương"](#diamond-problem---vấn-đề-kim-cương) |
| 45 | [Dependency Injection - Tiêm phụ thuộc "thần kỳ"](#dependency-injection---tiêm-phụ-thuộc-thần-kỳ) |
| 46 | [Shallow Copy vs Deep Copy - Sao chép nông hay sâu?](#shallow-copy-vs-deep-copy---sao-chép-nông-hay-sâu) |
| 47 | [Design Patterns - Mẫu thiết kế "bí kíp"](#design-patterns---mẫu-thiết-kế-bí-kíp) |
| 48 | [Factory Design Pattern - Xưởng sản xuất "thông minh"](#factory-design-pattern---xưởng-sản-xuất-thông-minh) |
| 49 | [Builder Design Pattern - Xây dựng "từng bước"](#builder-design-pattern---xây-dựng-từng-bước) |
| 50 | [Heap vs Stack Memory - Núi hay Đống?](#heap-vs-stack-memory---núi-hay-đống) |
| 51 | [Garbage Collection - Dọn rác "tự động"](#garbage-collection---dọn-rác-tự-động) |
| 52 | [Các loại Garbage Collectors - Đội dọn rác](#các-loại-garbage-collectors---đội-dọn-rác) |
| 53 | [wait() vs sleep() - Ngủ hay Chờ?](#wait-vs-sleep---ngủ-hay-chờ) |
| 54 | [notify() vs notifyAll() - Đánh thức một hay tất cả?](#notify-vs-notifyall---đánh-thức-một-hay-tất-cả) |
| 55 | [Immutable Class - Lớp "bất biến"](#immutable-class---lớp-bất-biến) |
| 56 | [String, StringBuilder, StringBuffer - Chuỗi "cứng đầu" hay "dễ bảo"?](#string-stringbuilder-stringbuffer---chuỗi-cứng-đầu-hay-dễ-bảo) |
| 57 | [static vs instance variables - Biến chung hay riêng?](#static-vs-instance-variables---biến-chung-hay-riêng) |
| 58 | [super - Từ khóa "cha mẹ"](#super---từ-khóa-cha-mẹ) |
| 59 | [this - Từ khóa "bản thân"](#this---từ-khóa-bản-thân) |
| 60 | [Generics - "Tham số hóa" kiểu dữ liệu](#generics---tham-số-hóa-kiểu-dữ-liệu) |
| 61 | [Type Erasure - Xóa bỏ kiểu "tinh vi"](#type-erasure---xóa-bỏ-kiểu-tinh-vi) |
<!-- TOC_END -->

<!-- QUESTIONS_START -->

## 1. ### JVM, JRE và JDK khác nhau thế nào? (Đừng nhầm nữa nhé!)

Ôi trời ơi, ba thứ này làm bao lập trình viên mới "đau đầu"! Nhưng đừng lo, chúng ta sẽ làm rõ từng cái một như cách bạn phân biệt ba anh em sinh ba vậy.

**JVM (Máy ảo Java):**  
Tưởng tượng JVM như một "dịch giả đa ngôn ngữ" vậy đó! Nó là cỗ máy trừu tượng cung cấp môi trường chạy cho mã Java Bytecode. Nói đơn giản, JVM là thành phần của JRE và có nhiệm vụ "phiên dịch" bytecode thành mã máy mà hệ điều hành có thể hiểu được.

Điều thú vị là:
- Bản thân JVM thì **PHỤ THUỘC** vào nền tảng (mỗi hệ điều hành có JVM riêng)
- Nhưng bytecode mà nó dịch thì **KHÔNG PHỤ THUỘC** nền tảng
- Chính vì thế mà ứng dụng Java mới có thể "viết một lần, chạy mọi nơi"!

**JRE (Môi trường chạy Java):**  
JRE chính là "bộ công cụ" giúp bạn chạy ứng dụng Java. Nó bao gồm:
- Máy ảo Java (JVM)
- Thư viện chuẩn (các class cần thiết)
- Các thành phần khác để chạy chương trình

**JDK (Bộ phát triển Java):**  
Nếu bạn muốn **lập trình** Java, bạn cần JDK - "bộ đồ nghề đầy đủ" cho lập trình viên:
- JRE (để chạy chương trình)
- Công cụ biên dịch (javac)
- Công cụ gỡ lỗi, giám sát
- Thư viện phát triển

![JVM JRE JDK](images/JVM_JRE_JDK.png)

**Mẹo nhớ nhanh:**  
- **JDK** = **JRE** + Công cụ phát triển  
- **JRE** = **JVM** + Thư viện chuẩn  
- **JVM** = "Dịch giả" bytecode

> 💡 **Brain Power:** Bạn không cần cài JDK để chạy ứng dụng Java, chỉ cần JRE là đủ! Nhưng để lập trình, bạn phải có JDK.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 2. ### Tại sao Java lại "không kén chọn" nền tảng?

Java nổi tiếng với câu slogan "Write Once, Run Anywhere" (WORA) - Viết một lần, chạy mọi nơi. Nhưng làm sao nó làm được điều "ma thuật" này?

**Bí mật nằm ở Bytecode và JVM!**

1. Bạn viết code Java (.java)
2. Trình biên dịch (javac) chuyển thành bytecode (.class)
3. Bytecode này **KHÔNG PHỤ THUỘC** vào hệ điều hành
4. Trên mỗi nền tảng, có **JVM riêng** để dịch bytecode thành mã máy

![Platform Independence](images/platform_independence.png)

**Ví dụ thực tế:**  
Bạn viết ứng dụng trên máy Windows → Chạy được trên macOS, Linux, thậm chí cả Raspberry Pi! Chỉ cần cài JVM tương ứng cho hệ điều đó.

> 💡 **Brain Power:** Không phải ngôn ngữ nào cũng làm được điều này! C/C++ phải biên dịch riêng cho từng nền tảng, còn Python cần trình thông dịch (interpreter) khác nhau.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 3. ### JVM hoạt động "ma thuật" thế nào?

JVM không phải là thứ "ma thuật" khó hiểu đâu! Hãy cùng khám phá "bí mật bên trong" của nó nhé.

### Kiến trúc JVM - 3 thành phần chính

1. **Bộ nạp lớp (Class Loader Subsystem)**
2. **Vùng nhớ thời gian chạy (Runtime Data Area)**
3. **Bộ thực thi (Execution Engine)**

### 1. Bộ nạp lớp (Class Loader Subsystem)

Bộ nạp lớp giống như "nhân viên thư viện" - nó biết cách tìm và nạp các class vào bộ nhớ. Có 3 "cấp bậc" trong hệ thống này:

- **Bootstrap ClassLoader (Cấp cao nhất):** Nạp các class lõi của Java (java.lang, java.util...)
- **Platform ClassLoader:** Nạp các class của nền tảng (java.net.http, java.sql...)
- **System/Application ClassLoader:** Nạp các class từ classpath của bạn

**Quy trình nạp lớp:**

1. **Loading (Nạp):** Đọc file .class, tạo biểu diễn trong bộ nhớ
2. **Linking (Liên kết):** 
   - *Verification:* Kiểm tra tính hợp lệ của file .class
   - *Preparation:* Cấp phát bộ nhớ cho biến tĩnh
   - *Resolution:* Thay thế tham chiếu bằng địa chỉ thực
3. **Initialization (Khởi tạo):** Gán giá trị thực cho biến tĩnh, chạy static block

### 2. Vùng nhớ thời gian chạy

Đây là "bộ não" của JVM, chia thành 5 khu vực:

- **Method Area:** Lưu thông tin lớp (tên class, phương thức, trường dữ liệu...)
- **Heap:** Khu vực lưu trữ **tất cả các đối tượng** - vùng "sống chung" của mọi thread
- **Stack:** Mỗi thread có stack riêng - lưu biến cục bộ, trạng thái phương thức
- **PC Registers:** Lưu địa chỉ lệnh đang thực thi
- **Native Method Stack:** Lưu thông tin cho phương thức native (C/C++)

### 3. Bộ thực thi (Execution Engine)

Bộ này "dịch" bytecode thành mã máy. Gồm 3 thành phần chính:

- **Interpreter:** Đọc và thực thi bytecode từng dòng - nhanh để bắt đầu nhưng chậm với code lặp
- **JIT Compiler (Just-In-Time):** Tối ưu code thường xuyên chạy - biến bytecode thành native code
- **Garbage Collector:** Dọn dẹp bộ nhớ, thu hồi đối tượng không dùng

![JVM Architecture](images/jvm_architecture.png)

> 💡 **Brain Power:** JIT Compiler chính là lý do Java chạy nhanh như native code! Nó chỉ dịch những phần code "nóng" (hotspot) mà thôi.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 4. ### Đặc điểm "độc" của Java là gì?

Java có những đặc điểm "độc nhất vô nhị" khiến nó trở thành "ông hoàng" trong làng lập trình. Hãy cùng khám phá nào!

### 1. **Đơn giản (Simple) - Dễ như ăn kẹo!**
- Dựa trên C++ nhưng bỏ đi những thứ phức tạp
- Không có con trỏ (pointer) - tránh các lỗi khó phát hiện
- Không overload operator - code rõ ràng hơn
- Garbage Collection tự động dọn rác - không cần lo "xóa bộ nhớ"

### 2. **Hướng đối tượng (OOP) - Mọi thứ đều là đối tượng!**
Java tuân thủ 4 nguyên tắc OOP "vàng":
- **Trừu tượng (Abstraction):** Che giấu chi tiết, chỉ hiện giao diện
- **Đóng gói (Encapsulation):** Dùng getter/setter thay vì biến public
- **Kế thừa (Inheritance):** "Con sinh ra từ cha" - tái sử dụng code
- **Đa hình (Polymorphism):** Một hành động, nhiều cách thực hiện

### 3. **Di động (Portable) - Mang theo mọi nơi!**
Bytecode sinh ra trên máy này chạy được trên máy khác - không cần biên dịch lại.

### 4. **Độc lập nền tảng (Platform Independent) - "Không kén chọn" OS!**
Như đã nói ở phần trước, nhờ WORA mà Java có thể chạy trên mọi hệ điều hành.

### 5. **Robust (Chắc chắn) - Ít bug, ít đau đầu!**
- Xử lý ngoại lệ (exception handling) tốt
- Quản lý bộ nhớ tự động qua Garbage Collector
- Kiểm tra lỗi biên dịch kỹ lưỡng

### 6. **Bảo mật (Secured) - An toàn như "pháo đài"!**
- Không có con trỏ - không thể truy cập vùng nhớ trái phép
- Chạy trong môi trường ảo (JVM) - cách ly với hệ điều hành
- Bytecode verifier kiểm tra code "độc hại"

### 7. **Phân tán (Distributed) - Kết nối mọi thứ!**
Hỗ trợ RMI (Remote Method Invocation) để gọi phương thức từ xa.

### 8. **Đa luồng (Multi-threaded) - Làm nhiều việc cùng lúc!**
Cho phép chạy song song nhiều tác vụ - tận dụng tối đa CPU.

### 9. **Biên dịch và Thông dịch - Kết hợp sức mạnh!**
- Biên dịch thành bytecode (nhanh)
- Thông dịch bytecode thành native code (linh hoạt)

### 10. **Hiệu năng cao - Nhanh như gió!**
- Bytecode gần với native code
- JIT Compiler tối ưu code thường xuyên chạy
- Các kỹ thuật như method inlining, dead code elimination...

> 💡 **Brain Power:** Java không phải là ngôn ngữ nhanh nhất (C/C++ vẫn nhanh hơn), nhưng nó cân bằng giữa tốc độ, bảo mật và dễ phát triển - đó là lý do nó tồn tại suốt 25+ năm!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 5. ### public static void main() - Cửa ngõ vào Java là gì?

`main()` chính là "cửa trước" của ngôi nhà Java - nơi JVM bắt đầu chạy chương trình của bạn. Nếu không có nó, chương trình sẽ không chạy được!

```java
public static void main(String[] args) {
    System.out.println("Hello World");
}
```

Hãy cùng "phân tích" từng từ trong dòng này:

1. **public:**  
   - "Mở cửa" cho JVM vào được!  
   - Nếu không public, JVM không gọi được → Lỗi "Main method not found"

2. **static:**  
   - Phương thức thuộc về **lớp**, không cần tạo đối tượng  
   - Tiết kiệm bộ nhớ (không cần new object chỉ để chạy main)

3. **void:**  
   - Phương thức **không trả về** giá trị nào  
   - Khi main() kết thúc, chương trình kết thúc

4. **main:**  
   - Tên **bắt buộc** JVM nhận ra  
   - Không thể đổi tên thành "start" hay "run"

5. **String[] args:**  
   - Mảng chuỗi nhận tham số từ dòng lệnh  
   - Ví dụ: `java MyApp arg1 arg2` → args = {"arg1", "arg2"}

> 💡 **Brain Power:** Bạn có thể tạo nhiều phương thức main() (nạp chồng), nhưng JVM chỉ chạy phương thức main() với đúng signature trên!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 6. ### String Constant Pool - "Kho chứa" chuỗi đặc biệt

String Constant Pool giống như một "kho chứa" thông minh trong vùng heap, nơi lưu trữ các **chuỗi literal** (chuỗi viết trực tiếp trong code).

**Tại sao cần Pool này?**
- Tiết kiệm bộ nhớ (nhiều biến cùng trỏ đến một chuỗi)
- Tăng tốc độ so sánh chuỗi

**Cơ chế hoạt động:**
1. Khi bạn tạo chuỗi literal: `String s = "Hello";`
2. JVM kiểm tra Pool xem có sẵn "Hello" chưa
3. Nếu có → trả về tham chiếu đến chuỗi đó
4. Nếu không → tạo mới và thêm vào Pool

```java
String s1 = "Hello"; // Tạo mới trong Pool
String s2 = "Hello"; // Lấy từ Pool (cùng tham chiếu với s1)
String s3 = new String("Hello"); // Tạo mới trên heap (khác tham chiếu)

System.out.println(s1 == s2); // true (cùng trong Pool)
System.out.println(s1 == s3); // false (s3 trên heap)
```

> 💡 **Brain Power:** String Pool được quản lý bởi lớp String, và nó **rỗng mặc định**. Bạn có thể "thêm" chuỗi vào Pool bằng `intern()`:
> ```java
> String s4 = new String("World").intern(); // Đẩy vào Pool
> ```

**[⬆ Quay lại Mục lục](#mục-lục)**

## 7. ### Tại sao String "cứng đầu" không thay đổi được?

String là **immutable** (bất biến) - một khi tạo ra, nội dung không thể thay đổi. Tại sao lại như vậy?

**Ví dụ "cứng đầu":**
```java
String s = "Hello";
s.concat(" World"); // Tạo CHUỖI MỚI, không thay đổi s
System.out.println(s); // Vẫn là "Hello"
```

**Lợi ích của việc immutable:**
- **Bảo mật:** Không ai thay đổi được nội dung (ví dụ: password)
- **Đồng bộ hóa:** An toàn khi dùng đa luồng (không cần synchronized)
- **Hiệu năng:** String Pool hoạt động hiệu quả hơn
- **Hashcode ổn định:** Hoạt động tốt với HashMap/HashSet

**Cơ chế "ẩn đằng sau":**
Khi bạn "thay đổi" String:
1. JVM tạo **chuỗi mới** với nội dung mới
2. Tham chiếu cũ trỏ đến chuỗi mới
3. Chuỗi cũ trở thành rác → Garbage Collector dọn dẹp

> 💡 **Brain Power:** Nếu bạn cần thay đổi chuỗi nhiều lần, hãy dùng **StringBuilder** hoặc **StringBuffer** - chúng là mutable!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 8. ### StringBuffer vs StringBuilder - Ai nhanh hơn?

Cả hai đều là phiên bản **mutable** của String, nhưng có sự khác biệt quan trọng:

| StringBuffer | StringBuilder |
|--------------|---------------|
| **Có từ Java 1.0** | Có từ Java 1.5 |
| **Đồng bộ hóa (thread-safe)** | **Không đồng bộ hóa** |
| **Chậm hơn** | **Nhanh hơn** |

**Giải thích "dễ hiểu":**
- **StringBuffer:** Giống như quán ăn có 1 nhân viên phục vụ - khách phải xếp hàng (thread-safe nhưng chậm)
- **StringBuilder:** Giống như quán ăn có nhiều nhân viên - khách được phục vụ cùng lúc (nhanh nhưng không an toàn đa luồng)

**Khi nào dùng cái nào?**
- Dùng **StringBuffer** khi làm việc với đa luồng (ví dụ: ứng dụng web)
- Dùng **StringBuilder** khi làm việc đơn luồng (ví dụ: xử lý chuỗi trong method)

```java
// Đơn luồng - dùng StringBuilder (nhanh hơn)
StringBuilder sb = new StringBuilder("Hello");
sb.append(" World");

// Đa luồng - dùng StringBuffer (an toàn)
StringBuffer sf = new StringBuffer("Hello");
sf.append(" World");
```

> 💡 **Brain Power:** Trong 90% trường hợp, bạn nên dùng **StringBuilder** - vì phần lớn code Java là đơn luồng!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 9. ### hashCode() và equals() - Cặp bài trùng không thể thiếu

Hai phương thức này là "cặp bài trùng" giúp xác định **sự bằng nhau** của các đối tượng trong Java.

### 1. equals() - So sánh nội dung

**Mặc định (trong Object):**
```java
public boolean equals(Object obj) {
    return (this == obj); // So sánh tham chiếu (như ==)
}
```

**Quy tắc khi override equals():**
- **Phản xạ (Reflexive):** `x.equals(x)` phải trả về true
- **Đối xứng (Symmetric):** Nếu `x.equals(y)` → `y.equals(x)` phải true
- **Bắc cầu (Transitive):** Nếu `x.equals(y)` và `y.equals(z)` → `x.equals(z)` phải true
- **Nhất quán (Consistent):** Gọi nhiều lần phải cho cùng kết quả

### 2. hashCode() - Mã băm "định danh"

**Quy tắc khi override hashCode():**
- Nếu `x.equals(y)` → `x.hashCode() == y.hashCode()`
- Nếu `x.hashCode() != y.hashCode()` → `x.equals(y)` phải false
- Nhưng nếu `x.hashCode() == y.hashCode()` → `x.equals(y)` có thể true hoặc false

**Ví dụ thực tế:**
```java
class Person {
    private String name;
    private int age;
    
    // Override equals()
    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        if (o == null || getClass() != o.getClass()) return false;
        Person person = (Person) o;
        return age == person.age && name.equals(person.name);
    }
    
    // Override hashCode()
    @Override
    public int hashCode() {
        return Objects.hash(name, age);
    }
}
```

> 💡 **Brain Power:** Luôn override **cả hai** khi bạn override một trong hai! Nếu không, các cấu trúc như HashMap sẽ hoạt động sai.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 10. ### Checked vs Unchecked Exceptions - Lỗi có báo trước và "hổ báo"

Trong Java, Exception được chia làm hai loại chính:

### 1. Checked Exceptions - Lỗi "có báo trước"

- **Bị kiểm tra tại thời điểm biên dịch**
- **Bắt buộc phải xử lý** (try/catch) hoặc khai báo (throws)
- **Là con của Exception (trừ RuntimeException)**

**Ví dụ:**
- IOException
- FileNotFoundException
- ClassNotFoundException
- SQLException

```java
// Phải xử lý hoặc khai báo
void readFile() throws FileNotFoundException {
    new FileInputStream("file.txt");
}
```

### 2. Unchecked Exceptions - Lỗi "hổ báo"

- **Không bị kiểm tra tại thời điểm biên dịch**
- **Không bắt buộc phải xử lý**
- **Là con của RuntimeException hoặc Error**

**Ví dụ:**
- NullPointerException
- ArrayIndexOutOfBoundsException
- ArithmeticException
- IllegalArgumentException

```java
// Không cần try/catch
void divide(int a, int b) {
    System.out.println(a / b); // Có thể gây ArithmeticException
}
```

![Exception Hierarchy](images/exception_hierarchy.png)

> 💡 **Brain Power:** Dùng **Checked** cho lỗi có thể phục hồi (ví dụ: file không tồn tại), dùng **Unchecked** cho lỗi lập trình (ví dụ: chia cho 0).

**[⬆ Quay lại Mục lục](#mục-lục)**

## 11. ### Wrapper Classes - "Bọc" kiểu nguyên thủy

Wrapper Classes là các lớp "bao bọc" cho các kiểu nguyên thủy (primitive types), giúp chúng hoạt động như đối tượng.

**Tại sao cần Wrapper?**
- Các cấu trúc Collections chỉ làm việc với đối tượng (không nhận primitive)
- Cần chuyển đổi giữa primitive và object
- Cung cấp các phương thức tiện ích

**Bảng tương ứng:**

| Kiểu nguyên thủy | Wrapper Class |
|------------------|---------------|
| byte             | Byte          |
| short            | Short         |
| int              | Integer       |
| long             | Long          |
| float            | Float         |
| double           | Double        |
| boolean          | Boolean       |
| char             | Character     |

**Autoboxing & Unboxing - "Tự động hóa"**

**Autoboxing (primitive → object):**
```java
int num = 10;
Integer x = num; // Tự động "bọc" (autoboxing)
```

**Unboxing (object → primitive):**
```java
Integer y = new Integer(20);
int value = y; // Tự động "gỡ bọc" (unboxing)
```

> 💡 **Brain Power:** Từ Java 5 trở đi, bạn không cần convert thủ công nữa! JVM tự động thực hiện autoboxing/unboxing.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 12. ### Java không phải OOP "nguyên chất" - Tại sao?

Mặc dù Java là ngôn ngữ hướng đối tượng, nhưng nó **KHÔNG PHẢI** OOP "nguyên chất" vì hai lý do chính:

### 1. Kiểu nguyên thủy (Primitive Types)
- Java có các kiểu nguyên thủy như `int`, `boolean`, `char`...
- Những kiểu này **không phải là đối tượng** (khác với trong Smalltalk, Ruby)
- Dù có Wrapper Classes, nhưng chúng chỉ là "bản sao" của primitive

### 2. Phương thức và biến static
- `static` methods và variables **không thuộc về đối tượng**
- Chúng thuộc về **lớp** - vi phạm nguyên tắc "mọi thứ đều là đối tượng"
- Ví dụ: `Math.sqrt()` không cần tạo đối tượng Math

**So sánh với OOP "nguyên chất":**
- Trong Smalltalk: Mọi thứ đều là đối tượng (kể cả số 5)
- Trong Java: Có primitive types và static members

> 💡 **Brain Power:** Java chọn **hiệu năng** thay vì thuần túy OOP. Primitive types giúp chạy nhanh hơn so với object.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 13. ### Abstract Class vs Interface - Ai là "ông trùm"?

Cả hai đều dùng để định nghĩa "giao ước", nhưng có sự khác biệt quan trọng:

| Abstract Class | Interface |
|----------------|-----------|
| Dùng `abstract` keyword | Dùng `interface` keyword |
| Kế thừa bằng `extends` | Kế thừa bằng `implements` |
| Có thể có **phương thức trừu tượng và cụ thể** | Từ Java 8: Có thể có **default và static methods** |
| Hỗ trợ **tất cả các biến** (final, static, non-static) | Chỉ hỗ trợ **biến static final** |
| **Không hỗ trợ đa kế thừa** | **Hỗ trợ đa kế thừa** |
| Có thể có **bất kỳ access modifier** nào | Chỉ có **public** (Java 9+ hỗ trợ private) |

**Khi nào dùng cái nào?**
- Dùng **Abstract Class** khi:
  - Bạn cần chia sẻ code giữa các lớp liên quan
  - Bạn cần có biến instance hoặc constructor
  - Bạn cần access modifier khác public

- Dùng **Interface** khi:
  - Bạn muốn một lớp implement nhiều behavior
  - Bạn cần đa kế thừa
  - Bạn muốn tách biệt hoàn toàn interface và implementation

> 💡 **Brain Power:** Từ Java 8, Interface và Abstract Class càng giống nhau hơn nhờ default methods. Nhưng Abstract Class vẫn có constructor và biến instance!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 14. ### Marker Interfaces - "Tem nhãn" bí ẩn

Marker Interfaces là những interface **trống rỗng** - không có phương thức, biến nào. Chúng giống như những "tem nhãn" dán lên lớp.

**Ví dụ nổi tiếng:**
- `Serializable` - Đánh dấu lớp có thể serialize
- `Cloneable` - Đánh dấu lớp có thể clone
- `Remote` - Đánh dấu lớp có thể truy cập từ xa

**Tại sao cần Marker Interfaces?**
- Cung cấp thông tin **thời gian chạy** cho JVM
- Dùng trong framework để nhận biết behavior đặc biệt
- Không cần code, chỉ cần "dán tem" là xong!

**Ví dụ thực tế:**
```java
// Marker Interface
public interface Serializable { }

// Lớp sử dụng
class User implements Serializable {
    // Code bình thường
}
```

**Cơ chế hoạt động:**
- Khi bạn gọi `ObjectOutputStream.writeObject(user)`
- JVM kiểm tra `user instanceof Serializable`
- Nếu không implement → Ném `NotSerializableException`

**Thay thế cho Marker Interfaces:**
- **Annotations:** `@Serializable` (linh hoạt hơn, có thể có tham số)
- **Internal flags:** Biến boolean trong lớp

> 💡 **Brain Power:** Marker Interfaces đang dần được thay thế bởi Annotations từ Java 5 trở đi, nhưng vẫn tồn tại vì tính tương thích ngược.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 15. ### Collections trong Java - "Rổ đựng" đối tượng

Collections Framework là **bộ khung thống nhất** để lưu trữ và xử lý nhóm đối tượng. Nó cung cấp nhiều cấu trúc dữ liệu "sẵn sàng sử dụng".

**Các thành phần chính:**

![Collections Framework](images/collections_framework.png)

**Phân loại chính:**
- **List:** Thứ tự, cho phép phần tử trùng lặp (ArrayList, LinkedList)
- **Set:** Không thứ tự, không phần tử trùng lặp (HashSet, TreeSet)
- **Queue:** Thứ tự FIFO (PriorityQueue, LinkedList)
- **Map:** Cặp key-value (HashMap, TreeMap)

**Lợi ích của Collections:**
- **Tái sử dụng code** - không cần tự viết lại cấu trúc dữ liệu
- **Hiệu năng tối ưu** - được các chuyên gia tối ưu hóa
- **Giao diện chuẩn** - dễ học, dễ dùng
- **Thuật toán sẵn có** - sort, search, shuffle...

```java
// Ví dụ sử dụng Collections
List<String> names = new ArrayList<>();
names.add("John");
names.add("Jane");
Collections.sort(names); // Sắp xếp dễ như ăn kẹo!
```

> 💡 **Brain Power:** Collections Framework được thiết kế theo mẫu **Adapter** - cho phép chuyển đổi giữa các cấu trúc một cách linh hoạt.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 16. ### ArrayList vs Vector - Ai mạnh hơn?

Cả hai đều là **danh sách động**, nhưng có những khác biệt quan trọng:

| ArrayList | Vector |
|-----------|--------|
| **Phần của Collections Framework (JDK 1.2)** | **Lớp "cổ điển" (JDK 1.0)** |
| **Không đồng bộ hóa (nhanh hơn)** | **Đồng bộ hóa (chậm hơn)** |
| **Tăng 50% kích thước khi đầy** | **Tăng 100% kích thước khi đầy** |
| **Chỉ dùng Iterator** | **Dùng cả Iterator và Enumeration** |

**Giải thích "dễ hiểu":**
- **ArrayList:** Giống như "thùng rác thông minh" - nhẹ nhàng, nhanh chóng
- **Vector:** Giống như "thùng rác an toàn" - chậm hơn nhưng an toàn đa luồng

**Khi nào dùng cái nào?**
- **ArrayList:** 90% trường hợp (đơn luồng, hiệu năng cao)
- **Vector:** Chỉ khi cần thread-safe mà không dùng Collections.synchronizedList()

```java
// Dùng ArrayList (phổ biến)
List<String> list = new ArrayList<>();

// Dùng Vector (ít phổ biến)
List<String> vector = new Vector<>();

// Hoặc dùng synchronizedList (tốt hơn Vector)
List<String> syncList = Collections.synchronizedList(new ArrayList<>());
```

> 💡 **Brain Power:** Vector đang dần bị "lỗi thời" - hãy dùng ArrayList kết hợp với synchronizedList khi cần thread-safe!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 17. ### finalize() - Lời từ biệt của đối tượng

`finalize()` là phương thức đặc biệt được gọi **trước khi** đối tượng bị Garbage Collector "dọn dẹp". Nó giống như "lời từ biệt" của đối tượng.

**Cú pháp:**
```java
protected void finalize() throws Throwable {
    // Code dọn dẹp tài nguyên
}
```

**Cơ chế hoạt động:**
1. GC phát hiện đối tượng không còn được tham chiếu
2. GC gọi `finalize()` (nếu có override)
3. Sau đó mới thu hồi bộ nhớ

**Ví dụ thực tế:**
```java
public class FileHandler {
    private FileInputStream stream;
    
    public FileHandler(String file) throws FileNotFoundException {
        stream = new FileInputStream(file);
    }
    
    @Override
    protected void finalize() throws Throwable {
        try {
            if (stream != null) {
                stream.close(); // Đảm bảo đóng file
            }
        } finally {
            super.finalize();
        }
    }
}
```

**Cảnh báo quan trọng:**
- **Không nên lạm dụng** - thời điểm gọi không xác định
- **Không đảm bảo được gọi** - GC có thể không chạy
- **Đã deprecated từ Java 9** - hãy dùng try-with-resources thay thế

> 💡 **Brain Power:** Hãy coi `finalize()` như "phương án cuối cùng" - luôn dùng try-finally hoặc try-with-resources để dọn dẹp tài nguyên!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 18. ### Comparable vs Comparator - Sắp xếp kiểu gì?

Cả hai đều dùng để sắp xếp, nhưng có cách dùng khác nhau:

### 1. Comparable - Sắp xếp "mặc định"

- **Lớp tự sắp xếp chính nó**
- Implement interface `Comparable<T>`
- Override phương thức `compareTo()`
- Chỉ cho phép **một cách sắp xếp**

```java
class Student implements Comparable<Student> {
    private int id;
    private String name;
    
    @Override
    public int compareTo(Student other) {
        return this.id - other.id; // Sắp xếp theo id
    }
}

// Sử dụng
List<Student> students = ...;
Collections.sort(students); // Dùng compareTo() mặc định
```

### 2. Comparator - Sắp xếp "tùy chọn"

- **Lớp bên ngoài sắp xếp cho lớp khác**
- Implement interface `Comparator<T>`
- Override phương thức `compare()`
- Cho phép **nhiều cách sắp xếp**

```java
// Sắp xếp theo tên
Comparator<Student> byName = (s1, s2) -> 
    s1.getName().compareTo(s2.getName());

// Sắp xếp theo tuổi
Comparator<Student> byAge = (s1, s2) -> 
    s1.getAge() - s2.getAge();

// Sử dụng
Collections.sort(students, byName);
```

**Khi nào dùng cái nào?**
- Dùng **Comparable** khi lớp có "thứ tự tự nhiên" (ví dụ: số nguyên sắp xếp theo giá trị)
- Dùng **Comparator** khi cần nhiều cách sắp xếp hoặc không thể sửa lớp gốc

> 💡 **Brain Power:** Từ Java 8, Comparator có các phương thức tiện ích như `comparing()`, `thenComparing()` giúp viết code ngắn gọn hơn!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 19. ### Inner Class - Lớp lồng trong lớp

Inner Class là lớp được định nghĩa **bên trong** một lớp khác. Nó giống như "ngôi nhà trong ngôi nhà" vậy!

**Có 4 loại Inner Class chính:**

### 1. Member Inner Class (Lớp lồng không static)

- Truy cập được **tất cả thành viên** của lớp ngoài
- Cần instance của lớp ngoài để tạo

```java
class Outer {
    private int data = 30;
    
    class Inner {
        void display() {
            System.out.println("Data: " + data); // Truy cập biến private
        }
    }
    
    public static void main(String[] args) {
        Outer outer = new Outer();
        Outer.Inner inner = outer.new Inner(); // Cần instance outer
        inner.display();
    }
}
```

### 2. Static Nested Class (Lớp lồng static)

- Chỉ truy cập được **thành viên static** của lớp ngoài
- Không cần instance của lớp ngoài

```java
class Outer {
    static int data = 30;
    
    static class Nested {
        void display() {
            System.out.println("Data: " + data);
        }
    }
    
    public static void main(String[] args) {
        Outer.Nested nested = new Outer.Nested(); // Không cần instance outer
        nested.display();
    }
}
```

### 3. Local Inner Class (Lớp trong phương thức)

- Định nghĩa **bên trong phương thức**
- Chỉ truy cập được biến **final** hoặc **effectively final**

```java
class Outer {
    void display() {
        final int num = 23; // Hoặc int num = 23 (effectively final)
        
        class Local {
            void print() {
                System.out.println("Number: " + num);
            }
        }
        
        new Local().print();
    }
}
```

### 4. Anonymous Inner Class (Lớp ẩn danh)

- Không có tên, định nghĩa và khởi tạo cùng lúc
- Thường dùng để override phương thức

```java
interface Greeting {
    void sayHello();
}

public class Main {
    public static void main(String[] args) {
        Greeting greeting = new Greeting() {
            @Override
            public void sayHello() {
                System.out.println("Hello from anonymous class!");
            }
        };
        
        greeting.sayHello();
    }
}
```

> 💡 **Brain Power:** Inner Class giúp tăng tính đóng gói và tổ chức code tốt hơn - nhưng đừng lạm dụng, code sẽ trở nên khó đọc!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 20. ### final, finally, finalize() - Ba thằng "gần giống nhau"

Ba từ khóa này **hoàn toàn khác nhau**, nhưng hay bị nhầm lẫn:

### 1. final - Từ khóa "bất biến"

- **Biến:** Không thể thay đổi giá trị sau khi khởi tạo
- **Phương thức:** Không thể override ở lớp con
- **Lớp:** Không thể kế thừa

```java
final int MAX = 100; // Biến final

final void display() { } // Phương thức final

final class CannotExtend { } // Lớp final
```

### 2. finally - Khối "luôn thực thi"

- Dùng trong **try-catch** để đảm bảo code luôn chạy
- Dù có exception hay không

```java
try {
    // Code có thể gây exception
} finally {
    // Luôn chạy, dù có exception hay không
    // Thường dùng để đóng tài nguyên
}
```

### 3. finalize() - Phương thức "từ biệt"

- Được gọi **trước khi** GC dọn dẹp đối tượng
- **Không đảm bảo** được gọi
- Đã **deprecated** từ Java 9

```java
@Override
protected void finalize() throws Throwable {
    // Code dọn dẹp (không nên dùng)
}
```

**So sánh nhanh:**

| final | finally | finalize() |
|-------|---------|------------|
| **Từ khóa** | **Khối code** | **Phương thức** |
| Dùng cho biến/phương thức/lớp | Dùng trong try-catch | Override từ Object |
| Đảm bảo bất biến | Đảm bảo thực thi | Không đảm bảo được gọi |

> 💡 **Brain Power:** Đừng bao giờ dùng `finalize()` để dọn dẹp tài nguyên quan trọng! Hãy dùng try-with-resources hoặc close() method.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 21. ### == vs equals() - So sánh kiểu gì cho đúng?

Cả hai đều so sánh đối tượng, nhưng **cơ chế hoàn toàn khác**:

### 1. == - So sánh tham chiếu

- So sánh **địa chỉ bộ nhớ** của hai đối tượng
- Trả về true nếu **cùng trỏ đến một đối tượng**

```java
String s1 = new String("Hello");
String s2 = new String("Hello");
System.out.println(s1 == s2); // false (2 đối tượng khác nhau)
```

### 2. equals() - So sánh nội dung

- So sánh **nội dung** của hai đối tượng
- Có thể override để thay đổi cách so sánh

```java
String s1 = new String("Hello");
String s2 = new String("Hello");
System.out.println(s1.equals(s2)); // true (nội dung giống nhau)
```

**Bảng so sánh:**

| == | equals() |
|----|----------|
| So sánh **tham chiếu** | So sánh **nội dung** |
| **Không override được** | **Override được** |
| Dùng cho **primitive và object** | Chỉ dùng cho **object** |
| Trả về true nếu **cùng địa chỉ** | Trả về true nếu **nội dung giống** |

**Lưu ý quan trọng:**
- Với **primitive** (int, char...), chỉ dùng `==`
- Với **String**, luôn dùng `equals()` để so sánh nội dung
- Với **Wrapper classes**, cẩn thận với autoboxing

```java
Integer a = 1000;
Integer b = 1000;
System.out.println(a == b); // false (so sánh tham chiếu)
System.out.println(a.equals(b)); // true (so sánh giá trị)
```

> 💡 **Brain Power:** Quy tắc vàng: **Luôn dùng equals() để so sánh nội dung đối tượng!**

**[⬆ Quay lại Mục lục](#mục-lục)**

## 22. ### Method Overloading vs Overriding - Ghi đè hay Tải chồng?

Hai khái niệm này đều liên quan đến đa hình (polymorphism), nhưng **khác nhau hoàn toàn**:

### 1. Method Overloading (Nạp chồng) - Cùng tên, khác tham số

- Xảy ra **trong cùng một lớp**
- Tên phương thức **giống nhau**, nhưng **tham số khác nhau**
- **Thời gian biên dịch** (compile-time polymorphism)

```java
class Calculator {
    // Nạp chồng với 2 tham số
    int add(int a, int b) {
        return a + b;
    }
    
    // Nạp chồng với 3 tham số
    int add(int a, int b, int c) {
        return a + b + c;
    }
    
    // Nạp chồng với tham số double
    double add(double a, double b) {
        return a + b;
    }
}
```

### 2. Method Overriding (Ghi đè) - Ghi đè phương thức lớp cha

- Xảy ra **giữa lớp cha và lớp con**
- Tên phương thức, tham số **giống hệt** lớp cha
- **Thời gian chạy** (runtime polymorphism)

```java
class Animal {
    void sound() {
        System.out.println("Animal makes sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() { // Ghi đè phương thức
        System.out.println("Dog barks");
    }
}
```

**Bảng so sánh:**

| Overloading | Overriding |
|-------------|------------|
| **Cùng lớp** | **Lớp cha - lớp con** |
| **Tham số khác nhau** | **Tham số giống nhau** |
| **Compile-time** | **Runtime** |
| **Return type có thể khác** | **Return type phải giống** |
| **Access modifier bất kỳ** | **Không thu hẹp access modifier** |

**Ví dụ thực tế:**
```java
Animal animal = new Dog();
animal.sound(); // Gọi sound() của Dog (overriding)
```

> 💡 **Brain Power:** Overloading giúp code **linh hoạt hơn**, overriding giúp code **mở rộng dễ dàng hơn**!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 23. ### HashMap vs Hashtable - Bản đồ của ai?

Cả hai đều là cấu trúc **key-value**, nhưng có sự khác biệt quan trọng:

| HashMap | Hashtable |
|---------|-----------|
| **Không đồng bộ hóa** (nhanh hơn) | **Đồng bộ hóa** (chậm hơn) |
| **Cho phép một key null** | **Không cho phép null** |
| **Cho phép nhiều value null** | **Không cho phép null** |
| **Java 1.2** | **Java 1.0 (cổ điển)** |
| **Iterator fail-fast** | **Enumerator không fail-fast** |
| **Kế thừa AbstractMap** | **Kế thừa Dictionary** |

**Giải thích "dễ hiểu":**
- **HashMap:** Giống như "sổ tay ghi chú" - nhanh, tiện lợi nhưng không an toàn khi dùng chung
- **Hashtable:** Giống như "sổ lưu trữ chính thức" - chậm hơn nhưng an toàn khi nhiều người dùng

**Ví dụ code:**
```java
// HashMap - cho phép null
HashMap<String, Integer> map = new HashMap<>();
map.put(null, 0); // OK
map.put("Two", null); // OK

// Hashtable - không cho phép null
Hashtable<String, Integer> table = new Hashtable<>();
// table.put(null, 0); // NullPointerException
// table.put("Two", null); // NullPointerException
```

**Cảnh báo quan trọng:**
- **Không dùng Hashtable** trong code mới
- Dùng **ConcurrentHashMap** nếu cần thread-safe
- Dùng **HashMap** cho phần lớn trường hợp

```java
// Thay thế tốt nhất cho Hashtable
ConcurrentHashMap<String, Integer> concurrentMap = new ConcurrentHashMap<>();
```

> 💡 **Brain Power:** Hashtable đang dần bị "lỗi thời" - hãy dùng HashMap kết hợp với Collections.synchronizedMap() hoặc ConcurrentHashMap khi cần thread-safe!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 24. ### ArrayList vs LinkedList - Mảng hay Danh sách liên kết?

Cả hai đều implement **List interface**, nhưng **cơ chế lưu trữ khác nhau**:

| ArrayList | LinkedList |
|-----------|------------|
| **Mảng động** | **Danh sách liên kết đôi** |
| **Truy cập nhanh** (O(1)) | **Thao tác nhanh** (O(1) ở đầu/cuối) |
| **Thao tác chậm** (phải dịch chuyển) | **Truy cập chậm** (phải duyệt) |
| **Chỉ implement List** | **Implement cả List và Deque** |
| **Ít bộ nhớ hơn** | **Nhiều bộ nhớ hơn** (lưu prev/next) |

**Khi nào dùng cái nào?**

- **Dùng ArrayList khi:**
  - Cần truy cập ngẫu nhiên nhiều (get/set theo index)
  - Ít chèn/xóa ở giữa danh sách
  - Ví dụ: Danh sách sản phẩm, danh sách người dùng

- **Dùng LinkedList khi:**
  - Cần chèn/xóa nhiều ở đầu/cuối danh sách
  - Ít truy cập ngẫu nhiên
  - Ví dụ: Hàng đợi, Stack

**Ví dụ thực tế:**
```java
// ArrayList - tốt cho truy cập ngẫu nhiên
ArrayList<String> arrayList = new ArrayList<>();
arrayList.add("A");
arrayList.add("B");
arrayList.get(0); // O(1) - rất nhanh

// LinkedList - tốt cho chèn/xóa
LinkedList<String> linkedList = new LinkedList<>();
linkedList.addFirst("A"); // O(1) - rất nhanh
linkedList.removeLast(); // O(1) - rất nhanh
```

> 💡 **Brain Power:** ArrayList nhanh hơn trong 80% trường hợp! Chỉ dùng LinkedList khi bạn thực sự cần chèn/xóa ở đầu/cuối danh sách thường xuyên.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 25. ### Java Reflection API - "Soi" vào bên trong lớp

Reflection API cho phép bạn **"soi" vào bên trong** lớp, phương thức, trường dữ liệu... **tại thời gian chạy**.

**Có thể làm gì với Reflection?**
- Xem thông tin lớp (method, field, constructor...)
- Tạo đối tượng **động**
- Gọi phương thức **động**
- Truy cập trường **private**
- Thay đổi hành vi của lớp

**Ví dụ "soi" vào lớp:**
```java
class Person {
    private String name;
    public int age;
    
    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }
    
    private void privateMethod() {
        System.out.println("Private method called");
    }
}

// Sử dụng Reflection
Class<?> clazz = Person.class;
Method[] methods = clazz.getDeclaredMethods();

for (Method method : methods) {
    System.out.println("Method: " + method.getName());
}

// Tạo đối tượng động
Constructor<?> constructor = clazz.getConstructor(String.class, int.class);
Person person = (Person) constructor.newInstance("John", 25);

// Truy cập field private
Field nameField = clazz.getDeclaredField("name");
nameField.setAccessible(true);
nameField.set(person, "Jane");

// Gọi method private
Method privateMethod = clazz.getDeclaredMethod("privateMethod");
privateMethod.setAccessible(true);
privateMethod.invoke(person);
```

**Khi nào dùng Reflection?**
- Framework như Spring, Hibernate
- Unit testing (JUnit)
- ORM mapping
- Dependency injection

**Cảnh báo:**
- **Chậm hơn** so với gọi trực tiếp
- **Phá vỡ encapsulation** (truy cập private)
- **Không type-safe** - lỗi chỉ phát hiện runtime

> 💡 **Brain Power:** Dùng Reflection như "dao hai lưỡi" - mạnh mẽ nhưng nguy hiểm! Chỉ dùng khi thực sự cần thiết.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 26. ### Các vùng nhớ JVM phân bổ - Bộ nhớ "chia năm xẻ bảy"

JVM chia bộ nhớ thành **nhiều vùng** để quản lý hiệu quả. Hãy cùng khám phá "bản đồ" bộ nhớ của JVM!

### 1. Method Area (Vùng phương thức)
- Lưu thông tin **cấp lớp** (cấu trúc class, phương thức, constant pool...)
- **Chia sẻ** giữa các thread
- Được tạo khi JVM khởi động

### 2. Heap Area (Vùng heap)
- Lưu trữ **tất cả các đối tượng**
- **Chia sẻ** giữa các thread
- Được quản lý bởi **Garbage Collector**
- Chia thành:
  - **Young Generation:** Đối tượng mới (Eden, Survivor spaces)
  - **Old Generation:** Đối tượng tồn tại lâu

### 3. Stack Area (Vùng stack)
- Mỗi thread có **stack riêng**
- Lưu biến cục bộ, trạng thái phương thức
- Chứa **stack frame** cho mỗi phương thức gọi
- Bộ nhớ được cấp/phóng **tự động**

### 4. PC Registers (Bộ đếm chương trình)
- Mỗi thread có **PC register riêng**
- Lưu địa chỉ lệnh đang thực thi
- Được cập nhật sau mỗi lệnh

### 5. Native Method Stack (Stack phương thức native)
- Chứa thông tin cho phương thức **native** (C/C++)
- Mỗi thread có **native stack riêng**

**Hình ảnh trực quan:**

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

> 💡 **Brain Power:** Hiểu rõ vùng nhớ giúp bạn tránh các lỗi như **OutOfMemoryError** và **StackOverflowError**!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 27. ### throw vs throws - Ném lỗi thế nào?

Cả hai đều liên quan đến exception handling, nhưng **công dụng khác nhau**:

### 1. throw - Ném ngoại lệ
- **Ném một ngoại lệ cụ thể**
- **Dùng trong thân phương thức**
- Chỉ ném **một ngoại lệ** tại một thời điểm
- Đứng sau là **đối tượng ngoại lệ**

```java
void validateAge(int age) {
    if (age < 0) {
        throw new IllegalArgumentException("Age cannot be negative");
    }
}
```

### 2. throws - Khai báo ngoại lệ
- **Khai báo ngoại lệ có thể xảy ra**
- **Dùng trong signature phương thức**
- Có thể khai báo **nhiều ngoại lệ**
- Đứng sau là **tên lớp ngoại lệ**

```java
void readFile(String filename) throws FileNotFoundException, IOException {
    new FileInputStream(filename);
}
```

**Kết hợp cả hai:**
```java
void processData(String data) throws CustomException {
    if (data == null) {
        throw new CustomException("Data cannot be null");
    }
}
```

**Bảng so sánh:**

| throw | throws |
|-------|--------|
| **Ném ngoại lệ** | **Khai báo ngoại lệ** |
| **Trong thân phương thức** | **Trong signature** |
| **Chỉ một ngoại lệ** | **Nhiều ngoại lệ** |
| **Đối tượng ngoại lệ** | **Tên lớp ngoại lệ** |
| **Checked exception phải catch** | **Chuyển ngoại lệ cho caller** |

> 💡 **Brain Power:** Dùng **throws** khi bạn không thể xử lý exception, dùng **throw** khi bạn tự tạo và ném exception!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 28. ### Singleton Class - Lớp "duy nhất" trên đời

Singleton là mẫu thiết kế đảm bảo **chỉ có duy nhất một instance** của lớp được tạo ra trong suốt vòng đời ứng dụng.

**Tại sao cần Singleton?**
- Quản lý tài nguyên chung (database connection pool)
- Cấu hình ứng dụng
- Logger
- Cache

**Các cách tạo Singleton:**

### 1. Eager Initialization (Khởi tạo sớm)
```java
public class EagerSingleton {
    private static final EagerSingleton instance = new EagerSingleton();
    
    private EagerSingleton() {} // Private constructor
    
    public static EagerSingleton getInstance() {
        return instance;
    }
}
```

### 2. Lazy Initialization (Khởi tạo muộn)
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

### 3. Thread-Safe Singleton (Double-Checked Locking)
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

### 4. Bill Pugh Singleton (Cách tốt nhất)
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

> 💡 **Brain Power:** Bill Pugh Singleton là cách **tối ưu nhất** - an toàn đa luồng mà không cần synchronized!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 29. ### Java 8 Stream API - Xử lý dữ liệu "dòng chảy"

Stream API cung cấp cách **chức năng** để xử lý tập hợp dữ liệu. Nó giống như "dòng chảy" dữ liệu qua các bước xử lý.

**Đặc điểm nổi bật:**
- **Lazy Evaluation:** Không thực thi cho đến khi có terminal operation
- **Pipelining:** Kết hợp nhiều thao tác thành chuỗi
- **Internal Iteration:** Stream tự quản lý vòng lặp
- **Parallel Processing:** Xử lý song song dễ dàng

**Các thao tác phổ biến:**

```java
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

// filter - lọc phần tử
List<Integer> evenNumbers = numbers.stream()
    .filter(n -> n % 2 == 0)
    .collect(Collectors.toList());

// map - biến đổi phần tử
List<Integer> squares = numbers.stream()
    .map(n -> n * n)
    .collect(Collectors.toList());

// reduce - kết hợp phần tử
int sum = numbers.stream().reduce(0, Integer::sum);

// sorted - sắp xếp
List<Integer> sorted = numbers.stream()
    .sorted(Comparator.reverseOrder())
    .collect(Collectors.toList());

// distinct - loại bỏ trùng lặp
List<Integer> unique = Arrays.asList(1, 1, 2, 2, 3).stream()
    .distinct()
    .collect(Collectors.toList());

// forEach - xử lý từng phần tử
numbers.stream().forEach(System.out::println);
```

**Terminal Operations quan trọng:**
- `collect()` - Thu thập kết quả
- `forEach()` - Xử lý từng phần tử
- `count()` - Đếm số phần tử
- `findFirst()`/`findAny()` - Tìm phần tử đầu tiên/bất kỳ
- `anyMatch()`/`allMatch()`/`noneMatch()` - Kiểm tra điều kiện

> 💡 **Brain Power:** Stream API giúp code **ngắn gọn**, **sạch sẽ** và dễ đọc hơn rất nhiều so với vòng lặp truyền thống!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 30. ### Fail-fast vs Fail-safe Iterators - Lặp lại an toàn?

Khi lặp qua collection trong khi sửa đổi, có hai hành vi khác nhau:

### 1. Fail-Fast Iterator - "Phát hiện ngay"
- **Ném ConcurrentModificationException** nếu collection bị sửa đổi
- **Làm việc trên collection gốc**
- **Ví dụ:** ArrayList, HashMap, HashSet

```java
List<String> list = new ArrayList<>();
list.add("A"); list.add("B"); list.add("C");

Iterator<String> it = list.iterator();
while (it.hasNext()) {
    String s = it.next();
    if (s.equals("B")) {
        list.remove(s); // Ném ConcurrentModificationException
    }
}
```

### 2. Fail-Safe Iterator - "Không phát hiện"
- **Không ném exception** khi collection bị sửa đổi
- **Làm việc trên bản sao** của collection
- **Ví dụ:** CopyOnWriteArrayList, ConcurrentHashMap

```java
CopyOnWriteArrayList<String> list = new CopyOnWriteArrayList<>();
list.add("A"); list.add("B"); list.add("C");

Iterator<String> it = list.iterator();
while (it.hasNext()) {
    String s = it.next();
    if (s.equals("B")) {
        list.remove(s); // Không ném exception
    }
}
```

**Bảng so sánh:**

| Fail-Fast | Fail-Safe |
|-----------|-----------|
| **Ném ConcurrentModificationException** | **Không ném exception** |
| **Làm việc trên collection gốc** | **Làm việc trên bản sao** |
| **Ít tốn bộ nhớ** | **Nhiều tốn bộ nhớ** |
| **ArrayList, HashMap** | **CopyOnWriteArrayList, ConcurrentHashMap** |

> 💡 **Brain Power:** Dùng **Fail-Fast** khi bạn muốn phát hiện sớm lỗi đồng bộ hóa, dùng **Fail-Safe** khi cần sửa đổi collection trong khi lặp.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 31. ### Process vs Thread - Tiến trình hay Luồng?

Cả hai đều là đơn vị thực thi, nhưng **khác biệt lớn**:

### Process (Tiến trình)
- **Chương trình thực thi độc lập** với không gian bộ nhớ riêng
- **Chứa ít nhất một luồng** (main thread)
- **Có không gian địa chỉ, heap, stack riêng**
- **Các tiến trình cách ly nhau**
- **IPC (Inter-Process Communication) tốn kém**

### Thread (Luồng)
- **Đơn vị thực thi nhẹ** bên trong tiến trình
- **Chia sẻ không gian bộ nhớ** với các luồng khác
- **Có stack riêng** nhưng chia sẻ heap
- **Các luồng giao tiếp trực tiếp**
- **Context switching nhanh hơn**

**Ví dụ minh họa:**
```java
// Tạo tiến trình mới
ProcessBuilder pb = new ProcessBuilder("notepad.exe");
Process process = pb.start(); // Tạo tiến trình mới

// Tạo luồng mới
Thread thread = new Thread(() -> {
    System.out.println("Thread running");
});
thread.start(); // Tạo luồng trong tiến trình hiện tại
```

**Bảng so sánh:**

| Process | Thread |
|---------|--------|
| **Nặng nề** | **Nhẹ nhàng** |
| **Không gian bộ nhớ riêng** | **Chia sẻ bộ nhớ** |
| **Context switching chậm** | **Context switching nhanh** |
| **Cách ly giữa các tiến trình** | **Giao tiếp trực tiếp** |
| **Tốn nhiều tài nguyên** | **Tốn ít tài nguyên** |
| **Crash tiến trình không ảnh hưởng** | **Crash luồng ảnh hưởng toàn bộ** |

> 💡 **Brain Power:** 1 Process = 1 ứng dụng (ví dụ: Chrome), 1 Thread = 1 tác vụ bên trong ứng dụng (ví dụ: tải trang web).

**[⬆ Quay lại Mục lục](#mục-lục)**

## 32. ### Các cách tạo Thread trong Java

Có nhiều cách để tạo Thread trong Java:

### 1. Kế thừa Thread class
```java
class MyThread extends Thread {
    @Override
    public void run() {
        System.out.println("Thread running");
    }
}

// Sử dụng
MyThread thread = new MyThread();
thread.start();
```

### 2. Implement Runnable interface
```java
class MyRunnable implements Runnable {
    @Override
    public void run() {
        System.out.println("Runnable running");
    }
}

// Sử dụng
Thread thread = new Thread(new MyRunnable());
thread.start();
```

### 3. Dùng Lambda (Java 8+)
```java
Thread thread = new Thread(() -> {
    System.out.println("Lambda thread running");
});
thread.start();
```

### 4. Implement Callable interface (trả về kết quả)
```java
class MyCallable implements Callable<Integer> {
    @Override
    public Integer call() {
        return 42;
    }
}

// Sử dụng
ExecutorService executor = Executors.newSingleThreadExecutor();
Future<Integer> future = executor.submit(new MyCallable());
Integer result = future.get(); // Lấy kết quả
executor.shutdown();
```

### 5. Dùng ExecutorService
```java
ExecutorService executor = Executors.newFixedThreadPool(5);

executor.execute(() -> {
    System.out.println("Task executed");
});

Future<String> future = executor.submit(() -> "Result");
String result = future.get();

executor.shutdown();
```

**Bảng so sánh:**

| Phương pháp | Trả về kết quả | Kế thừa lớp khác | Xử lý exception |
|-------------|----------------|------------------|----------------|
| Thread class | Không | Không | Chỉ unchecked |
| Runnable | Không | Có | Chỉ unchecked |
| Callable | Có | Có | Checked + Unchecked |

> 💡 **Brain Power:** Dùng **Runnable/Callable** thay vì **Thread** để tận dụng đa hình và tái sử dụng code tốt hơn!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 33. ### Synchronization - Đồng bộ hóa "cùng ăn, cùng ngủ"

Synchronization đảm bảo **chỉ một thread** truy cập tài nguyên chia sẻ tại một thời điểm. Nó giống như "luật xếp hàng" vậy!

### 1. Synchronized Method
```java
class Counter {
    private int count = 0;
    
    public synchronized void increment() {
        count++; // Chỉ một thread được vào đây
    }
}
```

### 2. Synchronized Block
```java
class Counter {
    private int count = 0;
    private final Object lock = new Object();
    
    public void increment() {
        synchronized (lock) {
            count++; // Chỉ một thread được vào đây
        }
    }
}
```

### 3. Static Synchronization
```java
class StaticCounter {
    private static int count = 0;
    
    public static synchronized void increment() {
        count++; // Đồng bộ trên lớp
    }
}
```

**Ví dụ về race condition (không đồng bộ):**
```java
class BankAccount {
    private int balance = 1000;
    
    public void withdraw(int amount) {
        if (balance >= amount) {
            System.out.println("Withdrawal in progress...");
            balance -= amount; // Race condition!
        }
    }
}
```

**Cách sửa (dùng synchronized):**
```java
public synchronized void safeWithdraw(int amount) {
    if (balance >= amount) {
        System.out.println("Withdrawal in progress...");
        balance -= amount;
    }
}
```

**Lưu ý quan trọng:**
- Mỗi object có **intrinsic lock** (monitor)
- Chỉ một thread giữ lock tại một thời điểm
- **Có thể gây hiệu năng thấp** - đừng lạm dụng
- **Prefer synchronized block** thay vì method để kiểm soát tốt hơn

> 💡 **Brain Power:** Synchronization giống như "phòng tắm chung" - chỉ một người được vào, những người khác phải chờ!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 34. ### Deadlock - Kẹt xe trong lập trình

Deadlock là tình huống **hai hay nhiều thread** đều **chờ nhau** giải phóng lock, dẫn đến **tắc nghẽn vĩnh viễn**.

**Ví dụ kinh điển:**
```java
Object lock1 = new Object();
Object lock2 = new Object();

// Thread 1
new Thread(() -> {
    synchronized (lock1) {
        System.out.println("Thread 1 holds lock1");
        try { Thread.sleep(100); } catch (Exception e) {}
        synchronized (lock2) { // Đang chờ lock2
            System.out.println("Thread 1 holds both");
        }
    }
}).start();

// Thread 2
new Thread(() -> {
    synchronized (lock2) {
        System.out.println("Thread 2 holds lock2");
        try { Thread.sleep(100); } catch (Exception e) {}
        synchronized (lock1) { // Đang chờ lock1
            System.out.println("Thread 2 holds both");
        }
    }
}).start();
```

**Cách tránh Deadlock:**

### 1. Luôn lấy lock theo thứ tự
```java
// Cả hai thread đều lấy lock theo thứ tự giống nhau
synchronized (lock1) {
    synchronized (lock2) {
        // Làm việc
    }
}
```

### 2. Dùng tryLock với timeout
```java
ReentrantLock lock1 = new ReentrantLock();
ReentrantLock lock2 = new ReentrantLock();

void safeMethod() {
    boolean gotLock1 = false;
    boolean gotLock2 = false;
    try {
        gotLock1 = lock1.tryLock(1, TimeUnit.SECONDS);
        gotLock2 = lock2.tryLock(1, TimeUnit.SECONDS);
        if (gotLock1 && gotLock2) {
            // Làm việc
        }
    } catch (InterruptedException e) {
        e.printStackTrace();
    } finally {
        if (gotLock1) lock1.unlock();
        if (gotLock2) lock2.unlock();
    }
}
```

### 3. Các cách khác
- Tránh lock lồng nhau
- Dùng lock với timeout
- Không giữ lock quá lâu

> 💡 **Brain Power:** Deadlock giống như "giao thông tắc nghẽn" - tất cả xe đều dừng và chờ nhau nhường đường!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 35. ### volatile - Từ khóa "biến động"

`volatile` đảm bảo **biến luôn được đọc từ bộ nhớ chính**, không phải từ cache của CPU. Nó như "biến không thể cache" vậy!

**Công dụng chính:**
- Đảm bảo **visibility** (thay đổi thấy được giữa các thread)
- Ngăn **CPU reordering** (thay đổi thứ tự thực thi lệnh)
- Không đảm bảo **atomicity** cho các thao tác phức tạp

**Ví dụ thực tế:**
```java
public class VolatileExample {
    private volatile boolean running = true;
    
    public void stop() {
        running = false; // Thay đổi này sẽ thấy ngay với thread khác
    }
    
    public void run() {
        while (running) {
            // Làm việc
        }
    }
}
```

**So sánh với synchronized:**

| volatile | synchronized |
|----------|--------------|
| **Chỉ đảm bảo visibility** | **Đảm bảo visibility và atomicity** |
| **Không blocking** | **Gây blocking** |
| **Không dùng cho thao tác phức tạp** | **Bảo vệ thao tác phức tạp** |
| **Ít tốn kém hơn** | **Tốn kém hơn** |

**Khi nào dùng:**
- Biến cờ (flag) đơn giản
- Biến chỉ ghi một lần, đọc nhiều lần
- Không dùng cho thao tác như `count++` (dùng AtomicInteger thay thế)

```java
// Không dùng volatile cho thao tác phức tạp
volatile int count = 0;
count++; // Không atomic - có thể gây race condition!
```

> 💡 **Brain Power:** volatile như "bảng thông báo công cộng" - mọi người đều thấy thay đổi ngay lập tức!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 36. ### transient - Từ khóa "tạm thời"

`transient` đánh dấu **trường không được serialize** khi chuyển đối tượng thành byte stream.

**Khi nào cần dùng:**
- Dữ liệu nhạy cảm (mật khẩu, token)
- Trường tính toán được (không cần lưu)
- Trường không serializable
- Dữ liệu thread-local

**Ví dụ thực tế:**
```java
class User implements Serializable {
    private static final long serialVersionUID = 1L;
    
    private String username;
    private transient String password; // Không serialize
    private transient int loginCount;  // Không serialize
    
    // Constructor và phương thức khác
}
```

**Cơ chế hoạt động:**
- Khi deserialize, transient fields nhận **giá trị mặc định**:
  - Object → null
  - Số nguyên → 0
  - boolean → false

**Custom serialization:**
```java
private void writeObject(ObjectOutputStream oos) throws IOException {
    oos.defaultWriteObject(); // Serialize các trường thông thường
    oos.writeObject(encrypt(password)); // Xử lý riêng transient field
}

private void readObject(ObjectInputStream ois) 
        throws IOException, ClassNotFoundException {
    ois.defaultReadObject(); // Deserialize các trường thông thường
    password = decrypt((String) ois.readObject()); // Xử lý riêng
}
```

> 💡 **Brain Power:** transient như "giấy tạm" - không được lưu vào sổ sách chính thức!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 37. ### Serialization & Deserialization - "Đóng băng" đối tượng

**Serialization** là chuyển đối tượng thành byte stream. **Deserialization** là chuyển ngược lại.

**Tại sao cần Serialization?**
- Lưu trạng thái đối tượng vào file/cơ sở dữ liệu
- Gửi đối tượng qua mạng
- Sao chép sâu (deep copy) đối tượng
- Cache đối tượng

**Ví dụ cơ bản:**
```java
// Serialize
try (ObjectOutputStream oos = new ObjectOutputStream(
        new FileOutputStream("user.ser"))) {
    oos.writeObject(user);
}

// Deserialize
try (ObjectInputStream ois = new ObjectInputStream(
        new FileInputStream("user.ser"))) {
    User deserializedUser = (User) ois.readObject();
}
```

**Quy tắc quan trọng:**
- Lớp phải implement **Serializable**
- Khai báo **serialVersionUID** để tránh lỗi tương thích
- transient fields không được serialize
- static fields không được serialize

**Custom Serialization:**
```java
class CustomSerializable implements Serializable {
    private String data;
    private transient String sensitiveData;
    
    private void writeObject(ObjectOutputStream oos) throws IOException {
        oos.defaultWriteObject();
        oos.writeObject(encrypt(sensitiveData));
    }
    
    private void readObject(ObjectInputStream ois) 
            throws IOException, ClassNotFoundException {
        ois.defaultReadObject();
        sensitiveData = decrypt((String) ois.readObject());
    }
}
```

> 💡 **Brain Power:** Serialization như "đóng băng" đối tượng - bạn có thể "rã đông" nó bất cứ lúc nào!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 38. ### Functional Interfaces - Giao diện "hàm số"

Functional Interface là interface **chỉ có một phương thức trừu tượng**. Chúng là nền tảng cho **Lambda expressions**.

**Đặc điểm chính:**
- Chỉ có **một phương thức trừu tượng**
- Có thể có nhiều phương thức **default/static**
- Được đánh dấu với `@FunctionalInterface`
- Dùng làm target cho lambda expressions

**Ví dụ cơ bản:**
```java
@FunctionalInterface
interface Calculator {
    int calculate(int a, int b);
    
    default void print(String msg) {
        System.out.println(msg);
    }
    
    static void info() {
        System.out.println("Calculator interface");
    }
}

// Sử dụng với lambda
Calculator add = (a, b) -> a + b;
Calculator multiply = (a, b) -> a * b;

System.out.println(add.calculate(5, 3)); // 8
```

**Các Functional Interfaces built-in:**

| Interface | Mô tả | Ví dụ |
|-----------|-------|-------|
| **Predicate<T>** | Kiểm tra điều kiện (boolean) | `Predicate<Integer> isEven = n -> n % 2 == 0;` |
| **Function<T,R>** | Chuyển đổi từ T sang R | `Function<String, Integer> length = s -> s.length();` |
| **Consumer<T>** | Xử lý T, không trả về | `Consumer<String> printer = s -> System.out.println(s);` |
| **Supplier<T>** | Tạo T, không tham số | `Supplier<Double> random = () -> Math.random();` |
| **BiFunction<T,U,R>** | Chuyển đổi T,U thành R | `BiFunction<Integer, Integer, Integer> add = (a,b) -> a+b;` |

> 💡 **Brain Power:** Functional Interfaces giúp Java có "hồn" của lập trình hàm - ngắn gọn, dễ đọc, dễ bảo trì!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 39. ### Lambda Expressions - Hàm ẩn danh "siêu gọn"

Lambda expressions là **hàm ẩn danh** giúp viết code ngắn gọn hơn. Chúng là trái tim của lập trình hàm trong Java.

**Cú pháp:**
```
(tham số) -> biểu thức
(tham số) -> { câu lệnh; }
```

**Ví dụ cơ bản:**
```java
// Không tham số
Runnable runnable = () -> System.out.println("Hello Lambda!");

// Một tham số (không cần dấu ngoặc)
Consumer<String> consumer = s -> System.out.println(s);

// Nhiều tham số
BiFunction<Integer, Integer, Integer> add = (a, b) -> a + b;
```

**Kết hợp với Collections:**
```java
List<String> names = Arrays.asList("John", "Jane", "Bob");

// forEach với lambda
names.forEach(name -> System.out.println(name));

// Sắp xếp với lambda
names.sort((s1, s2) -> s1.compareTo(s2));

// Lọc với Stream
List<String> filtered = names.stream()
    .filter(name -> name.startsWith("J"))
    .collect(Collectors.toList());
```

**Method References - Ngắn hơn nữa!**
```java
// Static method reference
Function<String, Integer> parseInt = Integer::parseInt;

// Instance method reference
String str = "Hello";
Supplier<Integer> length = str::length;

// Constructor reference
Supplier<ArrayList<String>> listSupplier = ArrayList::new;
```

**Lợi ích:**
- Code **ngắn gọn**, **sạch sẽ**
- Hỗ trợ **lập trình hàm**
- Tận dụng **xử lý song song**
- Giảm **boilerplate code**

> 💡 **Brain Power:** Lambda như "shortcut" - giúp bạn viết code nhanh như chớp!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 40. ### Optional Class - Hộp đựng an toàn

`Optional` là container chứa **có hoặc không** giá trị. Nó giúp tránh **NullPointerException** một cách tường minh.

**Tạo Optional:**
```java
Optional<String> empty = Optional.empty();
Optional<String> name = Optional.of("John");
Optional<String> nullable = Optional.ofNullable(null);
```

**Các phương thức quan trọng:**
```java
// Kiểm tra giá trị
System.out.println(name.isPresent()); // true
System.out.println(empty.isEmpty());  // true (Java 11+)

// Lấy giá trị an toàn
String value = name.get(); // Nguy hiểm - có thể ném exception
String safeValue = empty.orElse("Unknown"); // An toàn

// Xử lý nếu có giá trị
name.ifPresent(n -> System.out.println("Name: " + n));

// Xử lý với orElseThrow
String required = name.orElseThrow(() -> 
    new IllegalArgumentException("Name is required"));
```

**Kết hợp với Stream:**
```java
String result = Optional.of("  John  ")
    .map(String::trim)
    .map(String::toUpperCase)
    .orElse("UNKNOWN"); // "JOHN"
```

**Best Practices:**
- **Trả về Optional** cho phương thức có thể không tìm thấy kết quả
- **Không dùng Optional** cho tham số hoặc trường lớp
- **Không dùng get()** mà không kiểm tra trước

```java
// Tốt
public Optional<User> findById(int id) {
    return Optional.ofNullable(database.find(id));
}

// Xấu
private Optional<String> name; // Không nên
```

> 💡 **Brain Power:** Optional như "hộp quà" - bạn không biết có gì bên trong cho đến khi mở ra!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 41. ### Collection vs Collections - Khác một chữ, khác cả trời đất

Hai thứ này **hoàn toàn khác nhau**, nhưng hay bị nhầm lẫn:

### 1. Collection (Interface)
- **Giao diện** trong Collections Framework
- Đại diện cho **nhóm đối tượng** (phần tử)
- Được kế thừa bởi **List, Set, Queue**
- **Không thể khởi tạo**

### 2. Collections (Utility Class)
- **Lớp tiện ích** với các phương thức static
- Cung cấp các phương thức cho **thao tác collection**
- **Không thể khởi tạo** (tất cả phương thức static)

**Ví dụ minh họa:**
```java
// Collection - interface
Collection<String> collection = new ArrayList<>();
collection.add("Apple");
collection.add("Banana");

// Collections - utility class
List<String> list = new ArrayList<>(collection);

// Sắp xếp
Collections.sort(list);

// Đảo ngược
Collections.reverse(list);

// Trộn ngẫu nhiên
Collections.shuffle(list);

// Tạo collection bất biến
List<String> unmodifiable = Collections.unmodifiableList(list);
```

**Bảng so sánh:**

| Collection | Collections |
|------------|-------------|
| **Interface** | **Lớp tiện ích** |
| **Đại diện nhóm đối tượng** | **Cung cấp phương thức thao tác** |
| **Không thể khởi tạo** | **Không thể khởi tạo** |
| **Gốc của Collections Framework** | **Hỗ trợ cho Collections Framework** |

> 💡 **Brain Power:** Collection là "người chơi", Collections là "huấn luyện viên"!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 42. ### Set vs List - Tập hợp hay Danh sách?

Cả hai đều là interface trong Collections Framework, nhưng **khác biệt lớn**:

| List | Set |
|------|-----|
| **Cho phép phần tử trùng lặp** | **Không cho phép trùng lặp** |
| **Duy trì thứ tự chèn** | **Có thể không duy trì thứ tự** |
| **Truy cập qua index** | **Không truy cập qua index** |
| **Cho phép nhiều null** | **Chỉ cho phép một null** (HashSet) |
| **Cài đặt: ArrayList, LinkedList** | **Cài đặt: HashSet, TreeSet** |

**Ví dụ minh họa:**
```java
// List - cho phép trùng lặp, giữ thứ tự
List<String> list = new ArrayList<>();
list.add("Apple");
list.add("Banana");
list.add("Apple"); // Được
list.add(null);
list.add(null);    // Được
System.out.println(list.get(1)); // Truy cập qua index

// Set - không trùng lặp
Set<String> set = new HashSet<>();
set.add("Apple");
set.add("Banana");
set.add("Apple"); // Bị bỏ qua
set.add(null);    // Chỉ một null
```

**Các cài đặt phổ biến:**
- **HashSet:** Không thứ tự, nhanh
- **LinkedHashSet:** Giữ thứ tự chèn
- **TreeSet:** Sắp xếp tự động

```java
Set<String> linkedSet = new LinkedHashSet<>();
linkedSet.add("Cherry");
linkedSet.add("Apple");
System.out.println(linkedSet); // [Cherry, Apple] - giữ thứ tự

Set<String> treeSet = new TreeSet<>();
treeSet.add("Cherry");
treeSet.add("Apple");
System.out.println(treeSet); // [Apple, Cherry] - sắp xếp
```

> 💡 **Brain Power:** Dùng **List** khi cần thứ tự và cho phép trùng, dùng **Set** khi cần duy nhất!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 43. ### HashSet vs TreeSet - Ai nhanh hơn?

Cả hai đều implement **Set**, nhưng **cơ chế lưu trữ khác nhau**:

| HashSet | TreeSet |
|---------|---------|
| **Dùng HashMap** bên trong | **Dùng TreeMap** bên trong |
| **Không duy trì thứ tự** | **Duy trì thứ tự sắp xếp** |
| **Cho phép một null** | **Không cho phép null** |
| **O(1)** cho add/remove/contains | **O(log n)** cho các thao tác |
| **Dùng hashCode() và equals()** | **Dùng compareTo() hoặc Comparator** |

**Ví dụ minh họa:**
```java
// HashSet - không thứ tự, cho phép null
Set<Integer> hashSet = new HashSet<>();
hashSet.add(30);
hashSet.add(10);
hashSet.add(20);
hashSet.add(null); // Được
System.out.println(hashSet); // Thứ tự ngẫu nhiên

// TreeSet - sắp xếp, không null
Set<Integer> treeSet = new TreeSet<>();
treeSet.add(30);
treeSet.add(10);
treeSet.add(20);
// treeSet.add(null); // Ném NullPointerException
System.out.println(treeSet); // [10, 20, 30] - sắp xếp
```

**TreeSet với Comparator tùy chỉnh:**
```java
// Thứ tự giảm dần
Set<Integer> descendingSet = new TreeSet<>(Collections.reverseOrder());
descendingSet.add(30);
descendingSet.add(10);
descendingSet.add(20);
System.out.println(descendingSet); // [30, 20, 10]

// Sắp xếp theo tên
Set<Person> personSet = new TreeSet<>(Comparator.comparing(Person::getName));
personSet.add(new Person("John", 25));
personSet.add(new Person("Alice", 30));
System.out.println(personSet); // [Alice, John]
```

> 💡 **Brain Power:** Dùng **HashSet** khi cần tốc độ, dùng **TreeSet** khi cần thứ tự sắp xếp!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 44. ### Diamond Problem - Vấn đề "kim cương"

Diamond Problem là **mâu thuẫn kế thừa** khi một lớp kế thừa từ hai lớp cùng kế thừa từ một lớp cha.

**Sơ đồ "kim cương":**
```
       A
      / \
     B   C
      \ /
       D
```
Nếu D kế thừa từ B và C, và cả B và C đều override phương thức từ A, phương thức nào D dùng?

**Java giải quyết thế nào?**
- **Không cho phép đa kế thừa với class** (tránh Diamond Problem)
- Nhưng với **interface** (từ Java 8), vấn đề tương tự có thể xảy ra

**Ví dụ với interface:**
```java
interface A {
    default void display() {
        System.out.println("A");
    }
}

interface B extends A {
    @Override
    default void display() {
        System.out.println("B");
    }
}

interface C extends A {
    @Override
    default void display() {
        System.out.println("C");
    }
}

// Diamond Problem
class D implements B, C {
    // Phải override để giải quyết mâu thuẫn
    @Override
    public void display() {
        B.super.display(); // Chọn B
        // hoặc C.super.display();
        // hoặc cài đặt riêng
    }
}
```

**Luật giải quyết trong Java:**
1. **Class thắng interface:** Nếu lớp con override, dùng phương thức của lớp
2. **Lớp con thắng lớp cha:** Interface cụ thể hơn thắng interface tổng quát hơn
3. **Override tường minh:** Nếu vẫn mâu thuẫn, phải override và chỉ định rõ

```java
class Parent {
    void show() { System.out.println("Parent"); }
}

interface MyInterface {
    default void show() { System.out.println("Interface"); }
}

// Class method thắng interface
class Child extends Parent implements MyInterface {
    // Dùng Parent.show() - không cần override
}
```

> 💡 **Brain Power:** Diamond Problem như "con rối" - không biết nghe theo ai! Java buộc bạn phải quyết định rõ ràng.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 45. ### Dependency Injection - Tiêm phụ thuộc "thần kỳ"

Dependency Injection (DI) là mẫu thiết kế **đảo ngược sự kiểm soát** (IoC), giúp tạo và cung cấp phụ thuộc cho một lớp.

**Lợi ích của DI:**
- **Giảm coupling** giữa các lớp
- **Dễ unit test** (dùng mock objects)
- **Tái sử dụng code** tốt hơn
- **Dễ bảo trì và mở rộng**

**Các loại DI:**

### 1. Constructor Injection
```java
interface MessageService {
    void sendMessage(String message);
}

class EmailService implements MessageService {
    public void sendMessage(String message) {
        System.out.println("Email: " + message);
    }
}

class NotificationService {
    private final MessageService service;
    
    // Tiêm qua constructor
    public NotificationService(MessageService service) {
        this.service = service;
    }
    
    public void notify(String message) {
        service.sendMessage(message);
    }
}

// Sử dụng
NotificationService notifier = new NotificationService(new EmailService());
notifier.notify("Hello!");
```

### 2. Setter Injection
```java
class NotificationService {
    private MessageService service;
    
    // Tiêm qua setter
    public void setMessageService(MessageService service) {
        this.service = service;
    }
}
```

### 3. Interface Injection
```java
interface MessageServiceInjector {
    void injectMessageService(MessageService service);
}

class NotificationService implements MessageServiceInjector {
    private MessageService service;
    
    @Override
    public void injectMessageService(MessageService service) {
        this.service = service;
    }
}
```

**Framework hỗ trợ:**
- Spring Framework dùng `@Autowired`
- Java EE dùng `@Inject`
- Google Guice

> 💡 **Brain Power:** DI như "dịch vụ giao hàng" - bạn không tự đi mua, có người mang đến tận nhà!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 46. ### Shallow Copy vs Deep Copy - Sao chép nông hay sâu?

Khi sao chép đối tượng, có hai cách chính:

### 1. Shallow Copy (Sao chép nông)
- **Tạo đối tượng mới**, nhưng **copy tham chiếu** đến các đối tượng lồng
- Thay đổi đối tượng lồng **ảnh hưởng cả hai**
- Là hành vi mặc định của `clone()`

### 2. Deep Copy (Sao chép sâu)
- **Tạo đối tượng mới** và **sao chép đệ quy** các đối tượng lồng
- Thay đổi đối tượng lồng **không ảnh hưởng**
- Cần cài đặt thủ công

**Ví dụ minh họa:**
```java
class Address implements Cloneable {
    String city;
    
    public Address(String city) { this.city = city; }
    
    @Override
    protected Address clone() throws CloneNotSupportedException {
        return (Address) super.clone();
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
        cloned.address = this.address.clone(); // Sao chép sâu Address
        cloned.hobbies = new ArrayList<>(this.hobbies); // Sao chép sâu List
        return cloned;
    }
}

// Sử dụng
List<String> hobbies = new ArrayList<>(Arrays.asList("Reading"));
Person original = new Person("John", new Address("NY"), hobbies);

Person shallow = original.shallowCopy();
Person deep = original.deepCopy();

// Thay đổi original
original.address.city = "LA";
original.hobbies.add("Gaming");

System.out.println(shallow.address.city); // LA (bị ảnh hưởng)
System.out.println(deep.address.city);    // NY (không bị ảnh hưởng)
```

**Bảng so sánh:**

| Shallow Copy | Deep Copy |
|--------------|-----------|
| **Copy tham chiếu** | **Copy đối tượng** |
| **Đối tượng lồng chia sẻ** | **Đối tượng lồng độc lập** |
| **Nhanh, ít tốn bộ nhớ** | **Chậm, nhiều tốn bộ nhớ** |
| **Thay đổi ảnh hưởng cả hai** | **Thay đổi không ảnh hưởng** |
| **clone() mặc định** | **Cài đặt thủ công** |

> 💡 **Brain Power:** Shallow Copy như "bản photo" - thay đổi bản gốc ảnh hưởng bản photo. Deep Copy như "bản vẽ lại" - độc lập hoàn toàn.

**[⬆ Quay lại Mục lục](#mục-lục)**

## 47. ### Design Patterns - Mẫu thiết kế "bí kíp"

Design Patterns là **giải pháp tái sử dụng** cho các vấn đề thiết kế phần mềm phổ biến. Chúng là "bí kíp" của các lập trình viên.

**Các nhóm chính:**

### 1. Creational Patterns (Tạo đối tượng)
- **Singleton:** Đảm bảo chỉ một instance
- **Factory Method:** Tạo đối tượng qua phương thức
- **Abstract Factory:** Tạo họ đối tượng liên quan
- **Builder:** Xây dựng đối tượng phức tạp từng bước
- **Prototype:** Sao chép từ prototype

### 2. Structural Patterns (Cấu trúc)
- **Adapter:** Chuyển đổi interface
- **Composite:** Xử lý đối tượng nhóm như đối tượng đơn
- **Decorator:** Thêm chức năng động
- **Facade:** Đơn giản hóa interface phức tạp
- **Proxy:** Kiểm soát truy cập đối tượng

### 3. Behavioral Patterns (Hành vi)
- **Observer:** Thông báo thay đổi cho các đối tượng quan tâm
- **Strategy:** Chọn thuật toán tại runtime
- **Command:** Đóng gói yêu cầu thành đối tượng
- **State:** Thay đổi hành vi theo trạng thái
- **Template Method:** Xác định cấu trúc thuật toán

**Ví dụ thực tế:**

### Observer Pattern (Mẫu quan sát)
```java
interface Observer {
    void update(String message);
}

class NewsSubscriber implements Observer {
    private String name;
    public NewsSubscriber(String name) { this.name = name; }
    public void update(String message) {
        System.out.println(name + ": " + message);
    }
}

class NewsPublisher {
    private List<Observer> subscribers = new ArrayList<>();
    
    public void subscribe(Observer o) { subscribers.add(o); }
    public void unsubscribe(Observer o) { subscribers.remove(o); }
    public void notifySubscribers(String message) {
        for (Observer o : subscribers) {
            o.update(message);
        }
    }
}
```

### Strategy Pattern (Mẫu chiến lược)
```java
interface PaymentStrategy {
    void pay(int amount);
}

class CreditCardPayment implements PaymentStrategy {
    public void pay(int amount) {
        System.out.println("Paid $" + amount + " by Credit Card");
    }
}

class PayPalPayment implements PaymentStrategy {
    public void pay(int amount) {
        System.out.println("Paid $" + amount + " by PayPal");
    }
}

class ShoppingCart {
    private PaymentStrategy strategy;
    
    public void setPaymentStrategy(PaymentStrategy strategy) {
        this.strategy = strategy;
    }
    
    public void checkout(int amount) {
        strategy.pay(amount);
    }
}
```

> 💡 **Brain Power:** Design Patterns không phải "công thức vàng", mà là **kinh nghiệm được tổng kết** - hãy hiểu bản chất, không học vẹt!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 48. ### Factory Design Pattern - Xưởng sản xuất "thông minh"

Factory Pattern cung cấp **giao diện tạo đối tượng** mà không chỉ định lớp cụ thể. Nó giống như "xưởng sản xuất" vậy!

**Các loại Factory:**

### 1. Simple Factory (Static Factory Method)
```java
interface Shape { void draw(); }

class Circle implements Shape { public void draw() { System.out.println("Circle"); } }
class Rectangle implements Shape { public void draw() { System.out.println("Rectangle"); } }

class ShapeFactory {
    public static Shape createShape(String type) {
        return switch (type.toUpperCase()) {
            case "CIRCLE" -> new Circle();
            case "RECTANGLE" -> new Rectangle();
            default -> throw new IllegalArgumentException("Unknown shape");
        };
    }
}

// Sử dụng
Shape circle = ShapeFactory.createShape("CIRCLE");
circle.draw();
```

### 2. Factory Method Pattern
```java
interface Vehicle { void drive(); }

class Car implements Vehicle { public void drive() { System.out.println("Car"); } }
class Motorcycle implements Vehicle { public void drive() { System.out.println("Motorcycle"); } }

abstract class VehicleFactory {
    public abstract Vehicle createVehicle();
    
    public void deliver() {
        Vehicle vehicle = createVehicle();
        vehicle.drive();
    }
}

class CarFactory extends VehicleFactory {
    @Override
    public Vehicle createVehicle() {
        return new Car();
    }
}

// Sử dụng
VehicleFactory factory = new CarFactory();
factory.deliver(); // Driving a car
```

**Lợi ích:**
- **Tách biệt** việc tạo đối tượng khỏi sử dụng
- **Tuân thủ Open/Closed Principle** - dễ mở rộng
- **Giảm coupling** giữa creator và product
- **Đơn giản hóa** việc tạo đối tượng phức tạp

> 💡 **Brain Power:** Factory Pattern như "nhà phân phối" - bạn chỉ cần đặt hàng, họ lo phần còn lại!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 49. ### Builder Design Pattern - Xây dựng "từng bước"

Builder Pattern tách **quá trình xây dựng** đối tượng phức tạp khỏi **biểu diễn** của nó. Nó như "kiến trúc sư" vậy!

**Khi nào dùng:**
- Đối tượng có **nhiều tham số tùy chọn**
- Quá trình tạo đối tượng **nhiều bước**
- Muốn tạo **đối tượng bất biến** với nhiều trường

**Ví dụ thực tế:**
```java
class Computer {
    private final String processor;
    private final int ram;
    private final int storage;
    private final boolean hasGraphicsCard;
    
    // Private constructor
    private Computer(ComputerBuilder builder) {
        this.processor = builder.processor;
        this.ram = builder.ram;
        this.storage = builder.storage;
        this.hasGraphicsCard = builder.hasGraphicsCard;
    }
    
    // Builder class
    public static class ComputerBuilder {
        // Required parameters
        private final String processor;
        private final int ram;
        
        // Optional parameters with defaults
        private int storage = 256;
        private boolean hasGraphicsCard = false;
        
        public ComputerBuilder(String processor, int ram) {
            this.processor = processor;
            this.ram = ram;
        }
        
        public ComputerBuilder storage(int storage) {
            this.storage = storage;
            return this;
        }
        
        public ComputerBuilder graphicsCard(boolean hasGraphicsCard) {
            this.hasGraphicsCard = hasGraphicsCard;
            return this;
        }
        
        public Computer build() {
            return new Computer(this);
        }
    }
}

// Sử dụng
Computer gamingPC = new Computer.ComputerBuilder("i9", 32)
    .storage(1000)
    .graphicsCard(true)
    .build();

Computer basicPC = new Computer.ComputerBuilder("i3", 8)
    .build();
```

**Lợi ích:**
- Code **dễ đọc**, **dễ bảo trì**
- Tạo **đối tượng bất biến** dễ dàng
- Tránh **telescoping constructor** (constructor nhiều tham số)
- **Method chaining** (fluent interface) đẹp mắt

> 💡 **Brain Power:** Builder Pattern như "bộ lego" - bạn lắp từng mảnh nhỏ để tạo thành sản phẩm hoàn chỉnh!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 50. ### Heap vs Stack Memory - Núi hay Đống?

Bộ nhớ Java được chia thành **Heap** và **Stack** - hai khu vực hoàn toàn khác nhau:

| Stack Memory | Heap Memory |
|--------------|-------------|
| **Lưu phương thức và biến cục bộ** | **Lưu đối tượng và biến instance** |
| **Cấu trúc LIFO** | **Không thứ tự cụ thể** |
| **Mỗi thread có stack riêng** | **Chia sẻ giữa các thread** |
| **Tự động cấp/phóng** | **Quản lý bởi Garbage Collector** |
| **Kích thước cố định** | **Kích thước động** |
| **Truy cập nhanh** | **Truy cập chậm hơn** |
| **Lưu primitive và tham chiếu** | **Lưu đối tượng thực** |

**Ví dụ minh họa:**
```java
public class MemoryExample {
    private int instanceVar = 10; // Heap
    
    public static int staticVar = 20; // Method Area (phần của Heap)
    
    public void demonstrate() {
        int localPrimitive = 30; // Stack
        String localString = new String("Hello"); // Reference (Stack), Object (Heap)
        Person person = new Person("John", 25); // Reference (Stack), Object (Heap)
        int[] numbers = new int[5]; // Reference (Stack), Array (Heap)
    }
}
```

**Hình ảnh trực quan:**
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

**Lỗi thường gặp:**
- **StackOverflowError:** Đệ quy vô hạn
- **OutOfMemoryError:** Heap đầy

> 💡 **Brain Power:** Stack như "tầng hầm" - riêng tư, nhanh chóng. Heap như "toà nhà" - chung, rộng rãi!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 51. ### Garbage Collection - Dọn rác "tự động"

Garbage Collection (GC) là **quản lý bộ nhớ tự động** trong Java - dọn dẹp các đối tượng không dùng nữa.

**Cơ chế hoạt động:**
1. **Mark:** Xác định đối tượng còn dùng (reachable)
2. **Sweep:** Xóa đối tượng không dùng
3. **Compact (tùy chọn):** Nén bộ nhớ để tránh phân mảnh

**Khi nào đối tượng eligible cho GC?**
- Không còn tham chiếu trỏ đến
- Tham chiếu được gán null
- Tham chiếu được gán lại
- Đối tượng ra khỏi phạm vi

**Ví dụ:**
```java
public class GCDemo {
    public static void main(String[] args) {
        Object obj1 = new Object(); // Không eligible
        
        obj1 = null; // Eligible cho GC
        
        Object obj2 = new Object();
        obj2 = new Object(); // Object đầu tiên eligible
        
        createObjects(); // Objects trong method eligible khi method kết thúc
        
        System.gc(); // Yêu cầu GC (không đảm bảo chạy ngay)
    }
    
    static void createObjects() {
        Object localObj = new Object(); // Eligible khi method kết thúc
    }
}
```

**Heap Generations:**
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
1. Object mới tạo ở **Eden space**
2. Khi Eden đầy → **Minor GC**
3. Object sống sót → **Survivor space**
4. Object sống qua nhiều Minor GC → **Old Generation**
5. Khi Old Generation đầy → **Major GC (Full GC)**

> 💡 **Brain Power:** GC như "dọn dẹp nhà cửa" - định kỳ dọn rác, giúp nhà cửa luôn gọn gàng!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 52. ### Các loại Garbage Collectors - Đội dọn rác

Java cung cấp **nhiều loại GC** cho các tình huống khác nhau:

### 1. Serial GC (-XX:+UseSerialGC)
- **Một luồng** cho garbage collection
- **Dừng toàn bộ ứng dụng** (stop-the-world)
- Tốt cho ứng dụng **đơn luồng**, heap nhỏ
- Dùng cho client JVM

### 2. Parallel GC (-XX:+UseParallelGC)
- **Nhiều luồng** cho garbage collection
- **Tối ưu throughput** (throughput collector)
- GC mặc định trong Java 8
- Tốt cho ứng dụng **multi-threaded**

### 3. G1 GC (-XX:+UseG1GC)
- Chia heap thành **các regions**
- Thiết kế cho heap **lớn** (> 4GB)
- GC mặc định từ Java 9
- **Predictable pause times**

### 4. ZGC (-XX:+UseZGC)
- **Ultra-low latency** (< 10ms pause)
- Xử lý heap từ **8MB đến 16TB**
- Có từ Java 11
- **Concurrent garbage collection**

### 5. Shenandoah GC (-XX:+UseShenandoahGC)
- **Low pause time** collector
- **Concurrent compaction**
- Có trong OpenJDK

**Cách kiểm tra GC đang dùng:**
```java
for (GarbageCollectorMXBean bean : 
        ManagementFactory.getGarbageCollectorMXBeans()) {
    System.out.println("GC: " + bean.getName());
    System.out.println("Count: " + bean.getCollectionCount());
    System.out.println("Time: " + bean.getCollectionTime() + "ms");
}
```

**JVM Options:**
```bash
# Serial GC
java -XX:+UseSerialGC MyApp

# Parallel GC
java -XX:+UseParallelGC -XX:ParallelGCThreads=4 MyApp

# G1 GC
java -XX:+UseG1GC -XX:MaxGCPauseMillis=200 MyApp

# ZGC
java -XX:+UseZGC MyApp
```

**Bảng so sánh:**

| GC Type | Phù hợp | Thời gian dừng | Throughput |
|---------|---------|----------------|------------|
| Serial | Ứng dụng nhỏ | Cao | Thấp |
| Parallel | Throughput cao | Trung bình | Cao |
| G1 | Heap lớn | Thấp-Trung bình | Trung bình-Cao |
| ZGC | Low latency | Rất thấp | Trung bình |

> 💡 **Brain Power:** Chọn GC như chọn "đội dọn dẹp" - tùy quy mô nhà cửa (heap size) và yêu cầu (throughput/latency)!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 53. ### wait() vs sleep() - Ngủ hay Chờ?

Cả hai đều **dừng luồng**, nhưng **cơ chế hoàn toàn khác**:

| wait() | sleep() |
|--------|---------|
| **Định nghĩa trong Object class** | **Định nghĩa trong Thread class** |
| **Giải phóng lock/monitor** | **Không giải phóng lock** |
| **Phải gọi trong synchronized context** | **Có thể gọi bất kỳ đâu** |
| **Có thể đánh thức bằng notify()/notifyAll()** | **Không thể đánh thức (trừ interrupt)** |
| **Dùng cho giao tiếp giữa luồng** | **Dùng để delay** |
| **Phương thức instance** | **Phương thức static** |

**Ví dụ minh họa:**
```java
private static final Object lock = new Object();

// sleep()
Thread sleepThread = new Thread(() -> {
    System.out.println("Sleep thread starting...");
    try {
        Thread.sleep(2000);
    } catch (InterruptedException e) {
        e.printStackTrace();
    }
    System.out.println("Sleep thread woke up!");
});

// wait()
Thread waitThread = new Thread(() -> {
    synchronized (lock) {
        System.out.println("Wait thread starting...");
        try {
            lock.wait(2000);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }
        System.out.println("Wait thread woke up!");
    }
});

// notify
Thread notifyThread = new Thread(() -> {
    try { Thread.sleep(1000); } catch (InterruptedException e) {}
    synchronized (lock) {
        System.out.println("Notifying...");
        lock.notify();
    }
});

sleepThread.start();
waitThread.start();
notifyThread.start();
```

**Lưu ý quan trọng:**
- **wait()** dùng để **đồng bộ giữa các luồng**
- **sleep()** dùng để **giới thiệu thời gian**
- **Luôn gọi wait() trong synchronized block**
- **wait()** có thể bị đánh thức trước timeout

> 💡 **Brain Power:** wait() như "chờ có việc", sleep() như "ngủ say sưa" - một bên có thể bị gọi dậy, một bên ngủ đến khi báo thức!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 54. ### notify() vs notifyAll() - Đánh thức một hay tất cả?

Cả hai đều **đánh thức luồng đang chờ**, nhưng **cơ chế khác nhau**:

| notify() | notifyAll() |
|----------|-------------|
| **Chỉ đánh thức một luồng** | **Đánh thức tất cả luồng** |
| **Luồng được đánh thức không xác định** | **Tất cả luồng cạnh tranh lock** |
| **Hiệu quả hơn** khi chỉ một luồng cần tiếp tục | **An toàn hơn** khi nhiều luồng cần tài nguyên |
| **Có thể gây starvation** | **Không starvation** |

**Ví dụ minh họa:**
```java
private static final Object lock = new Object();
private static boolean resourceAvailable = false;

// Tạo 3 luồng chờ
for (int i = 1; i <= 3; i++) {
    new Thread(() -> {
        synchronized (lock) {
            while (!resourceAvailable) {
                lock.wait();
            }
            System.out.println("Thread got resource!");
        }
    }).start();
}

// notify() - chỉ một luồng được đánh thức
synchronized (lock) {
    resourceAvailable = true;
    lock.notify(); // Chỉ một luồng thức dậy
}

// notifyAll() - tất cả luồng được đánh thức
synchronized (lock) {
    resourceAvailable = true;
    lock.notifyAll(); // Tất cả luồng thức dậy
}
```

**Khi nào dùng cái nào?**
- Dùng **notify()** khi **chỉ một luồng** có thể tiếp tục (ví dụ: một tài nguyên)
- Dùng **notifyAll()** khi **nhiều luồng** có thể tiếp tục hoặc điều kiện thay đổi

> 💡 **Brain Power:** notify() như "gọi tên một người", notifyAll() như "gọi tất cả mọi người" - chọn cách phù hợp với tình huống!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 55. ### Immutable Class - Lớp "bất biến"

Immutable Class là lớp mà **trạng thái không thay đổi** sau khi tạo. Một khi tạo ra, nó **luôn như vậy**!

**Lợi ích của Immutable:**
- **Thread-safe** mà không cần synchronized
- **An toàn khi chia sẻ và cache**
- **Phù hợp làm key trong HashMap** (hashCode không đổi)
- **Dễ reason về code**

**Các quy tắc tạo Immutable Class:**
1. **Khai báo lớp là final**
2. **Tất cả trường là private và final**
3. **Không cung cấp setter methods**
4. **Khởi tạo tất cả trường qua constructor**
5. **Sao chép sâu cho các đối tượng mutable**
6. **Trả về bản sao của các đối tượng mutable trong getter**

**Ví dụ minh họa:**
```java
public final class ImmutablePerson {
    private final String name;
    private final int age;
    private final List<String> hobbies;
    
    public ImmutablePerson(String name, int age, List<String> hobbies) {
        this.name = name;
        this.age = age;
        this.hobbies = new ArrayList<>(hobbies); // Deep copy
    }
    
    public String getName() { return name; }
    public int getAge() { return age; }
    
    // Trả về unmodifiable copy
    public List<String> getHobbies() {
        return Collections.unmodifiableList(hobbies);
    }
    
    // Tạo instance mới với giá trị khác
    public ImmutablePerson withAge(int newAge) {
        return new ImmutablePerson(this.name, newAge, this.hobbies);
    }
}

// Sử dụng
List<String> hobbies = new ArrayList<>(Arrays.asList("Reading"));
ImmutablePerson person = new ImmutablePerson("John", 25, hobbies);

// Không thể thay đổi hobbies
// person.getHobbies().add("Gaming"); // UnsupportedOperationException

// Tạo person mới với tuổi khác
ImmutablePerson older = person.withAge(30);
```

**Java Records (Java 14+):**
```java
public record Person(String name, int age) {
    // Tự động tạo constructor, getters, equals, hashCode, toString
}
```

> 💡 **Brain Power:** Immutable như "viên đá" - không thể thay đổi hình dạng, luôn giữ nguyên bản chất!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 56. ### String, StringBuilder, StringBuffer - Chuỗi "cứng đầu" hay "dễ bảo"?

Cả ba đều xử lý chuỗi, nhưng **đặc điểm khác nhau**:

| Feature | String | StringBuilder | StringBuffer |
|---------|--------|---------------|--------------|
| **Tính bất biến** | Immutable | Mutable | Mutable |
| **Thread Safety** | Thread-safe (immutable) | Không thread-safe | Thread-safe (synchronized) |
| **Hiệu năng** | Chậm khi nối chuỗi | Nhanh nhất | Chậm hơn StringBuilder |
| **Lưu trữ** | String Pool | Heap | Heap |
| **Có từ** | Java 1.0 | Java 1.5 | Java 1.0 |

**Ví dụ so sánh hiệu năng:**
```java
// String - chậm
String s = "";
for (int i = 0; i < 100000; i++) {
    s += "a"; // Tạo mới mỗi lần
}

// StringBuilder - nhanh
StringBuilder sb = new StringBuilder();
for (int i = 0; i < 100000; i++) {
    sb.append("a");
}

// StringBuffer - trung bình
StringBuffer sf = new StringBuffer();
for (int i = 0; i < 100000; i++) {
    sf.append("a");
}
```

**Common Methods (StringBuilder/StringBuffer):**
```java
StringBuilder sb = new StringBuilder("Hello");
sb.append(" World");   // Nối chuỗi
sb.insert(5, ",");     // Chèn tại vị trí
sb.delete(5, 6);       // Xóa khoảng
sb.reverse();          // Đảo ngược
sb.replace(0, 5, "Hi"); // Thay thế
String result = sb.toString(); // Chuyển thành String
```

**Khi nào dùng cái nào?**
- **String:** Khi chuỗi ít thay đổi
- **StringBuilder:** Khi chuỗi thay đổi nhiều (đơn luồng)
- **StringBuffer:** Khi chuỗi thay đổi nhiều (đa luồng)

> 💡 **Brain Power:** String như "tượng đá" - không thay đổi. StringBuilder/StringBuffer như "bột nặn" - dễ dàng tạo hình!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 57. ### static vs instance variables - Biến chung hay riêng?

**static variables** thuộc về **lớp**, trong khi **instance variables** thuộc về **đối tượng**:

| static Variable | instance Variable |
|-----------------|-------------------|
| **Thuộc về lớp** | **Thuộc về đối tượng** |
| **Một bản sao chia sẻ** cho tất cả instance | **Mỗi instance có bản sao riêng** |
| **Khai báo với static** | **Khai báo không có static** |
| **Truy cập qua tên lớp** | **Truy cập qua đối tượng** |
| **Cấp phát khi class load** | **Cấp phát khi tạo object** |
| **Lưu trong Method Area** | **Lưu trong Heap** |

**Ví dụ minh họa:**
```java
public class Employee {
    // static variable - chia sẻ cho tất cả
    private static int employeeCount = 0;
    private static String companyName = "TechCorp";
    
    // instance variables - riêng cho mỗi đối tượng
    private int id;
    private String name;
    private double salary;
    
    public Employee(String name, double salary) {
        this.name = name;
        this.salary = salary;
        this.id = ++employeeCount; // Dùng static counter
    }
    
    // static method - chỉ truy cập static members
    public static int getEmployeeCount() {
        return employeeCount;
    }
    
    // instance method - truy cập cả static và instance
    public void displayInfo() {
        System.out.println("ID: " + id);
        System.out.println("Name: " + name);
        System.out.println("Company: " + companyName); // Truy cập static
    }
    
    public static void main(String[] args) {
        System.out.println(Employee.companyName); // Truy cập qua lớp
        
        Employee emp1 = new Employee("John", 50000);
        Employee emp2 = new Employee("Jane", 60000);
        
        emp1.displayInfo();
        emp2.displayInfo();
        
        System.out.println("Total: " + Employee.getEmployeeCount());
        
        // Thay đổi static variable - ảnh hưởng tất cả
        Employee.companyName = "NewTech";
        emp1.displayInfo(); // Company đã thay đổi
    }
}
```

**Static Block:**
```java
class StaticDemo {
    static int value;
    
    // Chạy khi class load
    static {
        System.out.println("Static block executed");
        value = 100;
    }
}
```

> 💡 **Brain Power:** static variable như "bảng thông báo chung", instance variable như "sổ tay cá nhân" - một cái chung, một cái riêng!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 58. ### super - Từ khóa "cha mẹ"

`super` dùng để **tham chiếu đến lớp cha**. Nó có ba công dụng chính:

### 1. Truy cập biến lớp cha
```java
class Animal {
    String name = "Animal";
}

class Dog extends Animal {
    String name = "Dog";
    
    void displayNames() {
        System.out.println("Child: " + name);
        System.out.println("Parent: " + super.name);
    }
}
```

### 2. Gọi phương thức lớp cha
```java
class Animal {
    void eat() {
        System.out.println("Animal eating");
    }
}

class Dog extends Animal {
    @Override
    void eat() {
        super.eat(); // Gọi phương thức cha trước
        System.out.println("Dog eating");
    }
}
```

### 3. Gọi constructor lớp cha
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
    
    Employee(String name, int age, String department) {
        super(name, age); // Gọi constructor cha (phải là câu lệnh đầu)
        this.department = department;
    }
}
```

**Ví dụ đầy đủ:**
```java
class Vehicle {
    String brand = "Generic";
    
    Vehicle() {
        System.out.println("Vehicle constructor");
    }
    
    Vehicle(String brand) {
        this.brand = brand;
        System.out.println("Vehicle parameterized constructor");
    }
    
    void start() {
        System.out.println("Vehicle starting...");
    }
}

class Car extends Vehicle {
    String brand = "Car Brand";
    
    Car(String brand) {
        super(brand); // Gọi constructor cha
        System.out.println("Car constructor");
    }
    
    @Override
    void start() {
        super.start(); // Gọi phương thức cha
        System.out.println("Car engine started!");
    }
    
    void showBrands() {
        System.out.println("Car brand: " + brand);
        System.out.println("Parent brand: " + super.brand);
    }
}
```

> 💡 **Brain Power:** super như "sợi dây nối với tổ tiên" - giúp bạn truy cập di sản từ lớp cha!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 59. ### this - Từ khóa "bản thân"

`this` tham chiếu đến **đối tượng hiện tại**. Nó có nhiều công dụng:

### 1. Phân biệt biến instance và tham số
```java
class Person {
    String name;
    int age;
    
    Person(String name, int age) {
        this.name = name; // this.name là biến instance
        this.age = age;   // age (phải) là tham số
    }
}
```

### 2. Gọi constructor khác (Constructor Chaining)
```java
class Employee {
    String name;
    int age;
    
    Employee() {
        this("Unknown", 0); // Gọi constructor khác
    }
    
    Employee(String name, int age) {
        this.name = name;
        this.age = age;
    }
}
```

### 3. Truyền đối tượng hiện tại
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
        display(this); // Truyền đối tượng hiện tại
    }
}
```

### 4. Trả về đối tượng hiện tại (Method Chaining)
```java
class Builder {
    private String name;
    private int age;
    
    Builder setName(String name) {
        this.name = name;
        return this; // Trả về đối tượng hiện tại
    }
    
    Builder setAge(int age) {
        this.age = age;
        return this;
    }
}

// Sử dụng với method chaining
new Builder()
    .setName("John")
    .setAge(25);
```

### 5. Tham chiếu lớp hiện tại trong inner class
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

> 💡 **Brain Power:** this như "chỉ tay vào bản thân" - giúp bạn xác định rõ đang làm việc với đối tượng nào!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 60. ### Generics - "Tham số hóa" kiểu dữ liệu

Generics cho phép **kiểu dữ liệu trở thành tham số** khi định nghĩa lớp, interface, phương thức. Nó như "khuôn đúc" vậy!

**Lợi ích:**
- **Type safety** tại thời điểm biên dịch
- **Loại bỏ việc cast** không cần thiết
- **Tái sử dụng code**
- **Hỗ trợ thuật toán tổng quát**

**Generic Class:**
```java
class Box<T> {
    private T content;
    
    public void set(T content) {
        this.content = content;
    }
    
    public T get() {
        return content;
    }
}

// Nhiều tham số kiểu
class Pair<K, V> {
    private K key;
    private V value;
    
    public Pair(K key, V value) {
        this.key = key;
        this.value = value;
    }
}
```

**Generic Method:**
```java
class Utilities {
    // Generic method
    public static <T> void printArray(T[] array) {
        for (T element : array) {
            System.out.print(element + " ");
        }
    }
    
    // Generic method với return type
    public static <T> T getFirst(List<T> list) {
        return list.isEmpty() ? null : list.get(0);
    }
}
```

**Bounded Type Parameters:**
```java
// Upper bound - T phải kế thừa Number
class NumberBox<T extends Number> {
    private T number;
    
    public NumberBox(T number) {
        this.number = number;
    }
    
    public double doubleValue() {
        return number.doubleValue();
    }
}

// Nhiều giới hạn
class MultiBound<T extends Number & Comparable<T>> {
    private T value;
    
    public int compareTo(T other) {
        return value.compareTo(other);
    }
}
```

**Wildcards:**
```java
// Unbounded wildcard
public static void printList(List<?> list) {
    for (Object item : list) {
        System.out.println(item);
    }
}

// Upper bounded wildcard (đọc)
public static double sumNumbers(List<? extends Number> list) {
    double sum = 0;
    for (Number n : list) {
        sum += n.doubleValue();
    }
    return sum;
}

// Lower bounded wildcard (ghi)
public static void addIntegers(List<? super Integer> list) {
    list.add(1);
    list.add(2);
}
```

> 💡 **Brain Power:** Generics như "khuôn đúc đa năng" - bạn có thể đổ bất kỳ chất liệu nào vào mà vẫn giữ nguyên hình dáng!

**[⬆ Quay lại Mục lục](#mục-lục)**

## 61. ### Type Erasure - Xóa bỏ kiểu "tinh vi"

Type Erasure là quá trình **xóa bỏ thông tin kiểu generic** khi biên dịch. Thông tin kiểu được thay bằng **giới hạn hoặc Object**.

**Cơ chế hoạt động:**

**Trước biên dịch:**
```java
public class Box<T> {
    private T content;
    
    public void set(T content) {
        this.content = content;
    }
    
    public T get() {
        return content;
    }
}
```

**Sau biên dịch (tương đương):**
```java
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

**Bounded Type Erasure:**
```java
// Trước
public class NumberBox<T extends Number> {
    private T number;
}

// Sau - T được thay bằng Number
public class NumberBox {
    private Number number;
}
```

**Bridge Methods:**
Trình biên dịch tạo **bridge methods** để giữ polymorphism:

```java
class Node<T> {
    public T data;
    public void setData(T data) { this.data = data; }
}

class IntegerNode extends Node<Integer> {
    @Override
    public void setData(Integer data) {
        super.setData(data);
    }
}

// Bridge method được tạo tự động:
// public void setData(Object data) {
//     setData((Integer) data);
// }
```

**Hệ quả của Type Erasure:**
- Không thể tạo instance của tham số kiểu
- Không thể tạo mảng kiểu tham số hóa
- Không thể dùng instanceof với kiểu tham số hóa
- Không thể nạp chồng phương thức với cùng erasure

```java
// Không thể
// T obj = new T();

// Không thể
// List<String>[] array = new List<String>[10];

// Không thể
// if (list instanceof ArrayList<String>) {}

// Không thể nạp chồng
// void process(List<String> list) {}
// void process(List<Integer> list) {} // Cùng erasure
```

**Tại sao có Type Erasure?**
- **Tương thích ngược** với code trước generics
- **Không cần bytecode mới**
- **Tiết kiệm bộ nhớ** (không lưu thông tin kiểu runtime)

> 💡 **Brain Power:** Type Erasure như "xóa dấu vết" - giữ code gọn nhẹ nhưng hạn chế một số tính năng runtime!

**[⬆ Quay lại Mục lục](#mục-lục)**

<!-- QUESTIONS_END -->
