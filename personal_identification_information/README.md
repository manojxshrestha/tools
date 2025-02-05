## Read PDF files
```
cat recon/all_extension_urls.txt | grep -aE '\.pdf' | while read -r url; do curl -s "$url" | pdftotext - - | grep -Eaiq '(internal use only|confidential|strictly private|personal & confidential|private|restricted|internal|not for distribution|do not share|proprietary|trade secret|classified|sensitive|bank statement|invoice|salary|contract|agreement|non disclosure|passport|social security|ssn|date of birth|credit card|identity|id number|company confidential|staff only|management only|internal only|shareholder information)' && echo "$url"; done
```
## Installation
```
wget "https://raw.githubusercontent.com/h6nt3r/tools/refs/heads/main/personal_identification_information/pii.sh"
sudo chmod +x pii.sh
```
