<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

Chọn ngôn ngữ: [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | VI | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Pepecoin là một loại tiền điện tử tập trung vào cộng đồng được tạo ra bởi một trong những người sáng lập Dogecoin nguyên bản từ năm 2013. Nó được tạo ra với một mục đích, đó là tạo ra một cộng đồng mới và vui vẻ giống như cộng đồng Dogecoin ban đầu.

Khác với tất cả các phiên bản trước, Pepecoin là một đồng tiền lớp 1. Điều này có nghĩa là không có các bể thanh khoản để rút tiền, không có ví bị cấm và không có hợp đồng thông minh phức tạp. Pepecoin là một blockchain đơn giản.

Phần mềm Pepecoin Core cho phép bất kỳ ai cũng có thể vận hành một nút trong mạng lưới blockchain của Pepecoin và sử dụng phương thức băm Scrypt cho Chứng minh công việc. Nó được điều chỉnh từ Dogecoin Core, Bitcoin Core và các loại tiền điện tử khác.

Để biết thông tin về các khoản phí mặc định được sử dụng trên mạng Pepecoin, vui lòng tham khảo [khuyến nghị về phí](doc/fee-recommendation.md).

**Website:** [pepecoin.org](https://pepecoin.org)

## Sự khác biệt so với Dogecoin

Pepecoin là một nhánh (fork) của Dogecoin. Để dễ làm quen, chúng tôi sẽ cố gắng giữ cho Pepecoin giống với Dogecoin.

Các thay đổi:

* Địa chỉ bắt đầu bằng `P` thay vì `D`
* Các tính năng BIPS sẽ bắt đầu từ khối 1000
* AuxPow bắt đầu từ khối 42.000 (ID chuỗi: 63)
* Giao diện người dùng với chủ đề Pepecoin

## Hướng dẫn sử dụng 💻

Để bắt đầu hành trình với Pepecoin Core, hãy tham khảo [hướng dẫn cài đặt](INSTALL.md) và [hướng dẫn bắt đầu](doc/getting-started.md).

API JSON-RPC được cung cấp bởi Pepecoin Core là tự tài liệu và có thể được duyệt thông qua `pepecoin-cli help`, trong khi thông tin chi tiết cho mỗi lệnh có thể xem qua `pepecoin-cli help <command>`. Ngoài ra, bạn có thể tham khảo [tài liệu của Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - cái này triển khai một giao thức tương tự - để có một phiên bản có thể duyệt.

### Cổng kết nối

Pepecoin Core mặc định sử dụng cổng `33874` cho việc truyền thông giữa các nút cần thiết để đồng bộ hóa blockchain "mainnet" và theo dõi các giao dịch và khối mới. Thêm vào đó, một cổng JSONRPC có thể được mở, mặc định là cổng `33873` cho các nút mainnet. Chúng tôi khuyến cáo mạnh mẽ không nên mở cổng RPC ra Internet công cộng.

| Chức năng | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Phát triển liên tục 💻

Pepecoin Core là một phần mềm mã nguồn mở và được điều hành bởi cộng đồng. Quá trình phát triển là công khai và có thể thấy được; bất kỳ ai cũng có thể xem, thảo luận và tham gia vào việc phát triển phần mềm.

Các tài nguyên phát triển chính:

* [GitHub Projects](https://github.com/pepecoinppc/pepecoin/projects) được sử dụng để theo dõi công việc kế hoạch và các công việc đang tiến hành cho các bản phát hành sắp tới.
* [GitHub Discussion](https://github.com/pepecoinppc/pepecoin/discussions) được sử dụng để thảo luận về các tính năng, cả đã được lên kế hoạch và chưa lên kế hoạch, liên quan đến việc phát triển phần mềm Pepecoin Core, các giao thức cơ bản và tài sản PEP.
* [PepecoinDev subreddit](https://www.reddit.com/r/pepecoindev)

### Chiến lược phiên bản
Số phiên bản theo cú pháp ```major.minor.patch```.

### Các nhánh
Có 3 loại nhánh trong kho lưu trữ này:

- **master:** Ổn định, chứa phiên bản mới nhất của bản phát hành *major.minor* mới nhất.
- **maintenance:** Ổn định, chứa phiên bản mới nhất của các bản phát hành trước vẫn đang được duy trì. Định dạng: ```<version>-maint```
- **development:** Không ổn định, chứa mã nguồn mới cho các bản phát hành dự kiến. Định dạng: ```<version>-dev```

*Các nhánh master và maintenance chỉ có thể thay đổi qua các bản phát hành. Các bản phát hành dự kiến luôn có một nhánh phát triển và các yêu cầu kéo (pull request) nên được gửi vào những nhánh này. Các nhánh maintenance chỉ dành cho **sửa lỗi**, vui lòng gửi các tính năng mới vào nhánh phát triển có phiên bản cao nhất.*

## Đóng góp 🤝

Nếu bạn phát hiện lỗi hoặc gặp sự cố với phần mềm này, vui lòng báo cáo qua [hệ thống vấn đề](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Hãy tham khảo [hướng dẫn đóng góp](CONTRIBUTING.md) để xem cách bạn có thể tham gia vào phát triển Pepecoin Core. Thường xuyên có [các chủ đề tìm kiếm sự giúp đỡ](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted) nơi đóng góp của bạn sẽ có tác động lớn và được đánh giá cao.

## Cộng đồng 🐸

Bạn có thể tham gia vào các cộng đồng trên các mạng xã hội khác nhau. Để xem những gì đang diễn ra, gặp gỡ mọi người và thảo luận, tìm meme mới nhất, học hỏi về Pepecoin, yêu cầu hoặc cung cấp sự giúp đỡ, chia sẻ dự án của bạn.

Dưới đây là một số nơi bạn có thể tham gia:

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## Câu hỏi thường gặp ❓

Bạn có câu hỏi về Pepecoin? Câu trả lời có thể đã có trong [FAQ](doc/FAQ.md) hoặc trong [mục Q&A của diễn đàn thảo luận](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a)!

## Giấy phép ⚖️
Pepecoin Core được phát hành dưới giấy phép MIT. Xem [COPYING](COPYING) để biết thêm chi tiết hoặc tham khảo [opensource.org](https://opensource.org/licenses/MIT)
