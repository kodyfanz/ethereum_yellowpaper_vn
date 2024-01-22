# Ethereum Yellow Paper (Giấy vàng Ethereum)

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Gitter](https://badges.gitter.im/ethereum/yellowpaper.svg)](https://gitter.im/ethereum/yellowpaper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitPOAP Badge](https://public-api.gitpoap.io/v1/repo/ethereum/yellowpaper/badge)](https://www.gitpoap.io/gh/ethereum/yellowpaper)

Giấy vàng (Yellow Paper) là một định nghĩa chính thức của giao thức Ethereum, được khởi đầu bởi Gavin Wood, hiện được duy trì bởi Nick Savers và với sự đóng góp từ nhiều người trên thế giới.

Đây là một tác phẩm văn hóa tự do, được cấp phép theo phiên bản Creative Commons Attribution Share-Olike (CC-by-SA) phiên bản 4.0.

## Kho lưu trữ hiện đã lỗi thời

Giấy vàng đã lỗi thời. Nó phản ánh đặc tả Ethereum cho đến bản nâng cấp [Paris](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/paris.md) hợp nhất ("the merge"), được kích hoạt trên ethereum mainnet tại khối `15_537_394` (Tháng 9 2022). 

Nó **không** chứa các thay đổi được giới thiệu trong bất kỳ bản nâng cấp sau khi hợp nhất. 

Một thay thế [Thông số kỹ thuật của lớp thực thi Python](https://ethereum.github.io/execution-specs/) được duy trì tích cực và cập nhật. 

## Cách sử dụng

Nếu bạn chỉ muốn đọc bài báo, phiên bản mới nhất thường có sẵn dưới dạng PDF tại https://ethereum.github.io/yellowpaper/paper.pdf. Nếu bạn thấy rằng các đường viền cho liên kết che mất nhiều văn bản khi xem PDF trong trình duyệt, bạn có thể tải xuống và mở xem nó bằng một ứng dụng xem PDF như Adobe Acrobat hoặc Evince, nơi các đường viền ít có khả năng hiển thị.

Tuy nhiên, nếu bạn muốn chỉnh sửa bài báo bằng Tiếng Việt và giúp hoàn thiện nó, hãy đọc tiếp. Bài báo đã được dịch Tiếng Việt được biểu diễn dưới dạng một tệp ``latex`` duy nhất là ``Paper_vn.tex``.  

Đề xuất sử dụng một môi trường phát triển tích hợp (IDE) như [Visual Studio Code](https://code.visualstudio.com/) với tiện ích mở rộng LaTeX Workshop để chỉnh sửa tệp tex và hiển thị PDF.

Một lựa chọn khác là chỉnh sửa tệp `tex` một cách riêng biệt và `build` như sau (bạn vẫn cần phải sao chép kho lưu trữ (clone repo) sau đó mở thư mục ethereum_yellowpaper_vn):

```
git clone https://github.com/kodyfanz/ethereum_yellowpaper_vn.git
cd ethereum_yellowpaper_vn
./build.sh
```
Điều này sẽ tạo ra một phiên bản PDF của Yellow Paper Tiếng Việt. Sau khi xây dựng, bạn cũng có thể sử dụng các công cụ `pdflatex` tiêu chuẩn để biên dịch/xem trước, như http://latex.informatik.uni-halle.de/latex-online/latex.php.

## Lời khuyên về chỉnh sửa

Bạn có thể sử dụng [TeX Stack Exchange](https://tex.stackexchange.com/); https://en.wikibooks.org/wiki/LaTeX/ (vd: [Bibliography Management](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management) và [Hyperlinks](https://en.wikibooks.org/wiki/LaTeX/Hyperlinks)); và [BibTeX editor](http://truben.no/latex/bibtex/).

## Các phiên bản

Các phiên bản giao thức trước được liệt kê trong [BRANCHES.md](./BRANCHES.md).

### Các phiên bản ngôn ngữ khác
- [English](https://github.com/ethereum/yellowpaper) phiên bản gốc của Gavin Wood, hiện được Nick Savers duy trì và với sự đóng góp từ nhiều người trên thế giới.
- [Chinese](https://github.com/yuange1024/ethereum_yellowpaper) được dịch bởi YuanGe và GaoTianlu.
- [French](https://github.com/asseth/yellowpaper) được dịch bởi Asseth (checkout sang nhánh 'french').
- [Vietnamese](https://github.com/kodyfanz/ethereum_yellowpaper_vn) được dịch bởi Kody Fanz (checkout sang nhánh 'vietnamese').
