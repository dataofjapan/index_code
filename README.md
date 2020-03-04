# Country Codes

国際標準化規格や、国際機関によって制定されている国コードをcsvファイルで用意した。各データとvlookup（Excel）や結合/join（SQL）して活用することを目的としている。



## ISO 3166-1 alpha-2

- 取得URL: https://www.nationsonline.org/oneworld/country_code_list.htm
- 取得日: 令和2年3月4日
- ファイル名: iso_3166_1.csv


### 紛争地域など、ISO 3116-1 alpha-2コードとは異なる国コードを持つ地域の一般的な事例

- 取得URL: https://github.com/OpenCageData/opencagedata-misc-docs/blob/master/countrycode.md
- 取得日: 令和2年3月4日
- ファイル名: dependent_territories..tsv

## 世界銀行
- 取得URL: https://datahelpdesk.worldbank.org/knowledgebase/articles/898590-country-api-queries
- 取得日: 令和2年3月4日
- 後処理: XMLファイルをcsv形式へ変更した。
- ファイル: worldbank.csv

## 国連

国連では、独自の"UN M49"というカントリーコードを利用している。

- 取得URL: https://unstats.un.org/unsd/methodology/m49/
- 取得日: 令和2年3月4日
- ファイル: m49standard.csv



## The Correlates of War Project

- 取得URL: https://correlatesofwar.org/data-sets/cow-country-codes
- 取得日: 令和2年3月4日
- ファイル: cow.csv

# Country Codeの一元化を試みている事例
### Central Intelligence Agency 
- https://www.cia.gov/library/publications/the-world-factbook/appendix/appendix-d.html

### Rパッケージ
- CRAN - Package countrycode https://cran.r-project.org/web/packages/countrycode/index.html
