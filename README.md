# 📝 Assignment – Pick ONE

## Option 1: Auto Delete Todo List

```
[
  { type: 'Fruit', name: 'Apple' },
  { type: 'Vegetable', name: 'Broccoli' },
  { type: 'Vegetable', name: 'Mushroom' },
  { type: 'Fruit', name: 'Banana' },
  { type: 'Vegetable', name: 'Tomato' },
  { type: 'Fruit', name: 'Orange' },
  { type: 'Fruit', name: 'Mango' },
  { type: 'Fruit', name: 'Pineapple' },
  { type: 'Vegetable', name: 'Cucumber' },
  { type: 'Fruit', name: 'Watermelon' },
  { type: 'Vegetable', name: 'Carrot' },
]
```

Please make a todo list that
- Your project must use React or Nextjs.
- Show a main list of buttons for each item.
- When you click an item, move it to the right side under its type column: Fruit or Vegetable.
- After 5 seconds, move it back to the bottom of the main list automatically.
- If the user clicks on the item again in the right column, immediately move it back to the bottom of the main list.

> [!CAUTION]
> Please host the test on a hosting service and send us the link.

🔗 Example
Watch this short video for reference:
[Video Link](https://drive.google.com/file/d/170AYx0lOXs4DLyZiPGGIgmQpFhwTKNih/view?usp=sharing)

☁️ Deployment
Please host your project (e.g., Vercel, Netlify).

Submit the link to your deployed project.

## Option 2: Create Data from API

API from <https://dummyjson.com/users>

🧑‍💻 Tech Requirements
Use TypeScript

Use TypeScript modules

Use an HTTP framework (e.g., Express, Fastify)

🎯 Task
Transform the response from the API into this structure:

--- sample response ---

```json
 {
  [Department]: {
    male: number,             // total male count
    female: number,           // total female count
    ageRange: "XX-XX",        // min-max age range
    hair: {
      Black: number,
      Blond: number,
      Chestnut: number,
      Brown: number
    },
    addressUser: {
      "firstNamelastName": "postalCode"
    }
  }
}
...
```

✅ Must-Haves
Group users by department

Output summary data: gender count, age range, hair color stats, and postal code mapping

Write unit tests

Focus on performance

---

## 📦 Submission
- Upload your code to GitHub (public or unlisted)

- Include a README.md with:

- Setup instructions

- How to run the server

- Sample requests using curl or Postman


## ✅ Evaluation Criteria
- Clean and readable code
- Well-structured RESTful design
- Good project setup and testing
- Bonus points for performance and creativity
