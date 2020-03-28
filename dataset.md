# Supported Datasets in Fukan System

Fukan System supports the following datasets and fields as of
[20190324.1](https://fukansystem.github.io/).

## Derwent Innovation (Thomson Innovation)

- `Cited Refs - Patent` (`引用文献 - 特許`)
- `Publication Number` (`公報番号`)
- `Publication Year`, `Publication Date` (`公報発行年`, `公報発行日`)
- Optional fields
  - `Abstract - DWPI`, `Abstract` (`抄録 - DWPI優位性`, `抄録`)
  - `Application Country` (`出願国`)
  - `Assignee/Applicant` (`譲受人/出願人`)
  - `Claims` (`請求項`)
  - `DWPI Family Members` (`DWPI ファミリーメンバー`)
  - `IPC - Current - DWPI` (`IPC - 最新 - DWPI`)
  - `Title - DWPI`, `Title` (`タイトル - DWPI`, `タイトル`)

## KAKEN

- 研究概要(採択時) (`Outline of Annual Research Achievements`, `研究実績の概要`)
- `Project/Area Number` (`研究課題/領域番号`)
- `Project Period (FY)` (`研究期間 (年度)`)
- Optional fields
  - `Keywords` (`キーワード`)
  - `Principal Investigator`, `Research Fellow`, `Foreign Research Fellow`
    (`研究代表者`, `特別研究員`, `外国人特別研究員`)
  - `Research Category` (`研究種目`)
  - `Research Field` (`研究分野`)
  - `Research Institution` (`研究機関`)
  - `Research Project Title` (`研究課題名`)

## PubMed

- `CommentsCorrectionsList`, `ReferenceList`
- `PMID`
- `PubmedArticle`
- `PubDate`
- Optional elements
  - `Abstract`
  - `ArticleTitle`
  - `AuthorList`
  - `KeywordList`
  - `MedlinePgn`
  - `Title`
  - `Volume`

## Scopus

- `Authors` (`著者名`)
- `Page start` (`開始ページ`)
- `References` (`参考文献`)
- `Source title` (`出版物名`, `ジャーナル名`)
- `Volume` (`巻`)
- `Year` (`出版年`)
- Optional fields
  - `Abstract` (`抄録`)
  - `Affiliations` (`著者所属機関名`)
  - `Author Keywords` (`著者キーワード`)
  - `Cited by` (`被引用数`)
  - `Index Keywords` (`索引キーワード`)
  - `Title` (`タイトル`)

## Web of Science

- Source item author (`AU`)
- Beginning page (`BP`)
- Cited references (`CR`)
- Abbreviated 29-character source title (`J9`)
- Publication year (`PY`)
- Article title (`TI`)
- Volume (`VL`)
- Optional fields
  - Abstract (`AB`)
  - Author first name (`AF`)
  - Research addresses (`C1`)
  - Author keyword (`DE`)
  - KeyWords Plus (`ID`)
  - Cited reference count (`NR`)
  - Publication discipline (Subject category) (`SC`)
  - Times cited (`TC`)

## Web of Science Core Collection raw XML

- Addresses (`addresses`)
- Names (`names`)
- Publication information (`pub_info`)
- References (`references`)
- Titles (`titles`)
- Unique identifier (`UID`)
- Volume (`vol`)
- Optional
  - Abstracts (`abstracts`)
  - Identifiers (`identifiers`)
  - Keywords (`keywords`)
  - Languages (`languages`)
  - Normalized languages (`normalized_languages`)
  - Subject categories (`subjects`)