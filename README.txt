bzBunny 3.0.0-alpha.5 – PWA phiên bản thử nghiệm

LƯU Ý: PWA cần được truy cập qua HTTPS (hoặc localhost). Không mở index.html trực tiếp từ file manager để cài PWA.

Cách dễ nhất để đưa lên mạng miễn phí:
1. Tạo tài khoản GitHub nếu chưa có.
2. Tạo repository mới, đặt tên bzbunny (Public).
3. Upload toàn bộ các file/thư mục trong gói này (index.html, manifest.webmanifest, sw.js, assets, README, sample-vocab.xlsx) lên repo, không upload thư mục bzBunny-pwa-work bên ngoài.
4. Vào Settings > Pages > Build and deployment, chọn Deploy from a branch, Branch main, Folder /(root), Save.
5. Đợi GitHub Pages cấp URL HTTPS dạng https://TEN-TAI-KHOAN.github.io/bzbunny/.
6. Mở URL trên tablet bằng Chrome. Chọn menu ⋮ > Install app hoặc Add to Home screen.
7. Mở icon bzBunny trên màn hình chính. App sẽ chạy dạng standalone.

Offline:
- Sau khi mở lần đầu có Internet, service worker sẽ lưu bộ khung app và các assets.
- Những tính năng cần Gemini API vẫn cần Internet.
- Dữ liệu từ vựng/tiến độ hiện vẫn lưu riêng trong trình duyệt/thiết bị; chưa tự đồng bộ giữa máy tính và tablet.

Nếu không muốn công khai repository, có thể dùng một host HTTPS riêng tư/khác. Không đưa API key vào file hay repo.

Alpha 7 dictionary: multi-source lookup (Minhqnd, FreeDictionaryAPI/Wiktionary, Datamuse suggestions), Soha attempt and Cambridge cross-check links. Soha/Cambridge access limitations are documented in app.

Alpha 8: Choose among 8 Bunny expression avatars in Settings; user avatar crop editor remains available. Card open sound replaced with provided tap-notification sound.
