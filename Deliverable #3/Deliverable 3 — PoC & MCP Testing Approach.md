# Deliverable 3: Proof-of-Concept & MVP Testing Approach

> ## Prototype your solution in some manner
> * *Working code*
> * *Analog prototype / mockups*
> * *Tech stack and wireframes*
> ## Define your Minimum Viable Product (MVP) testing approach
> * Marketing tests: landing page, explainer video, ad campaign, A/B Tests, crowdfunding
> * Product tests: sketches, wireframes, mockups, interactive prototype, Wizard of Oz, Concierge, live product
> ## End of Week Deliverables
> * Prototype /proof-of-concept uploaded
> * Document defining your MVP testing approach  


## Prototype
### Project architecture
The figure below shows the architecture of the project. For a detailed description and an overall project overview please refer to this [Medium post](MEDIUM POST LINK HERE) and [this architectural overview PDF](PDF LINK HERE).

![Architecture](IMAGE OF ARCHETECTURE HERE)

### Code deliverables

For the prototype we have built the following elements:
1. **The DAO**
    * We have deployed a DAO with the DAOStack framework on the Rinkeby network which you can find [here](5)
    * We have built a custom scheme (plugin) for Alchemy to be able to interact with our [`CO2ken.sol`]() contract. 
        * The process for setting up this scheme is described [here]()
        * The scheme is found [here]()
        * The custom Alchemy UI can be found [here]()
    
2. **The Smart Contracts**
    * All contracts can be found in [this folder](LINK TO CONTRACT FOLDER)
    * The `MAIN_CONTRACT_NAME` contract is the main token contract
    * The `SECONDARY_CONTRACT_NAME` contract contains the Solidity modifier which allows other contracts to automatically {function?}
    * The `DATA_CONTRACT_STORAGE` contract is a data storage contract accessed by the other two contracts above

3. **The API**
    * We have deployed an API called `eth-co2.js` which makes it easy for all dApps to interact with our smart contracts
    * The repo containing the code can be found [here](API code REPO LINK HERE)
    * The published npm package can be found [here](NPM_LINK_HERE)

4. **The Frontend / UI**
    * We've deployed a simple web3 app at <WEBSITE LINK HERE> which is using our **API** to connect to our smart contracts
    * The backend code for this can be found [here](BACKEND_LINK_HERE)
    * We've deployed a simple web3 app called *NAME_OF_DEMO_APP* to demonstrate the functionality of the Solidity modifier. It can be found at <LINK TO DEMO APP>
    * The code for the <NAME OF APP> page can be found [here](LINK_TO_MAIN_APP_DEMO_REPO)

* * *

## MVP Testing Approach

Based on our **user persona** research (figure below), we have identified *Dani* as the core customer we want to reach with our *MVP*. 

![User Persona]()

Since our project involves a lot of stakeholders which are not necessarily suppliers or customers, we've made a stakeholder map to have a better overview:

![Stakeholder Map]()

We then looked at the **Business Model Canvas** for *Phase 0: MVP*:

![User Persona]()

(FILLER INFORMATION BELOW THIS POINT.  DO NOT USE)

We then formulated 3 tests to validate the success of our MVP:
1. *Are people interested in buying tokenized carbon offsets?*  
    **Validation:** 40 users (like *Dani*) buy <TOKEN_NAME> via our UI.

2. *Are investors interested in founding this project?*  
    **Validation:** 1 fund reaching out (unsolicited) with the objective to invest.

3. *Are carbon offset projects interested in joining a CarbonDAO?*  
    **Validation:** contact 10 projects with at least 3 positive replies.

We further use Google Analytics to analyze the user's interaction with our UI.

![MVP Testing Approach](TESTING_APPROACH_IMAGE_LINK)
