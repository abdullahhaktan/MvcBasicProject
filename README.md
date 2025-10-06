# MvcBasicProject

[TR]

**ASP.NET MVC Temel Prensiplerini Uygulayan Basit Web Uygulaması Projesi**

[![ASP.NET MVC](https://img.shields.io/badge/Framework-ASP.NET_MVC-602C78.svg)](https://dotnet.microsoft.com/apps/aspnet/mvc)
[![C#](https://img.shields.io/badge/Language-C%23-blue.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![GitHub repo size](https://img.shields.io/github/repo-size/abdullahhaktan/MvcBasicProject)](https://github.com/abdullahhaktan/MvcBasicProject)

---

## 💻 Proje Hakkında

Bu proje, **Model-View-Controller (MVC)** mimarisinin temel yapısını ve işleyişini göstermek amacıyla geliştirilmiş bir **giriş seviyesi web uygulamasıdır**. Proje, Controller, View ve Model katmanlarının rollerini açıkça ayırarak, web uygulaması geliştirmenin temel prensiplerini pratikle pekiştirmeyi hedefler.

---

## ✨ Temel Özellikler ve Uygulanan Prensipler

### MVC Mimarisine Giriş
* **Katmanların Ayrılması:** Kullanıcı arayüzü (View), iş mantığı (Model) ve kontrol mekanizması (Controller) arasındaki net sorumluluk ayrımını gösterir.
* **Routing (Yönlendirme):** URL'lerin Controller eylemleriyle nasıl eşleştirildiğini temel düzeyde açıklar.

### Temel CRUD İşlemleri
* Projenin odağına göre, basit bir varlık üzerinde (örneğin To-Do Listesi, Temel Kayıt Formu) **Ekleme (Create), Listeleme (Read), Güncelleme (Update) ve Silme (Delete)** operasyonları uygulanmıştır.
* **Veri Taşıma:** **`ViewBag`**, **`ViewData`** veya **`ViewModel`** kullanarak Controller'dan View'a veri aktarma teknikleri kullanılmıştır.

### Kullanılan Teknolojiler
* **ASP.NET MVC:** Ana uygulama çatısı.
* **C#:** Arka uç (Backend) programlama dili.
* **Razor View Engine:** Dinamik HTML oluşturmak için kullanılan şablon motoru.
* **Entity Framework (Basit Bağlantı):** Veri erişimi ve basit veritabanı etkileşimleri için (varsayımsal).

---

## 🚀 Nasıl Çalıştırılır?

Bu proje, bir **Visual Studio** ortamını gerektirir ve genellikle ek bir veritabanı kurulumu gerektirmez (LocalDB veya InMemory kullanılabilir).

1.  **Projeyi Klonlama:**
    ```bash
    git clone [https://github.com/abdullahhaktan/MvcBasicProject](https://github.com/abdullahhaktan/MvcBasicProject)
    cd MvcBasicProject
    ```

2.  **Bağımlılıkları Yükleme:**
    * **Visual Studio**'da `.sln` (Solution) dosyasını açın.
    * Gerekliyse, projenin kullandığı tüm **NuGet** paketlerini geri yükleyin.

3.  **Projeyi Başlatma:**
    * Ana projeyi **`Startup Project`** olarak ayarlayın.
    * **F5** tuşu ile uygulamayı çalıştırın. Uygulama, belirtilen yerel adreste tarayıcınızda açılacaktır.

---
---

[EN]

# MvcBasicProject

**Basic Web Application Project Implementing ASP.NET MVC Fundamentals**

---

## 💻 About the Project

This project is a **beginner-level web application** developed to demonstrate the fundamental structure and operation of the **Model-View-Controller (MVC)** architecture. The project aims to reinforce the basic principles of web application development by clearly separating the roles of the Controller, View, and Model layers.

---

## ✨ Core Features and Applied Principles

### Introduction to MVC Architecture
* **Separation of Concerns:** Clearly demonstrates the separation of responsibility between the user interface (View), business logic (Model), and control mechanism (Controller).
* **Routing:** Explains the basic mechanism of how URLs are mapped to Controller actions.

### Essential CRUD Operations
* Depending on the project's focus (e.g., a To-Do List, a Basic Registration Form), **Create, Read, Update, and Delete (CRUD)** operations on a simple entity have been fully implemented.
* **Data Transfer:** Uses techniques like **`ViewBag`**, **`ViewData`**, or **`ViewModel`** to transfer data from the Controller to the View.

### Technologies Used
* **ASP.NET MVC:** The primary application framework.
* **C#:** The backend programming language.
* **Razor View Engine:** The templating engine used for generating dynamic HTML.
* **Entity Framework (Basic Connection):** Used for data access and simple database interactions (assumed).

---

## 🚀 How to Run

This project requires a **Visual Studio** environment and generally does not need a separate database setup (LocalDB or InMemory might be used).

1.  **Cloning the Project:**
    ```bash
    git clone [https://github.com/abdullahhaktan/MvcBasicProject](https://github.com/abdullahhaktan/MvcBasicProject)
    cd MvcBasicProject
    ```

2.  **Installing Dependencies:**
    * Open the **`.sln`** (Solution) file in **Visual Studio**.
    * Restore all necessary **NuGet** packages used by the project.

3.  **Starting the Project:**
    * Set the main project as the **`Startup Project`**.
    * Run the application by pressing **F5**. The application will open in your browser at the specified local address.

---
---

<img width="362" height="420" alt="basic1" src="https://github.com/user-attachments/assets/44c8ec28-55b9-444a-9360-173c351b843a" />
