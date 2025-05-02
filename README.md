# ✨ Projekt DSA ✨

[![Frontend Status](https://img.shields.io/badge/Frontend-Next.js_15_/_React_19-58A6FF?style=for-the-badge&logo=nextdotjs)](./dsa.frontend.nextjs)
[![Backend Status](https://img.shields.io/badge/Backend-.NET-934B8E?style=for-the-badge&logo=dotnet)](./dsa.net.backend)
[![Repo Structure](https://img.shields.io/badge/Structure-Git%20Submodules-orange?style=flat-square)](.)

Link do aplikacji: [https://dsa-frontend-nextjs-pkh4.vercel.app/](https://dsa-frontend-nextjs-pkh4.vercel.app/)


# Pamietaj że aplikacja jest w fazie testów!

**Aplikacja DSA czyli inaczej Data Structures and Algorithms, Aplikacja która pomoże ci w fajny sposób nauczyć się bardzo potrzebnych rzeczy! 🎯**

*Aplikacja jest w wersji demo, co oznacza że mogą pojawiać się tam wszelakie blędy, dziękuje za wszelkie Issues!* 🙏

Witaj w głównym centrum dowodzenia projektem DSA! 🚀 To repozytorium spina całość, wykorzystując potęgę **Git Submodules**. Oznacza to, że frontend i backend żyją w swoich własnych repozytoriach, ale tutaj łączymy je w jeden spójny projekt.

---



***Główny widok aplikacji DSA***
![zdjecie-dashboard](https://github.com/user-attachments/assets/f1ba0034-ad4c-4986-8e7a-823356bb4342)


## 🏗️ Struktura Projektu

Nasz projekt to zgrany duet:

*   🎨 **Frontend:** [`dsa.frontend.nextjs/`](./dsa.frontend.nextjs)
    *   Nowoczesny i interaktywny interfejs użytkownika. ✨
    *   Zbudowany na najnowszym [Next.js 15](https://nextjs.org/) i [React 19](https://react.dev/)! 🚀
    *   Repozytorium: [Pum2A/DSA.FRONTEND.NEXTJS](https://github.com/Pum2A/DSA.FRONTEND.NEXTJS)
*   ⚙️ **Backend:** [`dsa.net.backend/`](./dsa.net.backend)
    *   Mózg operacji - API dostarczające dane i logikę. 🧠
    *   Napędzany przez solidny [platformę .NET](https://dotnet.microsoft.com/). 💪
    *   Repozytorium: [Pum2A/DSA.NET.BACKEND](https://github.com/Pum2A/DSA.NET.BACKEND)



***Modul Learningowy***
![zdjecie-nauka-1](https://github.com/user-attachments/assets/cb3201b3-e9ce-4add-94b1-ed38830ea541)

***Wyglad Modulu***
![zdjecie-nauka-2](https://github.com/user-attachments/assets/2203ed8a-6a7e-4660-b146-1c7d19c3cae4)
## 💻 Stos Technologiczny

Nasze narzędzia i technologie - prawdziwy koktajl mocy! 🍹

*   **Frontend:**
    *   **Framework:** Next.js 15 (z Turbopack! ⚡), React 19
    *   **Język:** TypeScript
    *   **Styling:** Tailwind CSS v4 🌬️, `tailwind-merge`, `clsx`, CVA
    *   **Komponenty UI:** shadcn/ui (poprzez Radix UI & Lucide Icons 🧩), `lucide-react` 🦁
    *   **Zarządzanie Stanem:** Zustand 🐻, TanStack Query (React Query) v5 🎣 (dla stanu serwera)
    *   **Formularze:** React Hook Form v7 📋 + Zod 🛡️ (dla walidacji schematów)
    *   **Powiadomienia:** Sonner 🔔, React Hot Toast 🔥
    *   **API & Dane:** Axios 🌐, SWR
    *   **Markdown & Kod:** `react-markdown`, `remark-gfm`, `react-syntax-highlighter` 📝, Monaco Editor (`@monaco-editor/react`) 💻
    *   **AI:** Google Generative AI (`@google/generative-ai`) 🤖 <=== TODO ===>
    *   **Utilities & Efekty:** `react-use`, `react-confetti` 🎉, `tw-animate-css` 🕺
    *   

*   **Backend:** .NET [Wersja 8], C#, [ASP.NET Core Web API 🌐], [Entity Framework Core 💾], [Baza danych: PostgreSQL 🐘/🐬]

  ***Ranking w aplikacji***
![zdjecie-ranking](https://github.com/user-attachments/assets/fafeffe8-8f8e-44df-a9b1-3ae646c3a449)



***Wyglad profilu w aplikacji***
![zdjecie-profil](https://github.com/user-attachments/assets/a228ad96-3fbd-4ed1-906d-4be8c6c4005b)


## ▶️ Pierwsze Kroki - Odpalmy To!

Gotowy, aby zanurzyć się w kodzie? Oto jak postawić projekt lokalnie.

### ✅ Wymagania Wstępne

Upewnij się, że masz na pokładzie:

*   [Git](https://git-scm.com/) 🐙 (bez niego ani rusz!)
*   [Node.js](https://nodejs.org/) (wersja [np. 18.x+]) + npm / yarn 📦
*   [.NET SDK](https://dotnet.microsoft.com/download) (wersja [np. 8.0]) 🛠️ **[👉 Potwierdź wersję .NET]**

### 📥 Klonowanie Repozytorium (Uwaga: Submoduły!)

To **super ważne** przy submodułach! Klonuj z opcją `--recurse-submodules`:

```bash
git clone --recurse-submodules https://github.com/Pum2A/DSA.git
cd DSA
```

Zapomniałeś o `--recurse-submodules`? Żaden problem! Wejdź do folderu `DSA` i wpisz:

```bash
git submodule update --init --recursive
```

Ta komenda ściągnie kod dla wszystkich naszych submodułów (`dsa.frontend.nextjs` i `dsa.net.backend`). ✨

## 🔥 Uruchamianie Aplikacji

Frontend i backend startują oddzielnie.

### 🚀 Uruchamianie Frontendu

1.  Wskocz do katalogu frontendu:
    ```bash
    cd dsa.frontend.nextjs
    ```
2.  Zainstaluj paczki (tylko za pierwszym razem lub po zmianach):
    ```bash
    npm install
    # lub: yarn install
    ```
3.  Odpalamy serwer deweloperski (z Turbopackiem!) 🔥
    ```bash
    npm run dev
    # lub: yarn dev
    ```
4.  Otwórz [http://localhost:3000](http://localhost:3000) (lub inny port z konsoli) w przeglądarce i podziwiaj! 🎉


### ⚙️ Uruchamianie Backendu

1.  Przenieś się do królestwa backendu:
    ```bash
    cd dsa.net.backend
    ```
2.  Przywróć pakiety NuGet:
    ```bash
    dotnet restore
    ```
3.  Czas na start API! 🎬
    ```bash
    dotnet run
    # Wskazówka: Jeśli masz kilka projektów w solucji, może trzeba wskazać główny:
    # dotnet run --project Ścieżka/Do/TwojegoProjektuAPI.csproj
    ```
    Możesz też odpalić projekt z Visual Studio, otwierając plik `.sln`.
4.  Twoje API nasłuchuje! Sprawdź adres w konsoli (np. `http://localhost:5000` lub `https://localhost:5001`). 📡


## 🙏 Kontrybucja

Masz pomysł na ulepszenie? Znalazłeś błąd? Jesteśmy otwarci na Twoją pomoc! ❤️

*   Zgłoś błąd (Issue) lub zaproponuj funkcję w repozytorium **odpowiedniej części** (frontend lub backend).
*   **[👉 Tutaj możesz dodać więcej info, np. o stylu kodowania, procesie PR, jeśli chcesz.]**

## 📜 Licencja

**[👉 Tutaj wstaw informacje o licencji. Np. "Projekt udostępniony na licencji MIT."]**

---

Dzięki za zainteresowanie projektem DSA! 👋 Pamiętaj, że to README to tylko wstęp - szczegóły znajdziesz w README poszczególnych submodułów. Miłego kodowania! 💻
