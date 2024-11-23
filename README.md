# CW3D NFT Explorer Dành Cho Netlify

Bản mẫu này được thiết lập để triển khai trên Netlify và bạn có thể triển khai trực tiếp dự án này bằng cách nhấn vào nút bên dưới:

[![Triển khai trên Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alchemyplatform/netlify-alchemy-nft-explorer-template)

![image](https://user-images.githubusercontent.com/72762629/235919616-ba92fb9e-c171-4d7f-a928-862c80009075.png)

## Tài nguyên

Vui lòng tham khảo tài liệu của CW3D và các liên kết hữu ích sau để tìm hiểu sâu hơn về cách làm việc với các dự án khởi tạo bằng CW3D:

- [Tài liệu](https://docs.alchemy.com/docs/create-web3-dapp) - Mọi thứ bạn cần biết khi sử dụng CW3D
- [GitHub](https://github.com/alchemyplatform/create-web3-dapp) - Xem ví dụ mã chi tiết hoặc bắt đầu đóng góp
- [Website](https://createweb3dapp.alchemy.com) - Tìm hiểu thêm về CW3D và thêm các thành phần vào dự án của bạn
- [Mẫu dự án](https://createweb3dapp.alchemy.com/#templates) - Xem các mẫu dự án được xây dựng sẵn
- [Thư viện thành phần](https://createweb3dapp.alchemy.com/#components) - Thêm tính năng trực tiếp vào dự án của bạn thông qua các thành phần
- [Ví dụ](https://github.com/alchemyplatform/create-web3-dapp-examples) - Xem các thành phần được triển khai trong một dApp thực tế
- [Cộng đồng](https://t.me/createweb3dapp) - Kết nối với những nhà phát triển khác, nhận hỗ trợ và đưa ra phản hồi!

## Tổng quan

Dự án này đóng vai trò là điểm khởi đầu để tạo các ứng dụng phi tập trung (dApp) khám phá NFT bằng [Create Web3 Dapp](https://github.com/alchemyplatform/create-web3-dapp). Nó được cấu hình sẵn để triển khai trên [Netlify](https://www.netlify.com/), giúp bạn dễ dàng đưa dApp của mình vào hoạt động một cách nhanh chóng.

Bản mẫu này được xây dựng bằng [CW3D (Create Web3 Dapp)](https://github.com/alchemyplatform/create-web3-dapp), một công cụ mạnh mẽ được phát triển bởi [Alchemy](https://www.alchemy.com/) giúp các nhà phát triển nhanh chóng tạo và triển khai dApp.

## Bao gồm những gì?

Bản mẫu này có mọi thứ bạn cần để bắt đầu xây dựng dApp:

- Next.js
- Wagmi Hooks
- Ethers.js
- Rainbowkit
- Alchemy SDK

## Các chuỗi hỗ trợ

Dự án hỗ trợ tất cả các chuỗi EVM chính:

- Ethereum
- Polygon
- Arbitrum
- Optimism

## Bắt đầu

### Yêu cầu

Để bắt đầu với bản mẫu này, bạn cần cài đặt các phần mềm sau trên máy của mình:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Cài đặt

1. Sao chép kho lưu trữ về máy của bạn:
   ```bash
   git clone https://github.com/alchemyplatform/netlify-alchemy-nft-explorer-template

cd netlify-alchemy-nft-explorer-template

yarn install

npm install -g netlify-cli

netlify deploy

**Cấu trúc dự án**

📦root
 ┣ 📂components
 ┃ ┣ 📂navigation
 ┃ ┃ ┗ 📜navbar.jsx
 ┃ ┗ 📜nftGallery.jsx
 ┣ 📂layout
 ┃ ┗ 📜mainLayout.jsx
 ┣ 📂pages
 ┃ ┣ 📂api
 ┃ ┃ ┣ 📜getNftsForCollection.js
 ┃ ┃ ┗ 📜getNftsForOwner.js
 ┃ ┣ 📜_app.js
 ┃ ┗ 📜index.jsx
 ┣ 📂public
 ┃ ┗ 📜alchemy_logo.svg
 ┣ 📂styles
 ┃ ┣ 📜Home.module.css
 ┃ ┣ 📜Navbar.module.css
 ┃ ┣ 📜NftGallery.module.css
 ┃ ┗ 📜globals.css
 ┣ 📜.env.local
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜package-lock.json
 ┗ 📜package.json

