# Arkadaşları Repository'ye Ekleme Rehberi

Arkadaşlarınızın da bu projeye commit atabilmesi için onları **Collaborator** olarak eklemeniz gerekir.

## Adım Adım: Collaborator Ekleme

### 1. GitHub Repository Sayfasına Gidin
- https://github.com/kaganay/FreeRTOS_PC_Scheduler adresine gidin
- Sağ üstteki **"Settings"** butonuna tıklayın

### 2. Collaborators Bölümüne Gidin
- Sol menüden **"Collaborators"** seçeneğine tıklayın
- **"Add people"** butonuna tıklayın

### 3. Arkadaşınızı Ekleyin
- Arkadaşınızın GitHub kullanıcı adını veya e-posta adresini girin
- GitHub otomatik olarak kullanıcıyı bulacaktır
- **"Add [kullanıcı adı] to this repository"** butonuna tıklayın

### 4. İzin Seviyesi (Opsiyonel)
- **Write** izni verin (commit atabilmeleri için)
- Arkadaşınız bir e-posta davetiyesi alacak ve kabul etmesi gerekecek

## Arkadaşlarınızın Yapması Gerekenler

### İlk Kez Kullanım

1. **Repository'yi klonlayın:**
   ```bash
   git clone https://github.com/kaganay/FreeRTOS_PC_Scheduler.git
   cd FreeRTOS_PC_Scheduler
   ```

2. **Değişiklik yapın ve commit edin:**
   ```bash
   # Dosyalarda değişiklik yapın
   git add .
   git commit -m "Değişiklik açıklaması"
   ```

3. **GitHub'a gönderin:**
   ```bash
   git push origin master
   ```
   
   İlk kez push yaparken GitHub kullanıcı adı ve token isteyecek.

### Sonraki Kullanımlar

```bash
# Güncellemeleri çek
git pull

# Değişiklik yap
# ... dosyalarda değişiklik ...

# Commit ve push
git add .
git commit -m "Yeni değişiklik"
git push
```

## Önemli Notlar

- ✅ Collaborator olarak eklenen kişiler **Write** izni ile commit atabilir
- ✅ Herkes kendi commit'lerini görebilir
- ✅ Commit geçmişi herkeste görünür
- ⚠️ Dikkatli olun: Collaborator'lar projeyi değiştirebilir/silebilir
- 💡 Alternatif: Fork + Pull Request yöntemi daha güvenlidir (büyük projeler için)

## Alternatif: Fork + Pull Request (Daha Güvenli)

Eğer herkesin direkt commit atmasını istemiyorsanız:

1. Arkadaşlarınız repository'yi **Fork** eder
2. Kendi fork'larında değişiklik yapar
3. **Pull Request** gönderir
4. Siz değişiklikleri kontrol edip **Merge** edersiniz

Bu yöntem daha kontrollü ve profesyoneldir.

