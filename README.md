[contact.html](https://github.com/user-attachments/files/32160057/contact.html)
[index.html](https://github.com/user-attachments/files/32160058/index.html)[garden-view-155.html](https://github.com/user-attachments/files/32160064/garden-view-155.html)
[highvill-ishym-181.html](https://github.com/user-attachments/files/32160065/highvill-ishym-181.html)[style.css](https://github.com/user-attachments/files/32160301/style.css)
<img width="2000" height="1125" alt="Living_room_013_0000" src="https://github.com/user-attachments/assets/8e26c330-bb04-4589-b546-07ea01790f34" />
<img width="2000" height="1125" alt="Living_room_012_0000" src="https://github.com/user-attachments/assets/8012cce1-fb4b-46cb-8fdb-3256f38250fc" />
<img width="1601" height="2000" alt="Living_room_011_0000" src="https://github.com/user-attachments/assets/a8603a3a-fdfd-4933-a13f-cb7886d733ee" />
<img width="2000" height="1125" alt="Living_room_010_0000" src="https://github.com/user-attachments/assets/a800938e-0a3f-40ca-8e03-d87509796591" />
<img width="1599" height="2000" alt="Living_room_009_0000" src="https://github.com/user-attachments/assets/f9af0849-ec35-4c1d-b96f-aec81def5dac" />
<img width="1599" height="2000" alt="Living_room_008_0000" src="https://github.com/user-attachments/assets/10d25e0f-8eea-4a38-a0b5-fa18e85ee2b8" />
<img width="1600" height="2000" alt="Living_room_007_0000" src="https://github.com/user-attachments/assets/ca3a8f34-c6ce-4001-96e4-943233fd29b7" />
<img width="1600" height="2000" alt="Living_room_006_0000" src="https://github.com/user-attachments/assets/0fa4e9cd-ad90-4bb2-b5bd-16542ff4aee1" />
<img width="1600" height="2000" alt="Living_room_005_0000" src="https://github.com/user-attachments/assets/8001fc2f-3c45-4855-9737-75c85d00b21e" />
<img width="1599" height="2000" alt="Living_room_004_0000" src="https://github.com/user-attachments/assets/8d892ecb-9c95-4067-a044-090ced2dcaa0" />
<img width="1599" height="2000" alt="Living_room_003_0000" src="https://github.com/user-attachments/assets/8a280993-5808-46a7-9223-ddcc10bf02e8" />
<img width="1600" height="2000" alt="Living_room_002_0000" src="https://github.com/user-attachments/assets/b4177cde-3447-4ad6-93b9-3c98f989df7d" />
<img width="1599" height="2000" alt="Living_room_001_0000" src="https://github.com/user-attachments/assets/93f8ca03-2270-46ca-997b-498176dad113" />
<img width="1600" height="2000" alt="0210" src="https://github.com/user-attachments/assets/9793e4cc-07af-4af7-ab3b-374580b93d8c" />
<img width="1600" height="2000" alt="019" src="https://github.com/user-attachments/assets/798c521c-929e-40d5-ab1d-f0062ad0af33" />
<img width="1600" height="2000" alt="018" src="https://github.com/user-attachments/assets/0c6b7984-0992-4e81-bc30-d7aeb574b03a" />
<img width="1600" height="2000" alt="016" src="https://github.com/user-attachments/assets/184a3365-6663-447e-abb3-25859a950b6c" />
<img width="1600" height="2000" alt="015" src="https://github.com/user-attachments/assets/8fea6f7d-f4fc-48eb-aa3c-177898f2cebc" />
<img width="1600" height="2000" alt="014" src="https://github.com/user-attachments/assets/f4a51afa-e4f5-4535-8a13-2542e253641c" />
<img width="1600" height="2000" alt="013" src="https://github.com/user-att@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500&display=swap');

:root {
  --bone: #0e0d0c;
  --ink: #f2f0ec;
  --muted: #8a8579;
  --hairline: #2b2926;
  --bronze: #b3a087;
}

* { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  background: var(--bone);
  color: var(--ink);
  font-family: 'Inter', -apple-system, sans-serif;
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
}

a { color: inherit; text-decoration: none; }

img {
  display: block;
  width: 100%;
  height: auto;
}

/* ---------- Header ---------- */

.site-header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 50;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 28px 5vw;
  color: #fff;
  mix-blend-mode: difference;
}

.wordmark {
  font-family: 'Inter', sans-serif;
  font-weight: 300;
  font-size: 17px;
  letter-spacing: 0.08em;
}

.site-nav {
  display: flex;
  gap: 36px;
  font-size: 14px;
}

.site-nav a {
  border-bottom: 1px solid transparent;
  padding-bottom: 2px;
  transition: border-color 0.25s ease;
}

.site-nav a:hover { border-color: currentColor; }

/* ---------- Home hero ---------- */

.hero {
  position: relative;
  height: 100vh;
  min-height: 560px;
  overflow: hidden;
}

.hero img {
  height: 100%;
  object-fit: cover;
}

.hero-caption {
  position: absolute;
  left: 5vw;
  bottom: 48px;
  color: #fff;
  font-family: 'Inter', sans-serif;
  font-weight: 200;
  font-size: clamp(20px, 2.6vw, 30px);
  letter-spacing: 0.01em;
  max-width: 640px;
  line-height: 1.4;
}

/* ---------- Project grid ---------- */

.grid {
  padding: 120px 5vw 100px;
}

.grid-row {
  display: grid;
  gap: 4px;
  margin-bottom: 4px;
}

.grid-row.split { grid-template-columns: 1.4fr 1fr; }
.grid-row.single { grid-template-columns: 1fr; }

.tile {
  position: relative;
  overflow: hidden;
  aspect-ratio: 4 / 3;
}

.grid-row.single .tile { aspect-ratio: 21 / 9; }

.tile img {
  height: 100%;
  object-fit: cover;
  transition: transform 1.1s ease;
}

.tile:hover img { transform: scale(1.035); }

.tile-label {
  position: absolute;
  left: 24px;
  bottom: 22px;
  color: #fff;
  font-family: 'Inter', sans-serif;
  font-weight: 300;
  font-size: 16px;
  letter-spacing: 0.03em;
}

/* ---------- Project detail ---------- */

.project-intro {
  padding: 160px 5vw 60px;
  border-bottom: 1px solid var(--hairline);
  margin-bottom: 60px;
}

.project-title {
  font-family: 'Inter', sans-serif;
  font-weight: 200;
  letter-spacing: 0.01em;
  font-size: clamp(28px, 4.5vw, 48px);
  margin: 0 0 8px;
}

.project-back {
  font-size: 13px;
  color: var(--muted);
}

.project-gallery {
  display: flex;
  flex-direction: column;
  gap: 4px;
  padding-bottom: 100px;
}

.project-gallery img { width: 100%; }

/* ---------- Footer / contact ---------- */

.site-footer {
  padding: 80px 5vw 48px;
  border-top: 1px solid var(--hairline);
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 24px;
  font-size: 14px;
  color: var(--muted);
}

.site-footer a:hover { color: var(--ink); }

.contact-page {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 0 5vw;
}

.contact-page h1 {
  font-family: 'Inter', sans-serif;
  font-weight: 200;
  letter-spacing: 0.01em;
  font-size: clamp(26px, 4.5vw, 46px);
  margin-bottom: 32px;
}

.contact-lines a,
.contact-lines p {
  font-size: 16px;
  line-height: 2;
  margin: 0;
}

@media (max-width: 720px) {
  .grid-row.split { grid-template-columns: 1fr; }
  .site-nav { gap: 20px; }
}
achments/assets/3865e806-8920-4d54-9a45-2d2c29e915fa" />
<img width="1600" height="2000" alt="011" src="https://github.com/user-attachments/assets/a4139f92-550a-4dc9-9406-e4d64d89b2ca" />
<img width="1600" height="2000" alt="010" src="https://github.com/user-attachments/assets/44b5c67a-53e9-4b89-9f2a-c19b473339bc" />
<img width="2000" height="2500" alt="009" src="https://github.com/user-attachments/assets/493840a9-3d23-4bba-9cdb-502582f600d2" />
<img width="1600" height="2000" alt="06" src="https://github.com/user-attachments/assets/a4ee3a8e-7155-4dd7-ace3-ad061fbaaba3" />
<img width="1600" height="2000" alt="05" src="https://github.com/user-attachments/assets/4624bb61-b16f-46de-832c-ce5afc4846b3" />
<img width="1600" height="2000" alt="004" src="https://github.com/user-attachments/assets/8168bc3f-4d9f-4e8c-acf1-eb5510378cc9" />
<img width="1600" height="2000" alt="02" src="https://github.com/user-attachments/assets/a03b7f18-85ee-4fb1-bfca-bfa9cc29e088" />
<img width="1600" height="2000" alt="01" src="https://github.com/user-attachments/assets/ee37932b-8c5b-4d4f-a153-317d8601d967" />
<img width="1600" height="2000" alt="0210" src="https://github.com/user-attachments/assets/8915175d-f8d1-4f80-9ae6-82a9ba1031d9" />
<img width="1600" height="2000" alt="019" src="https://github.com/user-attachments/assets/34cf5e78-7fea-4280-955a-f31a0e80d218" />
<img width="1600" height="2000" alt="018" src="https://github.com/user-attachments/assets/72ffd158-7356-4b67-898e-55f63eb0b0d5" />
<img width="1600" height="2000" alt="016" src="https://github.com/user-attachments/assets/4d2e72fc-6499-443d-88a4-400e80269edd" />
<img width="1600" height="2000" alt="015" src="https://github.com/user-attachments/assets/4261a792-a43e-4089-9930-d5fb45e50427" />
<img width="1600" height="2000" alt="014" src="https://github.com/user-attachments/assets/8cbbbb6d-b9e5-4063-9e38-3ea60b0705ad" />
<img width="1600" height="2000" alt="013" src="https://github.com/user-attachments/assets/a8f94b0a-7a72-442d-911d-50588aafc9af" />
<img width="1600" height="2000" alt="011" src="https://github.com/user-attachments/assets/3a26be0f-d69e-4f97-9304-a2fb47e75d8e" />
<img width="1600" height="2000" alt="010" src="https://github.com/user-attachments/assets/f5903ca9-c34d-494b-95a1-b7d1c26f0d3a" />
<img width="2000" height="2500" alt="009" src="https://github.com/user-attachments/assets/10f0583d-ef71-4450-9087-ae11d3cca641" />
<img width="1600" height="2000" alt="06" src="https://github.com/user-attachments/assets/7be9f9ed-a6a4-4acf-a668-842f24210cd1" />
<img width="1600" height="2000" alt="05" src="https://github.com/user-attachments/assets/167d410c-ff83-401f-9d00-dfe4ec6a5edc" />
<img width="1600" height="2000" alt="004" src="https://github.com/user-attachments/assets/9515b96f-b6f9-4b6e-bde2-d47962c1050e" />
<img width="1600" height="2000" alt="02" src="https://github.com/user-attachments/assets/3b18139b-4f20-43ec-9377-e4b0bb1099fd" />
<img width="1600" height="2000" alt="01" src="https://github.com/user-attachments/assets/2b967d23-b1ce-4d41-bb95-88f3bb133600" />
[lumiere-250.html](https://github.com/user-attachments/files/32160066/lumiere-250.html)
