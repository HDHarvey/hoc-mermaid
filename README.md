```mermaid
erDiagram
KHACH_HANG ||--o{ DON_HANG : dat
DON_HANG ||--|{ CHI_TIET : co
SAN_PHAM ||--o{ CHI_TIET : trong
KHACH_HANG {
string ma_kh PK
string ten
string email
string sdtbuoi 03 mermaid-guide.md 2025-08-22
7 / 14
}
DON_HANG {
string ma_don PK
string ma_kh FK
date ngay_dat
float tong_tien
}
SAN_PHAM {
string ma_sp PK
string ten_sp
float gia
int ton_kho
}
```
