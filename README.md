## Data Science Portfolio by Nata Berishvili

This portfolio is a collection of notebooks which I created for data analysis and machine learning projects for academic, self learning, and hobby purposes.


## Exploratory Data Analysis - Medicare

For this project I use Medicare Provider Utilization and Payment Data for more than 3,000 U.S. hospitals that receive Medicare paments. I explore and visualize data to make comparisons between individual hospital-level charges and payments within local markets, and nationwide. (#R #dplyr #ggplot2)
- allala
- lalalal
**lalaaaa**
`usstates1 <- payment %>%
  group_by(Provider.State) %>% filter(Year == 2017) %>%
  summarize(totalcost = sum(Average.Covered.Charges, na.rm =TRUE))%>%
  mutate(percent = (totalcost/sum(totalcost))*100)%>%
  arrange(desc(totalcost))`

```markdown
usstates1 <- payment %>%
  group_by(Provider.State) %>% filter(Year == 2017) %>%
  summarize(totalcost = sum(Average.Covered.Charges, na.rm =TRUE))%>%
  mutate(percent = (totalcost/sum(totalcost))*100)%>%
  arrange(desc(totalcost))





```

For more details code can be found here [GitHub Flavored Markdown](https://github.com/nataberishvili/k_means_clustering_R_medicare).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nataberishvili/nataberishvili.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
