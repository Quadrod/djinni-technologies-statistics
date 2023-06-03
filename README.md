# djinni-technologies-statistics

### Example
![Image](demo/img.png)

### Install project

```shell
git clone https://github.com/Quadrod/djinni-technologies-statistics/tree/main
cd Djinni_technologies_statistics
python -m venv venv
source venv/bin/activate # on MacOS
venv\Scripts\activate # on Windows
pip install -r requirements.txt
cd djinni_scraping
scrapy crawl technologies -O technologies.csv
```
After this open `djinni_analysis/vacancies_analysis.ipynb` with Jupyter Notebook and run cells.

You can see your diagrams in data/