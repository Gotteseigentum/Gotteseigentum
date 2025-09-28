## ⚙️ Ayarlar Menüsü (Dikey Diyagram)

```mermaid
graph TB
    A[Ayarlar]

    %% Firma
    A --> B[Firma]
    B --> B1[Firma Grup Ayarları]
    B --> B2[Firma Tip Ayarları]
    B --> B3[Firma Özel Kod Ayarları]
    B --> B4[Firma Özel Kod Açıklama]
    B --> B5[Firma Bölge Ayarları]
    B --> B6[E-Posta Grup Ayarları]
    B --> B7[E-Posta Ayarları]

    %% Ürün
    A --> C[Ürün]
    C --> C1[Genel Ayarlar]
    C1 --> C11[Birim Ayarları]
    C1 --> C12[KDV Ayarları]
    C1 --> C13[Tevkifat Ayarları]
    C1 --> C14[ÖTV Ayarları]
    C1 --> C15[Fiyat Tip Ayarları]
    C1 --> C16[Ürün Özel Kod Açıklama]

    C --> C2[Barkod Ayarları]
    C2 --> C21[Barkod Etiket Ayarları]
    C2 --> C22[Barkod Tip Ayarları]
    C2 --> C23[Barkod Dosya Ayarları]
    C2 --> C24[Terazi Tip Ayarları]

    C --> C3[Grup Ayarları]
    C3 --> C31[Ürün Grup Ayarları]
    C3 --> C32[Ürün Özel Kod Ayarları]
    C3 --> C33[Ürün Kategori Ayarları]
    C3 --> C34[Reyon Ayarları]
    C3 --> C35[Marka Ayarları]
    C3 --> C36[Üretici Ayarları]
    C3 --> C37[Fiyat Grup Ayarları]

    %% Finans
    A --> D[Finans]
    D --> D1[Döviz Ayarları]
    D --> D2[Kasa Tip Ayarları]
    D --> D3[Banka Hesap Tip Ayarları]
    D --> D4[Banka Kredi Tip Ayarları]
    D --> D5[Banka Pos Hareket Tip Ayarları]

    %% Şube Depo
    A --> E[Şube - Depo]
    E --> E1[Şube Ayarları]
    E --> E2[Depo Ayarları]
    E --> E3[Depo Grup Ayarları]
    E --> E4[Depo Tür Ayarları]
    E --> E5[Depo Mağaza Reyon Ayarları]
    E --> E6[Şube Masraf Limit Dağılımları]

    %% Satın Alma
    A --> F[Satın Alma]
    F --> F1[Satın Alma Insert Sebepleri]
    F --> F2[Satın Alma İade Sebepleri]
    F --> F3[Sipariş Teslim Çeşitleri]
    F --> F4[Sipariş Kapatma Sebepleri]
    F --> F5[Sipariş Mal Toplama Sebepleri]

    %% Yazarkasa
    A --> G[Yazarkasa]
    G --> G1[Kasiyer Ayarları]
    G --> G2[Departman Ayarları]
    G --> G3[Pos Kredi Tip Ayarları]
    G --> G4[Pos Saat Dilim Ayarları]

    %% Tekstil
    A --> H[Tekstil]
    H --> H1[Renk Ayarları]
    H --> H2[Beden Ayarları]
    H --> H3[Kavala Ayarları]
    H --> H4[Asorti Ayarları]

    %% E-Posta & SMS
    A --> I[E-Posta & SMS]
    I --> I1[E-Posta Gönderme]
    I --> I2[Mesaj Gönderme]
    I --> I3[Gelen Mesajlar]
    I --> I4[Gönderilen Mesajlar]
    I --> I5[SMS Gönderme]
    I --> I6[SMS Raporu]

    %% Kullanıcı
    A --> J[Kullanıcı]
    J --> J1[Kullanıcı Ayarları]
    J --> J2[Kullanıcı Grup Ayarları]
    J --> J3[Formlara Departman Atama]
    J --> J4[El Terminali Mobil Kullanıcıları]
    J --> J5[Mobil Satış Kullanıcıları]

    %% Diğer
    A --> K[Diğer]

    K --> K1[Evrak Ayarları]
    K1 --> K11[Yazdırma Ayarları]
    K1 --> K12[Otomatik Kod Ayarları]
    K1 --> K13[Evrak Kilit Ayarları]
    K1 --> K14[Fatura Özel Kod Ayarları]
    K1 --> K15[Listeleme Sihirbazı]
    K1 --> K16[Hata Logları]

    K --> K2[Masraf Ayarları]
    K2 --> K21[Masraf Merkezi Ayarları]
    K2 --> K22[Masraf Grup Ayarları]
    K2 --> K23[Masraf Tip Ayarları]
    K2 --> K24[Fatura Masraf Tip Ayarları]

    K --> K3[Araç Ayarları]
    K3 --> K31[Araç Plaka Ayarları]
    K3 --> K32[Araç Şoför Ayarları]

    K --> K4[Plasiyer Ayarları]
    K --> K5[Hızlı Satış Ürün Kısayolları]
    K --> K6[Vardiya Ayarları]
    K --> K7[Dil Ayarları]
    K --> K8[Form Ayarları]

    %% Tek Satırlık Diğer
    A --> L[Hatırlatıcı]
    A --> M[Devir İşlemleri]
    A --> N[Servis İşlemleri]
    A --> O[Şifre Değiştirme]
    A --> P[Program Ayarları]
    A --> Q[E-Dönüşüm]
    A --> R[Veritabanı Yedekleme]
    A --> S[Veritabanı Bağlantısı Yenile]
