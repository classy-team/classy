![classy-banner](banner.svg)

<div align="center">
  <h3 align="center">Classy</h3>
  <p>Open-source AI prototyping and vibe-coding platform</p>
</div>

<p align="center">
  <a href="https://classy.dev">Official Website</a>
  ·
  <a href="https://github.com/classy-team/classy">GitHub</a>
</p>

<div align="center">
  <a href="https://github.com/classy-team/classy/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-AGPL--3.0-purple"></a>
</div>

## Features 💫

- 🧠 **Flexible LLM Support**: Works with OpenAI, Anthropic, Gemini, and more
- 🎨 **Beautiful UIs**: Create interactive React apps with popular component libraries
- 🧩 **Component Libraries**: Supports shadcn/ui and other popular UI libraries
- 📤 **Share & Collaborate**: Share your projects with one click and export code
- 🔧 **Customizable**: Configure your tech stack with different frameworks and models

## Made With 🛠️

- [Next.js](https://nextjs.org)
- [React](https://reactjs.org)
- [Prisma](https://prisma.io)
- [AI SDK](https://github.com/vercel/ai)
- [Tailwind CSS](https://tailwindcss.com)
- [NextAuth.js](https://next-auth.js.org)

## Local Development 🧑‍💻

1. Clone the repository

```bash
git clone https://github.com/classy-team/classy.git
cd classy
```

2. Install dependencies

```bash
npm install
```

3. Set up your environment variables

Create a `.env` file based on the example below:

```
DATABASE_URL="postgresql://username:password@localhost:5432/classy"
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key
```

4. Run database migrations

```bash
npx prisma generate
npx prisma db push
```

5. Start the development server

```bash
npm run dev
```

6. Open [http://localhost:3000](http://localhost:3000) with your browser

## Environment Variables 🔐

| Variable                | Description                        | Required | Example                                        |
| ----------------------- | ---------------------------------- | -------- | ---------------------------------------------- |
| `DATABASE_URL`          | PostgreSQL connection URL          | Yes      | `postgresql://user:pass@localhost:5432/classy` |
| `NEXTAUTH_URL`          | Base URL of your installation      | Yes      | `http://localhost:3000`                        |
| `NEXTAUTH_SECRET`       | Secret key for NextAuth            | Yes      | Random 32+ char string                         |
| `OPENAI_API_KEY`        | OpenAI API key                     | Optional | `sk-...`                                       |
| `ANTHROPIC_API_KEY`     | Anthropic API key                  | Optional | `sk-ant-...`                                   |
| `GOOGLE_AI_API_KEY`     | Google AI API key                  | Optional | `...`                                          |
| `BLOB_READ_WRITE_TOKEN` | Vercel Blob token for file uploads | Optional | `...`                                          |

## Contributing 🤝

We welcome contributions! Please feel free to submit a Pull Request.

## License 📝

Classy is licensed under the [AGPLv3 License](LICENSE).
