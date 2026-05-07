---
layout: default
title: "[World’s First External Public Verification · Public Verification Chain] LOTTOi Public Result Verification Whitepaper (English Version)"
permalink: /whitepaper-en.html
---

# [World-First-Level External Public Verification Framework] [LOTTOi](https://www.lottoi.kr) Public Result Verification Whitepaper
*(LOTTOi Public Verification Framework Whitepaper – EN)*

---

> **Since 2025. 02. 08.**  
> [LOTTOi](https://www.lottoi.kr) has applied a Google-based external public verification method since February 8, 2025, recording generated numbers in an external public document before the draw instead of keeping them only inside its internal system.
>
> Since January 29, 2026, LOTTOi has operated an external public verification framework that anchors each round’s Google document URL on GitHub before the draw, allowing anyone to check whether the verification URL disclosed after the draw was arbitrarily changed afterward.
>
> The term “world-first-level” in this whitepaper does not refer to lottery services as a whole, winning probability, prediction performance, or profit guarantees.  
> It refers to a public verification structure in which generated numbers are recorded in a Google document before the draw, the corresponding Google document URL is anchored on GitHub in advance, and the two records can be cross-checked after the draw.
>
> Based on public web research, LOTTOi has not identified an identical prior case to date, and therefore describes this structure as a world-first-level external public verification framework based on the research results and its operating structure.

---

## 1. Document Overview

[LOTTOi](https://www.lottoi.kr) designs and operates a public verification method that records pre-draw data in an external public document, so that anyone can compare the prior existence of generated numbers with the result of each lottery round.

LOTTOi has applied a Google-based external public verification method since February 8, 2025.  
The basic principle of this method is not to keep generated numbers only inside the internal system, but to record them in an external public document before the draw.

Since January 29, 2026, LOTTOi has operated an external public verification framework that further strengthens the verification standard by anchoring each round’s Google document URL on GitHub before the draw.

LOTTOi’s current public verification framework consists of the following two standards.

1. The actual generated number records are stored in a Google document.
2. The corresponding Google document URL is anchored on GitHub before the draw.

Through this structure, anyone can check whether the Google document URL disclosed after the draw was arbitrarily changed afterward, and compare it with the actual records in the Google document.

This whitepaper explains LOTTOi’s public verification principles, operating standards, the roles of Google documents and GitHub, and the scope and limitations of the expression “world-first-level external public verification framework.”

---

## 2. Why LOTTOi Designed This Public Verification Method

LunaSG focused on the possibility that, when reviewing lottery-related services, there may not be enough publicly verifiable standards for users to assess the actual value of a service.

In general, lottery-related services present their performance through various methods such as result explanations, reviews, images, and interviews.  
However, these methods alone may make it difficult for users to directly verify whether the generated numbers actually existed before the draw and whether the records were changed afterward.

For this reason, LOTTOi began reviewing ways to establish technically verifiable public verification standards.

As a result, LOTTOi designed a public verification method that records generated numbers in an external public document before the draw, and allows the existence time and public reference point of those records to be cross-checked through external records.

This awareness became a major background for LunaSG’s design and operation of LOTTOi.

---

## 3. Scope of the “World-First-Level” Expression

LOTTOi does not use the expression “world-first-level” to refer to lottery services as a whole or to prediction performance for winning numbers.

The expression “world-first-level” in this whitepaper refers to the following public verification structure.

First, generated numbers are recorded in an external public document such as a Google document before the draw, allowing anyone to check them afterward regardless of whether they use the service.

Second, the Google document URL containing the actual generated number records is anchored on GitHub before the draw, allowing anyone to check through GitHub commit history whether the verification URL disclosed after the draw was changed afterward.

Third, the actual generated number records in the Google document and the pre-draw URL anchoring record on GitHub can be cross-checked together, allowing anyone to review the existence of pre-draw records and whether post-draw changes occurred.

Based on public web research, LOTTOi has not identified an identical prior case to date, and therefore describes this structure as a world-first-level external public verification framework based on the research results and its operating structure.

The research standards and first-round comparison results for prior cases are explained separately in the later section, “Prior Case Research Standards and First-Round Comparison Table.”

However, this expression does not imply any guarantee of winning probability, prediction performance, profit, or results.  
It is an explanation of a public verification design method that combines pre-draw records with external verification standards.

---

## 4. Definitions of Key Terms

### 4-1. External Public Verification

External public verification is a method designed so that anyone can directly check whether generated numbers were recorded in an external public document before the draw, and whether those records were changed after the draw.

LOTTOi does not keep generated numbers only inside its internal system. It operates by leaving them in an external public document before the draw, so that post-draw verification is possible.

### 4-2. Public Verification Framework

A public verification framework refers to the overall structure configured so that anyone can check when, where, and under what standard a pre-draw record was made through external records.

The [LOTTOi public verification framework](https://www.lottoi.kr) separates the roles of Google documents and GitHub.

The actual generated number records are stored in a Google document.  
The corresponding Google document URL is recorded on GitHub before the draw.

Therefore, after the draw, anyone can cross-check the Google document and GitHub records to verify the prior existence of the disclosed verification URL and generated number records, as well as whether any post-draw changes occurred.

### 4-3. Meaning of the Term “Public Verification Chain”

When this whitepaper uses the expression “public verification chain,” it does not refer to blockchain.

The “chain” here refers to an external record verification structure in which Google document records and GitHub records are connected sequentially and can be cross-checked.

To reduce misunderstanding, this whitepaper generally uses the terms “public verification framework” or “cross-checkable public verification structure.”

---

## 5. Basic Principles of External Public Verification

LOTTOi’s external public verification is a method designed so that anyone can directly check whether generated numbers were recorded in an external public document before the draw, and whether those records were changed after the draw.

In a typical internal record system, it is difficult for anyone, regardless of whether they use the service, to directly confirm whether the numbers actually existed before the draw.

To reduce this limitation, LOTTOi records generated numbers in an external public document and allows anyone to check the records and change history after the draw.

The key principles of external public verification are as follows.

- Generated numbers are not kept only inside the internal system.
- Generated numbers are recorded in an external public document before the draw.
- After the draw, anyone can directly check the records regardless of whether they use the service.
- If a change occurs, the time and content of the change can be checked.

LOTTOi does not simply aim to prevent records from being modified.  
The key point is to make it impossible to hide the time and content of a change if a change occurs.

Through this, LOTTOi provides a verification standard that reduces post-draw manipulation concerns and allows anyone to check the records directly, regardless of whether they use the service.

---

## 6. Overall Structure of the Public Verification Framework

LOTTOi’s public verification framework is structured as follows based on actual operating standards.

```text
[Pre-creation of a Google public document for each round]
└ Create an external public document where actual generated number records will be stored
└ The document creation time and permission change history are recorded by Google systems
↓
[GitHub URL anchoring]
└ Record the Google document URL for the round on GitHub before the draw
└ The GitHub commit history allows verification of the URL’s pre-draw existence time
↓
[Generated numbers finalized and system closed]
↓
[On draw day, after lottery purchase closing and before the draw begins]
└ Store generated number data in the Google public document
└ The storage time and change history are recorded by Google systems
↓
[Lottery draw proceeds]
↓
[Post-draw verification by anyone]
└ Check on GitHub whether the Google document URL was anchored before the draw
└ Check generated number records and version history in the Google document
└ Check whether the data was modified after the draw
```

In this structure, Google documents and GitHub have different roles.

The Google document is the standard for checking the actual generated number records.  
GitHub is the standard for checking whether the corresponding Google document URL was anchored before the draw.

By comparing these two records together, the existence of pre-draw records and any post-draw changes can be verified more clearly.

---

## 7. Role of the Google Document

The Google document is the external public document where actual generated number records remain in LOTTOi’s public verification method.

LOTTOi creates a Google document for each round and records the necessary generated number data in that document based on the pre-draw standard.

The Google document allows the following items to be checked.

- Actual generated number records
- Document creation time
- Data storage time
- Permission change history
- Version history
- Whether any modification occurred after the draw

The core role of the Google document is to provide a standard for checking whether the actual generated numbers were recorded in an external document before the draw.

After the draw, anyone can review the records and version history of the Google document to check whether the data existed before the draw or whether it was changed after the draw.

---

## 8. Role of GitHub

GitHub is not used simply as a record storage location.

In the [LOTTOi public verification framework](https://www.lottoi.kr), the core role of GitHub is to anchor the Google document URL as an external record before the draw.

The actual generated number records are stored in a Google document.  
The corresponding Google document URL is recorded on GitHub before the draw.

Therefore, anyone can directly check whether the Google document URL disclosed on the LOTTOi site after the draw had already been recorded on GitHub before the draw.

GitHub records provide the following standards.

- Whether the Google document URL was recorded before the draw
- Whether the URL was modified later
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

The core verification standard is whether the Google document URL used as the final public verification standard was anchored on GitHub before the draw.

---

## 9. Google Document Permission Operation Method

LOTTOi operates Google documents so that pre-draw records and permission changes remain based on an external time standard.

### 9-1. When the Document Is First Created

A Google document for each round is created in advance.  
The document creation time and later permission change records remain in Google systems.

### 9-2. Operation on Draw Day

After lottery purchase closing, the necessary permission changes and data storage are carried out to store generated numbers.

At this time, the generated number data is recorded in the Google document.  
The storage time and later change history can be checked through the version history of the Google document.

This operation method is intended to record major points where operator intervention may occur in an external system.

---

## 10. Post-Draw Verification Method

Anyone can directly check the integrity of the data and the public verification standard through the following paths.

### 10-1. Checking GitHub Records

On GitHub, the following items can be checked.

- Whether the Google document URL was recorded before the draw
- Whether the URL was modified later
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

The core role of GitHub is to provide an external reference point where the Google document URL was anchored before the draw.

### 10-2. Checking the Google Document

In the Google document, the following items can be checked.

- Actual generated number records
- Document creation time
- Data storage time
- Version history
- Whether any modification occurred after the draw

In particular, it is important to check whether the record based on the pre-draw standard matches the result currently disclosed.

### 10-3. Comparing the Two Records

GitHub and Google documents have different roles.

GitHub is the standard for checking whether the URL was anchored in advance.  
The Google document is the standard for checking the actual generated number records.

By comparing these two records together, the existence of pre-draw records and any post-draw changes can be verified more clearly.

---

## 11. Standards for Modification Possibility and Change History

It is not technically possible to completely rule out the possibility that a public document may be modified after the draw.

However, the important standard in LOTTOi’s public verification framework is not a claim that modification is impossible.  
The important point is that if a modification occurs, the traces of that modification cannot be hidden.

The Google document may contain the following information.

- Change time
- Change content
- Change order
- Document version history

GitHub may contain the following information.

- Initial recording time of the Google document URL
- URL modification time
- Content before and after the modification
- Commit history

Therefore, anyone can verify afterward whether the data was changed after the draw time.

LOTTOi does not claim that post-draw modification is impossible.  
Instead, LOTTOi aims to provide a verification environment where post-draw modification can be checked through external records.

---

## 12. Operating Principles When Operational Modifications Occur

GitHub records may be modified before the draw due to operational issues such as an incorrect URL entry, document connection error, or input mistake.

In this case, LOTTOi considers the following standards important.

- Initial recording time
- Modification time
- URL before modification
- URL after modification
- Whether the final confirmed URL existed before the draw
- Whether the modification was completed before the draw time

The core verification standard is whether the Google document URL used as the final public verification standard was anchored on GitHub before the draw.

If a URL change occurs after the draw, the verification standard and change history for that round must be checked separately.

---

## 13. Technical Limitations and Operating Environment Notice

Due to unavoidable factors such as external network delays, Google or GitHub platform issues, or permission change delays, the timing of record creation or public standard confirmation may be temporarily delayed.

The purpose of this structure is not to claim a perfect system without delays.

Its purpose is to ensure that if delays or modifications occur, those facts remain in external records and can be checked afterward.

Because the actual creation time and change history remain on external platforms, the time relationship with the draw can be checked afterward.

---

## 14. Prior Case Research Standards and First-Round Comparison Table

LOTTOi uses the expression “world-first-level external public verification framework” in a limited sense, not as an absolute advertising claim, but to describe a structure for which an identical prior case has not been identified through public web research.

This section summarizes the first-round research standards and comparison results used to review whether any identical or similar prior case to LOTTOi’s public verification framework exists in publicly available web materials.

However, the comparison target of this whitepaper is not all number recommendation businesses or all lottery draw systems.  
The comparison target is **number-selection-based lotto and lottery number prediction, recommendation, and generation services or projects**.

For similar domestic services, this whitepaper does not list individual service names directly in the public comparison table in order to avoid unnecessary misunderstanding that could arise from naming specific businesses or appearing as comparative advertising. Individual service names, URLs, screenshots, confirmation dates, and related details are stored in a separate internal research log.

---

### 14-1. Research Standards

This first-round research was organized based on information available as of **May 2026**, and may be supplemented later as publicly available web materials change.

The research focuses on the following categories.

1. Lotto/lottery number prediction services
2. Lotto/lottery number recommendation services
3. Lotto/lottery number generation programs
4. Public GitHub lotto/lottery prediction code
5. Google Sheets or external document-based lotto/lottery analysis cases
6. Number-selection-based lottery analysis and prediction apps
7. Lottery prediction-related patents or system ideas
8. Services claiming to disclose or record prediction numbers before the draw
9. Domestic lotto number recommendation and analysis service types
10. Multilingual lottery number prediction and analysis projects

The following categories are excluded from direct comparison or are treated only as reference materials.

1. Blockchain lottery systems that verify the fairness of the lottery draw itself
2. General-purpose random number verification structures such as Chainlink VRF and commit-reveal
3. Third-party draw or audit services such as RANDOM.ORG
4. General draw verification systems such as casino, raffle, and promotion systems
5. Sports score prediction, stock number recommendation, and general AI number generation services

Although the excluded categories may be adjacent cases in the broad sense of “verifiability,” their purpose and structure differ from the market compared by LOTTOi: **number-selection-based lotto and lottery number recommendation/generation services**.

The main search terms used in the research were as follows.

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

### 14-2. Standards for Determining an Identical Case

In this whitepaper, an “identical case” does not simply mean a case where lottery numbers are predicted, draw results are disclosed, or program code is uploaded to GitHub.

Also, the comparison target of this whitepaper is not all number recommendation businesses.  
The comparison target is the **field of number-selection-based lotto and lottery number recommendation/generation services**.

To be considered identical to LOTTOi, the following conditions must be met together.

1. It must be a service or project that provides recommended or generated numbers for a number-selection-based lotto or lottery.
2. The recommended or generated numbers must be finalized before the draw.
3. The numbers must not be stored only inside an internal system, but must remain in an external public record.
4. After the draw, anyone must be able to directly check the records.
5. The record time or whether any post-draw change occurred must be verifiable through external records.
6. The actual number records and the external reference point that points to those records must be mutually cross-checkable.
7. Different external systems, such as a Google document and GitHub commit history, must be used to verify pre-draw existence and post-draw changes.

LOTTOi’s reference structure is as follows.

> **Google Document**  
> Actual generated number records
>
> **GitHub**  
> The corresponding Google document URL is anchored before the draw
>
> **Post-Draw Verification**  
> Cross-check the Google document records and GitHub commit history

Therefore, simple prediction code, simple number generators, statistical analysis tools, and post-draw result disclosure services may be classified as similar cases, but they are not considered identical cases unless they meet all of the above conditions.

---

### 14-3. First-Round Similar Case Comparison Table

This comparison table is organized around **number-selection-based lotto and lottery number prediction, recommendation, and generation services or projects**.

Blockchain lotteries, Chainlink VRF, commit-reveal, RANDOM.ORG, and similar systems are adjacent technologies related to lottery draw fairness or general-purpose random number verification. However, because their purpose differs from LOTTOi’s service structure, which verifies the pre-draw existence and post-draw change history of the recommended or generated numbers received by users, they are excluded from this comparison table.

Domestic similar services are categorized as “domestic lotto number recommendation services in general” rather than being listed by individual service names in the public whitepaper. This is intended to reduce unnecessary misunderstanding that could arise from naming specific businesses or appearing as comparative advertising.

| Category | Case Name / Type | Identified Features | Similarity to LOTTOi | Difference from LOTTOi | Identical Case? |
|---|---|---|---|---|---|
| Reference Case | [LOTTOi](https://www.lottoi.kr) | Generated numbers are recorded in a Google document, the corresponding Google document URL is anchored on GitHub before the draw, and the two records are cross-checked after the draw | Pre-draw external records, post-draw change history verification, verifiable by anyone | Reference case | Reference case |
| Domestic lotto number recommendation services in general | Lotto number recommendation and analysis services | Domestic service type providing past winning number analysis, number recommendation, statistical information, and in some cases result disclosure | Similar in that they involve lotto number recommendation and analysis | No confirmed structure in which recommended numbers are recorded in an external public document before the draw, the reference point is anchored on GitHub in advance, and post-draw changes are cross-checked | Not identical |
| GitHub prediction code | TensorFlow Lottery Prediction | RNN/LSTM-based lotto number prediction code repository | Subject matter relates to lotto number prediction | Public prediction code only; not a structure for pre-draw external recordkeeping and post-draw change verification of recommended numbers | Not identical |
| GitHub prediction code | Lottery Prediction with Machine Learning | Machine learning project for predicting Mega Millions and Powerball numbers | Subject matter relates to lotto/lottery number prediction | Code and model focused; prediction results are not anchored externally before the draw | Not identical |
| GitHub prediction code | Loto_Ai_Prediction | Structure involving past data collection, LSTM model training, and prediction number output | Similar as AI-based number prediction | Not a verification framework involving pre-draw external disclosure of prediction results and GitHub URL anchoring | Not identical |
| GitHub prediction code | LotteryPrediction | Repository with a lotto prediction program or prediction method guide | Subject matter relates to number prediction | Does not anchor service operation results in a public document before the draw | Not identical |
| GitHub prediction code | Lottery-Predict | Flask-based lotto number prediction web app | Similar in number prediction and web service form | No structure for pre-draw external records, change history checking, or mutual cross-checking | Not identical |
| GitHub prediction code | National Lottery Generator | App structure that analyzes past draw data and generates numbers | Similar as past data-based number generation | Does not verify recommended numbers through an external public document and GitHub commits | Not identical |
| GitHub analysis app | Mega-Sena Analyzer | Brazil Mega-Sena analysis app that imports past data and performs statistical analysis and strategy generation | Similar as statistical lotto analysis | Not a framework for pre-draw external disclosure and post-draw change verification of recommended results | Not identical |
| General prediction sites | UK49s / SA Lotto Prediction-related sites | Explain methods using past data analysis, Excel, or Google Sheets heat maps | Partly similar in using Google Sheets or statistical analysis | Google Sheets are used as analysis tools only; not a structure for pre-draw recommended number records and GitHub cross-verification | Not identical |
| Mobile apps | Lotto Prediction Android app types | Apps providing lotto number prediction or generation functions | Similar in number recommendation and prediction functions | No confirmed public verification framework, external records, or change history cross-checking structure | Not identical |
| Spreadsheet products | Lotto prediction spreadsheet types | Excel or Google Sheets templates for number analysis and prediction | Similar in potential Google Sheets usage | Personal analysis tools; not a structure for pre-draw external public records and GitHub anchoring | Not identical |
| Patent / idea | KR20090129245A, Lottery Prediction Winning Number Provision System | Patent related to a lottery prediction service system providing multiple predicted number combinations | Similar in providing prediction numbers | Does not involve external public document records, GitHub commit history, or post-draw change verification | Not identical |
| Chinese-language prediction code | LottoProphet | Chinese-language lottery prediction project using deep learning and conditional random fields for SSQ and DLT | Similar in lottery number prediction and analysis | Closer to a prediction model and analysis app; not a structure that records recommended numbers in Google documents before the draw and anchors URLs on GitHub | Not identical |
| Chinese-language analysis app | Lottery Analysis / 彩票数据分析 | Python/Streamlit-based project that collects and analyzes Chinese welfare and sports lottery data and provides AI prediction functions | Similar in lottery data collection, statistical analysis, and AI prediction | Analysis and prediction platform; not a pre-draw external public record and GitHub cross-check verification framework | Not identical |
| Chinese-language prediction system | gitmen-lottery / 彩票预测系统 | Web-service-style project using FastAPI, MySQL, Telegram integration, and Chinese lottery history lookup, prediction, and statistics | Similar in lottery prediction, statistics, and lookup system | No confirmed structure in which prediction results are recorded in an external public document in advance and verified through GitHub commit history | Not identical |
| Chinese-language AI prediction code | Double-Color-Ball-AI | Chinese-language AI prediction project using multiple AI models and past-data strategies for Double Color Ball | Similar as AI-based lottery number prediction | Focused on AI prediction generation and data verification; not a public verification framework using Google document records and GitHub URL anchoring | Not identical |
| Japanese-language prediction code | numbers4_lstm | Japanese-language project attempting to predict Japan Numbers4 winning numbers using LSTM and neural networks | Similar as number-selection lottery prediction | Prediction code focused; not a structure for pre-draw external disclosure of recommended numbers and post-draw change verification | Not identical |
| Japanese-language analysis code | Rosyuku/loto6 | GitHub project for analyzing Japan Loto6 | Similar in lotto number analysis | Closer to analysis code or data disclosure; not a public verification framework that cross-checks Google documents and GitHub | Not identical |
| Japanese-language analysis content | Loto6 statistical analysis tools and prediction content | Statistical analysis and prediction support content or tools for Loto6, Mini Loto, and Loto7 | Similar in Japanese lottery number analysis and prediction subject matter | Content or analysis tool type; not a verification structure that anchors service-recommended numbers in an external document before the draw | Not identical |
| Spanish-language prediction code | ojaviva/lottery | Spanish-language project aiming to predict future lottery winning numbers using machine learning | Similar as a lottery number prediction model | Model development and prediction focused; no pre-draw external public records or post-draw change history verification structure | Not identical |
| Spanish-language prediction tool | KinielaGPT | Prediction tool using match data, probabilities, and contextual analysis for Quiniela prediction | Similar as a prediction model and recommendation tool | Sports/Quiniela prediction tool; not a pre-draw external record verification structure for lotto recommended numbers | Not identical |
| French/European prediction code | Loto_Ai_Prediction | Project predicting Loto numbers using machine learning methods such as LSTM | Similar in Loto number prediction and past data learning | Prediction code focused; not a framework verifying pre-draw recommended numbers through Google documents and GitHub records | Not identical |
| Multilingual GitHub prediction group | GitHub lottery-prediction / loto topic projects | Numerous lottery, loto, and lotto prediction/analysis repositories exist across languages | Similar in showing that lottery prediction code and analysis attempts exist worldwide | Most are limited to code, models, or analysis disclosure and do not provide a structure for cross-checking pre-draw existence and post-draw changes through external records | Not identical |

※ Case names, repository names, search result screenshots, and access URLs for this comparison table are stored in a separate research log.  
※ Detailed comparison materials for domestic similar services are stored in a separate internal research log to avoid publicly identifying specific businesses.

---

### 14-4. Summary of First-Round Research Results

The first-round public web research did not identify a structure completely identical to LOTTOi.

In particular, no case was identified that met all of the following conditions.

1. It provides recommended or generated numbers for a number-selection-based lotto or lottery.
2. The recommended or generated numbers are finalized before the draw.
3. The actual recommended or generated numbers are recorded in a Google document as an external public record.
4. The corresponding Google document URL is anchored on GitHub before the draw.
5. After the draw, anyone can cross-check the Google document records and GitHub commit history.
6. Through this, the pre-draw existence of the recommended numbers and whether any post-draw changes occurred can be verified.

The identified similar cases can be broadly grouped into four categories.

First, domestic and overseas lotto/lottery number recommendation and analysis service types.  
These may provide past winning number analysis, number recommendation, statistical information, and in some cases result disclosure. However, no structure was identified in which recommended numbers are recorded in an external document before the draw and a reference point is anchored on GitHub in advance so that post-draw changes can be cross-checked.

Second, lotto/lottery number prediction code.  
These mostly focus on predicting or generating numbers through AI, LSTM, machine learning, or statistical analysis.

Third, lotto/lottery number analysis apps or web apps.  
These provide past winning number data analysis, number recommendation, number generation, and statistical visualization.

Fourth, multilingual prediction and analysis projects in Chinese, Japanese, Spanish, French, and other language regions.  
These are similar in that they involve number-selection lottery prediction or analysis, but no structure was identified for pre-draw external public records and post-draw change history verification.

Therefore, based on the first-round research, LOTTOi’s structure is distinguished from existing similar cases in the following way.

> **Existing Similar Cases**  
> Focus on lottery number recommendation, number generation, statistical analysis, AI models, and prediction code disclosure
>
> **LOTTOi**  
> A structure that cross-checks, through external public documents and GitHub commit history,  
> whether recommended numbers actually existed before the draw  
> and whether they were changed after the draw

---

### 14-5. Limitations of the Research Results

This research is a first-round investigation based on publicly available web materials.

It has the following limitations.

1. Private services, closed communities, and paid member-only materials may be excluded from the scope of confirmation.
2. Past services or closed websites that are not exposed through search engines may be omitted.
3. The research does not completely cover every language region and country.
4. The research focused on publicly accessible materials, including Google, GitHub, patent materials, and search terms in Korean, English, Chinese, Japanese, Spanish, French, and German.
5. The comparison of domestic similar services was conducted by reviewing lotto number recommendation and analysis service types, rather than publicly identifying specific businesses. Individual service names, URLs, screenshots, and related details are stored in a separate internal research log.
6. The expression “world-first-level” is used in a limited sense based on the fact that an identical prior case was not identified within the scope of this research.
7. Even though Chinese, Japanese, and European-language search terms were included, the research does not fully cover closed services in each country, app market-only descriptions, paid materials, or deleted past pages.

Therefore, rather than using “world’s first” as an absolute or definitive expression, LOTTOi limits the explanation as follows based on the scope of this research and the characteristics of its public verification structure.

> In the field of number-selection-based lotto and lottery number recommendation/generation services,  
> LOTTOi operates a Google·GitHub cross-checkable public number verification structure  
> for which no identical prior case has been identified through public web research,  
> and describes it as a world-first-level external public verification framework.

This expression does not imply any guarantee of winning probability, prediction performance, profit, or results.  
It is an explanation of a public verification design method that combines pre-draw records with external verification standards.

---

## 15. Expandability of the Public Verification Framework

LOTTOi’s current public verification framework is operated mainly through Google document records and GitHub URL anchoring.

This whitepaper explains the operating standards and verification methods of the public verification framework currently applied by LOTTOi.

Whether and how to expand the structure will be reviewed based on operating stability, user understanding, and the reliability of external records.

If the framework is expanded, LOTTOi will continue to improve the public verification framework based on the reliability of external records, user verifiability, and operating stability.

---

## 16. Scope and Limitations of This Document

This whitepaper was prepared for the following purposes.

- To explain the structure for checking the pre-draw existence of generated number records
- To explain the operating standards of the external public verification method
- To explain the operation of the public verification framework
- To distinguish the roles of Google documents and GitHub
- To provide standards that anyone can directly verify, regardless of whether they use the service
- To explain the technical design intended to reduce post-draw manipulation concerns
- To explain the scope and limitations of the expression “world-first-level”

This document does not guarantee winning probability, prediction performance, profit, or results.  
Under no circumstances should it be interpreted as an investment, prediction, or guarantee document.

In addition, the expression “world-first-level” is a limited explanation of a structure for which no identical prior case has been identified through public web research. It is not a statement that no private case exists anywhere in the world.

---

## 17. Closing Statement

[LOTTOi](https://www.lottoi.kr) aims to leave behind a verification standard before speaking about results.

LOTTOi’s public verification whitepaper has one goal.

It is to help the public verification framework we designed become a more transparent standard for lottery-related services and contribute to a lottery market without manipulation concerns.

LOTTOi records generated numbers externally before the draw and operates a public verification framework so that those records can be connected and verified through external public record methods.

We hope this model will go beyond the differentiation of a single service and become a trust standard for lottery-related services as a whole.

To support a transparent environment that helps users make rational choices, LOTTOi will continue to treat record standards as important.

---

## Summary

> **Actual generated number records are stored in Google documents.**  
> **The corresponding Google document URL is anchored on GitHub before the draw.**  
> **After the draw, anyone can compare the two records and check whether any post-draw change occurred.**

Based on public web research, LOTTOi has not identified an identical prior case to date, and therefore describes this structure as a world-first-level external public verification framework based on the research results and its operating structure.

---

## Key Timeline

| Date | Description |
|---|---|
| 2025. 02. 08. | Applied the Google-based external public verification method |
| 2026. 01. 29. | Applied the external public verification framework that anchors the Google document URL on GitHub before the draw |
| 2026. 02. 19. | Published the public verification whitepaper |

---

## Short Introduction

LOTTOi has applied a Google-based external public verification method since February 8, 2025.

Since January 29, 2026, LOTTOi has operated an external public verification framework that anchors the Google document URL on GitHub before the draw, allowing anyone to cross-check Google document records and GitHub commit history after the draw.

Based on public web research, LOTTOi has not identified an identical prior case to date, and therefore describes this structure as a world-first-level external public verification framework based on the research results and its operating structure.
