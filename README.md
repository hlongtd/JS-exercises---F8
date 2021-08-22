# JS-exercises---F8
1. Cách khai báo biến.
  Test 1:
    1.1: 
    Tạo biến bossName và gán giá trị cho biến này là tên thú cưng của bạn
    Tạo biến bossAge và gán cho giá trị là số tuổi thú cưng của bạn
    Tạo biến senName để lưu tên của bạn
    Tạo biến senAge để lưu số tuổi của bạn
    Hiển thị giá trị biến bossName với hàm alert
    // Đọc kỹ mô tả bên trái màn hình
    // Viết code của bạn tại đây
          let bossName = 'uen';
          let bossAge = 18;
          let senName = 'thng811';
          let senAge = 19;
          alert(bossName);
    1.2:
    Tạo biến currentCourse và gán cho giá trị là 'Javascript cơ bản'
    Tạo biến newCourse và sao chép giá trị của biến currentCourse
    Sử dụng hàm alert hiển thị giá trị của biến currentCourse
    Sử dụng hàm alert hiển thị giá trị của biến newCourse
    Sửa giá trị của biến newCourse thành 'Javascript nâng cao'
    Sử dụng hàm alert hiển thị giá trị của biến newCourse sau khi sửa
    // Làm bài tập tại đây
          let currentCourse = 'Javascript cơ bản';
          let newCourse = currentCourse;
          alert(currentCourse);
          alert(newCourse);
          newCourse = 'Javascript nâng cao';
          alert(newCourse);
2. Comments
  Test 2:
    2.1:
    Sử dụng // comment dòng code bossSound = 'Cạp cạp';
    Sử dụng /* */ comment từ dòng myBossAge = 4; tới dòng myBossAge = 8;
    // Làm bài tập tại đây
          var bossSound = 'Meozzz';
          var bossAge = 2;
          //bossSound = 'Cạp cạp';

          /*bossAge = 4;
          bossSound = 'Gâu Gâu'
          bossAge = 8;*/
3. Một số hàm built-in
  Test 3:
    3.1:
      Tạo biến fullName có giá trị là tên của bạn
      Sử dụng hàm alert để hiển thị giá trị của biến fullName
      Tạo thêm các biến sau:
          message có giá trị 'Học về built-in functions trong JS'
          warnMessage có giá trị 'Đây là message cảnh báo'
          errorMessage có giá trị 'Đây là message lỗi'
      Sử dụng console.log để in giá trị biến message ra tab console
      Sử dụng console.warn để in giá trị biến warnMessage ra tab console
      Sử dụng console.error để in giá trị biến errorMessage ra tab console
      // Làm bài tập tại đây
            let fullName = 'thng811';
            alert(fullName);
            let message = 'Học về built-in functions trong JS';
            let warnMessage = 'Đây là message cảnh báo';
            let errorMessage = 'Đây là message lỗi';
            console.log(message);
            console.warn;
            console.error;
4. Làm quen với toán tử
  Test 4:
    4.1: 
    Cho trước biến a, b là 2 số bất kỳ. Hãy viết chương trình tính tổng 2 số này.
    // Làm bài tập tại đây
            function run(a, b) {
            c = a + b;
            return c;
            }
5. Toán tử số học
  Test 5:
    5.1:
    Cho tam giác có cạnh đáy là a và chiều cao là h. Hãy tính diện tích tam giác này và gán cho biến s.
    Ví dụ: Cho a = 10, h = 20. Kết quả sẽ là 100
          // Sửa code tại vị trí dấu [3 chấm]
            function run(a, h) {
              var s = (a * h) / 2;
              return s;
            }
    5.2:
    Cho biến sum là tổng của a và b, different là hiệu của a và b. Hãy tìm a và b.
          // Sửa code tại vị trí dấu [3 chấm]

            function run(sum, different) {
              var a = (sum + different) / 2;
              var b = (sum - different) / 2;
              return 'a is ' + a + ' and b is ' + b;
            }
    5.3:
    Cho biến minutes có giá trị là số phút. Hãy tính ra số giây và gán cho biến seconds.
    // Làm bài tập tại đây
              function run(minutes) {
                var seconds = minutes * 60;
                return seconds;
              }
    5.4:
    Cho a là đáy nhỏ, b là đáy lớn và h là chiều cao của hình thang. 
    Hãy tính diện tích hình thang từ các biến đã cho trước và lưu kết quả vào biến s.
    // Làm bài tập tại đây
              function run(a, b, h) {
                  s = ((a+ b) * h) / 2;
                  return s;
              }
6. Toán tử ++ -- với tiền tố & hậu tố
  Test 6:
    6.1:
    Cho trước biến a và b là các số nguyên ngẫu nhiên:
      Hãy tăng giá trị của biến a lên 1
      Hãy giảm giá trị của biến b xuống 1
    // Làm bài tập tại đây
              function run(a, b) {
                  a++;
                  b--;
                  return 'a is ' + a + ' and b is ' + b;
              }
     6.2:
    Cho trước a và b là các số nguyên ngẫu nhiên:
        Hãy giảm giá trị biến a xuống 1 và gán cho biến c
        Hãy tăng giá trị biến b lên 1 và gán cho biến d
    // Làm bài tập tại đây
              function run(a, b) {
                  var c = --a;
                  var d = ++b;
                  return 'c is ' + c + ' and d is ' + d;
              }
7. Toán tử gán
  Test 7:
    7.1:
    Cho biến x, y và z là các giá trị số ngẫu nhiên:
        Nhân đôi giá trị của x
        Chia 3 giá trị của y
        Gán z bằng số dư của z / 2
    // Làm bài tập tại đây
              function run(x, y, z) {
                  x *= 2;
                  y /= 3;
                  z %= 2;
                  return 'x is ' + x + ' and y is ' + y + ' and z is ' + z;
              }
8. Toán tử chuỗi
  Test 8:
    8.1:
    Khai báo biến firstName, lastName và gán giá trị là Họ và Tên bất kì.
    Khai báo biến fullName có giá trị là kết quả của firstName nối với lastName. 
    Giữa firstName và lastName cần có một khoảng trắng (sử dụng một chuỗi chứa dấu cách)
    // Làm bài tập tại đây
              let firstName = 'Vo';
              let lastName = 'Thang';
              let fullName = `${firstName} ${lastName}`;
9. Toán tử so sánh - Phần 1
  Test 9:
    9.1:
    Tại một website bán sách online. Để mua được một cuốn sách bạn cần có số tiền tối thiểu bằng tiền của cuốn sách muốn mua. 
    Nếu số tiền trong tài khoản không đủ thì không thể mua được sách.
    Cho trước biến bookCoin là giá tiền của cuốn sách và biến userCoin là số tiền người dùng hiện có.
    // Làm bài tập tại đây
    // Chỉ sửa code tại vị trí dấu 3 chấm
              function run(bookCoin, userCoin) {
                  if (bookCoin <= userCoin) {
                      return 'Bạn có thể mua cuốn sách này!';
                  } else {
                      return 'Bạn không thể mua cuốn sách này!';
                  }
              }
10. Kiểu dữ liệu Boolean
  Test 10:
    10.1:
    Tại một website có chức năng bình luận, chức năng này yêu cầu người dùng đã xác minh tài khoản mới có thể sử dụng.
    Cho trước biến verifiedAt chứa giá trị là thời gian người dùng đã xác minh tài khoản. 
    Nếu verifiedAt có giá trị '' thì người dùng này chưa xác minh tài khoản.
    Bên phải màn hình là hàm isCommentable được sử dụng để kiểm tra xem người dùng có quyền bình luận hay không.
    // Làm bài tập tại đây
                function isCommentable(verifiedAt) {
                    var result;
                    if (verifiedAt == '') {
                        result = false;
                    } else {
                        result = true;
                    }
                    return result;
                }
                
11. Câu lệnh điều kiện If
  11.1:
  Cho biến number có thể là một số bất kì. Hãy kiểm tra number có phải là số chẵn hay không.
      Nếu number là số chẵn, hãy gán 'even' cho biến result
      Nếu number không phải số chẵn, hãy gán 'odd' cho biến result
  // Làm bài tập tại đây
              function run(number) {
                  var result;
                  if(number % 2 === 0) {
                      result = 'even';
                  }
                  else 
                      result = 'odd';
                  return result;
              }
  11.2:
  Một website bán rượu chỉ cho phép người dùng truy cập nếu người dùng xác nhận đã đủ 16 tuổi. 
  Developer phụ trách phát triển website đó đang không biết code như thế nào để kiểm tra được người dùng đã đủ tuổi chưa. 
  Hãy giúp họ!
  Cho trước biến age là số tuổi của người dùng truy cập website.
  Yêu cầu:
      Nếu người dùng chưa đủ 16 tuổi gán false cho isAccessible
      Nếu người dùng đã đủ 16 tuổi gán true cho isAccessible
  // Làm bài tập tại đây
              function checkCanAccessible(age) {
                  var isAccessible;
                  if (age < 16) {
                      isAccessible = false;
                  }
                  else
                      isAccessible = true;
                  return isAccessible;
              }
12. Toán tử logical
  12.1
  // đề dài nên các bạn vô https://fullstack.edu.vn/learning/javascript-co-ban/toan-tu-logical để xem đề nhé.
  // Làm bài tập tại đây
              function run(socialType, isVerified) {
                  var result;
                  if (socialType === 'google' || socialType === 'facebook') {
                      result = true;
                  }
                  if (socialType === 'email') {
                      if (isVerified == true) {
                          result = true;
                      }
                      else 
                          result = undefined;
                  }
                  return result;
              }
  12.2:
  // đề dài nên các bạn vô https://fullstack.edu.vn/learning/javascript-co-ban/toan-tu-logical để xem đề nhé.
  // làm bài tập tại đây
              function votableCheck(isAuthenticated, role) {
                  var result;

                  if (isAuthenticated == true) {
                      if(role === 'member' || role === 'admin') {
                          result = true;
                      }
                      else
                          result = false;
                  }
                  else 
                      result = false;
                  return result;
              }
13. Kiểu dữ liệu
  Test 13:
    13.1:
    Tạo biến age lưu số tuổi bất kì
    Tạo biến pi để lưu số PI (làm tròn tới 2 số thập phân)
    Tạo biến bonusPoint gán giá trị là số điểm bạn sẽ đạt được nếu vượt qua toàn bộ test case của bài tập này
    // Làm bài tập tại đây
              let age = 19;
              let pi = 3.14;
              let bonusPoint = 69;
    13.2:
    Tạo biến fullName và gán tên bất kì.
    Tạo biến myGirlFriendName và gán tên gấu của bạn. Nếu không có gấu thì gán chuỗi gì cũng được.
    Tạo biến currentLanguage và gán giá trị là tên ngôn ngữ lập trình bạn đang học tại khóa học này.
    // Làm bài tập tại đây
              let fullName = 'thng811';
              let myGirlFriendName = 'xxx';
              let currentLanguage = 'Javascript';
    13.3:
    Kiểm tra biến input có phải là chuỗi hay không. Là chuỗi gán true cho output, không phải là chuỗi gán false cho output.   
    // Làm bài tập tại đây
              function run(input) {
                  var output;
                  if (typeof input === 'string') {
                      output = true;
                  }
                  else 
                      output = false;
                  return output;
              }
14. Toán tử so sánh - Phần 2
  Test 14:
    14.1:
    Kiểm tra biến bonusPoint có phải chứa giá trị là 50 hay không. Nếu đúng gán true cho result, sai gán false cho result.   
              function run(bonusPoint) {
                  var result;
                  result = bonusPoint === 50 ? true : false;
                  return result;
              }
    14.2:
    Kiểm tra biến bonusPoint có phải chứa giá trị là 50 hay không. Nếu đúng gán true cho result, sai gán false cho result.   
              function run(bonusPoint) {
                  var result;
                  result = bonusPoint === 50 ? true : false;
                  return result;
              }
15. Toán tử logical và câu lệnh điều kiện if
  Test 15:
    15.1:
   Cho trước các biến a, b, c có thể là bất kì kiểu dữ liệu gì.
   Nếu biến a có giá trị truthy thì gán a cho result, a là falsy b là truthy thì gán b cho result, b là falsy thì gán c cho result.
    // Làm bài tập tại đây
              function run(a, b, c) {
                  var result = a || b || c;
                  return result;
              }
16. Chuỗi
  16.1:
  Tạo biến commentText để lưu nội dung bình luận sau: "Học chưa hiểu là học chưa đủ!" (bao gồm cả dấu ngoặc kép).
  Tạo biến authorName có giá trị Sơn Đặng:
  Tạo biến fullCommentText có giá trị bằng authorName nối với commentText, sử dụng template string để nối, 
  giữa authorName và commentText cần nối thêm một khoảng trắng (một dấu cách).
  // Làm bài tập tại đây
              let commentText = '"\Học chưa hiểu là học chưa đủ!\"';
              let authorName = 'Sơn Đặng:';
              let fullCommentText = `${authorName} ${commentText}`;
   16.2:
   Tạo biến commentText để lưu bình luận sau: Để hiển thị được chuỗi chứa dấu gạch chéo ngược 
   (\) ta phải thêm dấu \ vào trước hoặc sau nó
   Sử dụng làm alert hoặc console.log để xem giá trị biến commentText
   // Làm bài tập tại đây
              let commentText = 'Để hiển thị được chuỗi chứa dấu gạch chéo ngược (\\) ta phải thêm dấu \\ vào trước hoặc sau nó';
              console.log(commentText);
17. Làm việc với chuỗi.
  17.1:
  Cho trước biến commentText là một chuỗi bất kì. Hãy lưu độ dài chuỗi của commentText vào biến textLength.
  // Làm bài tập tại đây  
              function run(commentText) {
                  let textLength = commentText.length;
                  return textLength;
              }
  17.2:
  Cho statusText là một biến có thể là bất cứ kiểu dữ liệu gì.
    Nếu statusText là chuỗi và có độ dài từ 1 trở lên hãy gán true cho result.
    Các trường hợp khác hãy gán false cho result.
  // Làm bài tập tại đây
              function run(statusText) {
                  let result;
                  if (statusText === 'string' || statusText.length >= 1) {
                      result = true;
                  }
                  else 
                      result = false;
                  return result;
              }
  17.3:
  Cho trước biến title và description là các chuỗi có nội dung bất kì.
      Nếu cả hai biến cho trước giá trị đều có chứa chuỗi Javascript thì gán true cho result.
      Trường hợp khác gán false cho result.
  // Làm bài tập tại đây  
              function run(title, description) {
                  let result;
                  if (title.indexOf('Javascript') != -1 && description.indexOf('Javascript') != -1 ) {
                      result = true;
                  }
                  else 
                      result = false;

                  return result;
              }
  17.4:
  Cho trước biến title có giá trị 'Học Javascript tại F8'.
      Cắt lấy chuỗi Javascript từ biến cho trước và lưu vào biến language
      Cắt phần chuỗi còn lại (từ sau chuỗi Javascript) và lưu vào biến rest
  // Làm bài tập tại đây 
              function run(title) {
                  let language = title.slice(4, 14);
                  let rest = title.slice(14);
                  return `Language is ${language} and rest is ${rest}`;
              }
  17.5:
  Cho biến content là chuỗi bất kì có chứa một hoặc nhiều chuỗi JS. 
  Hãy thay thế toàn bộ chuỗi JS tìm được trong giá trị của biến content thành Javascript.
  // Làm bài tập tại đây
              function run(content) {
                  return content.replace(/JS/g, 'Javascript' )
              }
  17.6:
  Cho biến a và b có giá trị là các chuỗi bất kì.
      Hãy chuyển đổi toàn bộ giá trị của biến a trở thành kiểu chữ thường
      Hãy chuyển đổi toàn bộ giá trị của biến b trở thành kiểu chữ IN HOA
  // Làm bài tập tại đây 
              function run(a, b) {
                  a = a.toLowerCase();
                  b = b.toUpperCase();
                  return a + '|' + b;
              }
  17.7:
  // đề dài các bạn vô https://fullstack.edu.vn/learning/javascript-co-ban/lam-viec-voi-chuoi để xem đề nhé.
  // làm bài tập tại đây
              function trimText(statusText) {
                  return statusText.trim()
              }
18. Số và làm việc với số
  Test 18:
    18.1:
    Cho biến number có thể là số bất kì. Hãy chuyển đổi kiểu dữ liệu của biến number sang string.
    // Làm bài tập tại đây
              function numberToString(number) {
                  return number.toString();
              }
    18.2: 
    Cho biến pi có giá trị là 3.141592653589793. Hãy rút gọn giá trị đó chỉ còn hai số phần thập phân.
    // Làm bài tập tại đây
              function run(pi) {
              return pi.toFixed(2);
              }
    18.3:
    Cho trước biến number có giá trị là một số bất kì. 
    Hãy kiếm tra xem number có phải là số nguyên dương hay không và lưu kết quả vào biến result.
    // Làm bài tập tại đây    
              function run(number) {
                  let result;
                  if (number > 0) {
                      result = true;
                  }
                  else 
                      result = false
                  return result;
              }
19. Mảng
  Test 19:
    19.1:
    Tạo biến foods và gán cho biến một array có 3 phần tử là tên các món ăn mà bạn thích.
    // Làm bài tập tại đây
              let foods = ['rice', 'fish', 'chicken'];
    19.2:
    Cho biến couldBeAnything có thể là bất cứ kiểu dữ liệu gì. 
    Hãy kiểm tra nếu biến cho trước là array thì gán true cho result. Các trường hợp khác gán false cho result.
    // Làm bài tập tại đây
              function checkIsArray(couldBeAnything) {
                  let result;
                  if(Array.isArray(couldBeAnything)) {
                      result = true;
                  }
                  else 
                      result = false;
                  return result;
              }
    19.3:
    Cho biến input có thể là array bất kì. Hãy gán cho biến result có giá trị bằng giá trị của phần tử cuối cùng trong mảng input.
    // Làm bài tập tại đây    
              function getLastElementOfArray(input) {
                  let result = input[input.length - 1];
                  return result;
              }
20. Làm việc với mảng
  Test 20:
    20.1:
    Cho biến input là mảng bất kì. Hãy chuyển đổi kiểu dữ liệu của input sang chuỗi và gán cho biến result.
    // Làm bài tập tại đây   
              function arrayToString(input) {
                  let result = input.toString()
                  return result;
              }
    20.2: 
    Cho trước biến input là array bất kì. Hãy chuyển đổi kiểu dữ liệu biến input sang chuỗi, 
    mỗi giá trị của các phần tử được cách nhau bằng dấu ' - ', gán giá trị sau chuyển đổi cho biến result.
    // Làm bài tập tại đây    
              function arrayToString(input) {
                  let result = input.join(' - ')
                  return result;
              }
    20.3:
    Cho biến anArray là mảng bất kì.
        Nếu mảng có ít hơn 3 phần tử thì hãy xóa một phần tử đầu mảng đi
        Nếu mảng có nhiều hơn 2 phần tử thì hãy xóa hai phần tử cuối mảng đi
    // Làm bài tập tại đây
              function run(anArray) {   
              if (anArray.length < 3) {
                  anArray.shift();
              }
              if (anArray.length >= 3)
                  anArray.splice(anArray.length - 2, 2)
              return anArray;
              }
    20.4:
    Cho biến animals là mảng chứa tên các loài động vật. 
    Hãy thêm tên các loài động vật khác vào mảng animals tuân thủ theo các yêu cầu sau:
        Nếu mảng không có phần tử nào, hãy thêm hai phần tử Cat, Mouse vào mảng
        Nếu mảng có một phần tử, hãy thêm phần tử Elephant vào đầu mảng
        Nếu mảng có trên hai phần tử, hãy xóa phần tử thứ hai đi và thêm hai phần tử Monkey, Tiger vào vị trí đã xóa
    // Làm bài tập tại đây
              function run(animals) {
              if (animals.length === 0) {
                  animals.push('Cat', 'Mouse');
              } else 
              if (animals.length === 1) {
                  animals.unshift('Elephant')
              } 
              else {
                  animals.splice(1, 1, 'Monkey', 'Tiger')
              }   
              return animals;
              }
    20.5
    // đề dài các bạn vào https://fullstack.edu.vn/learning/javascript-co-ban/lam-viec-voi-mang để xem đề nhé
    // Làm bài tập tại đây   
              function joinTwoArrays(products, newProducts) {
                  let output = products.concat(newProducts);
                  return output;
              }
  21. Function
   21.1:
    Tạo hàm showMessage
    Trong hàm vừa tạo, thêm alert('Học JS tại F8');
    Gọi tới hàm vừa tạo
    
   // Làm bài tập tại đây
   
    function showMessage() {
        alert('Học JS tại F8');
    }
   21.2:
    Tạo hàm showLog
    Thêm mã console.log('Học JS tại F8!'); vào nội dung của hàm
    Gọi tới hàm vừa định nghĩa
    Gọi tới hàm vừa định nghĩa một lần nữa
   // Làm bài tập tại đây

      function showLog() {
          console.log('Học JS tại F8!');
      }

      showLog();
      showLog();
22. Tham số trong function
  22.1:
    Tạo hàm showMessage và định nghĩa tham số message cho hàm này
    Trong cặp {} của hàm vừa tạo thêm mã sau: alert(message);
    Gọi hàm showMessage và truyền đối số cho tham số message là một chuỗi bất kì
    
    // Làm bài tập tại đây

      function showMessage(message) {
          alert(message);
      }
      showMessage('thng811')
   22.2:
    Tạo hàm writeLog, định nghĩa 2 tham số là prefix và message
    Thêm vào trong cặp {} của hàm nội dung: console.log(prefix + ': ' + message);
    Gọi hàm writeLog và truyền đối số cho hai tham số đã định nghĩa phía trên với nội dung là các chuỗi tùy ý.
      // Làm bài tập tại đây

        function writeLog(prefix, message) {
            console.log(prefix + ': ' + message);
        }

        writeLog('prepare', 'thng811')
23. Return trong function
  23.1:
    Tạo hàm tính tổng hai số a và b:
      Tạo hàm sum và định nghĩa hai tham số a và b
      Trong trường hợp giá trị của a và b hợp lệ để thực hiện phép tính thì return tổng của a và b
      Trường hợp a và b không hợp lệ để thực hiện phép tính thì return false
   // Làm bài tập tại đây
         function sum(a, b) {
           if(Number.isInteger(a) && Number.isInteger(b)) {
              return a + b;
           }
           else 
             return false;
          }
24. Hiểu hơn về function
  24.1:
    Tạo hàm checkPositiveInteger có tham số là number, hàm này dùng để kiểm tra một số có phải là số nguyên dương hay không.
      Nếu number là số nguyên dương hàm sẽ return true
      Nếu number không phải số nguyên dương hàm sẽ return false
  // Làm bài tập tại đây

      function checkPositiveInteger(number) {
          if(number > 0) {
              return true;
          }
          else {
              return false;
          }
      }
   24.2:
    Viết hàm calculateTriangleArea để tính diện tích tam giác.
    Hàm này nhận hai tham số là a (cạnh đáy), h (chiều cao) và hàm sẽ trả về giá trị là diện tích của tam giác 
      được tính từ hai tham số đã cho. 
    a và h sẽ được truyền các giá trị số nguyên bất kì từ hệ thống test case.
    // Làm bài tập tại đây

        function calculateTriangleArea(a, h) {
            if(a > 0 && h > 0) {
                return (a*h) / 2;
            }
            else {
                return false;
            }
        }
  24.3:
    Viết hàm kiểm tra một chuỗi có nằm trong một chuỗi khác hay không. 
    Đặt tên hàm này là stringInString, hàm có hai tham số lần lượt là needle (chuỗi muốn tìm) 
    và haystack (chuỗi gốc, giá trị của needle sẽ được tìm xem có tồn tại trong haystack hay không)
      Tạo hàm stringInString theo mô tả trên
      Nếu needle được tìm thấy trong haystack hàm sẽ trả về true
      Nếu không tìm thấy needle trong haystack hàm sẽ trả về false
      Nếu một trong các giá trị đầu vào không phải chuỗi hàm sẽ trả về false
      // Làm bài tập tại đây
            function stringInString(needle, haystack) {
              if(typeof needle === 'string' && typeof haystack === 'string') {
                    if(haystack.indexOf(needle) != -1) {
                    return true;
                  }
                    else {
                    return false;
                  }
                }
                else {
                    return false;
                }
            }
25. Làm việc mới mảng - Phần 2
  25.1:
    Cho trước hàm getRequestBodyFromValues và tham số formValues, 
    các test case sẽ gọi hàm này và truyền đối số có định dạng tương tự như sau:
            [
                { field: 'name', value: 'Sơn Đặng' },
                { field: 'age', value: 18 },
                { field: 'address', value: 'Hà Nội' },
                // ...
             ]
    Như các bạn thấy, formValues là một mảng có thể chứa nhiều objects. Mỗi object chứa 2 keys là field và value.

    Yêu cầu:Từ array formValues đã cho, hãy trả về một object có các keys tương ứng với các fields 
            của các objects nằm trong array formValues.
            
          // Làm bài tập tại đây
      function getRequestBodyFromValues(formValues) {
          return formValues.reduce((result, item) => {
              result[item.field] = item.value;
              return result;
          }, {});
      }
   25.2:
    Cho trước hàm checkPositiveNumbers có tham số numbers sẽ nhận một mảng gồm các phần tử là những số bất kì. 
    Hàm này được tạo ra với mục đích kiểm tra toàn bộ các chữ số trong mảng numbers có phải là số dương hay không.
          Nếu toàn bộ phần tử trong mảng numbers là số dương hàm sẽ trả về true
          Nếu một trong các phần tử của mảng numbers không phải số dương hàm sẽ trả về false
    
    // Làm bài tập tại đây
          function checkPositiveNumbers(numbers) {
              let a = numbers.every(function(x) {
                  return x > 0;
              })
              return a;
          }
   25.3:
    Cho hàm hasFreeCourses để kiểm tra một danh sách khóa học có khóa học nào miễn phí hay không.
    Cho biến courses là tham số của hàm trên, biến này là một array chứa nhiều object đại diện cho khóa học có định dạng như sau:
            [
                { name: 'Javascript', vnd: 1000000 },
                { name: 'PHP', vnd: 990000 },
                { name: 'HTML, CSS', vnd: 0 }
                // ...
            ]
    Yêu cầu:
        Hàm hasFreeCourses sẽ trả về true nếu đối số truyền vào có chứa khóa học miễn phí
        Hàm hasFreeCourses sẽ trả về false nếu đối số truyền vào không chứa khóa học miễn phí
      // Làm bài tập tại đây
        function hasFreeCourses(courses) {
            let a = courses.some(function(x) {
                return x.vnd === 0;
            });
            return a;
        }
  25.4:
    Cho trước biến monsters là một danh sách các con thú trong game có định dạng như sau:
          [
              {
                  name: 'Cá heo',
                  attack: 50,
                  speed: 100,
                  hitpoint: 100,
              },
              {
                  name: 'Khủng long',
                  attack: 150,
                  speed: 80,
                  hitpoint: 180,
              },
              // ...
          ]
    Yêu cầu: 
          Tìm thú có chỉ số attack bằng 150 và trả về thú đó trong hàm findAMonsterByAttack đã cho trước
          Trường hợp trong danh sách monsters không có thú phù hợp thì hàm findAMonsterByAttack trả về null
    // Làm bài tập tại đây
          function findAMonsterByAttack(monsters) {
              return monsters.find((monster, index) => {
                  return monster.attack == 150;
              }) || null
          }
  25.5:
    Cho trước hàm findStringsInArrayByKeyword và tham số thứ nhất có tên keyword sẽ là một chuỗi bất kỳ.
    Tham số thứ hai có tên strings sẽ là một array chứa các chuỗi bất kì, array này có định dạng như sau:
        ['hi', 'abc', 'chuỗi', '123']
    Yêu cầu
          Trong hàm cho trước, hãy trả về một array mới gồm các phần tử trong array strings có chứa giá trị của biến keyword. 
          Trường hợp không có phần tử phù hợp trả về mảng rỗng.
  // Làm bài tập tại đây
          function findStringsInArrayByKeyword(keyword, strings) {
            return strings.filter(function(x) {
              if (x.includes(keyword)) {
                return x;
              }
            })
          }
  25.6:
  Tại bài tập này chúng ta sẽ cùng nhau tạo hàm findEqualValues để tìm ra các giá trị bằng nhau giữa hai array.
    Yêu cầu
      - Tạo hàm findEqualValues có hai tham số là array1 và array2 
            (Hai tham số này sẽ được test case tại F8 truyền đối số là các array chứa nhiều các giá trị số hoặc chuỗi bất kì).
      - Trường hợp array1 và array2 có các giá trị bằng nhau thì hàm findEqualValues sẽ trả về mảng mới 
            chứa các giá trị đó (mỗi giá trị là một phần tử trong array mới)
      - Trường hợp không có giá trị bằng nhau giữa hai tham số thì hàm trả về array rỗng []
      // Làm bài tập tại đây

        function findEqualValues(array1, array2){
            return array1.filter(function(num) {
                return array2.includes(num);
            })
        }
26. Array map() method
  26.1:
    Cho trước hàm convertToBoolean có tham số inputs là một array gồm các phần tử có giá trị bất kì. Ví dụ:
          [1, 'hi', false, 8, undefined, '', NaN]
    Yêu cầu:
      Hãy xử lý để hàm trên trả về một mảng mới gồm các phần tử được chuyển đổi sang kiểu dữ liệu boolean.
  // Làm bài tập tại đây
          function convertToBoolean(inputs) {
              return inputs.map(function(x) {
                if(x) {
                  return true;
                }
                else {
                  return false;
                }
              })
          }
  26.2:
    Cho trước biến inputs là một array gồm các phần tử là các chữ số bất kì. 
    Trong hàm run, hãy trả về array mới từ array inputs đã cho với giá trị các phần tử có giá trị x 3 lần.
  // Làm bài tập tại đây
        function run(inputs) {
          return inputs.map(function(x) {
            return x*3;
          })
        }
  26.3: 
  Cho trước hàm convertToNumber và tham số strings là một mảng gồm nhiều chuỗi chữa các số tương tự như sau:
        ['1', '6', '2', '8']
Yêu cầu:
        Dựa vào kiến thức đã học hãy xử lý để hàm convertToNumber trả về một array mới từ array strings, 
        các phần tử trong array trả về được chuyển đổi sang kiểu dữ liệu number.
  // Làm việc tại đây
          function convertToNumber(inputs) {
            return inputs.map(function(x) {
              return Number(x);
            })
          }
  26.4:
    Cho trước hàm convertToString và tham số numbers là một mảng gồm nhiều các số tương tự như sau:
        [1, 20, -8, 0, 16]
    Yêu cầu:
      Dựa vào kiến thức đã học hãy xử lý để hàm convertToString trả về một array mới từ array numbers, 
      các phần tử trong array trả về được chuyển đổi sang kiểu dữ liệu string.
  // Làm bài tập tại đây
        function convertToString(inputs) {
          return inputs.map(function(x) {
            return x.toString();
          })
        }
27. Array reduce() method
  27.1:
    Cho biến numbers là một mảng chứa các giá trị số bất kì. 
    Trong hàm cho trước, hãy trả về tổng của toàn bộ giá trị của các phần tử trong mảng numbers
    // Làm bài tập tại đây
          function sum(numbers) {
              return numbers.reduce(function(a, b) {
                  return a + b;
              }, 0)
          }
  27.2:
  Cho biến inputs là một mảng chứa các giá trị có thể là bất kì kiểu dữ liệu nào. 
  Trong hàm cho trước, hãy trả về tổng của toàn bộ giá trị số hợp lệ của các phần tử trong mảng inputs
  // Làm bài tập tại đây
          function sumNumbers(inputs) {
              let filterArray = inputs.filter(element => Number(element));
              return filterArray.reduce((a, b) => 
              (a + b));
          }
28. Ví dụ Array reduce() method
  Cho trước biến courses có định dạng như sau:
    [
        { name: 'Javascript', coin: 1000 },
        { name: 'PHP', coin: 1200 },
        { name: 'Dart', coin: 1400 }
    ]
  Yêu cầu:
  Trả về tổng coin của toàn bộ các khóa học
  // Làm bài tập tại đây
        function run(courses) {
            return courses.reduce(function(a, b) {
                return a + b.coin;
            }, 0)
        }
29. Lệnh rẻ nhánh If else
  Cho trước biến number có giá trị số ngẫu nhiên trong các số sau: 3, 5, 15
    Yêu cầu
      Nếu number chia hết cho 3 thì trả về chuỗi f
      Nếu number chia hết cho 5 thì trả về số 8
      Nếu number chia hết cho 15 thì trả về chuỗi f8
  // Làm bài tập tại đây
          function run(number) {
          if (number % 15 === 0) {
            return 'f8';
          }
          else if (number % 5 === 0) {
            return 8;
          }
          else {
            return 'f';
          }
        }
