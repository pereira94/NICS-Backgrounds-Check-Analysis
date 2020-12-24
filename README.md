# Exploring FBI NICS Firearms Data
**The Data**

Following the implementation of the Brady act in 1994, the Federal Bureau of Investigation (FBI) developed a system to conduct background checks on individuals wanting to obtain a firearm. The system known as the National Instant Criminal Background Check System (NICS) was created in collaboration with the Buereu of Alcohol, Tabacco and Firearms and local law enforcement agencies. Since it's inception in November 1998, the FBI has released monthly data from each state and U.S territory. The FBI claims that over 300 million requests have been aprroved, and 1.5 million have been denied.  

**Source**

The FBI releases the monthly data in pdf format. Thanks to Buzzfeed's Jeremy Singer Vine, a public repository on resides on GitHub containing the pdf data parsed into a csv file. The data csv file can be accessed here: [Data in csv format](https://raw.githubusercontent.com/BuzzFeedNews/nics-firearm-background-checks/master/data/nics-firearm-background-checks.csv)
The pdf version of the data can be found here: [PDF data directly from FBI website](https://www.fbi.gov/file-repository/nics_firearm_checks_-_month_year_by_state_type.pdf/view)

**Important Considerations About the Data**

The data simply collects the quantity of background checks conducted. The FBI advices agaisnt the use of this data to analyze gun sales, as conducting a background check does not implictly mean that a firearm was purchased. For example, some states require monthly background checks on all their current conceal carry permit holders. Additionally, some states participate in the program more agressively than others. A map displaying the level of compliance by state can be found here: [NICS Participation Map](https://www.fbi.gov/file-repository/nics-participation-map.pdf/view)

**Questions to Be Answered**

What is the overall trend of the usage of the system nationwide?

Which year had the largest increase and decrease in background checks in comparison to the previous year?

Which state or territory has the highest per capita rate of background checks?

Which state or territory has the lowest per capita rate of background checks?
