# Double_Barrel
Ddos attack and scraper that leverages LinkedIn as an attack vector for multiple companies:
Incorrectly judged report by Hackerone 2665876

### How to use:

Change the URL in the scraper to the posts link of the profile you want to scrape for their external links.

Then
install the necessary requirements:

```bash
pip install

selenium==4.10.0                                                                                                webdriver-manager==3.8.6
```

then:

```bash
python3 double_barrell_scraper.py
```

![Scraper pulling links for other resources](https://raw.githubusercontent.com/DeadmanXXXII/Double_Barrel/main/Screenshot_20240816-131211.png)

![Scraper pulling links for other resources](https://raw.githubusercontent.com/DeadmanXXXII/Double_Barrel/main/Screenshot_20240816-131228.png)


With the links connecting to other resources add them too Double_Barrel.py
where all the other links are:
lines 24 to 28 and input the urls reduced too:

    "https://lnkd.in/emrjmnvZ",
    "https://lnkd.in/e3jSxi7g",
    "https://lnkd.in/e3pEtH6D",
    "https://lnkd.in/eDWrvvsS",
    "https://lnkd.in/e8hPSyBx"


Then once you have updated your script 
run double_barrel.py with
```bash
double_barrel.py
```
As you can see that began exhausting resources everywhere:

![Ddos attack in work](https://raw.githubusercontent.com/DeadmanXXXII/Double_Barrel/main/Screenshot_20240816-134035.png)



