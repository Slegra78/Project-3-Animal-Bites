# Project-3-Animal-Bites


## About the author

Stephanie Le Grange  
Grad Student   
Mercyhurst University  
DATA 550 Data Visualization  
Project 3 Animal Bites  
12/14/17  

## The goals for this repository are:
The data set that I decided to use for my final project is going to take a look at animal bites in the United States. Wehn someone is bitten there is always a concer that they might have rabis. The data set from Kaan Can will look at information fom over 9,000 animal bites which occurred from 1985 to 2017 and includes information on whether the animal was quarantined after the bite occurred and whether that animal was rabid.

## Content:
1. Features of Animal Bite Data
2. Animal Species
3. Animal Name VS Number of Bite
4. The Most Aggressive 10 Species
5. When Animals Bite
6. Male or Female is More Dangerous
7. Probability of Being Rabid
8. Common Feature of 4 Rabid Animal


## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Related Efforts](#related-efforts)
- [Project Explaination](#Project-explaination)
- [License](#license)

## Background

**1)** This data set consists of a csv (excel) file. There are 9003 rows of data in Health_AnimalBites.
**2)** THe columns in this file consist of the following data
     * Bite Date
     * Species ID
     * Breed ID
     * Gender ID
     * Color
     * Vaccination year & dates
     * Victim Zip
     * Location of the Bite
     * Quarantine
     * Deposition of the Animal
     
## Install: 

**1)** We begin by importing the following first
        * numpy
        * pandas
        * seaborn
        * matplotlib.pyplot
        * matplotlib.patches
        
## Project Description:

Line 1: after importing all our supporting modules we ask for the Health_AnimalBites.csv to be read.
Line 2: we take a look at the data columns.
        * bite_date', 'SpeciesIDDesc', 'BreedIDDesc', 'GenderIDDesc', 'color','vaccination_yrs', 'vaccination_date', 'victim_zip',                'AdvIssuedYNDesc','WhereBittenIDDesc', 'quarantine_date', 'DispositionIDDesc','head_sent_date', 'release_date',                          'ResultsIDDesc'
Line 3: call th the data fromt he excel sheet. here we can see the full excel sheet with all the columns and rows.
Line 4: we are now begining to define some of our data that we want pulled. this shows us what animals are in our data set.
Line 5: we make a graph showing the number of animals bites recorder per animal in our data set.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Animal_Bites.PNG)
Line 6: we want to graph the months that animals bites are reported for dogs, cats and Bats through a year.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Dog_Bites.PNG)
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Cat_Bites.PNG)
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Bat_Bites.PNG)
Line 7: the animals that we want to reallypay attention to are dogs as they are the most commonly reported bite cases. We desing a graph that shows the number of reported bites amoung the 10 most aggressive breeds.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Dog_Breed_Bites.PNG)
Line 8: graphs the positions of the body that bites are most commonly found. Most bits from Cats, Dogs, and Bats are on the head or body of a person.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Dog_Probability.PNG)
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Cat_Probability.PNG)
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Bat_Probability.PNG)
The above graphs show us the following probabilities
       * Dogs are 19% more likely to bite people on the head adn 81% on the body.
       * Cats are 4% more likely to bite people on the head and 96% on the body.
       * Bats are 5% more likely to bite people on the head and 95% on the boody.
Line 9: we go back to lookign at dogs, but now we want to compare male and female dogs. We see that Male dogs are more likely to bite then female dogs.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Male_VS_Female.PNG)
Line 10: lastly we want to look at how many of these reported bites are from rabit animals. Fromt he pie charts we see that there are very low percentage of rabit animals that bit people.
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Rabid_Bat.PNG)
![alt text](C:/Users/stephanie/Documents/DATA SCIENCE/Rabid_Bat.PNG)

## Conclusion:

Even though this data provided us with a lot of bite records amoung different animals this can still not be relied on to judge which animal would be more likely to bite people, because animals are just that animals and they can be unpredictable. 



















