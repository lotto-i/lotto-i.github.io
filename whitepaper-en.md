---
layout: default
title: "[World’s First External Public Verification · Public Verification Chain] LOTTOi Public Result Verification Whitepaper (English Version)"
permalink: /whitepaper-en.html
---

# [World-First-Level External Public Verification Framework] [LOTTOi](https://www.lottoi.kr) Result Public Verification Whitepaper
*(LOTTOi Public Verification Framework Whitepaper – EN)*

---

> **Since 2025. 02. 08.**  
> [LOTTOi](https://www.lottoi.kr) has applied a Google-based external public verification method since February 8, 2025. Under this method, generated numbers are not kept only inside the internal system, but are recorded in an external public document before the draw.
>
> Since January 29, 2026, LOTTOi has also operated an external public verification framework in which the Google document URL for each round is first fixed on GitHub before the draw. This allows anyone to check whether the verification URL disclosed after the draw was arbitrarily changed later.
>
> In this whitepaper, “world-first-level” does not refer to the entire lottery service, winning probability, prediction performance, profit, or result guarantee.  
> It refers to LOTTOi’s judgment regarding a public verification structure in which generated numbers are recorded externally in a Google document before the draw, the corresponding Google document URL is pre-fixed on GitHub, and the two records can be cross-checked after the draw.
>
> Based on publicly available web research, LOTTOi has not identified an identical prior case to date. For this reason, LOTTOi regards this structure as a world-first-level external public verification framework.

---

## 1. Document Overview

[LOTTOi](https://www.lottoi.kr) designs and operates a public verification method that records pre-draw data in an external public document so that anyone can compare the prior existence of generated numbers with round results.

Since February 8, 2025, LOTTOi has applied a Google-based external public verification method.  
>The basic principle of this method is that generated numbers are not stored only inside the internal system, but are recorded in an external public document before the draw.

Since January 29, 2026, LOTTOi has strengthened its verification standard by operating an external public verification framework in which the Google document URL for each round is first fixed on GitHub before the draw.

LOTTOi’s current public verification framework consists of two core standards.

1. The actual generated-number record is stored in a Google document.
2. The corresponding Google document URL is first fixed on GitHub before the draw.

This allows anyone, after the draw, to check whether the disclosed Google document URL was arbitrarily changed later, and to compare it with the actual record inside the Google document.

This whitepaper explains LOTTOi’s public verification principles, operating standards, the roles of Google documents and GitHub, and the scope and limitations of the phrase “world-first-level external public verification framework.”

---

## 2. Scope of the Phrase “World-First-Level”

LOTTOi does not use the phrase “world-first-level” to refer to the entire lottery service or to lottery prediction performance.

In this whitepaper, “world-first-level” refers to the following public verification structure.

First, generated numbers are recorded in an external public document such as a Google document before the draw, so that anyone can directly verify the record afterward regardless of whether they used the service.

Second, the Google document URL that contains the actual generated-number record is first fixed on GitHub before the draw, so that anyone can check through GitHub commit history whether the verification URL disclosed after the draw was changed later.

Third, the actual generated-number record in the Google document and the pre-fixed URL record on GitHub can be cross-checked together, allowing anyone to review the existence of the pre-draw record and whether any post-draw changes occurred.

Based on publicly available web research, LOTTOi has not identified an identical prior case to date. For this reason, LOTTOi regards the above structure as a world-first-level external public verification framework.

However, this phrase does not imply winning probability, prediction performance, profit, or result guarantee.  
>It is a judgment about a public verification design method that combines pre-draw records with an external verification standard.

---

## 3. Key Definitions

### 3-1. External Public Verification

External public verification is a method designed so that anyone can directly check whether generated numbers were recorded in an external public document before the draw, and whether the record was changed after the draw.

LOTTOi does not keep generated numbers only inside its internal system. It records them in an external public document before the draw so that post-draw verification is possible.

### 3-2. Public Verification Framework

A public verification framework is the overall structure that allows anyone to confirm, through external records, when, where, and under what standard a pre-draw record was created.

[LOTTOi’s public verification framework](https://www.lottoi.kr) separates the roles of Google documents and GitHub.

The Google document stores the actual generated-number record.  
GitHub records the corresponding Google document URL before the draw.

Therefore, after the draw, anyone can cross-check the Google document and GitHub records to verify whether the disclosed verification URL and generated-number record existed before the draw and whether any post-draw change occurred.

### 3-3. The Phrase “Public Verification Chain”

When this whitepaper uses the phrase “public verification chain,” it does not mean blockchain.

Here, “chain” means an external record verification structure in which Google document records and GitHub records are sequentially linked and cross-checked.

To reduce misunderstanding, this whitepaper primarily uses the phrases “public verification framework” or “cross-check public verification structure.”

---

## 4. Definition of External Public Verification

LOTTOi’s external public verification is a method designed so that anyone can directly check whether generated numbers were recorded in an external public document before the draw, and whether the record was changed after the draw.

In a typical internal-record method, a person who did not use the service cannot easily verify directly whether a given number actually existed before the draw.

To reduce this limitation, LOTTOi records generated numbers in an external public document and allows anyone to check the record and change history after the draw.

The core principles of external public verification are as follows.

- Generated numbers are not kept only inside the internal system.
- They are recorded in an external public document before the draw.
- After the draw, anyone can directly check the record regardless of whether they used the service.
- If a change occurs, the change time and changed content can be checked.

LOTTOi’s goal is not simply to prevent all modification of records.  
>The key point is to make it impossible to hide the time and content of a change if a change occurs.

Through this, LOTTOi reduces post-draw manipulation concerns and provides a verification standard that anyone can directly check regardless of service usage.

---

## 5. Overall Structure of the Public Verification Framework

LOTTOi’s public verification framework is structured as follows in actual operation.

```text
[Pre-creation of a round-specific public Google document]
└ Create the external public document in which actual generated-number records will be stored
└ The document creation time and permission-change history are recorded by the Google system
↓
[GitHub URL pre-fixing]
└ Record the Google document URL for the corresponding round on GitHub before the draw
└ The GitHub commit history can confirm the prior existence time of the URL
↓
[Generated-number finalization and system closing]
↓
[On draw day, after lottery purchase closing and before the draw begins]
└ Store generated-number data in the public Google document
└ The storage time and change history are recorded by the Google system
↓
[Lottery draw]
↓
[Post-draw verification by anyone]
└ Check on GitHub whether the Google document URL was fixed before the draw
└ Check the generated-number record and version history in the Google document
└ Check whether the data was modified after the draw
```

In this structure, Google documents and GitHub have separate roles.

The Google document is the standard for checking the actual generated-number record.  
GitHub is the standard for checking whether the corresponding Google document URL was fixed before the draw.

When both records are cross-checked, the existence of the pre-draw record and whether a post-draw change occurred can be confirmed more clearly.

---

## 6. Role of the Google Document

The Google document is the external public document in which the actual generated-number record is stored in LOTTOi’s public verification method.

LOTTOi creates a Google document for each round and records the required generated-number data in that document before the draw.

The Google document can provide the following information.

- Actual generated-number record
- Document creation time
- Data storage time
- Permission-change history
- Version history
- Whether post-draw modification occurred

The core role of the Google document is to provide a standard for confirming whether actual generated numbers were recorded in an external document before the draw.

After the draw, anyone can review the Google document record and version history to check whether the data existed before the draw or whether it was changed after the draw.

---

## 7. Role of GitHub

GitHub is not used merely as a record storage space.

In LOTTOi’s public verification framework, GitHub’s core role is to fix the Google document URL as an external record before the draw.

The Google document stores the actual generated-number record.  
GitHub stores the corresponding Google document URL before the draw.

Therefore, after the draw, anyone can directly check whether the Google document URL disclosed on the [LOTTOi official site](https://www.lottoi.kr) had already been recorded on GitHub before the draw.

GitHub records provide the following standards.

- Whether the Google document URL was recorded before the draw
- Whether that URL was later modified
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

The core verification standard is whether the Google document URL used as the final public verification standard was fixed on GitHub before the draw.

---

## 8. Google Document Permission Operation

LOTTOi operates Google documents so that pre-draw records and permission-change processes remain as external time-based records.

### 8-1. When the Document Is First Created

A round-specific Google document is created in advance.  
The document creation time and later permission-change records remain in the Google system.

### 8-2. Operation on Draw Day

After lottery purchase closing, the necessary permission transition and data storage are carried out to store generated-number data.

At this time, generated-number data is recorded in the Google document.  
The storage time and later change history can be checked through the version history of the Google document.

This operating method is designed to leave key moments where operator intervention may occur as external system records.

---

## 9. Post-Draw Verification Method

Anyone can directly check data integrity and the public verification standard through the following paths.

### 9-1. Checking GitHub Records

On GitHub, the following points are checked.

- Whether the Google document URL was recorded before the draw
- Whether the URL was later modified
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

GitHub’s core role is to provide an external reference point showing that the Google document URL was fixed before the draw.

### 9-2. Checking the Google Document

In the Google document, the following points are checked.

- Actual generated-number record
- Document creation time
- Data storage time
- Version history
- Whether post-draw modification occurred

In particular, it is important to check whether the record at the pre-draw reference time matches the result currently disclosed.

### 9-3. Cross-Checking the Two Records

GitHub and Google documents have separate roles.

GitHub is the standard for confirming whether the URL was fixed before the draw.  
The Google document is the standard for checking the actual generated-number record.

When both records are cross-checked, the existence of the pre-draw record and whether a post-draw change occurred can be confirmed more clearly.

---

## 10. Standards Regarding Modifiability and Change History

It is technically impossible to completely rule out the possibility that a public document may be modified after the draw.

However, in LOTTOi’s public verification framework, the important standard is not a claim that modification is absolutely impossible.  
>The important point is that, if a modification occurs, its trace cannot be hidden.

The Google document may retain the following information.

- Change time
- Changed content
- Change order
- Document version history

GitHub may retain the following information.

- Initial recording time of the Google document URL
- URL modification time
- Content before and after modification
- Commit history

Therefore, anyone can check through post-draw verification whether data was changed after the draw time.

LOTTOi does not claim that post-draw modification is impossible.  
>Instead, LOTTOi aims to provide a verification environment where post-draw modification can be checked through external records.

---

## 11. Operating Principles When a Modification Occurs

A GitHub record may be modified before the draw due to URL typos, document-link errors, or operating-input mistakes.

In such cases, LOTTOi considers the following standards important.

- Initial recording time
- Time when the modification occurred
- URL before modification
- URL after modification
- Whether the final confirmed URL existed before the draw
- Whether the modification was completed before the draw time

The core verification standard is whether the Google document URL used as the final public verification standard was fixed on GitHub before the draw.

If a URL change occurs after the draw, the verification standard and change details for that round must be checked separately.

---

## 12. Why LOTTOi Designed This Public Verification Method

LunaSG identified that, in lottery services, users often lack sufficient criteria to judge actual service value.

Many services explain results, but users do not always have enough standards to verify them directly.  
LOTTOi judged that photos, testimonials, and interviews alone make it difficult to confirm whether generated numbers actually existed before the draw.

For this reason, LOTTOi began looking for a method that could technically prove facts.

As a result, LOTTOi designed a public verification method that records generated numbers externally before the draw and allows the existence time and public standard of the record to be confirmed through external records.

This problem awareness became a major background for LunaSG’s design and operation of LOTTOi.

---

## 13. Technical Limitations and Operating Environment Notice

External network delays, Google or GitHub platform outages, permission-change delays, or other force majeure factors may temporarily delay record creation or public standard confirmation.

The purpose of this structure is not to claim a perfect system without delay.

The purpose is to ensure that, when delay or modification occurs, the fact remains in external records and can be checked afterward.

Because the actual creation time and change history remain on external platforms, their time relationship with the draw time can be checked afterward.

---

## 14. Prior-Case Research Criteria and First Comparison Table

LOTTOi uses the phrase “world-first-level external public verification framework” in a limited sense. It is not used as an absolute advertising claim, but as a statement that, based on publicly available web research, LOTTOi has not identified an identical prior case.

This section summarizes the first research criteria and comparison results for reviewing whether there are publicly available prior cases identical or similar to LOTTOi’s public verification framework.

However, the comparison target of this whitepaper is not every number-recommendation business or every lottery-draw system.  
The comparison target is **number-selection lottery number prediction, recommendation, and generation services or projects**.

For domestic similar services, this public whitepaper avoids naming individual companies directly to prevent the text from appearing as comparative advertising or as a public targeting of specific operators. Instead, domestic services are summarized under the category “Domestic lottery number recommendation services in general.” Individual service names, URLs, screenshots, and verification dates are kept in a separate internal research log.

---

### 14-1. Research Criteria

This first research was organized **as of May 2026**, and may be supplemented later as publicly available web data changes.

The research focuses on the following categories.

1. Lottery/lotto number prediction services
2. Lottery/lotto number recommendation services
3. Lottery/lotto number generation programs
4. Public GitHub lottery/lotto prediction code
5. Google Sheets or external-document-based lottery/lotto analysis cases
6. Number-selection lottery analysis and prediction apps
7. Patents or system ideas related to lottery prediction
8. Services claiming to publish or record prediction numbers before the draw
9. Domestic lottery number recommendation and analysis service types
10. Multilingual lottery number prediction and analysis projects

The following categories are excluded from direct comparison or are treated only as reference areas.

1. Blockchain lottery systems that verify the fairness of the lottery draw itself
2. General-purpose randomness verification structures such as Chainlink VRF or commit-reveal
3. Third-party draw and audit services such as RANDOM.ORG
4. General draw-verification systems for casinos, raffles, or promotions
5. Sports score prediction, stock-number recommendation, and general AI number-generation services

These excluded categories may be adjacent cases in the broad sense of “verifiability,” but they differ in purpose and structure from the market LOTTOi compares itself with: **number-selection lottery number recommendation/generation services**.

The main search terms used in the research are as follows.

| Language | Search Term |
|---|---|
| Korean | 로또 번호 공개 검증 |
| Korean | 로또 추천번호 추첨 전 공개 |
| Korean | 로또 번호 추첨 전 기록 |
| Korean | 로또 GitHub 검증 |
| Korean | 로또 구글 공개 검증 |
| Korean | 로또 예측번호 공개 기록 |
| Korean | 로또 번호 추천 검증 시스템 |
| Korean | 로또 번호 추천 서비스 |
| Korean | 로또 번호 생성 서비스 |
| Korean | 로또 번호 분석 서비스 |
| English | lotto prediction public verification |
| English | lottery prediction public verification |
| English | lottery numbers before draw public record |
| English | lottery prediction GitHub timestamp |
| English | Google Sheets lottery prediction GitHub |
| English | lottery number prediction proof before draw |
| English | verifiable lottery prediction system |
| English | timestamped lottery prediction |
| English | public lottery prediction record |
| English | lotto number generator verification |
| English | lottery number recommendation verification |
| Simplified Chinese | 彩票 预测号码 公开 验证 |
| Simplified Chinese | 彩票 预测 抽奖前 公开 |
| Simplified Chinese | 彩票 号码 公开记录 |
| Simplified Chinese | 彩票 预测 GitHub 验证 |
| Simplified Chinese | 彩票 Google 表格 预测 |
| Simplified Chinese | 彩票 预测 公开 时间戳 |
| Simplified Chinese | 彩票 号码 推荐 验证 系统 |
| Traditional Chinese | 彩券 預測號碼 公開 驗證 |
| Traditional Chinese | 彩券 預測 抽獎前 公開 |
| Traditional Chinese | 彩券 號碼 公開紀錄 |
| Traditional Chinese | 彩券 預測 GitHub 驗證 |
| Traditional Chinese | 彩券 Google 試算表 預測 |
| Japanese | ロト 予想番号 公開 検証 |
| Japanese | ロト 予想番号 抽選前 公開 |
| Japanese | 宝くじ 予想 検証 公開 |
| Japanese | ロト GitHub 検証 |
| Japanese | ロト Google スプレッドシート 予想 |
| Spanish | predicción lotería verificación pública |
| Spanish | números de lotería antes del sorteo registro público |
| Spanish | predicción lotería GitHub |
| Spanish | predicción lotería hoja de cálculo Google |
| French | prédiction loto vérification publique |
| French | numéros loto avant tirage registre public |
| French | prédiction loterie GitHub |
| French | prédiction loto feuille Google |
| German | Lotto Vorhersage öffentliche Verifizierung |
| German | Lottozahlen vor Ziehung öffentlicher Nachweis |
| German | Lotto Vorhersage GitHub |
| German | Lotto Vorhersage Google Tabelle |

---

### 14-2. Criteria for Identical Cases

In this whitepaper, an “identical case” does not simply mean a case that predicts lottery numbers, publishes draw results, or uploads program code to GitHub.

Also, the comparison target of this whitepaper is not every number-recommendation business.  
The comparison target is **the field of number-selection lottery number recommendation/generation services**.

To be considered identical to LOTTOi, a case must satisfy all of the following conditions.

1. It must be a service or project that provides recommended or generated numbers for a number-selection lottery.
2. The recommended or generated numbers must be finalized before the draw.
3. Those numbers must not be stored only in an internal system, but must remain in an external public record.
4. After the draw, anyone must be able to directly check that record.
5. The time of recording or whether a post-draw change occurred must be checkable through an external record.
6. The actual number record and the external reference point pointing to that record must be cross-checkable.
7. Prior existence and post-draw change status must be checkable through different external systems, such as Google documents and GitHub commit history.

LOTTOi’s reference structure is as follows.

> **Google Document**  
> Actual generated-number record
>
> **GitHub**  
> The corresponding Google document URL is fixed before the draw
>
> **Post-Draw Verification**  
> Cross-check the Google document record and GitHub commit history

Therefore, a simple prediction codebase, simple number generator, statistical analysis tool, or post-draw result disclosure service may be classified as a similar case, but it is not considered identical unless all of the above conditions are satisfied.

---

### 14-3. First Similar-Case Comparison Table

This comparison table focuses on **number-selection lottery number prediction, recommendation, and generation services or projects**.

Blockchain lotteries, Chainlink VRF, commit-reveal, RANDOM.ORG, and similar cases are adjacent technologies related to draw fairness or general-purpose randomness verification. However, they differ in purpose from LOTTOi’s service structure, which verifies the prior existence and post-draw change status of recommendation or generated numbers received by users. Therefore, they are excluded from this comparison table.

Domestic similar services are categorized as “Domestic lottery number recommendation services in general” rather than being named individually in this public whitepaper. This is intended to reduce unnecessary misunderstanding that could arise from naming a specific company or appearing to make comparative advertising.

| Category | Case / Type | Confirmed Features | Similarity to LOTTOi | Difference from LOTTOi | Identical Case? |
|---|---|---|---|---|---|
| Reference Case | LOTTOi | Generated numbers are recorded in a Google document, the Google document URL is fixed on GitHub before the draw, and both records are cross-checked after the draw | Pre-draw external record, post-draw change-history check, publicly verifiable structure | Reference case | Reference case |
| Domestic lottery number recommendation services in general | Lottery number recommendation and analysis services | Domestic service type that provides past winning-number analysis, number recommendation, statistics, and in some cases result disclosure | Similar in that it provides lottery number recommendation and analysis | No confirmed structure in which recommended numbers are recorded in an external public document before the draw and the reference point is pre-fixed on GitHub for post-draw cross-checking | Not identical |
| GitHub prediction code | TensorFlow Lottery Prediction | RNN/LSTM-based lottery number prediction code repository | Similar topic of lottery number prediction | It publicly shares prediction code, but does not provide a structure for pre-draw external record keeping and post-draw change verification of recommended numbers | Not identical |
| GitHub prediction code | Lottery Prediction with Machine Learning | Machine-learning project for predicting Mega Millions and Powerball numbers | Similar topic of lottery/lotto number prediction | Focused on code and models, and does not fix prediction results in an external record before the draw | Not identical |
| GitHub prediction code | Loto_Ai_Prediction | Historical data collection, LSTM model training, and prediction-number output structure | Similar in using AI-based number prediction | No confirmed pre-draw external public record or GitHub URL pre-fixing verification framework | Not identical |
| GitHub prediction code | LotteryPrediction | Repository related to lottery prediction programs or prediction methods | Similar topic of number prediction | Does not fix service operation results in a public document before the draw | Not identical |
| GitHub prediction code | Lottery-Predict | Flask-based lottery number prediction web app | Similar in number prediction and web-service format | No pre-draw external record, change-history check, or cross-check structure | Not identical |
| GitHub prediction code | National Lottery Generator | App structure that analyzes past draw data and generates numbers | Similar in past-data-based number generation | Does not verify recommended numbers through an external public document and GitHub commits | Not identical |
| GitHub analysis app | Mega-Sena Analyzer | Brazilian Mega-Sena analysis app that imports past data and performs statistical analysis and strategy generation | Similar in statistical lottery analysis | Does not provide pre-draw external record keeping and post-draw change verification of recommendation results | Not identical |
| General prediction site | UK49s / SA Lotto Prediction-type sites | Sites that analyze past data or use Excel/Google Sheets to create heat maps and related analysis | Some similarity in using Google Sheets or statistical analysis | Google Sheets is used as an analysis tool, not as a pre-draw record with GitHub cross-checking | Not identical |
| Mobile app | Lotto Prediction Android app types | Apps that provide lottery number prediction or generation functions | Similar in number recommendation or prediction | No confirmed public verification framework, external record, or change-history cross-check structure | Not identical |
| Spreadsheet product | Lotto prediction spreadsheet type | Excel or Google Sheets templates used for number analysis or prediction | Similar in using Google Sheets | Personal analysis tools, not a pre-draw external public record with GitHub pre-fixing | Not identical |
| Patent / idea | KR20090129245A, Lottery Prediction Winning Number Provision System | Patent related to a lottery prediction service system that provides multiple prediction-number combinations | Similar in providing predicted number combinations | Does not include an external public document record, GitHub commit history, or post-draw change verification structure | Not identical |
| Chinese-language prediction code | LottoProphet | Chinese lottery prediction project for SSQ and DLT using deep learning and conditional random fields | Similar in lottery number prediction and analysis | Closer to a prediction model or analysis app; no structure where recommended numbers are recorded in a Google document before the draw and the URL is pre-fixed on GitHub | Not identical |
| Chinese-language analysis app | Lottery Analysis / 彩票数据分析 | Python/Streamlit project that collects and analyzes Chinese Welfare Lottery and Sports Lottery data and provides AI prediction features | Similar in lottery data collection, statistical analysis, and AI prediction | Analysis and prediction platform; not an external pre-draw record and GitHub cross-check verification framework | Not identical |
| Chinese-language prediction system | gitmen-lottery / 彩票预测系统 | Web-service-type project using FastAPI, MySQL, Telegram integration, historical Chinese lottery lookup, prediction, and statistics | Similar in lottery prediction, statistics, and lookup system | No confirmed structure where prediction results are recorded in an external public document and verified through GitHub commit history | Not identical |
| Chinese-language AI prediction code | Double-Color-Ball-AI | Chinese AI prediction project for Double Color Ball using multiple AI models and historical-data strategies | Similar in AI-based lottery number prediction | Focused on AI prediction generation and data validation, not on a Google document record and GitHub URL pre-fixing public verification framework | Not identical |
| Japanese-language prediction code | numbers4_lstm | Japanese project attempting to predict Numbers4 winning numbers using LSTM and neural networks | Similar in number-selection lottery prediction | Prediction-code centered; no pre-draw external record or post-draw change verification structure | Not identical |
| Japanese-language analysis code | Rosyuku/loto6 | GitHub project for analyzing or interpreting Japan’s Loto 6 | Similar in Loto number analysis | Closer to analysis code or material disclosure, not a Google document and GitHub cross-check verification framework | Not identical |
| Japanese-language analysis content | Loto 6 statistical analysis tools and prediction content | Statistical analysis and prediction-support content or tools for Loto 6, Mini Loto, Loto 7, etc. | Similar in Japanese lottery number analysis and prediction | Content or analysis-tool type; does not fix service recommendation numbers in an external document before the draw | Not identical |
| Spanish-language prediction code | ojaviva/lottery | Spanish-language project aimed at predicting future lottery winning numbers using machine learning | Similar in lottery number prediction models | Focused on model development and prediction, not on pre-draw external public records or post-draw change-history verification | Not identical |
| Spanish-language prediction tool | KinielaGPT | Prediction tool using match data, probabilities, and contextual analysis for Quiniela prediction | Similar as a prediction model or recommendation tool | Sports/Quiniela prediction tool; not a pre-draw external verification structure for lottery recommendation numbers | Not identical |
| French/European prediction code | Loto_Ai_Prediction | Project using machine learning such as LSTM to predict Loto numbers | Similar in Loto number prediction and historical-data learning | Prediction-code centered; does not verify pre-draw recommendation numbers through Google documents and GitHub records | Not identical |
| Multilingual GitHub prediction group | GitHub lottery-prediction / loto topic repositories | Numerous repositories in different languages related to lottery, loto, lotto prediction, and analysis | Shows that lottery prediction code and analysis attempts exist globally | Most are limited to code, models, or analysis disclosure, with no confirmed external-record cross-check structure for prior existence and post-draw changes | Not identical |

※ Case names, repository names, search result screenshots, and access URLs for this comparison table are stored in a separate research log.  
※ Detailed comparison materials for domestic similar services are stored in a separate internal research log to avoid publicly naming specific operators.

---

### 14-4. Summary of First Research Results

In the first public web research, LOTTOi did not identify a structure completely identical to its own.

In particular, no case was identified that satisfies all of the following conditions.

1. It provides recommended or generated numbers for a number-selection lottery.
2. The recommended or generated numbers are finalized before the draw.
3. The actual recommended or generated numbers are recorded in a Google document as an external public record.
4. The corresponding Google document URL is first fixed on GitHub before the draw.
5. After the draw, anyone can cross-check the Google document record and GitHub commit history.
6. Through this, anyone can check the prior existence and post-draw change status of the recommended numbers.

The identified similar cases fall broadly into four categories.

First, domestic and international lottery number recommendation and analysis service types.  
These may provide past winning-number analysis, number recommendations, statistics, and in some cases result disclosure, but no structure was confirmed in which recommended numbers are recorded in an external document before the draw and a reference point is pre-fixed on GitHub for post-draw cross-checking.

Second, lottery number prediction code.  
These mostly focus on predicting or generating numbers through AI, LSTM, machine learning, or statistical analysis.

Third, lottery number analysis apps or web apps.  
These provide past winning-number data analysis, number recommendation, number generation, statistical visualization, and similar features.

Fourth, multilingual prediction and analysis projects from Chinese, Japanese, Spanish, French, and other language regions.  
These are similar in that they relate to number-selection lottery prediction or analysis, but no pre-draw external public record and post-draw change-history verification structure was confirmed.

Therefore, under the first research criteria, LOTTOi’s structure is distinguished from existing similar cases as follows.

> **Existing similar cases**  
> Lottery number recommendation, number generation, statistical analysis, AI models, and prediction-code disclosure
>
> **LOTTOi**  
> A structure that cross-checks, through an external public document and GitHub commit history,  
> whether recommended numbers actually existed before the draw  
> and whether they were changed after the draw

---

### 14-5. Limitations of the Research Results

This research is a first-stage review based on publicly available web data.

It has the following limitations.

1. Private services, closed communities, and paid members-only materials may be excluded from the scope of review.
2. Past services or closed websites not exposed in search engines may be omitted.
3. This research does not completely cover every national language region.
4. The review centered on publicly accessible materials including Google, GitHub, GitLab, patent materials, and search terms in Korean, English, Chinese, Japanese, Spanish, French, and German.
5. For domestic similar services, the review used service-type categories such as lottery number recommendation and analysis services rather than publicly naming specific operators. Individual service names, URLs, screenshots, and related materials are stored in a separate internal research log.
6. The phrase “world-first-level” is used only in a limited sense based on the judgment that no identical prior case was identified under this research standard.
7. Even though Chinese, Japanese, and European-language search terms were included, this does not completely cover each country’s closed services, app-market internal descriptions, paid materials, or deleted past pages.

Therefore, LOTTOi does not use “world first” as an absolute or definitive expression. Instead, it limits the expression as follows.

> In the field of number-selection lottery number recommendation/generation services,  
> LOTTOi operates a Google-GitHub cross-check public number verification structure  
> for which no identical prior case has been identified under publicly available web research,  
> and regards it as a world-first-level external public verification framework.

This expression does not mean winning probability, prediction performance, profit, or result guarantee.  
It is a judgment regarding a public verification design method that combines pre-draw records with an external verification standard.

---

## 15. Expandability of the Public Verification Framework

LOTTOi’s current public verification framework is centered on Google document records and GitHub URL pre-fixing.

This whitepaper explains the operating standards and verification methods of the currently applied public verification framework.

Future expansion and application methods will be reviewed based on operational stability, user comprehensibility, and the reliability of external records.

If expansion is implemented, LOTTOi will continue to improve the public verification framework based on the reliability of external records, user verifiability, and operational stability.

---

## 16. Scope and Limitations of This Document

This whitepaper was prepared for the following purposes.

- Explaining a structure that allows confirmation of the prior existence of generated-number records
- Explaining operating standards for the external public verification method
- Explaining the operating method of the public verification framework
- Separating the roles of Google documents and GitHub
- Providing a standard that anyone can directly verify regardless of service usage
- Explaining the technical design intended to reduce post-draw manipulation concerns
- Explaining the scope and limitations of the phrase “world-first-level”

This document does not guarantee winning probability, prediction performance, profit, or results.  
It must not be interpreted as an investment, prediction, or guarantee document under any circumstances.

Also, the phrase “world-first-level” is LOTTOi’s judgment regarding a structure for which no identical prior case has been identified under publicly available web research. It is not a statement that definitively proves the nonexistence of every private case in the world.

---

## 17. Closing

[LOTTOi](https://www.lottoi.kr) intended to leave a record standard that can verify results before talking about the results themselves.

The purpose of publishing LOTTOi’s public verification whitepaper is one thing.

LOTTOi aims for the public verification framework it designed to become a more transparent standard for lottery services and to contribute to a lottery market with fewer manipulation concerns.

LOTTOi records generated numbers externally before the draw and operates a public verification framework that links those records again through an external public means for verification.

LOTTOi hopes this model will go beyond a differentiating factor for one service and become a trust standard for lottery-related services as a whole.

For a transparent environment that helps users make rational choices, LOTTOi will continue to treat record standards as important.

---

## Summary

> **The Google document stores the actual generated-number record.**  
> **GitHub first fixes the Google document URL before the draw.**  
> **After the draw, anyone can cross-check the two records to verify whether post-draw changes occurred.**

LOTTOi regards this structure, for which no identical prior case has been identified under publicly available web research, as a world-first-level external public verification framework.

---

## Key Timeline

| Date | Details |
|---|---|
| 2025. 02. 08. | Applied the Google-based external public verification method |
| 2026. 01. 29. | Applied the external public verification framework that first fixes the Google document URL on GitHub before the draw |
| 2026. 02. 19. | Published the public verification whitepaper |

---

## Short Introduction

[LOTTOi](https://www.lottoi.kr) has applied a Google-based external public verification method since February 8, 2025.

Since January 29, 2026, LOTTOi has operated an external public verification framework in which the Google document URL is first fixed on GitHub before the draw, allowing anyone to cross-check the Google document record and GitHub commit history after the draw.

Based on publicly available web research, LOTTOi has not identified an identical prior case, and therefore regards this structure as a world-first-level external public verification framework.

