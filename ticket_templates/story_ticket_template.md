π‘ *Although often desired not every bug or new functionality needs a fully filled out template. Some topics may not always apply or are too obvious to be filled in for that specific ticket. So, feel free to remove sections as needed or leave βN/Aβ to indicate that itβs not applicable. Also please note that the structure of given subjects are mere guidelines, if you feel a subject would be better explained in plain sentences, drawings or a whole different way then by all means feel free to remove the initial structure and implement it as you see fit.*


# βοΈ Questions

---

β *Questions and/or pressing matters in here need to be resolved as soon as possible, preferably before or shortly after starting the ticket.*


- N/A

# π£ User Story

---

π‘ ***As a** ROLE **I want** BEHAVIOUR s**o that** REASON.*


- **What:**
    - N/A
- **Why:**
    - N/A

# βοΈ Requirements

---

π‘ *Functional requirements define what the system does or must not do, non-functional requirements specify how the system should do it. Do X (functional) within 5 seconds (non-functional).*


- **Functional:**
    - N/A
- **Non-Functional:**
    - N/A

# πΎ Data Model

---

π‘ *Old and new data models that will be created and/or altered when this feature is added. Describe the new name and location of the model as well as any fields that are new or will be removed. Show a JSON for easy reference. Use [https://beta5.objgen.com/json?demo=true](https://beta5.objgen.com/json?demo=true) for quick JSON generation.*


- **Name:** ExampleName
    - **Description:** N/A
    - **ObjGen:**

        ```yaml
        
        ```

    - **JSON:**

        ```json
        
        ```


# π Security Rules

---

π‘ *Old and new security rules with roles and access that will be created and/or altered when this feature is added.*


- **Collection:** ExampleCollection
    - **Access & Conditions**: ExampleAccessIfExampleCondition

    ```
        match /Collection/{documentId} {
          allow get, list: if request.auth != null;
        }
    ```


# π API

---

π‘ *Anything related to new API calls. Copy/paste the template and/or components inside the template to cover all new endpoints, requests and responses. Use [https://beta5.objgen.com/json?demo=true](https://beta5.objgen.com/json?demo=true) for easy JSON generation.*


- **Name:** CreateExample
    - **Description:** N/A
    - **Type:** GetPutPostDelete
    - **Endpoint:** ExampleEndpoint
    - **Request body:**

        ```json
        
        ```

    - **200 response:**

        ```json
        
        ```

    - **Other responses 200/400/500:**

        ```json
        
        ```


# π Analytics

---

π‘ *Name preferably ends with a verb. The βWhenβ describes when this analytic is fired and βPropertiesβ describe the map of properties thatβs sent along with the analytic. Use [https://beta5.objgen.com/json?demo=true](https://beta5.objgen.com/json?demo=true) for easy properties (JSON) generation.*


- **Name:** example_created
    - **When:** When.
    - **Properties:**

        ```json
        {
          "state": true,
          "days": "6,7",
          "time": "2021-08-29T18:06:13.051Z"
        }
        ```


# β‘οΈ Integration Tests

---

π‘ *Check out [https://cucumber.io/docs/gherkin/reference/](https://cucumber.io/docs/gherkin/reference/) for more info.*


- **What to test and why?**
    - N/A
- **Ideas for different scenarios?**
    - N/A
- **Ideas for different examples?**
    - N/A

# πΎ Unit Tests

---

π‘ *Components that would benefit from separate unit tests and which scenario's should be tested.*


- **What to test and why?**
    - N/A
- **Ideas for different scenarios?**
    - N/A
- **Ideas for different examples?**
    - N/A

# **π¨βπ§ Current Tests**

---

π‘ *Integration and/or unit tests components that need an upgrade when this feature is added.*


**Any existing tests that need to be updated?**

- N/A

# π¨ UI/UX Behaviour

π‘ *Anything to take note of regarding the behaviour of UI/UX elements (if applicable). Think of position, behaviour when elements do not fit the screen, feedback on elements and properties of animations.*


- N/A

# π Suggested Approach

---

π‘ *With knowledge of the current codebase, try to define a best suggested approach. Think of current components used, flow of data and UI elements.*


- [ ]  TODO

# ποΈ Final Remarks

---

β  *Anything to take note off that is not properly defined yet. Think of out of scope notes, dependencies, anything to be extra cautious about and/or information about related issues.*


- N/A
