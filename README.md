## Investigating Data on National Instant Criminal Check System

The National Instant Criminal Check System (NICS) is the official system used by the FBI to keep under check suspicious criminal activities. The NICS was invented as a successor to the Brady Handgun Act of 1992 and officially came into existence in 1998. While the law acted as a prevention tool to keep arms trade and transactions under check, the NICS was the tool through which law enforcement agencies could pin-point any suspicious activity by constantly monitoring weapon transactions in all of the NICS registered weapon shops. In this manner, these two tools served the purpose of a firearm limiting toolset with NICS playing an important part through its innovative and practical approach.

The data for NICS and several of its variants can be found all over the official FBI website. The data that I used here can be found [here](https://github.com/BuzzFeedNews/nics-firearm-background-checks), the source through which students enrolled in the course are instructed to download the data from. Besides the NICS, the student had the option of picking any one of the remaining four topics ranging from a variety of genres including finance/economic data to data derived from database files. I picked the NICS data because of my personal interest in it.

The dataset primarily contains only two tables; one in Excel format while the other is a .csv file. Of these two, the `gun_data.xlsx` is of primary importance since it notes down every permit check recorded since 1998 for all the states of the U.S. For getting started into the world of descriptive statistics, the NICS data is an ideal choice since it offers a wide variety of columns and variables that any analyst could play upon and extract unlimited information. Since a table that allows statistics to be efficiently carried out is capable enough to have a learning algorithm to be run on it, the `gun_data` has those characterstics and can well serve as a perfect training ground for understanding how algorithms work.

Second is the `U.S. census data` that has some valauable 'facts' for each of the state. Each row states down some census fact and consequently records data for it for each state. In the notebook that I wrote down, the `gun_data` found purpose almost 99% of the time since both files come off as unrelated in several aspects. However, some engineering can be done here to make the best possible use of both the tables. Due to lack of sufficient time, I rested focus only on `gun_data` and received perfect results.

**Note:** Requires Python 3.6 with latest modules for best results and visual renderings.
