# [Analyzing-Millions-of-NYC-Parking-Violations](https://github.com/OjeWilliams/Analyzing-Millions-of-NYC-Parking-Violations)

This project involves interacting and analyzing NYC parking violations over the last decade through the Socrata Open Data API. To achieve this I utilized a EC2 instance from Amazon Web Services, the Linux terminal, Docker, Elasticsearch and finally Kibana.

Parking tickets are a headache for most people but for some states it's a tremendous money maker with them raking in millions if not billions in fees and fines. Luckily, we are afforded a chance to analyze this data through NYC Open Data which is a free public data site which offers an api for this very purpose. The Open Parking and Camera Violations api is a very large data source that can be much more easily and efficiently handled through cloud computing and thats what we plan to do here. <br />

The Average Payment,Fine and Penalty amount over the last decade
  ![](/images/YearlyAvgs.png)

<br />

The Top 50 Parking Violations Wordcloud
  ![](/images/TopViolations.png)
  <br />


Total Dashboard
![](/images/kibanadashboard.png) 
 <br />
  <br />


# [Analyzing Yelp Reviews Dataset](https://github.com/OjeWilliams/Analyzing-Yelp-Reviews-Dataset/blob/main/README.md)
 This project involves diving into a dataset of [Yelp](https://www.kaggle.com/yelp-dataset/yelp-dataset) reviews and seeing what interesting things we can find. The dataset is a collection of Yelp's reviews, user data and businesses across 8 metropolitan areas in the USA and Canada. The Yelp Dataset is a great resource for us to Extract, Load and Transform as a Big Data project. The dataset is quite large (11gb) and therefore to investigate it we will leverage a Spark Cluster on AWS EMR for loading the data as well as an S3 bucket for uploading the data while all analysis was completed using Pyspark, SQL inside a Jupyter Notebook. 
As part of the analysis I investigated the skewness of the data as well as the trustworthyness of Elite reviews.

Top Business Categories 
![](/images/Top-Categories-by-Business.png)
<br />

Yelp Review Skewness
![](/images/Yelp-Review-Skewness.png)
<br />

Review Comparison
![](/images/Review-Comparison.png)




 



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/OjeWilliams/Analyzing-Yelp-Reviews-Dataset) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/OjeWilliams/Oje_Portfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
