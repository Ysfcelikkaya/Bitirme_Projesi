<div align="center">
  <h1>🏥 Hospital Management System</h1>
  <p><strong>A robust, scalable, and secure RESTful Web API and MVC Client for modern healthcare management.</strong></p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white" alt=".NET 8" />
  <img src="https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Entity%20Framework-Core-0078D7?logo=nuget&logoColor=white" alt="EF Core" />
  <img src="https://img.shields.io/badge/Dapper-Micro%20ORM-E34F26?logo=database&logoColor=white" alt="Dapper" />
  <img src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
</div>

<br>

## 📝 Proje Hakkında

Bu proje, hastane operasyonlarını (hasta, doktor, randevu vb. yönetimleri) dijitalleştirmek amacıyla geliştirilmiş **uçtan uca bir yazılım çözümüdür**. Arka planda yüksek performanslı bir **RESTful Web API** koşarken, ön tarafta **ASP.NET Core MVC** kullanılarak kullanıcı dostu bir arayüz tasarlanmıştır.

Veritabanı operasyonlarında yükü hafifletmek ve yanıt süresini maksimize etmek için **Entity Framework Core**, **Dapper**, **LINQ** ve doğrudan **Stored Procedure**'ler bir arada kullanılmıştır.

---

## 🚀 Öne Çıkan Özellikler

* 🔐 **Güvenli Kimlik Doğrulama:** **JWT (JSON Web Token)** ve Azure SDK entegrasyonu ile bulut tabanlı ve güvenilir yetkilendirme altyapısı.
* ⚡ **Yüksek Performans:** Kritik CRUD işlemlerinde Stored Procedure ve Dapper/LINQ kullanılarak optimize edilmiş veritabanı sorguları.
* 🧩 **Çok Katmanlı Mimari:** Sürdürülebilirlik ve temiz kod (Clean Code) prensiplerine uygun, ölçeklenebilir proje yapısı.
* 🌐 **Uçtan Uca Entegrasyon:** Web API ile MVC istemcisi (client) arasında `HttpClient` üzerinden kesintisiz veri iletişimi.
* 📄 **API Dökümantasyonu:** Tüm API uç noktaları için standartlara uygun, etkileşimli **Swagger (OpenAPI)** arayüzü.

---

## 🛠️ Kullanılan Teknolojiler & Araçlar

### 💻 Backend
* **C# 12 & .NET 8.0**
* **ASP.NET Core Web API**
* **ASP.NET Core MVC**

### 🗄️ Veritabanı & ORM
* **MS SQL Server**
* **Entity Framework Core** (Code-First)
* **Dapper** (Micro-ORM)
* **LINQ & Stored Procedures**

### 🔒 Güvenlik & Bulut
* **JWT (JSON Web Token)** tabanlı yetkilendirme
* **Azure SDK** entegrasyonları

### ⚙️ Araçlar ve Pratikler
* **Git & GitHub** (Versiyon Kontrolü)
* **Swagger** (API Dokümantasyonu)
* **HttpClient** (Servisler arası haberleşme)

---

## 📂 Proje Yapısı (Mimari)

Proje, temel olarak üç ana bileşenden (Solution) oluşmaktadır:
1. ⚙️ **HospitalAppApi:** İş mantığının ve veritabanı işlemlerinin yürütüldüğü, dış dünyaya hizmet veren RESTful Web API katmanı.
2. 🖥️ **HospitalAppMvc:** API ile `HttpClient` üzerinden haberleşen, son kullanıcının etkileşime girdiği web arayüzü katmanı.
3. ⚡ **HospitalAppDppr:** Performansın kritik olduğu yerlerde Dapper (Micro-ORM) ile desteklenen veri erişim katmanı.

---

## 👨‍💻 Geliştirici

**Yusuf Çelikkaya**  
*Bilgisayar Mühendisi*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yusuf-celikkaya)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ysfcelikkaya)

> _"Clean Code prensiplerine bağlı kalarak, iş süreçlerini dijitalleştiren yenilikçi çözümler üretmeye odaklanıyorum."_
