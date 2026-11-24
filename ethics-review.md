# Ethics Review — Smart Snack

## Identification
One major ethical concern with our snack-analyzer agent is misidentifying food items or hidden allergens from blurry photos—especially for unpackaged or homemade snacks where there is no barcode or nutrition label to scan. A second concern is the risk of triggering unhealthy eating habits or body-image anxiety by labeling foods as strictly "good" or "bad" for teenage users.
## Analysis
These concerns matter because our actual users are high school students grabbing a quick snack between classes, not nutritionists. If a student with a severe nut or gluten allergy trusts a wrong visual guess, it could cause a serious medical emergency, and judgmental feedback about calories could negatively impact peers who are sensitive about food and weight.
## Design Response
To address the allergen and misidentification risk, we configured the agent's system prompt to explicitly ask the user to confirm ingredients whenever confidence is low and added a mandatory safety banner stating it cannot guarantee allergen-free foods or replace a nutritionist. To avoid promoting disordered eating, we programmed the agent to avoid calorie-shaming language and instead frame its suggestions around balanced energy and focus for class.
## Honest Limitations
Within our four-week timeline, we couldn't train the vision model on local bakery items or homemade regional snacks, so it still struggles with foods that don't have standardized packaging. If we had more time, our next step would be integrating a verified regional food database and having a school nutritionist review our recommendation prompts.
