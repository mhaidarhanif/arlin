# Arlin Routes v2 References

List of routes for basic actions of users, questions, answers:

Route            | Component       | Access           | Description
---------------- | --------------- | ---------------- | ------------
`/`              | Landing or Home | -                | Landing page (redirect to)
`/signup`        | Signup          | `/signup`        | Sign up with `email` and `password`
`/signin`        | Signin          | `/auth/local`    | Authenticate with local, `email` and `password`
`/ask`           | Ask             | `/questions`     | <Description>
`/questions`     | QuestionsList   | `/questions`     | <Description>
`/questions/:id` | Question        | `/questions/:id` | <Description>
