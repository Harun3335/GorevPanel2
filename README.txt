# Görev Yönetimi Paneli - Django Projesi

## Gereksinimler

- Python 3.8+
- Django 4.x

## Kurulum

1. Proje dosyasını indirin veya klasörü açın.

2. Sanal ortam oluşturun (opsiyonel ama önerilir):

python -m venv env
env\Scripts\activate   # Windows
source env/bin/activate  # Mac/Linux

3. Gereken paketleri yükleyin:

pip install django

4. Veritabanını hazırlayın:

python manage.py makemigrations
python manage.py migrate

5. Geliştirme sunucusunu başlatın:

python manage.py runserver

6. Tarayıcıdan uygulamayı açın:

http://127.0.0.1:8000

## Admin Paneli (Opsiyonel)

Superuser oluşturmak için:

python manage.py createsuperuser

## Özellikler

- Görev Ekleme, Düzenleme, Silme
- Görev Tamamlama / Tamamlanmadı Yapma
- Geç Kaldınız Durumu
- Giriş / Çıkış / Kayıt İşlemleri
- Kullanıcıya özel görev listesi
- Şık ve modern görünüm (Bootstrap)
