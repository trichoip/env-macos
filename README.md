-   Showing hidden files: Command Shift .
-   show env: env
-   muốn xóa tài khoảng github trên macos thì:

    -   Nhấp vào biểu tượng Spotlight (kính lúp) ở bên phải thanh menu.
    -   Spotlight: Keychain Access
    -   Nhập Keychain Access
    -   Trong Keychain Access, tìm kiếm github.com.

-   cài gcm cho macos

    -   https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/install.md#macos
    -   check credential: git config --get credential.helper
    -   lưu ý:
        -   trên windown thì không cần configure credential gcm , windown tự nhận dạng gcm
        -   nhưng trên macos thì không có tự nhận dạng gcm, nếu không có configure credential gcm trong .gitignore thì khi push nó không nhận gcm (không xổ ô box chọn tài khoản github)
        -   lúc tải gcm về thì gcm tự configure credential gcm vào .gitignore
        -   nếu không có configure credential gcm trong .gitignore thì chạy lệnh để configure -> git-credential-manager configure
        -   để hủy configure thì -> git-credential-manager unconfigure

-   env path:
    -   tạo file .zshenv
    -   nhập env
