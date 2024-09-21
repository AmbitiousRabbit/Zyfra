# Zyfra

Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry. The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification. The model will help to optimize the production and eliminate unprofitable parameters.

# Project description of the dataset
1. Flotation
Gold ore mixture is fed into the float banks to obtain rougher Au concentrate and rougher tails (product residues with a low concentration of valuable metals). The stability of this process is affected by the volatile and non-optimal physicochemical state of the flotation pulp (a mixture of solid particles and liquid).

2. Purification
The rougher concentrate undergoes two stages of purification. After purification, we have the final concentrate and new tails.

# Data description
* `Rougher feed` — raw material
* `Rougher additions` (or reagent additions) — flotation reagents: Xanthate, Sulphate, Depressant
* `Xanthate` — promoter or flotation activator;
* `Sulphate` — sodium sulphide for this particular process;
* `Depressant` — sodium silicate.
* `Rougher process` — flotation
* `Rougher tails` — product residues
* `Float banks` — flotation unit
* `Cleaner process` — purification
* `Rougher Au` — rougher gold concentrate
* `Final Au` — final gold concentrate
* `air amount` — volume of air
* `fluid levels`
* `feed size` — feed particle size
* `feed rate`

# Project Process

## Step 1 | Access & Study the data
* Open and skim to become familiarize with the data
## Step 2 | Prepare the data
* Convert the data to the necessary types
* Find & Eliminate errors in the data
## Step 3 | Analyze the data
* Conduct EDA & SDA while exercising the 5 analytic frameworks (if applicable):
  * What happened? - Descriptive 
  * Why did it happen? - Diagnostic 
  * What will happen? - Predictive
  * How can we make it happen? - Prescriptive
## Step 4 | Build a predictive model 
* Consider and select useful data to analyze the gold concentrate rate retention.
## Step 5 | General Conclusion
* State found insights in a clear, concise manner.
