# Problem C: Foreigners Traveling in China

Recently, the internet buzzword "city or not city" has gained attention, particularly driven by foreign influencers. With the implementation of China's visa-free transit policy, more and more foreign tourists are visiting China, sharing their travel experiences through online platforms. This not only promotes the development of China's tourism industry but also showcases a real and vivid image of China on the international stage, achieving multiple benefits.

Assuming foreign tourists can stay in China for 144 hours and can depart from any airport near the city, and given that each city has many attractions, we will follow the principle of "visiting only the highest-rated attraction in each city," referred to as the "Best Attraction Tour Principle."

We have a dataset containing tourist attractions for 352 cities in mainland China (excluding Hong Kong, Macau, and Taiwan). Each city's CSV file includes 100 attractions, with information such as attraction name, website, address, description, opening hours, image URL, ratings, suggested visit duration, best seasons to visit, ticket information, and tips.

Please establish a mathematical model to address the following questions:

## Question 1
What is the highest rating (Best Score, BS) among the 35,200 attraction ratings in the 352 cities? How many attractions received this highest rating (BS)? Which cities have the most attractions rated with this highest score (BS)? List the top 10 cities based on the number of attractions with the highest rating (BS).

## Question 2
Assuming foreign tourists follow the "Best Attraction Tour Principle," please conduct a comprehensive evaluation of the 352 cities based on factors such as city size, environmental sustainability, cultural heritage, transportation convenience, climate, and cuisine. Identify the "50 Most Desired Cities for Foreign Tourists."

## Question 3
A foreign tourist arrives in Guangzhou and wants to visit as many cities as possible within 144 hours while ensuring the best overall experience. Please plan his travel route, providing specific details such as total time spent, total ticket and transportation costs, and the number of attractions visited. His requirements include:
1. Following the Best Attraction Tour Principle;
2. Traveling between cities exclusively by high-speed train;
3. Selecting cities only from the "50 Most Desired Cities for Foreign Tourists."

## Question 4
If the goal of Question 3 is modified to visit as many cities as possible while minimizing total ticket and transportation costs, please replan the travel route. Provide the total ticket and transportation costs, total time spent, and the number of cities visited.

## Question 5
A foreign tourist only wants to visit mountainous attractions in China and can enter through any airport. Please choose the entry airport and city for him and customize a 144-hour travel route, aiming to visit as many mountains as possible while minimizing total ticket and transportation costs. Provide specific details for the travel route, including total time spent, total ticket and transportation costs, and the number of attractions visited. His requirements include:
1. Visiting only the highest-rated mountain in each city;
2. Traveling between cities exclusively by high-speed train;
3. Expanding the range of tourism cities beyond the "50 Most Desired Cities for Foreign Tourists" to include all 352 cities.
