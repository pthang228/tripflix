# tripflix

Repo gốc gom 3 phần của hệ thống, mỗi phần là một thư mục và vẫn giữ công cụ riêng:

| Thư mục | Nội dung | Nguồn |
|---|---|---|
| `tripflix-be/` | Backend, hợp đồng API, `deploy/compose.yaml` | https://github.com/Sukemcute/tripflix-be |
| `tripflix-fe/` | Web, admin, mobile | https://github.com/Sukemcute/tripflix-fe |
| `tripflix-ai/` | Dịch vụ AI | https://github.com/Sukemcute/tripflix-ai |

Tên thư mục cần giữ nguyên vì compose và `orval.config.ts` trỏ tới nhau qua đường dẫn tương đối.
Cách chạy: xem `tripflix-be/README.md`.

## Lấy cập nhật từ repo nguồn

```bash
git subtree pull --prefix=tripflix-be https://github.com/Sukemcute/tripflix-be.git main
```

Đổi `tripflix-be` thành `tripflix-fe` hoặc `tripflix-ai` cho hai phần còn lại.
