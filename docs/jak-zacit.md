# Jak začít

## 1. Vytvořte si vlastní repozitář z tohoto template

1. Klikněte na tlačítko **"Use this template"** → **"Create a new repository"** (nahoře na stránce repa).
2. Pojmenujte repozitář (např. `portfolio-programovani`).
3. Nastavte jako **Public** (nebo Private, pokud nechcete, aby to viděli ostatní).
4. Klikněte **"Create repository"**.

## 2. Naklonujte si repozitář pomocí Visual Studia

**Varianta A – vestavěný Git klient ve Visual Studiu (doporučeno):**
1. Otevřete Visual Studio.
2. Na úvodní obrazovce zvolte **Clone a repository** (případně **Git → Clone Repository** v horním menu, pokud už máte VS otevřené).
3. Vložte URL adresu svého repozitáře (najdete ji na GitHubu pod zeleným tlačítkem **Code**), např. `https://github.com/VASE-JMENO/NAZEV-REPA.git`.
4. Vyberte složku na disku, kam se má repozitář naklonovat, a klikněte **Clone**.
5. Visual Studio si repozitář rovnou otevře a propojí – v okně **Git Changes** pak uvidíte přehled změn a odtud budete i commitovat a pushovat.

**Varianta B – příkazová řádka:**
```bash
git clone https://github.com/VASE-JMENO/NAZEV-REPA.git
```

## 3. Otevřete si dummy projekt

- Otevřete složku `1_rocnik/00_dummyProject` jako projekt.
- Vyzkoušejte, že jde projekt spustit (F5).

## 4. První commit

1. Upravte nějaký soubor (klidně jen zkuste, jestli commit funguje).
2. Ve Visual Studiu otevřete okno **Git Changes** (View → Git Changes), napište zprávu commitu a klikněte **Commit All**, poté **Push**.
3. Zkontrolujte na GitHubu, že se změna objevila.

## 5. Nový projekt = nová složka

Když dostanete nové zadání, vytvořte si ve Visual Studiu nový projekt přímo do příslušné složky ročníku ve formátu `číslo_nazevProjektu`, např. `01_helloworld`. Protože je projekt uložený uvnitř naklonovaného repozitáře, Visual Studio ho automaticky rozpozná jako součást repozitáře – stačí ho pak stejným způsobem commitnout a pushnout a objeví se na GitHubu.
