## 12/04

### Introduction to Economy

- Law of offer and demand
- - Offer is the desire to sell.
- - Demand is the desire to buy.
- - There is a graph drawn, in which it shows two lines over the price and quantity of a product.
- - Each line represents either the offer or the demand and they have only one intersection which is called the point of balance
- - When the quantity is high, the demand is low and the offer is high.
- - When the quantity is low the demand is high and the offer is low.
- - Two other concepts were introduced, the essentiality, which tells if the product is unique or can be replaced by a similar, and the market, which is the interaction of a person wanting to buy and a person wanting to sell.
- - Then a function to calculate demand was introduced, and it depended of the following variables: Price of the product and its similars products, income of the person and personal taste.
- - To study a specific variable, we think of other variables as constants, that way we can notice that the income of the person translates the demand line to the right, as the person now has more money so it can afford to buy bigger quantities of that product.
- - There is the study of the price too, if the price of a product is essential then the demand line is more vertical, if it is more horizontal I don't remember what it means
- - Elasticity measures the sensibility of demand over time, if its module is bigger than one then the demand is elastic, if it is lower than one then it is inelastic and if it is equal to one then it is called unitary elasticity
- - There are other types of elasticity, like the elasticity of the price and revenue, which is the price times the quantity. If this elasticity is unitary, it does not matter if the price or quantity changes, the variation of revenue will be close to 0.
- - There is also the elasticity of revenue of demand, if it is lower than zero then the product is considered a lower good, if it is between zero and one, then the product is a normal good, if it is bigger than one than the product is a superior good. That introduces the possibility of another consequence of bigger income, as if the person buys a lower good because it is what they can afford, they won't buy it anymore but replace it with a superior good if their income increases.
- - There is also the elasticity of crossed price, which measures the relation between prices of different goods, if it is bigger than zero then it is a replaceble good, if it is lower than zero then it is a complementary good, but if it is equal to 0 then it is an independant product.
- - Then there is the elasticity of offer, which relates time and product factors like capital, labor and inputs. The more there are replacebla inputs the better for an industry, as it may not be affected by the price of a specific input, because it can replace it.

## 13/04

### Macroeconomics

- Aggregate product is the sum of the final values of goods and services.
- Aggregate value is the brute product value minus the intermediary comsumption.
- Aggregate income is the sum of the salary, interest, rent and profits.
- Aggregate expense is the destination of the product.
- In a closed economy, with no government, the aggregate product is equal to the aggregate expense, which is also equal to the aggregate income. By representing these concepts with a diagram, we have two entities, the family and the enterprise, that relate by:
- - The family buys goods from the enterprise;
- - The family offers production factors services to the enterprise;
- - The enterprise provides goods and services to the family;
- - The enterprise pays the family with aggregate income.
- In this model, all money paid to the family is spent on goods.
- Afterwards we have the concept of investiment, which is the acquisition of capital goods that aim to improve the production capacity, basically, buying modern tools and equipments.
- We also have the savings concepts, which are a part of income the families hold on to, and it did not turn into consumption.
- By introducing these productis to each side of the equation (aggregate expenses = aggregate  income) we can see the saving related to the investiments by a relation of similarity.
- Afterwards, the concept of government was introduced, were the government is an entity that receives taxes in exchange of services like security and public goods.
- It can receive direct taxes that are calculated over income.
- It can receive indirect taxes that are calculated over services and goods, deducing of the families income.
- The governement expenses should be equal to what it raises with taxes, but that does not happen, to equalize how the government spends more than it raises, the savings minus the investments should be equal to the government expenses minus the taxes.
- The market price of a product is bigger than the production cost and is calculated by summing the factor cost product and the indirect taxes over that product. Sometimes the government pays a value over each product to hold its cost, that is called subsidy, and consists in a negative tax over that product.
- Then the concept of the rest of the world was introduced, exportation and importation.
- Then there is the income sent abroad, which is calculated by summing all kinds of exportation and subtracting all kinds of importation.
- Usually, what happens is that the governments spends more than it raises with taxes, and to balance that, besides using the savings of the families, it also exports more than imports, which end up sending more income abroad.
- Speculator is the person that is willing to take risks.
- Personal income is equal to the national product minus the direct tax, minus other receipts, plus governments transfers like retirement and unemployment insurance.
- The final model presented introduced new entities and relations:
- - The family receives income from the production factors market, then it pays taxes to the government, has private savings in the finantial market and consumes goods and services from the goods and services market.
- - The finantial market pays the deficit of the government and invests in the goods and services market
- - the government receives taxes from the families and has its deficits payed by the finantial market, and also the government expenses from the market of goods and services
- - the market of goods and services provides revenue to the enterprises, which pays the factor of production market
- - the rest of the world acts over this model by receiving exportation, getting factors payment and paying factors, then sending importations.

## 14/04

### Formal Languages and Automata

- All languages have an alphabet, which is the group of symbols represented by the serial sum symbol.
- A string is a finite sequence of symbols from an alphabet.
- (the serial sum symbol) with and * represents all strings from an alphabet.
- Language is a subset of the set of all strings from an alphabet.
- Deterministic finite automata (DFA) is the first type we will study
- Deterministic in this situation defines that each state will move to only one other state
- In the visual representation, the triangle represents the initial state, and any double circle state is part of the set of final states.
- When the string ends in a final state, it is a valid string, part of the language.
- A DFA processes a string from left to right.
- Q represents the finite set of states
- δ is the transition function
- q0 is the initial state
- ∑ represents the input symbols
- δ(q0, a) -> means that the transition function goes over a symbol a that is part of the ∑ from leftt to right and parts from a state, which in this case is the initial one.
- If the input symbols is completely read and the final state is not a part of the set of final states, then that input set is not a string of the represented language.

### Machine Learning and Pattern Recognition

- Project structure:
- - Introduction to show where the project could or will be used. The objective of the project must be mentioned, and what will be done must be shown specifically. "What, who and in which way?" with what you plan to do or contribute to.
- - Problem description, which contains the mathematical model of the problem. This part defines the problem to be solved, which must be completely solved by the end of the project.
- - Proposed method, describes what will be done in a general perspective and based on something.
- - Computational experiments, the most important part, defines the benchmark. The paper must be autocontinuous, which means that it defines everything used, details the data with a table describing everypart, it also shows the quantity of each class. Hablation test and use of visualizations. 

- Concepts:
- - Soft Computing: eficient and low cost computation.
- - Handcrafted features: LBP, SIET, KAZE -> Good to extract specific textures from the image. This has pros like improving the accuracy, using less resources and amenizes overfitting, but in counterpart, depends of parametrization and the accuracy is generally inferior to deep learning.
- - Tensor: Image representation of a vector of vectors, each vector may have information like the mean, standard deviation, entropy, and may others, from a little section of the image. This little section has a defined size.
- - CRISP DM: Compares your work with others, already done, projects.
- - Hablation test: Tests each method individually and all combinations od methods. This proves that the combination of functionalities is what improves the accuracy.

- Statistics review:
- - Random variable is a function that associates a number to an event in the mostral space.
- - The random variable is discrete if the space of numbers associate is finite, or better, if the possible values of that function are finete.
- - The random variable is continuous if there is an infinite number of possible values.
- - With DRV, we can use the amount of times a function leads to that outcome to define de probability of that outcome over all possible outcomes.