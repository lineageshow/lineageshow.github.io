# Probation Review - Hank Huang
  
## Tasks
* CC1-356 - [BAU][Risk] Display SBK Max Bet Percentage Value in iOWB
  * QT-12976 - [CSB-60][iOWB] SBK Statement : The old data all displayed as 0%
  * QT-12977 - [CC1-356][iOWB][Function] MaxBet % display incorrect
* CC1-621 - [BAU][Product] Remove Bingo from create transfer in member profile of iOWB
* ~~CC1-879 - [BAU][CS] Validate Phone Numbers by Country in Member Site~~
* CC1-883 - [BAU][MKT] Profile Verification Widget Display Order For Individual KYC Doc Status
  * QT-12766 - [CC1-883][Desktop][Function] Display order error in profile verification widget
  * QT-12752 - [CC1-883][iOWB][Function] cannot add doc verification type
  * UTIM-3855 - [CC1-883] Photo ID and Address did not change to "REQUIRED" when expired in the Profile Verification Widget.
* CC1-884 - [BAU][MKT] Customer Transparency _Profile Verification Enhancement
* CC1-941 - [APMO][PROD] Product Integration - KaiYuan 開元 - Chess Game
* CC1-958 - [BAU][Risk] KYC Doc Status change shall be synced between Profile Verification Widget and iOWB
  * PIM-10447 - [CC1-958] Widget status no change when updated the Doc status under Check Doc Link

## System Domain
### APS & PMS
* APS Domain Training by Eva
* PMS Domain Training by Eva
* Trace code -> not yet

### iOWB
* KYC
  * <a href="https://lineageshow.github.io/KYC.html">ER Model</a>
* Messaging
  * Template Management
* Balance (Acturl Balance)
  * Actual Balance => AccountBalance.AccountingBalance
  * Available Total Balance => AccountBalance.AvailableBalance
  * Churn Balance => AccountChurnBalance.ChurnBalance
  * Generated Balance <=> Member site->Member Balance
* Cash Log 
  * from GeneralLedger and 
* Chrun Log 
  * from xxx

### To have an overiew of 188 Asia all systems
<a href="https://lineageshow.github.io/188AsiaOverviewAllSystem.html">Overview of 188 Asia</a>
###  JIRA flow, and Git usage
about ticket type
1. CC1
2. QT
3. UTIM
4. PIM
5. RLUU
6. RLPU
7. IDP  
   

<p><a href="https://lineageshow.github.io/RLPU.html">RLPU Flow diagram </a></p>
<p><a href="https://lineageshow.github.io/CC1.html">CC1 Flow diagram</a></p>

## Others
____
### ETL & SSIS
* add git version control(CanReport, Accpac, XDM)
* know how to release from dev to prod
### Affiliate System
* about data flow PRA,Accwager188.. -> STG -> XDM
* BackOffice site

## Feedback and Self Review
* About Git when developer Merge code
* understand deeply the system
* code refactoring
  * SQL and code should put right place
  * third-party lib
  * useless table column and code
* understand TransactionSource / TransactionType and how to use it