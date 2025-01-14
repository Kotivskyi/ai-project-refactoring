# Table of Contents
- LICENSE
- Troubleshooting.md
- README.md
- .gitignore
- .gitattributes
- docker-compose.yml
- design-docs.md
- Evaluation.md
- frontend/tsconfig.node.json
- frontend/index.html
- frontend/tailwind.config.js
- frontend/Dockerfile
- frontend/jest.config.js
- frontend/.eslintrc.cjs
- frontend/yarn.lock
- frontend/.gitignore
- frontend/package.json
- frontend/components.json
- frontend/tsconfig.json
- frontend/.env.example
- frontend/vite.config.ts
- frontend/postcss.config.js
- frontend/src/App.tsx
- frontend/src/main.tsx
- frontend/src/urls.ts
- frontend/src/index.css
- frontend/src/setupTests.ts
- frontend/src/types.ts
- frontend/src/vite-env.d.ts
- frontend/src/constants.ts
- frontend/src/.env.jest.example
- frontend/src/config.ts
- frontend/src/generateCode.ts
- frontend/src/tests/qa.test.ts
- frontend/src/components/UrlInputSection.tsx
- frontend/src/components/ImportCodeSection.tsx
- frontend/src/components/TermsOfServiceDialog.tsx
- frontend/src/components/ImageUpload.tsx
- frontend/src/components/commits/utils.ts
- frontend/src/components/commits/types.ts
- frontend/src/components/sidebar/Sidebar.tsx
- frontend/src/components/ui/alert-dialog.tsx
- frontend/src/components/ui/tabs.tsx
- frontend/src/components/ui/popover.tsx
- frontend/src/components/ui/progress.tsx
- frontend/src/components/ui/hover-card.tsx
- frontend/src/components/ui/scroll-area.tsx
- frontend/src/components/ui/label.tsx
- frontend/src/components/ui/accordion.tsx
- frontend/src/components/ui/switch.tsx
- frontend/src/components/ui/dialog.tsx
- frontend/src/components/ui/badge.tsx
- frontend/src/components/ui/separator.tsx
- frontend/src/components/ui/button.tsx
- frontend/src/components/ui/checkbox.tsx
- frontend/src/components/ui/collapsible.tsx
- frontend/src/components/ui/select.tsx
- frontend/src/components/ui/textarea.tsx
- frontend/src/components/ui/input.tsx
- frontend/src/components/settings/GenerationSettings.tsx
- frontend/src/components/settings/OutputSettingsSection.tsx
- frontend/src/components/settings/SettingsDialog.tsx
- frontend/src/components/evals/BestOfNEvalsPage.tsx
- frontend/src/components/evals/AllEvalsPage.tsx
- frontend/src/components/evals/EvalsPage.tsx
- frontend/src/components/evals/RunEvalsPage.tsx
- frontend/src/components/evals/PairwiseEvalsPage.tsx
- frontend/src/components/evals/RatingPicker.tsx
- frontend/src/components/select-and-edit/utils.ts
- frontend/src/components/select-and-edit/EditPopup.tsx
- frontend/src/components/select-and-edit/SelectAndEditModeToggleButton.tsx
- frontend/src/components/start-pane/StartPane.tsx
- frontend/src/components/variants/Variants.tsx
- frontend/src/components/messages/PicoBadge.tsx
- frontend/src/components/messages/OnboardingNote.tsx
- frontend/src/components/messages/DeprecationMessage.tsx
- frontend/src/components/messages/TipLink.tsx
- frontend/src/components/core/StackLabel.tsx
- frontend/src/components/core/KeyboardShortcutBadge.tsx
- frontend/src/components/core/Spinner.tsx
- frontend/src/components/recording/ScreenRecorder.tsx
- frontend/src/components/recording/utils.ts
- frontend/src/components/history/utils.test.ts
- frontend/src/components/history/utils.ts
- frontend/src/components/history/HistoryDisplay.tsx
- frontend/src/components/preview/CodeMirror.tsx
- frontend/src/components/preview/CodePreview.tsx
- frontend/src/components/preview/PreviewPane.tsx
- frontend/src/components/preview/PreviewComponent.tsx
- frontend/src/components/preview/simpleHash.ts
- frontend/src/components/preview/download.ts
- frontend/src/components/preview/extractHtml.ts
- frontend/src/components/preview/CodeTab.tsx
- frontend/src/hooks/useBrowserTabIndicator.ts
- frontend/src/hooks/useThrottle.ts
- frontend/src/hooks/usePersistedState.ts
- frontend/src/lib/stacks.ts
- frontend/src/lib/utils.ts
- frontend/src/lib/takeScreenshot.ts
- frontend/src/lib/models.ts
- frontend/src/store/app-store.ts
- frontend/src/store/project-store.ts
- backend/config.py
- backend/pyrightconfig.json
- backend/.pre-commit-config.yaml
- backend/Dockerfile
- backend/mock_llm.py
- backend/pyproject.toml
- backend/llm.py
- backend/start.py
- backend/README.md
- backend/run_evals.py
- backend/.gitignore
- backend/utils.py
- backend/custom_types.py
- backend/poetry.lock
- backend/main.py
- backend/run_image_generation_evals.py
- backend/video_to_app.py
- backend/video/utils.py
- backend/evals/runner.py
- backend/evals/config.py
- backend/evals/__init__.py
- backend/evals/core.py
- backend/evals/utils.py
- backend/image_generation/replicate.py
- backend/image_generation/__init__.py
- backend/image_generation/core.py
- backend/codegen/test_utils.py
- backend/codegen/__init__.py
- backend/codegen/utils.py
- backend/fs_logging/__init__.py
- backend/fs_logging/core.py
- backend/prompts/test_prompts.py
- backend/prompts/__init__.py
- backend/prompts/types.py
- backend/prompts/screenshot_system_prompts.py
- backend/prompts/imported_code_prompts.py
- backend/prompts/claude_prompts.py
- backend/routes/generate_code.py
- backend/routes/home.py
- backend/routes/evals.py
- backend/routes/screenshot.py
- backend/ws/constants.py
- backend/ws/__init__.py
- backend/debug/__init__.py
- backend/debug/DebugFileWriter.py
- backend/image_processing/__init__.py
- backend/image_processing/utils.py
- blog/evaluating-claude.md
- .github/FUNDING.yml
- .github/ISSUE_TEMPLATE/feature_request.md
- .github/ISSUE_TEMPLATE/bug_report.md
- .github/ISSUE_TEMPLATE/custom.md
- .vscode/settings.json

## File: LICENSE

- Extension: 
- Language: unknown
- Size: 1065 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
MIT License

Copyright (c) 2023 Abi Raja

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

## File: Troubleshooting.md

- Extension: .md
- Language: markdown
- Size: 1851 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
### Getting an OpenAI API key with GPT-4 model access

You don't need a ChatGPT Pro account. Screenshot to code uses API keys from your OpenAI developer account. In order to get access to the GPT4 Vision model, log into your OpenAI account and then, follow these instructions:

1. Open [OpenAI Dashboard](https://platform.openai.com/)
1. Go to Settings > Billing
1. Click at the Add payment details
<img width="900" alt="285636868-c80deb92-ab47-45cd-988f-deee67fbd44d" src="https://github.com/abi/screenshot-to-code/assets/23818/4e0f4b77-9578-4f9a-803c-c12b1502f3d7">

4. You have to buy some credits. The minimum is $5.
5. Go to Settings > Limits and check at the bottom of the page, your current tier has to be "Tier 1" to have GPT4 access
<img width="900" alt="285636973-da38bd4d-8a78-4904-8027-ca67d729b933" src="https://github.com/abi/screenshot-to-code/assets/23818/8d07cd84-0cf9-4f88-bc00-80eba492eadf">

6. Navigate to OpenAI [api keys](https://platform.openai.com/api-keys) page and create and copy a new secret key.
7. Go to Screenshot to code and paste it in the Settings dialog under OpenAI key (gear icon). Your key is only stored in your browser. Never stored on our servers.

## Still not working?

- Some users have also reported that it can take upto 30 minutes after your credit purchase for the GPT4 vision model to be activated.
- You need to add credits to your account AND set it to renew when credits run out in order to be upgraded to Tier 1. Make sure your "Settings > Limits" page shows that you are at Tier 1.

If you've followed these steps, and it still doesn't work, feel free to open a Github issue. We only provide support for the open source version since we don't have debugging logs on the hosted version. If you're looking to use the hosted version, we recommend getting a paid subscription on screenshottocode.com

```

## File: README.md

- Extension: .md
- Language: markdown
- Size: 5541 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
# screenshot-to-code

A simple tool to convert screenshots, mockups and Figma designs into clean, functional code using AI. **Now supporting Claude Sonnet 3.5 and Gemini 2.0 Flash!**

https://github.com/abi/screenshot-to-code/assets/23818/6cebadae-2fe3-4986-ac6a-8fb9db030045

Supported stacks:

- HTML + Tailwind
- HTML + CSS
- React + Tailwind
- Vue + Tailwind
- Bootstrap
- Ionic + Tailwind
- SVG

Supported AI models:

- Claude Sonnet 3.5 - Best model!
- GPT-4o - also recommended!
- DALL-E 3 or Flux Schnell (using Replicate) for image generation

See the [Examples](#-examples) section below for more demos.

We also just added experimental support for taking a video/screen recording of a website in action and turning that into a functional prototype.

![google in app quick 3](https://github.com/abi/screenshot-to-code/assets/23818/8758ffa4-9483-4b9b-bb66-abd6d1594c33)

[Learn more about video here](https://github.com/abi/screenshot-to-code/wiki/Screen-Recording-to-Code).

[Follow me on Twitter for updates](https://twitter.com/_abi_).

## 🌍  Hosted Version

[Try it live on the hosted version (paid)](https://screenshottocode.com). If you're a large or medium enterprise (50+ employees), [book a meeting to explore custom enterprise plans](https://cal.com/abi-raja-wy2pfh/30min).

## 🛠 Getting Started

The app has a React/Vite frontend and a FastAPI backend.

Keys needed:

- [OpenAI API key with access to GPT-4](https://github.com/abi/screenshot-to-code/blob/main/Troubleshooting.md) or Anthropic key (optional)
- Both are recommended so you can compare results from both Claude and GPT4o

If you'd like to run the app with Ollama open source models (not recommended due to poor quality results), [follow this comment](https://github.com/abi/screenshot-to-code/issues/354#issuecomment-2435479853).

Run the backend (I use Poetry for package management - `pip install poetry` if you don't have it):

```bash
cd backend
echo "OPENAI_API_KEY=sk-your-key" > .env
echo "ANTHROPIC_API_KEY=your-key" > .env
poetry install
poetry shell
poetry run uvicorn main:app --reload --port 7001
```
You can also set up the keys using the settings dialog on the front-end (click the gear icon after loading the frontend).

Run the frontend:

```bash
cd frontend
yarn
yarn dev
```

Open http://localhost:5173 to use the app.

If you prefer to run the backend on a different port, update VITE_WS_BACKEND_URL in `frontend/.env.local`

For debugging purposes, if you don't want to waste GPT4-Vision credits, you can run the backend in mock mode (which streams a pre-recorded response):

```bash
MOCK=true poetry run uvicorn main:app --reload --port 7001
```

## Docker

If you have Docker installed on your system, in the root directory, run:

```bash
echo "OPENAI_API_KEY=sk-your-key" > .env
docker-compose up -d --build
```

The app will be up and running at http://localhost:5173. Note that you can't develop the application with this setup as the file changes won't trigger a rebuild.

## 🙋‍♂️ FAQs

- **I'm running into an error when setting up the backend. How can I fix it?** [Try this](https://github.com/abi/screenshot-to-code/issues/3#issuecomment-1814777959). If that still doesn't work, open an issue.
- **How do I get an OpenAI API key?** See https://github.com/abi/screenshot-to-code/blob/main/Troubleshooting.md
- **How can I configure an OpenAI proxy?** - If you're not able to access the OpenAI API directly (due to e.g. country restrictions), you can try a VPN or you can configure the OpenAI base URL to use a proxy: Set OPENAI_BASE_URL in the `backend/.env` or directly in the UI in the settings dialog. Make sure the URL has "v1" in the path so it should look like this: `https://xxx.xxxxx.xxx/v1`
- **How can I update the backend host that my front-end connects to?** - Configure VITE_HTTP_BACKEND_URL and VITE_WS_BACKEND_URL in front/.env.local For example, set VITE_HTTP_BACKEND_URL=http://124.10.20.1:7001
- **Seeing UTF-8 errors when running the backend?** - On windows, open the .env file with notepad++, then go to Encoding and select UTF-8.
- **How can I provide feedback?** For feedback, feature requests and bug reports, open an issue or ping me on [Twitter](https://twitter.com/_abi_).

## 📚 Examples

**NYTimes**

| Original                                                                                                                                                        | Replica                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="1238" alt="Screenshot 2023-11-20 at 12 54 03 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/3b644dfa-9ca6-4148-84a7-3405b6671922"> | <img width="1414" alt="Screenshot 2023-11-20 at 12 59 56 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/26201c9f-1a28-4f35-a3b1-1f04e2b8ce2a"> |

**Instagram page (with not Taylor Swift pics)**

https://github.com/abi/screenshot-to-code/assets/23818/503eb86a-356e-4dfc-926a-dabdb1ac7ba1

**Hacker News** but it gets the colors wrong at first so we nudge it

https://github.com/abi/screenshot-to-code/assets/23818/3fec0f77-44e8-4fb3-a769-ac7410315e5d

```

## File: .gitignore

- Extension: 
- Language: unknown
- Size: 178 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
.aider*

# Project-related files

# Run logs
backend/run_logs/*

# Weird Docker setup related files
backend/backend/*

# Env vars
frontend/.env.local
.env

# Mac files
.DS_Store

```

## File: .gitattributes

- Extension: 
- Language: unknown
- Size: 66 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
# Auto detect text files and perform LF normalization
* text=auto

```

## File: docker-compose.yml

- Extension: .yml
- Language: yaml
- Size: 609 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```yaml
version: '3.9'

services:
  backend:
    build: 
      context: ./backend
      dockerfile: Dockerfile
    
    env_file:
      - .env
    
    # or 
    # environment:
      #- BACKEND_PORT=7001   # if you change the port, make sure to also change the VITE_WS_BACKEND_URL at frontend/.env.local
      # - OPENAI_API_KEY=your_openai_api_key
    
    ports:
      - "${BACKEND_PORT:-7001}:${BACKEND_PORT:-7001}"

    command: poetry run uvicorn main:app --host 0.0.0.0 --port ${BACKEND_PORT:-7001}
  
  frontend:
    build:
      context: ./frontend
      dockerfile: Dockerfile
    ports:
      - "5173:5173"

```

## File: design-docs.md

- Extension: .md
- Language: markdown
- Size: 192 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
## Version History

Version history is stored as a tree on the client-side.

![Screenshot to Code](https://github.com/abi/screenshot-to-code/assets/23818/e35644aa-b90a-4aa7-8027-b8732796fd7c)

```

## File: Evaluation.md

- Extension: .md
- Language: markdown
- Size: 1193 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
## Evaluating models and prompts

Evaluation dataset consists of 16 screenshots. A Python script for running screenshot-to-code on the dataset and a UI for rating outputs is included. With this set up, we can compare and evaluate various models and prompts.

### Running evals

- Input screenshots should be located at `backend/evals_data/inputs` and the outputs will be `backend/evals_data/outputs`. If you want to modify this, modify `EVALS_DIR` in `backend/evals/config.py`. You can download the input screenshot dataset here: TODO.
- Set a stack and model (`STACK` var, `MODEL` var) in `backend/run_evals.py`
- Run `OPENAI_API_KEY=sk-... python run_evals.py` - this runs the screenshot-to-code on the input dataset in parallel but it will still take a few minutes to complete.
- Once the script is done, you can find the outputs in `backend/evals_data/outputs`.

### Rating evals

In order to view and rate the outputs, visit your front-end at `/evals`.

- Rate each output on a scale of 1-4
- You can also print the page as PDF to share your results with others.

Generally, I run three tests for each model/prompt + stack combo and take the average score out of those tests to evaluate.

```

## File: frontend/tsconfig.node.json

- Extension: .json
- Language: json
- Size: 213 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "compilerOptions": {
    "composite": true,
    "skipLibCheck": true,
    "module": "ESNext",
    "moduleResolution": "bundler",
    "allowSyntheticDefaultImports": true
  },
  "include": ["vite.config.ts"]
}

```

## File: frontend/index.html

- Extension: .html
- Language: html
- Size: 1809 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/png" href="/favicon/main.png" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap"
      rel="stylesheet"
    />

    <!-- Injected code for hosted version -->
    <%- injectHead %>

    <title>Screenshot to Code</title>

    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="Screenshot to Code" />
    <meta
      property="og:description"
      content="Convert any screenshot or design to clean code"
    />
    <meta
      property="og:image"
      content="https://screenshottocode.com/brand/twitter-summary-card.png"
    />
    <meta property="og:image:width" content="1200" />
    <meta property="og:image:height" content="628" />
    <meta property="og:url" content="https://screenshottocode.com" />
    <meta property="og:type" content="website" />
    <!-- Twitter Card tags -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:site" content="@picoapps" />
    <!-- Keep in sync with og:title, og:description and og:image -->
    <meta name="twitter:title" content="Screenshot to Code" />
    <meta
      name="twitter:description"
      content="Convert any screenshot or design to clean code"
    />
    <meta
      name="twitter:image"
      content="https://screenshottocode.com/brand/twitter-summary-card.png"
    />
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>

```

## File: frontend/tailwind.config.js

- Extension: .js
- Language: javascript
- Size: 2184 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  darkMode: ["class"],
  content: [
    "./pages/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
  ],
  theme: {
    container: {
      center: true,
      padding: "2rem",
      screens: {
        "2xl": "1400px",
      },
    },
    extend: {
      colors: {
        button: "#ffd803",
        highlight: "#ffd803",
        border: "hsl(var(--border))",
        input: "hsl(var(--input))",
        ring: "hsl(var(--ring))",
        background: "hsl(var(--background))",
        foreground: "hsl(var(--foreground))",
        primary: {
          DEFAULT: "hsl(var(--primary))",
          foreground: "hsl(var(--primary-foreground))",
        },
        secondary: {
          DEFAULT: "hsl(var(--secondary))",
          foreground: "hsl(var(--secondary-foreground))",
        },
        destructive: {
          DEFAULT: "hsl(var(--destructive))",
          foreground: "hsl(var(--destructive-foreground))",
        },
        muted: {
          DEFAULT: "hsl(var(--muted))",
          foreground: "hsl(var(--muted-foreground))",
        },
        accent: {
          DEFAULT: "hsl(var(--accent))",
          foreground: "hsl(var(--accent-foreground))",
        },
        popover: {
          DEFAULT: "hsl(var(--popover))",
          foreground: "hsl(var(--popover-foreground))",
        },
        card: {
          DEFAULT: "hsl(var(--card))",
          foreground: "hsl(var(--card-foreground))",
        },
      },
      borderRadius: {
        lg: "var(--radius)",
        md: "calc(var(--radius) - 2px)",
        sm: "calc(var(--radius) - 4px)",
      },
      keyframes: {
        "accordion-down": {
          from: { height: 0 },
          to: { height: "var(--radix-accordion-content-height)" },
        },
        "accordion-up": {
          from: { height: "var(--radix-accordion-content-height)" },
          to: { height: 0 },
        },
      },
      animation: {
        "accordion-down": "accordion-down 0.2s ease-out",
        "accordion-up": "accordion-up 0.2s ease-out",
      },
    },
  },
  plugins: [require("tailwindcss-animate")],
};

```

## File: frontend/Dockerfile

- Extension: 
- Language: unknown
- Size: 496 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
FROM node:22-bullseye-slim

# Set the working directory in the container
WORKDIR /app

# Copy package.json and yarn.lock
COPY package.json yarn.lock /app/

# Set the environment variable to skip Puppeteer download
ENV PUPPETEER_SKIP_DOWNLOAD=true

# Install dependencies
RUN yarn install

# Copy the current directory contents into the container at /app
COPY ./ /app/

# Expose port 5173 to access the server
EXPOSE 5173

# Command to run the application
CMD ["yarn", "dev", "--host", "0.0.0.0"]

```

## File: frontend/jest.config.js

- Extension: .js
- Language: javascript
- Size: 187 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```javascript
export default {
  preset: "ts-jest",
  testEnvironment: "node",
  setupFiles: ["<rootDir>/src/setupTests.ts"],
  transform: {
    "^.+\\.tsx?$": "ts-jest",
  },
  testTimeout: 30000,
};

```

## File: frontend/.eslintrc.cjs

- Extension: .cjs
- Language: unknown
- Size: 436 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
module.exports = {
  root: true,
  env: { browser: true, es2020: true },
  extends: [
    'eslint:recommended',
    'plugin:@typescript-eslint/recommended',
    'plugin:react-hooks/recommended',
  ],
  ignorePatterns: ['dist', '.eslintrc.cjs'],
  parser: '@typescript-eslint/parser',
  plugins: ['react-refresh'],
  rules: {
    'react-refresh/only-export-components': [
      'warn',
      { allowConstantExport: true },
    ],
  },
}

```

## File: frontend/yarn.lock

- Extension: .lock
- Language: unknown
- Size: 262421 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
# THIS IS AN AUTOGENERATED FILE. DO NOT EDIT THIS FILE DIRECTLY.
# yarn lockfile v1


"@aashutoshrathi/word-wrap@^1.2.3":
  version "1.2.6"
  resolved "https://registry.npmjs.org/@aashutoshrathi/word-wrap/-/word-wrap-1.2.6.tgz"
  integrity sha512-1Yjs2SvM8TflER/OD3cOjhWWOZb58A2t7wpE2S9XfBYTiIl+XFhQG2bjy4Pu1I+EAlCNUzRDYDdFwFYUKvXcIA==

"@alloc/quick-lru@^5.2.0":
  version "5.2.0"
  resolved "https://registry.npmjs.org/@alloc/quick-lru/-/quick-lru-5.2.0.tgz"
  integrity sha512-UrcABB+4bUrFABwbluTIBErXwvbsU/V7TZWfmbgJfbkwiBuziS9gxdODUyuiecfdGQ85jglMW6juS3+z5TsKLw==

"@ampproject/remapping@^2.2.0":
  version "2.2.1"
  resolved "https://registry.npmjs.org/@ampproject/remapping/-/remapping-2.2.1.tgz"
  integrity sha512-lFMjJTrFL3j7L9yBxwYfCq2k6qqwHyzuUl/XBnif78PWTJYyL/dfowQHWE3sp6U6ZzqWiiIZnpTMO96zhkjwtg==
  dependencies:
    "@jridgewell/gen-mapping" "^0.3.0"
    "@jridgewell/trace-mapping" "^0.3.9"

"@babel/code-frame@^7.0.0", "@babel/code-frame@^7.23.5", "@babel/code-frame@^7.24.2":
  version "7.24.2"
  resolved "https://registry.yarnpkg.com/@babel/code-frame/-/code-frame-7.24.2.tgz#718b4b19841809a58b29b68cde80bc5e1aa6d9ae"
  integrity sha512-y5+tLQyV8pg3fsiln67BVLD1P13Eg4lh5RW9mF0zUuvLrv9uIQ4MCL+CRT+FTsBlBjcIan6PGsLcBN0m3ClUyQ==
  dependencies:
    "@babel/highlight" "^7.24.2"
    picocolors "^1.0.0"

"@babel/code-frame@^7.12.13", "@babel/code-frame@^7.22.13":
  version "7.22.13"
  resolved "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.22.13.tgz"
  integrity sha512-XktuhWlJ5g+3TJXc5upd9Ks1HutSArik6jf2eAjYFyIOf4ej3RN+184cZbzDvbPnuTJIUhPKKJE3cIsYTiAT3w==
  dependencies:
    "@babel/highlight" "^7.22.13"
    chalk "^2.4.2"

"@babel/compat-data@^7.22.9":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.23.3.tgz"
  integrity sha512-BmR4bWbDIoFJmJ9z2cZ8Gmm2MXgEDgjdWgpKmKWUt54UGFJdlj31ECtbaDvCG/qVdG3AQ1SfpZEs01lUFbzLOQ==

"@babel/compat-data@^7.23.5":
  version "7.24.4"
  resolved "https://registry.yarnpkg.com/@babel/compat-data/-/compat-data-7.24.4.tgz#6f102372e9094f25d908ca0d34fc74c74606059a"
  integrity sha512-vg8Gih2MLK+kOkHJp4gBEIkyaIi00jgWot2D9QOmmfLC8jINSOzmCLta6Bvz/JSBCqnegV0L80jhxkol5GWNfQ==

"@babel/core@^7.11.6", "@babel/core@^7.12.3", "@babel/core@^7.23.9":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/core/-/core-7.24.5.tgz#15ab5b98e101972d171aeef92ac70d8d6718f06a"
  integrity sha512-tVQRucExLQ02Boi4vdPp49svNGcfL2GhdTCT9aldhXgCJVAI21EtRfBettiuLUwce/7r6bFdgs6JFkcdTiFttA==
  dependencies:
    "@ampproject/remapping" "^2.2.0"
    "@babel/code-frame" "^7.24.2"
    "@babel/generator" "^7.24.5"
    "@babel/helper-compilation-targets" "^7.23.6"
    "@babel/helper-module-transforms" "^7.24.5"
    "@babel/helpers" "^7.24.5"
    "@babel/parser" "^7.24.5"
    "@babel/template" "^7.24.0"
    "@babel/traverse" "^7.24.5"
    "@babel/types" "^7.24.5"
    convert-source-map "^2.0.0"
    debug "^4.1.0"
    gensync "^1.0.0-beta.2"
    json5 "^2.2.3"
    semver "^6.3.1"

"@babel/core@^7.23.2":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/core/-/core-7.23.3.tgz"
  integrity sha512-Jg+msLuNuCJDyBvFv5+OKOUjWMZgd85bKjbICd3zWrKAo+bJ49HJufi7CQE0q0uR8NGyO6xkCACScNqyjHSZew==
  dependencies:
    "@ampproject/remapping" "^2.2.0"
    "@babel/code-frame" "^7.22.13"
    "@babel/generator" "^7.23.3"
    "@babel/helper-compilation-targets" "^7.22.15"
    "@babel/helper-module-transforms" "^7.23.3"
    "@babel/helpers" "^7.23.2"
    "@babel/parser" "^7.23.3"
    "@babel/template" "^7.22.15"
    "@babel/traverse" "^7.23.3"
    "@babel/types" "^7.23.3"
    convert-source-map "^2.0.0"
    debug "^4.1.0"
    gensync "^1.0.0-beta.2"
    json5 "^2.2.3"
    semver "^6.3.1"

"@babel/generator@^7.23.3":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/generator/-/generator-7.23.3.tgz"
  integrity sha512-keeZWAV4LU3tW0qRi19HRpabC/ilM0HRBBzf9/k8FFiG4KVpiv0FIy4hHfLfFQZNhziCTPTmd59zoyv6DNISzg==
  dependencies:
    "@babel/types" "^7.23.3"
    "@jridgewell/gen-mapping" "^0.3.2"
    "@jridgewell/trace-mapping" "^0.3.17"
    jsesc "^2.5.1"

"@babel/generator@^7.24.5", "@babel/generator@^7.7.2":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/generator/-/generator-7.24.5.tgz#e5afc068f932f05616b66713e28d0f04e99daeb3"
  integrity sha512-x32i4hEXvr+iI0NEoEfDKzlemF8AmtOP8CcrRaEcpzysWuoEb1KknpcvMsHKPONoKZiDuItklgWhB18xEhr9PA==
  dependencies:
    "@babel/types" "^7.24.5"
    "@jridgewell/gen-mapping" "^0.3.5"
    "@jridgewell/trace-mapping" "^0.3.25"
    jsesc "^2.5.1"

"@babel/helper-compilation-targets@^7.22.15":
  version "7.22.15"
  resolved "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.22.15.tgz"
  integrity sha512-y6EEzULok0Qvz8yyLkCvVX+02ic+By2UdOhylwUOvOn9dvYc9mKICJuuU1n1XBI02YWsNsnrY1kc6DVbjcXbtw==
  dependencies:
    "@babel/compat-data" "^7.22.9"
    "@babel/helper-validator-option" "^7.22.15"
    browserslist "^4.21.9"
    lru-cache "^5.1.1"
    semver "^6.3.1"

"@babel/helper-compilation-targets@^7.23.6":
  version "7.23.6"
  resolved "https://registry.yarnpkg.com/@babel/helper-compilation-targets/-/helper-compilation-targets-7.23.6.tgz#4d79069b16cbcf1461289eccfbbd81501ae39991"
  integrity sha512-9JB548GZoQVmzrFgp8o7KxdgkTGm6xs9DW0o/Pim72UDjzr5ObUQ6ZzYPqA+g9OTS2bBQoctLJrky0RDCAWRgQ==
  dependencies:
    "@babel/compat-data" "^7.23.5"
    "@babel/helper-validator-option" "^7.23.5"
    browserslist "^4.22.2"
    lru-cache "^5.1.1"
    semver "^6.3.1"

"@babel/helper-environment-visitor@^7.22.20":
  version "7.22.20"
  resolved "https://registry.npmjs.org/@babel/helper-environment-visitor/-/helper-environment-visitor-7.22.20.tgz"
  integrity sha512-zfedSIzFhat/gFhWfHtgWvlec0nqB9YEIVrpuwjruLlXfUSnA8cJB0miHKwqDnQ7d32aKo2xt88/xZptwxbfhA==

"@babel/helper-function-name@^7.23.0":
  version "7.23.0"
  resolved "https://registry.npmjs.org/@babel/helper-function-name/-/helper-function-name-7.23.0.tgz"
  integrity sha512-OErEqsrxjZTJciZ4Oo+eoZqeW9UIiOcuYKRJA4ZAgV9myA+pOXhhmpfNCKjEH/auVfEYVFJ6y1Tc4r0eIApqiw==
  dependencies:
    "@babel/template" "^7.22.15"
    "@babel/types" "^7.23.0"

"@babel/helper-hoist-variables@^7.22.5":
  version "7.22.5"
  resolved "https://registry.npmjs.org/@babel/helper-hoist-variables/-/helper-hoist-variables-7.22.5.tgz"
  integrity sha512-wGjk9QZVzvknA6yKIUURb8zY3grXCcOZt+/7Wcy8O2uctxhplmUPkOdlgoNhmdVee2c92JXbf1xpMtVNbfoxRw==
  dependencies:
    "@babel/types" "^7.22.5"

"@babel/helper-module-imports@^7.22.15":
  version "7.22.15"
  resolved "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.22.15.tgz"
  integrity sha512-0pYVBnDKZO2fnSPCrgM/6WMc7eS20Fbok+0r88fp+YtWVLZrp4CkafFGIp+W0VKw4a22sgebPT99y+FDNMdP4w==
  dependencies:
    "@babel/types" "^7.22.15"

"@babel/helper-module-imports@^7.24.3":
  version "7.24.3"
  resolved "https://registry.yarnpkg.com/@babel/helper-module-imports/-/helper-module-imports-7.24.3.tgz#6ac476e6d168c7c23ff3ba3cf4f7841d46ac8128"
  integrity sha512-viKb0F9f2s0BCS22QSF308z/+1YWKV/76mwt61NBzS5izMzDPwdq1pTrzf+Li3npBWX9KdQbkeCt1jSAM7lZqg==
  dependencies:
    "@babel/types" "^7.24.0"

"@babel/helper-module-transforms@^7.23.3":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.23.3.tgz"
  integrity sha512-7bBs4ED9OmswdfDzpz4MpWgSrV7FXlc3zIagvLFjS5H+Mk7Snr21vQ6QwrsoCGMfNC4e4LQPdoULEt4ykz0SRQ==
  dependencies:
    "@babel/helper-environment-visitor" "^7.22.20"
    "@babel/helper-module-imports" "^7.22.15"
    "@babel/helper-simple-access" "^7.22.5"
    "@babel/helper-split-export-declaration" "^7.22.6"
    "@babel/helper-validator-identifier" "^7.22.20"

"@babel/helper-module-transforms@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-module-transforms/-/helper-module-transforms-7.24.5.tgz#ea6c5e33f7b262a0ae762fd5986355c45f54a545"
  integrity sha512-9GxeY8c2d2mdQUP1Dye0ks3VDyIMS98kt/llQ2nUId8IsWqTF0l1LkSX0/uP7l7MCDrzXS009Hyhe2gzTiGW8A==
  dependencies:
    "@babel/helper-environment-visitor" "^7.22.20"
    "@babel/helper-module-imports" "^7.24.3"
    "@babel/helper-simple-access" "^7.24.5"
    "@babel/helper-split-export-declaration" "^7.24.5"
    "@babel/helper-validator-identifier" "^7.24.5"

"@babel/helper-plugin-utils@^7.0.0", "@babel/helper-plugin-utils@^7.10.4", "@babel/helper-plugin-utils@^7.12.13", "@babel/helper-plugin-utils@^7.14.5", "@babel/helper-plugin-utils@^7.24.0", "@babel/helper-plugin-utils@^7.8.0":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-plugin-utils/-/helper-plugin-utils-7.24.5.tgz#a924607dd254a65695e5bd209b98b902b3b2f11a"
  integrity sha512-xjNLDopRzW2o6ba0gKbkZq5YWEBaK3PCyTOY1K2P/O07LGMhMqlMXPxwN4S5/RhWuCobT8z0jrlKGlYmeR1OhQ==

"@babel/helper-plugin-utils@^7.22.5":
  version "7.22.5"
  resolved "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.22.5.tgz"
  integrity sha512-uLls06UVKgFG9QD4OeFYLEGteMIAa5kpTPcFL28yuCIIzsf6ZyKZMllKVOCZFhiZ5ptnwX4mtKdWCBE/uT4amg==

"@babel/helper-simple-access@^7.22.5":
  version "7.22.5"
  resolved "https://registry.npmjs.org/@babel/helper-simple-access/-/helper-simple-access-7.22.5.tgz"
  integrity sha512-n0H99E/K+Bika3++WNL17POvo4rKWZ7lZEp1Q+fStVbUi8nxPQEBOlTmCOxW/0JsS56SKKQ+ojAe2pHKJHN35w==
  dependencies:
    "@babel/types" "^7.22.5"

"@babel/helper-simple-access@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-simple-access/-/helper-simple-access-7.24.5.tgz#50da5b72f58c16b07fbd992810be6049478e85ba"
  integrity sha512-uH3Hmf5q5n7n8mz7arjUlDOCbttY/DW4DYhE6FUsjKJ/oYC1kQQUvwEQWxRwUpX9qQKRXeqLwWxrqilMrf32sQ==
  dependencies:
    "@babel/types" "^7.24.5"

"@babel/helper-split-export-declaration@^7.22.6":
  version "7.22.6"
  resolved "https://registry.npmjs.org/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.22.6.tgz"
  integrity sha512-AsUnxuLhRYsisFiaJwvp1QF+I3KjD5FOxut14q/GzovUe6orHLesW2C7d754kRm53h5gqrz6sFl6sxc4BVtE/g==
  dependencies:
    "@babel/types" "^7.22.5"

"@babel/helper-split-export-declaration@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.24.5.tgz#b9a67f06a46b0b339323617c8c6213b9055a78b6"
  integrity sha512-5CHncttXohrHk8GWOFCcCl4oRD9fKosWlIRgWm4ql9VYioKm52Mk2xsmoohvm7f3JoiLSM5ZgJuRaf5QZZYd3Q==
  dependencies:
    "@babel/types" "^7.24.5"

"@babel/helper-string-parser@^7.22.5":
  version "7.22.5"
  resolved "https://registry.npmjs.org/@babel/helper-string-parser/-/helper-string-parser-7.22.5.tgz"
  integrity sha512-mM4COjgZox8U+JcXQwPijIZLElkgEpO5rsERVDJTc2qfCDfERyob6k5WegS14SX18IIjv+XD+GrqNumY5JRCDw==

"@babel/helper-string-parser@^7.24.1":
  version "7.24.1"
  resolved "https://registry.yarnpkg.com/@babel/helper-string-parser/-/helper-string-parser-7.24.1.tgz#f99c36d3593db9540705d0739a1f10b5e20c696e"
  integrity sha512-2ofRCjnnA9y+wk8b9IAREroeUP02KHp431N2mhKniy2yKIDKpbrHv9eXwm8cBeWQYcJmzv5qKCu65P47eCF7CQ==

"@babel/helper-validator-identifier@^7.22.20":
  version "7.22.20"
  resolved "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.22.20.tgz"
  integrity sha512-Y4OZ+ytlatR8AI+8KZfKuL5urKp7qey08ha31L8b3BwewJAoJamTzyvxPR/5D+KkdJCGPq/+8TukHBlY10FX9A==

"@babel/helper-validator-identifier@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-validator-identifier/-/helper-validator-identifier-7.24.5.tgz#918b1a7fa23056603506370089bd990d8720db62"
  integrity sha512-3q93SSKX2TWCG30M2G2kwaKeTYgEUp5Snjuj8qm729SObL6nbtUldAi37qbxkD5gg3xnBio+f9nqpSepGZMvxA==

"@babel/helper-validator-option@^7.22.15":
  version "7.22.15"
  resolved "https://registry.npmjs.org/@babel/helper-validator-option/-/helper-validator-option-7.22.15.tgz"
  integrity sha512-bMn7RmyFjY/mdECUbgn9eoSY4vqvacUnS9i9vGAGttgFWesO6B4CYWA7XlpbWgBt71iv/hfbPlynohStqnu5hA==

"@babel/helper-validator-option@^7.23.5":
  version "7.23.5"
  resolved "https://registry.yarnpkg.com/@babel/helper-validator-option/-/helper-validator-option-7.23.5.tgz#907a3fbd4523426285365d1206c423c4c5520307"
  integrity sha512-85ttAOMLsr53VgXkTbkx8oA6YTfT4q7/HzXSLEYmjcSTJPMPQtvq1BD79Byep5xMUYbGRzEpDsjUf3dyp54IKw==

"@babel/helpers@^7.23.2":
  version "7.23.2"
  resolved "https://registry.npmjs.org/@babel/helpers/-/helpers-7.23.2.tgz"
  integrity sha512-lzchcp8SjTSVe/fPmLwtWVBFC7+Tbn8LGHDVfDp9JGxpAY5opSaEFgt8UQvrnECWOTdji2mOWMz1rOhkHscmGQ==
  dependencies:
    "@babel/template" "^7.22.15"
    "@babel/traverse" "^7.23.2"
    "@babel/types" "^7.23.0"

"@babel/helpers@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/helpers/-/helpers-7.24.5.tgz#fedeb87eeafa62b621160402181ad8585a22a40a"
  integrity sha512-CiQmBMMpMQHwM5m01YnrM6imUG1ebgYJ+fAIW4FZe6m4qHTPaRHti+R8cggAwkdz4oXhtO4/K9JWlh+8hIfR2Q==
  dependencies:
    "@babel/template" "^7.24.0"
    "@babel/traverse" "^7.24.5"
    "@babel/types" "^7.24.5"

"@babel/highlight@^7.22.13":
  version "7.22.20"
  resolved "https://registry.npmjs.org/@babel/highlight/-/highlight-7.22.20.tgz"
  integrity sha512-dkdMCN3py0+ksCgYmGG8jKeGA/8Tk+gJwSYYlFGxG5lmhfKNoAy004YpLxpS1W2J8m/EK2Ew+yOs9pVRwO89mg==
  dependencies:
    "@babel/helper-validator-identifier" "^7.22.20"
    chalk "^2.4.2"
    js-tokens "^4.0.0"

"@babel/highlight@^7.24.2":
  version "7.24.2"
  resolved "https://registry.yarnpkg.com/@babel/highlight/-/highlight-7.24.2.tgz#3f539503efc83d3c59080a10e6634306e0370d26"
  integrity sha512-Yac1ao4flkTxTteCDZLEvdxg2fZfz1v8M4QpaGypq/WPDqg3ijHYbDfs+LG5hvzSoqaSZ9/Z9lKSP3CjZjv+pA==
  dependencies:
    "@babel/helper-validator-identifier" "^7.22.20"
    chalk "^2.4.2"
    js-tokens "^4.0.0"
    picocolors "^1.0.0"

"@babel/parser@^7.1.0", "@babel/parser@^7.20.7", "@babel/parser@^7.22.15", "@babel/parser@^7.23.3":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/parser/-/parser-7.23.3.tgz"
  integrity sha512-uVsWNvlVsIninV2prNz/3lHCb+5CJ+e+IUBfbjToAHODtfGYLfCFuY4AU7TskI+dAKk+njsPiBjq1gKTvZOBaw==

"@babel/parser@^7.14.7", "@babel/parser@^7.23.9", "@babel/parser@^7.24.0", "@babel/parser@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/parser/-/parser-7.24.5.tgz#4a4d5ab4315579e5398a82dcf636ca80c3392790"
  integrity sha512-EOv5IK8arwh3LI47dz1b0tKUb/1uhHAnHJOrjgtQMIpu1uXd9mlFrJg9IUgGUgZ41Ch0K8REPTYpO7B76b4vJg==

"@babel/plugin-syntax-async-generators@^7.8.4":
  version "7.8.4"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-async-generators/-/plugin-syntax-async-generators-7.8.4.tgz#a983fb1aeb2ec3f6ed042a210f640e90e786fe0d"
  integrity sha512-tycmZxkGfZaxhMRbXlPXuVFpdWlXpir2W4AMhSJgRKzk/eDlIXOhb2LHWoLpDF7TEHylV5zNhykX6KAgHJmTNw==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-bigint@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-bigint/-/plugin-syntax-bigint-7.8.3.tgz#4c9a6f669f5d0cdf1b90a1671e9a146be5300cea"
  integrity sha512-wnTnFlG+YxQm3vDxpGE57Pj0srRU4sHE/mDkt1qv2YJJSeUAec2ma4WLUnUPeKjyrfntVwe/N6dCXpU+zL3Npg==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-class-properties@^7.8.3":
  version "7.12.13"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-class-properties/-/plugin-syntax-class-properties-7.12.13.tgz#b5c987274c4a3a82b89714796931a6b53544ae10"
  integrity sha512-fm4idjKla0YahUNgFNLCB0qySdsoPiZP3iQE3rky0mBUtMZ23yDJ9SJdg6dXTSDnulOVqiF3Hgr9nbXvXTQZYA==
  dependencies:
    "@babel/helper-plugin-utils" "^7.12.13"

"@babel/plugin-syntax-import-meta@^7.8.3":
  version "7.10.4"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-import-meta/-/plugin-syntax-import-meta-7.10.4.tgz#ee601348c370fa334d2207be158777496521fd51"
  integrity sha512-Yqfm+XDx0+Prh3VSeEQCPU81yC+JWZ2pDPFSS4ZdpfZhp4MkFMaDC1UqseovEKwSUpnIL7+vK+Clp7bfh0iD7g==
  dependencies:
    "@babel/helper-plugin-utils" "^7.10.4"

"@babel/plugin-syntax-json-strings@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-json-strings/-/plugin-syntax-json-strings-7.8.3.tgz#01ca21b668cd8218c9e640cb6dd88c5412b2c96a"
  integrity sha512-lY6kdGpWHvjoe2vk4WrAapEuBR69EMxZl+RoGRhrFGNYVK8mOPAW8VfbT/ZgrFbXlDNiiaxQnAtgVCZ6jv30EA==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-jsx@^7.7.2":
  version "7.24.1"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-jsx/-/plugin-syntax-jsx-7.24.1.tgz#3f6ca04b8c841811dbc3c5c5f837934e0d626c10"
  integrity sha512-2eCtxZXf+kbkMIsXS4poTvT4Yu5rXiRa+9xGVT56raghjmBTKMpFNc9R4IDiB4emao9eO22Ox7CxuJG7BgExqA==
  dependencies:
    "@babel/helper-plugin-utils" "^7.24.0"

"@babel/plugin-syntax-logical-assignment-operators@^7.8.3":
  version "7.10.4"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-logical-assignment-operators/-/plugin-syntax-logical-assignment-operators-7.10.4.tgz#ca91ef46303530448b906652bac2e9fe9941f699"
  integrity sha512-d8waShlpFDinQ5MtvGU9xDAOzKH47+FFoney2baFIoMr952hKOLp1HR7VszoZvOsV/4+RRszNY7D17ba0te0ig==
  dependencies:
    "@babel/helper-plugin-utils" "^7.10.4"

"@babel/plugin-syntax-nullish-coalescing-operator@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-nullish-coalescing-operator/-/plugin-syntax-nullish-coalescing-operator-7.8.3.tgz#167ed70368886081f74b5c36c65a88c03b66d1a9"
  integrity sha512-aSff4zPII1u2QD7y+F8oDsz19ew4IGEJg9SVW+bqwpwtfFleiQDMdzA/R+UlWDzfnHFCxxleFT0PMIrR36XLNQ==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-numeric-separator@^7.8.3":
  version "7.10.4"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-numeric-separator/-/plugin-syntax-numeric-separator-7.10.4.tgz#b9b070b3e33570cd9fd07ba7fa91c0dd37b9af97"
  integrity sha512-9H6YdfkcK/uOnY/K7/aA2xpzaAgkQn37yzWUMRK7OaPOqOpGS1+n0H5hxT9AUw9EsSjPW8SVyMJwYRtWs3X3ug==
  dependencies:
    "@babel/helper-plugin-utils" "^7.10.4"

"@babel/plugin-syntax-object-rest-spread@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-object-rest-spread/-/plugin-syntax-object-rest-spread-7.8.3.tgz#60e225edcbd98a640332a2e72dd3e66f1af55871"
  integrity sha512-XoqMijGZb9y3y2XskN+P1wUGiVwWZ5JmoDRwx5+3GmEplNyVM2s2Dg8ILFQm8rWM48orGy5YpI5Bl8U1y7ydlA==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-optional-catch-binding@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-optional-catch-binding/-/plugin-syntax-optional-catch-binding-7.8.3.tgz#6111a265bcfb020eb9efd0fdfd7d26402b9ed6c1"
  integrity sha512-6VPD0Pc1lpTqw0aKoeRTMiB+kWhAoT24PA+ksWSBrFtl5SIRVpZlwN3NNPQjehA2E/91FV3RjLWoVTglWcSV3Q==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-optional-chaining@^7.8.3":
  version "7.8.3"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-optional-chaining/-/plugin-syntax-optional-chaining-7.8.3.tgz#4f69c2ab95167e0180cd5336613f8c5788f7d48a"
  integrity sha512-KoK9ErH1MBlCPxV0VANkXW2/dw4vlbGDrFgz8bmUsBGYkFRcbRwMh6cIJubdPrkxRwuGdtCk0v/wPTKbQgBjkg==
  dependencies:
    "@babel/helper-plugin-utils" "^7.8.0"

"@babel/plugin-syntax-top-level-await@^7.8.3":
  version "7.14.5"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-top-level-await/-/plugin-syntax-top-level-await-7.14.5.tgz#c1cfdadc35a646240001f06138247b741c34d94c"
  integrity sha512-hx++upLv5U1rgYfwe1xBQUhRmU41NEvpUvrp8jkrSCdvGSnM5/qdRMtylJ6PG5OFkBaHkbTAKTnd3/YyESRHFw==
  dependencies:
    "@babel/helper-plugin-utils" "^7.14.5"

"@babel/plugin-syntax-typescript@^7.7.2":
  version "7.24.1"
  resolved "https://registry.yarnpkg.com/@babel/plugin-syntax-typescript/-/plugin-syntax-typescript-7.24.1.tgz#b3bcc51f396d15f3591683f90239de143c076844"
  integrity sha512-Yhnmvy5HZEnHUty6i++gcfH1/l68AHnItFHnaCv6hn9dNh0hQvvQJsxpi4BMBFN5DLeHBuucT/0DgzXif/OyRw==
  dependencies:
    "@babel/helper-plugin-utils" "^7.24.0"

"@babel/plugin-transform-react-jsx-self@^7.22.5":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-self/-/plugin-transform-react-jsx-self-7.23.3.tgz"
  integrity sha512-qXRvbeKDSfwnlJnanVRp0SfuWE5DQhwQr5xtLBzp56Wabyo+4CMosF6Kfp+eOD/4FYpql64XVJ2W0pVLlJZxOQ==
  dependencies:
    "@babel/helper-plugin-utils" "^7.22.5"

"@babel/plugin-transform-react-jsx-source@^7.22.5":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-source/-/plugin-transform-react-jsx-source-7.23.3.tgz"
  integrity sha512-91RS0MDnAWDNvGC6Wio5XYkyWI39FMFO+JK9+4AlgaTH+yWwVTsw7/sn6LK0lH7c5F+TFkpv/3LfCJ1Ydwof/g==
  dependencies:
    "@babel/helper-plugin-utils" "^7.22.5"

"@babel/runtime@^7.13.10", "@babel/runtime@^7.23.1":
  version "7.23.2"
  resolved "https://registry.yarnpkg.com/@babel/runtime/-/runtime-7.23.2.tgz#062b0ac103261d68a966c4c7baf2ae3e62ec3885"
  integrity sha512-mM8eg4yl5D6i3lu2QKPuPH4FArvJ8KhTofbE7jwMUv9KX5mBvwPAqnV3MlyBNqdp9RyRKP6Yck8TrfYrPvX3bg==
  dependencies:
    regenerator-runtime "^0.14.0"

"@babel/template@^7.22.15":
  version "7.22.15"
  resolved "https://registry.npmjs.org/@babel/template/-/template-7.22.15.tgz"
  integrity sha512-QPErUVm4uyJa60rkI73qneDacvdvzxshT3kksGqlGWYdOTIUOwJ7RDUL8sGqslY1uXWSL6xMFKEXDS3ox2uF0w==
  dependencies:
    "@babel/code-frame" "^7.22.13"
    "@babel/parser" "^7.22.15"
    "@babel/types" "^7.22.15"

"@babel/template@^7.24.0", "@babel/template@^7.3.3":
  version "7.24.0"
  resolved "https://registry.yarnpkg.com/@babel/template/-/template-7.24.0.tgz#c6a524aa93a4a05d66aaf31654258fae69d87d50"
  integrity sha512-Bkf2q8lMB0AFpX0NFEqSbx1OkTHf0f+0j82mkw+ZpzBnkk7e9Ql0891vlfgi+kHwOk8tQjiQHpqh4LaSa0fKEA==
  dependencies:
    "@babel/code-frame" "^7.23.5"
    "@babel/parser" "^7.24.0"
    "@babel/types" "^7.24.0"

"@babel/traverse@^7.23.2", "@babel/traverse@^7.23.3":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/traverse/-/traverse-7.23.3.tgz"
  integrity sha512-+K0yF1/9yR0oHdE0StHuEj3uTPzwwbrLGfNOndVJVV2TqA5+j3oljJUb4nmB954FLGjNem976+B+eDuLIjesiQ==
  dependencies:
    "@babel/code-frame" "^7.22.13"
    "@babel/generator" "^7.23.3"
    "@babel/helper-environment-visitor" "^7.22.20"
    "@babel/helper-function-name" "^7.23.0"
    "@babel/helper-hoist-variables" "^7.22.5"
    "@babel/helper-split-export-declaration" "^7.22.6"
    "@babel/parser" "^7.23.3"
    "@babel/types" "^7.23.3"
    debug "^4.1.0"
    globals "^11.1.0"

"@babel/traverse@^7.24.5":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/traverse/-/traverse-7.24.5.tgz#972aa0bc45f16983bf64aa1f877b2dd0eea7e6f8"
  integrity sha512-7aaBLeDQ4zYcUFDUD41lJc1fG8+5IU9DaNSJAgal866FGvmD5EbWQgnEC6kO1gGLsX0esNkfnJSndbTXA3r7UA==
  dependencies:
    "@babel/code-frame" "^7.24.2"
    "@babel/generator" "^7.24.5"
    "@babel/helper-environment-visitor" "^7.22.20"
    "@babel/helper-function-name" "^7.23.0"
    "@babel/helper-hoist-variables" "^7.22.5"
    "@babel/helper-split-export-declaration" "^7.24.5"
    "@babel/parser" "^7.24.5"
    "@babel/types" "^7.24.5"
    debug "^4.3.1"
    globals "^11.1.0"

"@babel/types@^7.0.0", "@babel/types@^7.20.7", "@babel/types@^7.22.15", "@babel/types@^7.22.5", "@babel/types@^7.23.0", "@babel/types@^7.23.3":
  version "7.23.3"
  resolved "https://registry.npmjs.org/@babel/types/-/types-7.23.3.tgz"
  integrity sha512-OZnvoH2l8PK5eUvEcUyCt/sXgr/h+UWpVuBbOljwcrAgUl6lpchoQ++PHGyQy1AtYnVA6CEq3y5xeEI10brpXw==
  dependencies:
    "@babel/helper-string-parser" "^7.22.5"
    "@babel/helper-validator-identifier" "^7.22.20"
    to-fast-properties "^2.0.0"

"@babel/types@^7.24.0", "@babel/types@^7.24.5", "@babel/types@^7.3.3":
  version "7.24.5"
  resolved "https://registry.yarnpkg.com/@babel/types/-/types-7.24.5.tgz#7661930afc638a5383eb0c4aee59b74f38db84d7"
  integrity sha512-6mQNsaLeXTw0nxYUYu+NSa4Hx4BlF1x1x8/PMFbiR+GBSr+2DkECc69b8hgy2frEodNcvPffeH8YfWd3LI6jhQ==
  dependencies:
    "@babel/helper-string-parser" "^7.24.1"
    "@babel/helper-validator-identifier" "^7.24.5"
    to-fast-properties "^2.0.0"

"@bcoe/v8-coverage@^0.2.3":
  version "0.2.3"
  resolved "https://registry.yarnpkg.com/@bcoe/v8-coverage/-/v8-coverage-0.2.3.tgz#75a2e8b51cb758a7553d6804a5932d7aace75c39"
  integrity sha512-0hYQ8SB4Db5zvZB4axdMHGwEaQjkZzFjQiN9LVYvIFB2nSUHW9tYpxWriPrWDASIxiaXax83REcLxuSdnGPZtw==

"@codemirror/autocomplete@^6.0.0":
  version "6.11.0"
  resolved "https://registry.yarnpkg.com/@codemirror/autocomplete/-/autocomplete-6.11.0.tgz#406dee8bf5342dfb48920ad75454d3406ddf9963"
  integrity sha512-LCPH3W+hl5vcO7OzEQgX6NpKuKVyiKFLGAy7FXROF6nUpsWUdQEgUb3fe/g7B0E1KZCRFfgzdKASt6Wly2UOBg==
  dependencies:
    "@codemirror/language" "^6.0.0"
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.17.0"
    "@lezer/common" "^1.0.0"

"@codemirror/commands@^6.0.0":
  version "6.3.0"
  resolved "https://registry.yarnpkg.com/@codemirror/commands/-/commands-6.3.0.tgz#cb7ad6ddc1e8af3a3c352135bd0348e6950b4e9d"
  integrity sha512-tFfcxRIlOWiQDFhjBSWJ10MxcvbCIsRr6V64SgrcaY0MwNk32cUOcCuNlWo8VjV4qRQCgNgUAnIeo0svkk4R5Q==
  dependencies:
    "@codemirror/language" "^6.0.0"
    "@codemirror/state" "^6.2.0"
    "@codemirror/view" "^6.0.0"
    "@lezer/common" "^1.1.0"

"@codemirror/lang-css@^6.0.0":
  version "6.2.1"
  resolved "https://registry.yarnpkg.com/@codemirror/lang-css/-/lang-css-6.2.1.tgz#5dc0a43b8e3c31f6af7aabd55ff07fe9aef2a227"
  integrity sha512-/UNWDNV5Viwi/1lpr/dIXJNWiwDxpw13I4pTUAsNxZdg6E0mI2kTQb0P2iHczg1Tu+H4EBgJR+hYhKiHKko7qg==
  dependencies:
    "@codemirror/autocomplete" "^6.0.0"
    "@codemirror/language" "^6.0.0"
    "@codemirror/state" "^6.0.0"
    "@lezer/common" "^1.0.2"
    "@lezer/css" "^1.0.0"

"@codemirror/lang-html@^6.4.6":
  version "6.4.6"
  resolved "https://registry.yarnpkg.com/@codemirror/lang-html/-/lang-html-6.4.6.tgz#25c1c71591da80e75dceb67ceeab41e87bde29a5"
  integrity sha512-E4C8CVupBksXvgLSme/zv31x91g06eZHSph7NczVxZW+/K+3XgJGWNT//2WLzaKSBoxpAjaOi5ZnPU1SHhjh3A==
  dependencies:
    "@codemirror/autocomplete" "^6.0.0"
    "@codemirror/lang-css" "^6.0.0"
    "@codemirror/lang-javascript" "^6.0.0"
    "@codemirror/language" "^6.4.0"
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.17.0"
    "@lezer/common" "^1.0.0"
    "@lezer/css" "^1.1.0"
    "@lezer/html" "^1.3.0"

"@codemirror/lang-javascript@^6.0.0":
  version "6.2.1"
  resolved "https://registry.yarnpkg.com/@codemirror/lang-javascript/-/lang-javascript-6.2.1.tgz#8068d44365d13cdb044936fb4e3483301c12ef95"
  integrity sha512-jlFOXTejVyiQCW3EQwvKH0m99bUYIw40oPmFjSX2VS78yzfe0HELZ+NEo9Yfo1MkGRpGlj3Gnu4rdxV1EnAs5A==
  dependencies:
    "@codemirror/autocomplete" "^6.0.0"
    "@codemirror/language" "^6.6.0"
    "@codemirror/lint" "^6.0.0"
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.17.0"
    "@lezer/common" "^1.0.0"
    "@lezer/javascript" "^1.0.0"

"@codemirror/language@^6.0.0", "@codemirror/language@^6.4.0", "@codemirror/language@^6.6.0":
  version "6.9.2"
  resolved "https://registry.yarnpkg.com/@codemirror/language/-/language-6.9.2.tgz#1fba6e0eab995afda683d4e6c556365a982b5258"
  integrity sha512-QGTQXSpAKDIzaSE96zNK1UfIUhPgkT1CLjh1N5qVzZuxgsEOhz5RqaN8QCIdyOQklGLx3MgHd9YrE3X3+Pl1ow==
  dependencies:
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.0.0"
    "@lezer/common" "^1.1.0"
    "@lezer/highlight" "^1.0.0"
    "@lezer/lr" "^1.0.0"
    style-mod "^4.0.0"

"@codemirror/lint@^6.0.0":
  version "6.4.2"
  resolved "https://registry.yarnpkg.com/@codemirror/lint/-/lint-6.4.2.tgz#c13be5320bde9707efdc94e8bcd3c698abae0b92"
  integrity sha512-wzRkluWb1ptPKdzlsrbwwjYCPLgzU6N88YBAmlZi8WFyuiEduSd05MnJYNogzyc8rPK7pj6m95ptUApc8sHKVA==
  dependencies:
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.0.0"
    crelt "^1.0.5"

"@codemirror/search@^6.0.0":
  version "6.5.4"
  resolved "https://registry.yarnpkg.com/@codemirror/search/-/search-6.5.4.tgz#54005697bf581f7dccbbb4a0c34d3a7aa25a513a"
  integrity sha512-YoTrvjv9e8EbPs58opjZKyJ3ewFrVSUzQ/4WXlULQLSDDr1nGPJ67mMXFNNVYwdFhybzhrzrtqgHmtpJwIF+8g==
  dependencies:
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.0.0"
    crelt "^1.0.5"

"@codemirror/state@^6.0.0", "@codemirror/state@^6.1.4", "@codemirror/state@^6.2.0":
  version "6.3.1"
  resolved "https://registry.yarnpkg.com/@codemirror/state/-/state-6.3.1.tgz#acabbbaeedcbfd31680704aba22102a75104f434"
  integrity sha512-88e4HhMtKJyw6fKprGaN/yZfiaoGYOi2nM45YCUC6R/kex9sxFWBDGatS1vk4lMgnWmdIIB9tk8Gj1LmL8YfvA==

"@codemirror/view@^6.0.0", "@codemirror/view@^6.17.0":
  version "6.22.0"
  resolved "https://registry.yarnpkg.com/@codemirror/view/-/view-6.22.0.tgz#5a5214a04f149ecf54c4803b7fec9bdac56d0d74"
  integrity sha512-6zLj4YIoIpfTGKrDMTbeZRpa8ih4EymMCKmddEDcJWrCdp/N1D46B38YEz4creTb4T177AVS9EyXkLeC/HL2jA==
  dependencies:
    "@codemirror/state" "^6.1.4"
    style-mod "^4.1.0"
    w3c-keyname "^2.2.4"

"@esbuild/android-arm64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/android-arm64/-/android-arm64-0.18.20.tgz#984b4f9c8d0377443cc2dfcef266d02244593622"
  integrity sha512-Nz4rJcchGDtENV0eMKUNa6L12zz2zBDXuhj/Vjh18zGqB44Bi7MBMSXjgunJgjRhCmKOjnPuZp4Mb6OKqtMHLQ==

"@esbuild/android-arm64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/android-arm64/-/android-arm64-0.19.8.tgz#fb7130103835b6d43ea499c3f30cfb2b2ed58456"
  integrity sha512-B8JbS61bEunhfx8kasogFENgQfr/dIp+ggYXwTqdbMAgGDhRa3AaPpQMuQU0rNxDLECj6FhDzk1cF9WHMVwrtA==

"@esbuild/android-arm@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/android-arm/-/android-arm-0.18.20.tgz#fedb265bc3a589c84cc11f810804f234947c3682"
  integrity sha512-fyi7TDI/ijKKNZTUJAQqiG5T7YjJXgnzkURqmGj13C6dCqckZBLdl4h7bkhHt/t0WP+zO9/zwroDvANaOqO5Sw==

"@esbuild/android-arm@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/android-arm/-/android-arm-0.19.8.tgz#b46e4d9e984e6d6db6c4224d72c86b7757e35bcb"
  integrity sha512-31E2lxlGM1KEfivQl8Yf5aYU/mflz9g06H6S15ITUFQueMFtFjESRMoDSkvMo8thYvLBax+VKTPlpnx+sPicOA==

"@esbuild/android-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/android-x64/-/android-x64-0.18.20.tgz#35cf419c4cfc8babe8893d296cd990e9e9f756f2"
  integrity sha512-8GDdlePJA8D6zlZYJV/jnrRAi6rOiNaCC/JclcXpB+KIuvfBN4owLtgzY2bsxnx666XjJx2kDPUmnTtR8qKQUg==

"@esbuild/android-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/android-x64/-/android-x64-0.19.8.tgz#a13db9441b5a4f4e4fec4a6f8ffacfea07888db7"
  integrity sha512-rdqqYfRIn4jWOp+lzQttYMa2Xar3OK9Yt2fhOhzFXqg0rVWEfSclJvZq5fZslnz6ypHvVf3CT7qyf0A5pM682A==

"@esbuild/darwin-arm64@0.18.20":
  version "0.18.20"
  resolved "https://registry.npmjs.org/@esbuild/darwin-arm64/-/darwin-arm64-0.18.20.tgz"
  integrity sha512-bxRHW5kHU38zS2lPTPOyuyTm+S+eobPUnTNkdJEfAddYgEcll4xkT8DB9d2008DtTbl7uJag2HuE5NZAZgnNEA==

"@esbuild/darwin-arm64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/darwin-arm64/-/darwin-arm64-0.19.8.tgz#49f5718d36541f40dd62bfdf84da9c65168a0fc2"
  integrity sha512-RQw9DemMbIq35Bprbboyf8SmOr4UXsRVxJ97LgB55VKKeJOOdvsIPy0nFyF2l8U+h4PtBx/1kRf0BelOYCiQcw==

"@esbuild/darwin-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/darwin-x64/-/darwin-x64-0.18.20.tgz#d70d5790d8bf475556b67d0f8b7c5bdff053d85d"
  integrity sha512-pc5gxlMDxzm513qPGbCbDukOdsGtKhfxD1zJKXjCCcU7ju50O7MeAZ8c4krSJcOIJGFR+qx21yMMVYwiQvyTyQ==

"@esbuild/darwin-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/darwin-x64/-/darwin-x64-0.19.8.tgz#75c5c88371eea4bfc1f9ecfd0e75104c74a481ac"
  integrity sha512-3sur80OT9YdeZwIVgERAysAbwncom7b4bCI2XKLjMfPymTud7e/oY4y+ci1XVp5TfQp/bppn7xLw1n/oSQY3/Q==

"@esbuild/freebsd-arm64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/freebsd-arm64/-/freebsd-arm64-0.18.20.tgz#98755cd12707f93f210e2494d6a4b51b96977f54"
  integrity sha512-yqDQHy4QHevpMAaxhhIwYPMv1NECwOvIpGCZkECn8w2WFHXjEwrBn3CeNIYsibZ/iZEUemj++M26W3cNR5h+Tw==

"@esbuild/freebsd-arm64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/freebsd-arm64/-/freebsd-arm64-0.19.8.tgz#9d7259fea4fd2b5f7437b52b542816e89d7c8575"
  integrity sha512-WAnPJSDattvS/XtPCTj1tPoTxERjcTpH6HsMr6ujTT+X6rylVe8ggxk8pVxzf5U1wh5sPODpawNicF5ta/9Tmw==

"@esbuild/freebsd-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/freebsd-x64/-/freebsd-x64-0.18.20.tgz#c1eb2bff03915f87c29cece4c1a7fa1f423b066e"
  integrity sha512-tgWRPPuQsd3RmBZwarGVHZQvtzfEBOreNuxEMKFcd5DaDn2PbBxfwLcj4+aenoh7ctXcbXmOQIn8HI6mCSw5MQ==

"@esbuild/freebsd-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/freebsd-x64/-/freebsd-x64-0.19.8.tgz#abac03e1c4c7c75ee8add6d76ec592f46dbb39e3"
  integrity sha512-ICvZyOplIjmmhjd6mxi+zxSdpPTKFfyPPQMQTK/w+8eNK6WV01AjIztJALDtwNNfFhfZLux0tZLC+U9nSyA5Zg==

"@esbuild/linux-arm64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-arm64/-/linux-arm64-0.18.20.tgz#bad4238bd8f4fc25b5a021280c770ab5fc3a02a0"
  integrity sha512-2YbscF+UL7SQAVIpnWvYwM+3LskyDmPhe31pE7/aoTMFKKzIc9lLbyGUpmmb8a8AixOL61sQ/mFh3jEjHYFvdA==

"@esbuild/linux-arm64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-arm64/-/linux-arm64-0.19.8.tgz#c577932cf4feeaa43cb9cec27b89cbe0df7d9098"
  integrity sha512-z1zMZivxDLHWnyGOctT9JP70h0beY54xDDDJt4VpTX+iwA77IFsE1vCXWmprajJGa+ZYSqkSbRQ4eyLCpCmiCQ==

"@esbuild/linux-arm@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-arm/-/linux-arm-0.18.20.tgz#3e617c61f33508a27150ee417543c8ab5acc73b0"
  integrity sha512-/5bHkMWnq1EgKr1V+Ybz3s1hWXok7mDFUMQ4cG10AfW3wL02PSZi5kFpYKrptDsgb2WAJIvRcDm+qIvXf/apvg==

"@esbuild/linux-arm@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-arm/-/linux-arm-0.19.8.tgz#d6014d8b98b5cbc96b95dad3d14d75bb364fdc0f"
  integrity sha512-H4vmI5PYqSvosPaTJuEppU9oz1dq2A7Mr2vyg5TF9Ga+3+MGgBdGzcyBP7qK9MrwFQZlvNyJrvz6GuCaj3OukQ==

"@esbuild/linux-ia32@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-ia32/-/linux-ia32-0.18.20.tgz#699391cccba9aee6019b7f9892eb99219f1570a7"
  integrity sha512-P4etWwq6IsReT0E1KHU40bOnzMHoH73aXp96Fs8TIT6z9Hu8G6+0SHSw9i2isWrD2nbx2qo5yUqACgdfVGx7TA==

"@esbuild/linux-ia32@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-ia32/-/linux-ia32-0.19.8.tgz#2379a0554307d19ac4a6cdc15b08f0ea28e7a40d"
  integrity sha512-1a8suQiFJmZz1khm/rDglOc8lavtzEMRo0v6WhPgxkrjcU0LkHj+TwBrALwoz/OtMExvsqbbMI0ChyelKabSvQ==

"@esbuild/linux-loong64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-loong64/-/linux-loong64-0.18.20.tgz#e6fccb7aac178dd2ffb9860465ac89d7f23b977d"
  integrity sha512-nXW8nqBTrOpDLPgPY9uV+/1DjxoQ7DoB2N8eocyq8I9XuqJ7BiAMDMf9n1xZM9TgW0J8zrquIb/A7s3BJv7rjg==

"@esbuild/linux-loong64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-loong64/-/linux-loong64-0.19.8.tgz#e2a5bbffe15748b49356a6cd7b2d5bf60c5a7123"
  integrity sha512-fHZWS2JJxnXt1uYJsDv9+b60WCc2RlvVAy1F76qOLtXRO+H4mjt3Tr6MJ5l7Q78X8KgCFudnTuiQRBhULUyBKQ==

"@esbuild/linux-mips64el@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-mips64el/-/linux-mips64el-0.18.20.tgz#eeff3a937de9c2310de30622a957ad1bd9183231"
  integrity sha512-d5NeaXZcHp8PzYy5VnXV3VSd2D328Zb+9dEq5HE6bw6+N86JVPExrA6O68OPwobntbNJ0pzCpUFZTo3w0GyetQ==

"@esbuild/linux-mips64el@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-mips64el/-/linux-mips64el-0.19.8.tgz#1359331e6f6214f26f4b08db9b9df661c57cfa24"
  integrity sha512-Wy/z0EL5qZYLX66dVnEg9riiwls5IYnziwuju2oUiuxVc+/edvqXa04qNtbrs0Ukatg5HEzqT94Zs7J207dN5Q==

"@esbuild/linux-ppc64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-ppc64/-/linux-ppc64-0.18.20.tgz#2f7156bde20b01527993e6881435ad79ba9599fb"
  integrity sha512-WHPyeScRNcmANnLQkq6AfyXRFr5D6N2sKgkFo2FqguP44Nw2eyDlbTdZwd9GYk98DZG9QItIiTlFLHJHjxP3FA==

"@esbuild/linux-ppc64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-ppc64/-/linux-ppc64-0.19.8.tgz#9ba436addc1646dc89dae48c62d3e951ffe70951"
  integrity sha512-ETaW6245wK23YIEufhMQ3HSeHO7NgsLx8gygBVldRHKhOlD1oNeNy/P67mIh1zPn2Hr2HLieQrt6tWrVwuqrxg==

"@esbuild/linux-riscv64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-riscv64/-/linux-riscv64-0.18.20.tgz#6628389f210123d8b4743045af8caa7d4ddfc7a6"
  integrity sha512-WSxo6h5ecI5XH34KC7w5veNnKkju3zBRLEQNY7mv5mtBmrP/MjNBCAlsM2u5hDBlS3NGcTQpoBvRzqBcRtpq1A==

"@esbuild/linux-riscv64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-riscv64/-/linux-riscv64-0.19.8.tgz#fbcf0c3a0b20f40b5fc31c3b7695f0769f9de66b"
  integrity sha512-T2DRQk55SgoleTP+DtPlMrxi/5r9AeFgkhkZ/B0ap99zmxtxdOixOMI570VjdRCs9pE4Wdkz7JYrsPvsl7eESg==

"@esbuild/linux-s390x@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-s390x/-/linux-s390x-0.18.20.tgz#255e81fb289b101026131858ab99fba63dcf0071"
  integrity sha512-+8231GMs3mAEth6Ja1iK0a1sQ3ohfcpzpRLH8uuc5/KVDFneH6jtAJLFGafpzpMRO6DzJ6AvXKze9LfFMrIHVQ==

"@esbuild/linux-s390x@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-s390x/-/linux-s390x-0.19.8.tgz#989e8a05f7792d139d5564ffa7ff898ac6f20a4a"
  integrity sha512-NPxbdmmo3Bk7mbNeHmcCd7R7fptJaczPYBaELk6NcXxy7HLNyWwCyDJ/Xx+/YcNH7Im5dHdx9gZ5xIwyliQCbg==

"@esbuild/linux-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-x64/-/linux-x64-0.18.20.tgz#c7690b3417af318a9b6f96df3031a8865176d338"
  integrity sha512-UYqiqemphJcNsFEskc73jQ7B9jgwjWrSayxawS6UVFZGWrAAtkzjxSqnoclCXxWtfwLdzU+vTpcNYhpn43uP1w==

"@esbuild/linux-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/linux-x64/-/linux-x64-0.19.8.tgz#b187295393a59323397fe5ff51e769ec4e72212b"
  integrity sha512-lytMAVOM3b1gPypL2TRmZ5rnXl7+6IIk8uB3eLsV1JwcizuolblXRrc5ShPrO9ls/b+RTp+E6gbsuLWHWi2zGg==

"@esbuild/netbsd-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/netbsd-x64/-/netbsd-x64-0.18.20.tgz#30e8cd8a3dded63975e2df2438ca109601ebe0d1"
  integrity sha512-iO1c++VP6xUBUmltHZoMtCUdPlnPGdBom6IrO4gyKPFFVBKioIImVooR5I83nTew5UOYrk3gIJhbZh8X44y06A==

"@esbuild/netbsd-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/netbsd-x64/-/netbsd-x64-0.19.8.tgz#c1ec0e24ea82313cb1c7bae176bd5acd5bde7137"
  integrity sha512-hvWVo2VsXz/8NVt1UhLzxwAfo5sioj92uo0bCfLibB0xlOmimU/DeAEsQILlBQvkhrGjamP0/el5HU76HAitGw==

"@esbuild/openbsd-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/openbsd-x64/-/openbsd-x64-0.18.20.tgz#7812af31b205055874c8082ea9cf9ab0da6217ae"
  integrity sha512-e5e4YSsuQfX4cxcygw/UCPIEP6wbIL+se3sxPdCiMbFLBWu0eiZOJ7WoD+ptCLrmjZBK1Wk7I6D/I3NglUGOxg==

"@esbuild/openbsd-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/openbsd-x64/-/openbsd-x64-0.19.8.tgz#0c5b696ac66c6d70cf9ee17073a581a28af9e18d"
  integrity sha512-/7Y7u77rdvmGTxR83PgaSvSBJCC2L3Kb1M/+dmSIvRvQPXXCuC97QAwMugBNG0yGcbEGfFBH7ojPzAOxfGNkwQ==

"@esbuild/sunos-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/sunos-x64/-/sunos-x64-0.18.20.tgz#d5c275c3b4e73c9b0ecd38d1ca62c020f887ab9d"
  integrity sha512-kDbFRFp0YpTQVVrqUd5FTYmWo45zGaXe0X8E1G/LKFC0v8x0vWrhOWSLITcCn63lmZIxfOMXtCfti/RxN/0wnQ==

"@esbuild/sunos-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/sunos-x64/-/sunos-x64-0.19.8.tgz#2a697e1f77926ff09fcc457d8f29916d6cd48fb1"
  integrity sha512-9Lc4s7Oi98GqFA4HzA/W2JHIYfnXbUYgekUP/Sm4BG9sfLjyv6GKKHKKVs83SMicBF2JwAX6A1PuOLMqpD001w==

"@esbuild/win32-arm64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-arm64/-/win32-arm64-0.18.20.tgz#73bc7f5a9f8a77805f357fab97f290d0e4820ac9"
  integrity sha512-ddYFR6ItYgoaq4v4JmQQaAI5s7npztfV4Ag6NrhiaW0RrnOXqBkgwZLofVTlq1daVTQNhtI5oieTvkRPfZrePg==

"@esbuild/win32-arm64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-arm64/-/win32-arm64-0.19.8.tgz#ec029e62a2fca8c071842ecb1bc5c2dd20b066f1"
  integrity sha512-rq6WzBGjSzihI9deW3fC2Gqiak68+b7qo5/3kmB6Gvbh/NYPA0sJhrnp7wgV4bNwjqM+R2AApXGxMO7ZoGhIJg==

"@esbuild/win32-ia32@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-ia32/-/win32-ia32-0.18.20.tgz#ec93cbf0ef1085cc12e71e0d661d20569ff42102"
  integrity sha512-Wv7QBi3ID/rROT08SABTS7eV4hX26sVduqDOTe1MvGMjNd3EjOz4b7zeexIR62GTIEKrfJXKL9LFxTYgkyeu7g==

"@esbuild/win32-ia32@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-ia32/-/win32-ia32-0.19.8.tgz#cbb9a3146bde64dc15543e48afe418c7a3214851"
  integrity sha512-AIAbverbg5jMvJznYiGhrd3sumfwWs8572mIJL5NQjJa06P8KfCPWZQ0NwZbPQnbQi9OWSZhFVSUWjjIrn4hSw==

"@esbuild/win32-x64@0.18.20":
  version "0.18.20"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-x64/-/win32-x64-0.18.20.tgz#786c5f41f043b07afb1af37683d7c33668858f6d"
  integrity sha512-kTdfRcSiDfQca/y9QIkng02avJ+NCaQvrMejlsB3RRv5sE9rRoeBPISaZpKxHELzRxZyLvNts1P27W3wV+8geQ==

"@esbuild/win32-x64@0.19.8":
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/@esbuild/win32-x64/-/win32-x64-0.19.8.tgz#c8285183dbdb17008578dbacb6e22748709b4822"
  integrity sha512-bfZ0cQ1uZs2PqpulNL5j/3w+GDhP36k1K5c38QdQg+Swy51jFZWWeIkteNsufkQxp986wnqRRsb/bHbY1WQ7TA==

"@eslint-community/eslint-utils@^4.2.0", "@eslint-community/eslint-utils@^4.4.0":
  version "4.4.0"
  resolved "https://registry.npmjs.org/@eslint-community/eslint-utils/-/eslint-utils-4.4.0.tgz"
  integrity sha512-1/sA4dwrzBAyeUoQ6oxahHKmrZvsnLCg4RfxW3ZFGGmQkSNQPFNLV9CUEFQP1x9EYXHTo5p6xdhZM1Ne9p/AfA==
  dependencies:
    eslint-visitor-keys "^3.3.0"

"@eslint-community/regexpp@^4.5.1", "@eslint-community/regexpp@^4.6.1":
  version "4.10.0"
  resolved "https://registry.npmjs.org/@eslint-community/regexpp/-/regexpp-4.10.0.tgz"
  integrity sha512-Cu96Sd2By9mCNTx2iyKOmq10v22jUVQv0lQnlGNy16oE9589yE+QADPbrMGCkA51cKZSg3Pu/aTJVTGfL/qjUA==

"@eslint/eslintrc@^2.1.3":
  version "2.1.3"
  resolved "https://registry.npmjs.org/@eslint/eslintrc/-/eslintrc-2.1.3.tgz"
  integrity sha512-yZzuIG+jnVu6hNSzFEN07e8BxF3uAzYtQb6uDkaYZLo6oYZDCq454c5kB8zxnzfCYyP4MIuyBn10L0DqwujTmA==
  dependencies:
    ajv "^6.12.4"
    debug "^4.3.2"
    espree "^9.6.0"
    globals "^13.19.0"
    ignore "^5.2.0"
    import-fresh "^3.2.1"
    js-yaml "^4.1.0"
    minimatch "^3.1.2"
    strip-json-comments "^3.1.1"

"@eslint/js@8.53.0":
  version "8.53.0"
  resolved "https://registry.npmjs.org/@eslint/js/-/js-8.53.0.tgz"
  integrity sha512-Kn7K8dx/5U6+cT1yEhpX1w4PCSg0M+XyRILPgvwcEBjerFWCwQj5sbr3/VmxqV0JGHCBCzyd6LxypEuehypY1w==

"@floating-ui/core@^1.4.2":
  version "1.5.0"
  resolved "https://registry.yarnpkg.com/@floating-ui/core/-/core-1.5.0.tgz#5c05c60d5ae2d05101c3021c1a2a350ddc027f8c"
  integrity sha512-kK1h4m36DQ0UHGj5Ah4db7R0rHemTqqO0QLvUqi1/mUUp3LuAWbWxdxSIf/XsnH9VS6rRVPLJCncjRzUvyCLXg==
  dependencies:
    "@floating-ui/utils" "^0.1.3"

"@floating-ui/dom@^1.5.1":
  version "1.5.3"
  resolved "https://registry.yarnpkg.com/@floating-ui/dom/-/dom-1.5.3.tgz#54e50efcb432c06c23cd33de2b575102005436fa"
  integrity sha512-ClAbQnEqJAKCJOEbbLo5IUlZHkNszqhuxS4fHAVxRPXPya6Ysf2G8KypnYcOTpx6I8xcgF9bbHb6g/2KpbV8qA==
  dependencies:
    "@floating-ui/core" "^1.4.2"
    "@floating-ui/utils" "^0.1.3"

"@floating-ui/react-dom@^2.0.0":
  version "2.0.4"
  resolved "https://registry.yarnpkg.com/@floating-ui/react-dom/-/react-dom-2.0.4.tgz#b076fafbdfeb881e1d86ae748b7ff95150e9f3ec"
  integrity sha512-CF8k2rgKeh/49UrnIBs4BdxPUV6vize/Db1d/YbCLyp9GiVZ0BEwf5AiDSxJRCr6yOkGqTFHtmrULxkEfYZ7dQ==
  dependencies:
    "@floating-ui/dom" "^1.5.1"

"@floating-ui/utils@^0.1.3":
  version "0.1.6"
  resolved "https://registry.yarnpkg.com/@floating-ui/utils/-/utils-0.1.6.tgz#22958c042e10b67463997bd6ea7115fe28cbcaf9"
  integrity sha512-OfX7E2oUDYxtBvsuS4e/jSn4Q9Qb6DzgeYtsAdkPZ47znpoNsMgZw0+tVijiv3uGNR6dgNlty6r9rzIzHjtd/A==

"@humanwhocodes/config-array@^0.11.13":
  version "0.11.13"
  resolved "https://registry.npmjs.org/@humanwhocodes/config-array/-/config-array-0.11.13.tgz"
  integrity sha512-JSBDMiDKSzQVngfRjOdFXgFfklaXI4K9nLF49Auh21lmBWRLIK3+xTErTWD4KU54pb6coM6ESE7Awz/FNU3zgQ==
  dependencies:
    "@humanwhocodes/object-schema" "^2.0.1"
    debug "^4.1.1"
    minimatch "^3.0.5"

"@humanwhocodes/module-importer@^1.0.1":
  version "1.0.1"
  resolved "https://registry.npmjs.org/@humanwhocodes/module-importer/-/module-importer-1.0.1.tgz"
  integrity sha512-bxveV4V8v5Yb4ncFTT3rPSgZBOpCkjfK0y4oVVVJwIuDVBRMDXrPyXRL988i5ap9m9bnyEEjWfm5WkBmtffLfA==

"@humanwhocodes/object-schema@^2.0.1":
  version "2.0.1"
  resolved "https://registry.npmjs.org/@humanwhocodes/object-schema/-/object-schema-2.0.1.tgz"
  integrity sha512-dvuCeX5fC9dXgJn9t+X5atfmgQAzUOWqS1254Gh0m6i8wKd10ebXkfNKiRK+1GWi/yTvvLDHpoxLr0xxxeslWw==

"@istanbuljs/load-nyc-config@^1.0.0":
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/@istanbuljs/load-nyc-config/-/load-nyc-config-1.1.0.tgz#fd3db1d59ecf7cf121e80650bb86712f9b55eced"
  integrity sha512-VjeHSlIzpv/NyD3N0YuHfXOPDIixcA1q2ZV98wsMqcYlPmv2n3Yb2lYP9XMElnaFVXg5A7YLTeLu6V84uQDjmQ==
  dependencies:
    camelcase "^5.3.1"
    find-up "^4.1.0"
    get-package-type "^0.1.0"
    js-yaml "^3.13.1"
    resolve-from "^5.0.0"

"@istanbuljs/schema@^0.1.2", "@istanbuljs/schema@^0.1.3":
  version "0.1.3"
  resolved "https://registry.yarnpkg.com/@istanbuljs/schema/-/schema-0.1.3.tgz#e45e384e4b8ec16bce2fd903af78450f6bf7ec98"
  integrity sha512-ZXRY4jNvVgSVQ8DL3LTcakaAtXwTVUxE81hslsyD2AtoXW/wVob10HkOJ1X/pAlcI7D+2YoZKg5do8G/w6RYgA==

"@jest/console@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/console/-/console-29.7.0.tgz#cd4822dbdb84529265c5a2bdb529a3c9cc950ffc"
  integrity sha512-5Ni4CU7XHQi32IJ398EEP4RrB8eV09sXP2ROqD4bksHrnTree52PsxvX8tpL8LvTZ3pFzXyPbNQReSN41CAhOg==
  dependencies:
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    chalk "^4.0.0"
    jest-message-util "^29.7.0"
    jest-util "^29.7.0"
    slash "^3.0.0"

"@jest/core@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/core/-/core-29.7.0.tgz#b6cccc239f30ff36609658c5a5e2291757ce448f"
  integrity sha512-n7aeXWKMnGtDA48y8TLWJPJmLmmZ642Ceo78cYWEpiD7FzDgmNDV/GCVRorPABdXLJZ/9wzzgZAlHjXjxDHGsg==
  dependencies:
    "@jest/console" "^29.7.0"
    "@jest/reporters" "^29.7.0"
    "@jest/test-result" "^29.7.0"
    "@jest/transform" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    ansi-escapes "^4.2.1"
    chalk "^4.0.0"
    ci-info "^3.2.0"
    exit "^0.1.2"
    graceful-fs "^4.2.9"
    jest-changed-files "^29.7.0"
    jest-config "^29.7.0"
    jest-haste-map "^29.7.0"
    jest-message-util "^29.7.0"
    jest-regex-util "^29.6.3"
    jest-resolve "^29.7.0"
    jest-resolve-dependencies "^29.7.0"
    jest-runner "^29.7.0"
    jest-runtime "^29.7.0"
    jest-snapshot "^29.7.0"
    jest-util "^29.7.0"
    jest-validate "^29.7.0"
    jest-watcher "^29.7.0"
    micromatch "^4.0.4"
    pretty-format "^29.7.0"
    slash "^3.0.0"
    strip-ansi "^6.0.0"

"@jest/environment@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/environment/-/environment-29.7.0.tgz#24d61f54ff1f786f3cd4073b4b94416383baf2a7"
  integrity sha512-aQIfHDq33ExsN4jP1NWGXhxgQ/wixs60gDiKO+XVMd8Mn0NWPWgc34ZQDTb2jKaUWQ7MuwoitXAsN2XVXNMpAw==
  dependencies:
    "@jest/fake-timers" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    jest-mock "^29.7.0"

"@jest/expect-utils@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/expect-utils/-/expect-utils-29.7.0.tgz#023efe5d26a8a70f21677d0a1afc0f0a44e3a1c6"
  integrity sha512-GlsNBWiFQFCVi9QVSx7f5AgMeLxe9YCCs5PuP2O2LdjDAA8Jh9eX7lA1Jq/xdXw3Wb3hyvlFNfZIfcRetSzYcA==
  dependencies:
    jest-get-type "^29.6.3"

"@jest/expect@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/expect/-/expect-29.7.0.tgz#76a3edb0cb753b70dfbfe23283510d3d45432bf2"
  integrity sha512-8uMeAMycttpva3P1lBHB8VciS9V0XAr3GymPpipdyQXbBcuhkLQOSe8E/p92RyAdToS6ZD1tFkX+CkhoECE0dQ==
  dependencies:
    expect "^29.7.0"
    jest-snapshot "^29.7.0"

"@jest/fake-timers@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/fake-timers/-/fake-timers-29.7.0.tgz#fd91bf1fffb16d7d0d24a426ab1a47a49881a565"
  integrity sha512-q4DH1Ha4TTFPdxLsqDXK1d3+ioSL7yL5oCMJZgDYm6i+6CygW5E5xVr/D1HdsGxjt1ZWSfUAs9OxSB/BNelWrQ==
  dependencies:
    "@jest/types" "^29.6.3"
    "@sinonjs/fake-timers" "^10.0.2"
    "@types/node" "*"
    jest-message-util "^29.7.0"
    jest-mock "^29.7.0"
    jest-util "^29.7.0"

"@jest/globals@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/globals/-/globals-29.7.0.tgz#8d9290f9ec47ff772607fa864ca1d5a2efae1d4d"
  integrity sha512-mpiz3dutLbkW2MNFubUGUEVLkTGiqW6yLVTA+JbP6fI6J5iL9Y0Nlg8k95pcF8ctKwCS7WVxteBs29hhfAotzQ==
  dependencies:
    "@jest/environment" "^29.7.0"
    "@jest/expect" "^29.7.0"
    "@jest/types" "^29.6.3"
    jest-mock "^29.7.0"

"@jest/reporters@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/reporters/-/reporters-29.7.0.tgz#04b262ecb3b8faa83b0b3d321623972393e8f4c7"
  integrity sha512-DApq0KJbJOEzAFYjHADNNxAE3KbhxQB1y5Kplb5Waqw6zVbuWatSnMjE5gs8FUgEPmNsnZA3NCWl9NG0ia04Pg==
  dependencies:
    "@bcoe/v8-coverage" "^0.2.3"
    "@jest/console" "^29.7.0"
    "@jest/test-result" "^29.7.0"
    "@jest/transform" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@jridgewell/trace-mapping" "^0.3.18"
    "@types/node" "*"
    chalk "^4.0.0"
    collect-v8-coverage "^1.0.0"
    exit "^0.1.2"
    glob "^7.1.3"
    graceful-fs "^4.2.9"
    istanbul-lib-coverage "^3.0.0"
    istanbul-lib-instrument "^6.0.0"
    istanbul-lib-report "^3.0.0"
    istanbul-lib-source-maps "^4.0.0"
    istanbul-reports "^3.1.3"
    jest-message-util "^29.7.0"
    jest-util "^29.7.0"
    jest-worker "^29.7.0"
    slash "^3.0.0"
    string-length "^4.0.1"
    strip-ansi "^6.0.0"
    v8-to-istanbul "^9.0.1"

"@jest/schemas@^29.6.3":
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/@jest/schemas/-/schemas-29.6.3.tgz#430b5ce8a4e0044a7e3819663305a7b3091c8e03"
  integrity sha512-mo5j5X+jIZmJQveBKeS/clAueipV7KgiX1vMgCxam1RNYiqE1w62n0/tJJnHtjW8ZHcQco5gY85jA3mi0L+nSA==
  dependencies:
    "@sinclair/typebox" "^0.27.8"

"@jest/source-map@^29.6.3":
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/@jest/source-map/-/source-map-29.6.3.tgz#d90ba772095cf37a34a5eb9413f1b562a08554c4"
  integrity sha512-MHjT95QuipcPrpLM+8JMSzFx6eHp5Bm+4XeFDJlwsvVBjmKNiIAvasGK2fxz2WbGRlnvqehFbh07MMa7n3YJnw==
  dependencies:
    "@jridgewell/trace-mapping" "^0.3.18"
    callsites "^3.0.0"
    graceful-fs "^4.2.9"

"@jest/test-result@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/test-result/-/test-result-29.7.0.tgz#8db9a80aa1a097bb2262572686734baed9b1657c"
  integrity sha512-Fdx+tv6x1zlkJPcWXmMDAG2HBnaR9XPSd5aDWQVsfrZmLVT3lU1cwyxLgRmXR9yrq4NBoEm9BMsfgFzTQAbJYA==
  dependencies:
    "@jest/console" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/istanbul-lib-coverage" "^2.0.0"
    collect-v8-coverage "^1.0.0"

"@jest/test-sequencer@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/test-sequencer/-/test-sequencer-29.7.0.tgz#6cef977ce1d39834a3aea887a1726628a6f072ce"
  integrity sha512-GQwJ5WZVrKnOJuiYiAF52UNUJXgTZx1NHjFSEB0qEMmSZKAkdMoIzw/Cj6x6NF4AvV23AUqDpFzQkN/eYCYTxw==
  dependencies:
    "@jest/test-result" "^29.7.0"
    graceful-fs "^4.2.9"
    jest-haste-map "^29.7.0"
    slash "^3.0.0"

"@jest/transform@^29.7.0":
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/@jest/transform/-/transform-29.7.0.tgz#df2dd9c346c7d7768b8a06639994640c642e284c"
  integrity sha512-ok/BTPFzFKVMwO5eOHRrvnBVHdRy9IrsrW1GpMaQ9MCnilNLXQKmAX8s1YXDFaai9xJpac2ySzV0YeRRECr2Vw==
  dependencies:
    "@babel/core" "^7.11.6"
    "@jest/types" "^29.6.3"
    "@jridgewell/trace-mapping" "^0.3.18"
    babel-plugin-istanbul "^6.1.1"
    chalk "^4.0.0"
    convert-source-map "^2.0.0"
    fast-json-stable-stringify "^2.1.0"
    graceful-fs "^4.2.9"
    jest-haste-map "^29.7.0"
    jest-regex-util "^29.6.3"
    jest-util "^29.7.0"
    micromatch "^4.0.4"
    pirates "^4.0.4"
    slash "^3.0.0"
    write-file-atomic "^4.0.2"

"@jest/types@^29.6.3":
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/@jest/types/-/types-29.6.3.tgz#1131f8cf634e7e84c5e77bab12f052af585fba59"
  integrity sha512-u3UPsIilWKOM3F9CXtrG8LEJmNxwoCQC/XVj4IKYXvvpx7QIi/Kg1LI5uDmDpKlac62NUtX7eLjRh+jVZcLOzw==
  dependencies:
    "@jest/schemas" "^29.6.3"
    "@types/istanbul-lib-coverage" "^2.0.0"
    "@types/istanbul-reports" "^3.0.0"
    "@types/node" "*"
    "@types/yargs" "^17.0.8"
    chalk "^4.0.0"

"@jridgewell/gen-mapping@^0.3.0", "@jridgewell/gen-mapping@^0.3.2":
  version "0.3.3"
  resolved "https://registry.npmjs.org/@jridgewell/gen-mapping/-/gen-mapping-0.3.3.tgz"
  integrity sha512-HLhSWOLRi875zjjMG/r+Nv0oCW8umGb0BgEhyX3dDX3egwZtB8PqLnjz3yedt8R5StBrzcg4aBpnh8UA9D1BoQ==
  dependencies:
    "@jridgewell/set-array" "^1.0.1"
    "@jridgewell/sourcemap-codec" "^1.4.10"
    "@jridgewell/trace-mapping" "^0.3.9"

"@jridgewell/gen-mapping@^0.3.5":
  version "0.3.5"
  resolved "https://registry.yarnpkg.com/@jridgewell/gen-mapping/-/gen-mapping-0.3.5.tgz#dcce6aff74bdf6dad1a95802b69b04a2fcb1fb36"
  integrity sha512-IzL8ZoEDIBRWEzlCcRhOaCupYyN5gdIK+Q6fbFdPDg6HqX6jpkItn7DFIpW9LQzXG6Df9sA7+OKnq0qlz/GaQg==
  dependencies:
    "@jridgewell/set-array" "^1.2.1"
    "@jridgewell/sourcemap-codec" "^1.4.10"
    "@jridgewell/trace-mapping" "^0.3.24"

"@jridgewell/resolve-uri@^3.1.0":
  version "3.1.1"
  resolved "https://registry.npmjs.org/@jridgewell/resolve-uri/-/resolve-uri-3.1.1.tgz"
  integrity sha512-dSYZh7HhCDtCKm4QakX0xFpsRDqjjtZf/kjI/v3T3Nwt5r8/qz/M19F9ySyOqU94SXBmeG9ttTul+YnR4LOxFA==

"@jridgewell/set-array@^1.0.1":
  version "1.1.2"
  resolved "https://registry.npmjs.org/@jridgewell/set-array/-/set-array-1.1.2.tgz"
  integrity sha512-xnkseuNADM0gt2bs+BvhO0p78Mk762YnZdsuzFV018NoG1Sj1SCQvpSqa7XUaTam5vAGasABV9qXASMKnFMwMw==

"@jridgewell/set-array@^1.2.1":
  version "1.2.1"
  resolved "https://registry.yarnpkg.com/@jridgewell/set-array/-/set-array-1.2.1.tgz#558fb6472ed16a4c850b889530e6b36438c49280"
  integrity sha512-R8gLRTZeyp03ymzP/6Lil/28tGeGEzhx1q2k703KGWRAI1VdvPIXdG70VJc2pAMw3NA6JKL5hhFu1sJX0Mnn/A==

"@jridgewell/source-map@^0.3.3":
  version "0.3.5"
  resolved "https://registry.yarnpkg.com/@jridgewell/source-map/-/source-map-0.3.5.tgz#a3bb4d5c6825aab0d281268f47f6ad5853431e91"
  integrity sha512-UTYAUj/wviwdsMfzoSJspJxbkH5o1snzwX0//0ENX1u/55kkZZkcTZP6u9bwKGkv+dkk9at4m1Cpt0uY80kcpQ==
  dependencies:
    "@jridgewell/gen-mapping" "^0.3.0"
    "@jridgewell/trace-mapping" "^0.3.9"

"@jridgewell/sourcemap-codec@^1.4.10", "@jridgewell/sourcemap-codec@^1.4.14", "@jridgewell/sourcemap-codec@^1.4.15":
  version "1.4.15"
  resolved "https://registry.npmjs.org/@jridgewell/sourcemap-codec/-/sourcemap-codec-1.4.15.tgz"
  integrity sha512-eF2rxCRulEKXHTRiDrDy6erMYWqNw4LPdQ8UQA4huuxaQsVeRPFl2oM8oDGxMFhJUWZf9McpLtJasDDZb/Bpeg==

"@jridgewell/trace-mapping@^0.3.12", "@jridgewell/trace-mapping@^0.3.18", "@jridgewell/trace-mapping@^0.3.24", "@jridgewell/trace-mapping@^0.3.25":
  version "0.3.25"
  resolved "https://registry.yarnpkg.com/@jridgewell/trace-mapping/-/trace-mapping-0.3.25.tgz#15f190e98895f3fc23276ee14bc76b675c2e50f0"
  integrity sha512-vNk6aEwybGtawWmy/PzwnGDOjCkLWSD2wqvjGGAgOAwCGWySYXfYoxt00IJkTF+8Lb57DwOb3Aa0o9CApepiYQ==
  dependencies:
    "@jridgewell/resolve-uri" "^3.1.0"
    "@jridgewell/sourcemap-codec" "^1.4.14"

"@jridgewell/trace-mapping@^0.3.17", "@jridgewell/trace-mapping@^0.3.9":
  version "0.3.20"
  resolved "https://registry.npmjs.org/@jridgewell/trace-mapping/-/trace-mapping-0.3.20.tgz"
  integrity sha512-R8LcPeWZol2zR8mmH3JeKQ6QRCFb7XgUhV9ZlGhHLGyg4wpPiPZNQOOWhFZhxKw8u//yTbNGI42Bx/3paXEQ+Q==
  dependencies:
    "@jridgewell/resolve-uri" "^3.1.0"
    "@jridgewell/sourcemap-codec" "^1.4.14"

"@lezer/common@^1.0.0", "@lezer/common@^1.0.2", "@lezer/common@^1.1.0":
  version "1.1.1"
  resolved "https://registry.yarnpkg.com/@lezer/common/-/common-1.1.1.tgz#4a06a0e1b9214d7eb2ea4a9354d47a63044cee49"
  integrity sha512-aAPB9YbvZHqAW+bIwiuuTDGB4DG0sYNRObGLxud8cW7osw1ZQxfDuTZ8KQiqfZ0QJGcR34CvpTMDXEyo/+Htgg==

"@lezer/css@^1.0.0", "@lezer/css@^1.1.0":
  version "1.1.4"
  resolved "https://registry.yarnpkg.com/@lezer/css/-/css-1.1.4.tgz#428923881b102ee55e3bdc1e169639c942e71c24"
  integrity sha512-CuUwjidrU7FOBokqASRJc72SmJ9g1PsHXDOWMoKg4md6+2u/Zxzwx5YsYrAFxRDsLrjLlsIyEF1rZHK3gFEJbw==
  dependencies:
    "@lezer/highlight" "^1.0.0"
    "@lezer/lr" "^1.0.0"

"@lezer/highlight@^1.0.0", "@lezer/highlight@^1.1.3":
  version "1.2.0"
  resolved "https://registry.yarnpkg.com/@lezer/highlight/-/highlight-1.2.0.tgz#e5898c3644208b4b589084089dceeea2966f7780"
  integrity sha512-WrS5Mw51sGrpqjlh3d4/fOwpEV2Hd3YOkp9DBt4k8XZQcoTHZFB7sx030A6OcahF4J1nDQAa3jXlTVVYH50IFA==
  dependencies:
    "@lezer/common" "^1.0.0"

"@lezer/html@^1.3.0":
  version "1.3.6"
  resolved "https://registry.yarnpkg.com/@lezer/html/-/html-1.3.6.tgz#26a2a17da4e0f91835e36db9ccd025b2ed8d33f7"
  integrity sha512-Kk9HJARZTc0bAnMQUqbtuhFVsB4AnteR2BFUWfZV7L/x1H0aAKz6YabrfJ2gk/BEgjh9L3hg5O4y2IDZRBdzuQ==
  dependencies:
    "@lezer/common" "^1.0.0"
    "@lezer/highlight" "^1.0.0"
    "@lezer/lr" "^1.0.0"

"@lezer/javascript@^1.0.0":
  version "1.4.9"
  resolved "https://registry.yarnpkg.com/@lezer/javascript/-/javascript-1.4.9.tgz#1536427af5187621b3b616f21b6a21df3ffd1dbe"
  integrity sha512-7Uv8mBBE6l44spgWEZvEMdDqGV+FIuY7kJ1o5TFm+jxIuxydO3PcKJYiINij09igd1D/9P7l2KDqpkN8c3bM6A==
  dependencies:
    "@lezer/highlight" "^1.1.3"
    "@lezer/lr" "^1.3.0"

"@lezer/lr@^1.0.0", "@lezer/lr@^1.3.0":
  version "1.3.14"
  resolved "https://registry.yarnpkg.com/@lezer/lr/-/lr-1.3.14.tgz#59d4a3b25698bdac0ef182fa6eadab445fc4f29a"
  integrity sha512-z5mY4LStlA3yL7aHT/rqgG614cfcvklS+8oFRFBYrs4YaWLJyKKM4+nN6KopToX0o9Hj6zmH6M5kinOYuy06ug==
  dependencies:
    "@lezer/common" "^1.0.0"

"@nodelib/fs.scandir@2.1.5":
  version "2.1.5"
  resolved "https://registry.npmjs.org/@nodelib/fs.scandir/-/fs.scandir-2.1.5.tgz"
  integrity sha512-vq24Bq3ym5HEQm2NKCr3yXDwjc7vTsEThRDnkp2DK9p1uqLR+DHurm/NOTo0KG7HYHU7eppKZj3MyqYuMBf62g==
  dependencies:
    "@nodelib/fs.stat" "2.0.5"
    run-parallel "^1.1.9"

"@nodelib/fs.stat@2.0.5", "@nodelib/fs.stat@^2.0.2":
  version "2.0.5"
  resolved "https://registry.npmjs.org/@nodelib/fs.stat/-/fs.stat-2.0.5.tgz"
  integrity sha512-RkhPPp2zrqDAQA/2jNhnztcPAlv64XdhIp7a7454A5ovI7Bukxgt7MX7udwAu3zg1DcpPU0rz3VV1SeaqvY4+A==

"@nodelib/fs.walk@^1.2.3", "@nodelib/fs.walk@^1.2.8":
  version "1.2.8"
  resolved "https://registry.npmjs.org/@nodelib/fs.walk/-/fs.walk-1.2.8.tgz"
  integrity sha512-oGB+UxlgWcgQkgwo8GcEGwemoTFt3FIO9ababBmaGwXIoBKZ+GTy0pP185beGg7Llih/NSHSV2XAs1lnznocSg==
  dependencies:
    "@nodelib/fs.scandir" "2.1.5"
    fastq "^1.6.0"

"@puppeteer/browsers@2.2.1":
  version "2.2.1"
  resolved "https://registry.yarnpkg.com/@puppeteer/browsers/-/browsers-2.2.1.tgz#c40608b96b10c09a6b2d08ab5ea31dfe1b409455"
  integrity sha512-QSXujx4d4ogDamQA8ckkkRieFzDgZEuZuGiey9G7CuDcbnX4iINKWxTPC5Br2AEzY9ICAvcndqgAUFMMKnS/Tw==
  dependencies:
    debug "4.3.4"
    extract-zip "2.0.1"
    progress "2.0.3"
    proxy-agent "6.4.0"
    semver "7.6.0"
    tar-fs "3.0.5"
    unbzip2-stream "1.4.3"
    yargs "17.7.2"

"@puppeteer/browsers@2.2.3":
  version "2.2.3"
  resolved "https://registry.yarnpkg.com/@puppeteer/browsers/-/browsers-2.2.3.tgz#ad6b79129c50825e77ddaba082680f4dad0b674e"
  integrity sha512-bJ0UBsk0ESOs6RFcLXOt99a3yTDcOKlzfjad+rhFwdaG1Lu/Wzq58GHYCDTlZ9z6mldf4g+NTb+TXEfe0PpnsQ==
  dependencies:
    debug "4.3.4"
    extract-zip "2.0.1"
    progress "2.0.3"
    proxy-agent "6.4.0"
    semver "7.6.0"
    tar-fs "3.0.5"
    unbzip2-stream "1.4.3"
    yargs "17.7.2"

"@radix-ui/number@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/number/-/number-1.0.1.tgz#644161a3557f46ed38a042acf4a770e826021674"
  integrity sha512-T5gIdVO2mmPW3NNhjNgEP3cqMXjXL9UbO0BzWcXfvdBs+BohbQxvd/K5hSVKmn9/lbTdsQVKbUcP5WLCwvUbBg==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/primitive@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/primitive/-/primitive-1.0.1.tgz#e46f9958b35d10e9f6dc71c497305c22e3e55dbd"
  integrity sha512-yQ8oGX2GVsEYMWGxcovu1uGWPCxV5BFfeeYxqPmuAzUyLT9qmaMXSAhXpb0WrspIeqYzdJpkh2vHModJPgRIaw==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-accordion@^1.1.2":
  version "1.1.2"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-accordion/-/react-accordion-1.1.2.tgz#738441f7343e5142273cdef94d12054c3287966f"
  integrity sha512-fDG7jcoNKVjSK6yfmuAs0EnPDro0WMXIhMtXdTBWqEioVW206ku+4Lw07e+13lUkFkpoEQ2PdeMIAGpdqEAmDg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-collapsible" "1.0.3"
    "@radix-ui/react-collection" "1.0.3"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-direction" "1.0.1"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-controllable-state" "1.0.1"

"@radix-ui/react-alert-dialog@^1.0.5":
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-alert-dialog/-/react-alert-dialog-1.0.5.tgz#70dd529cbf1e4bff386814d3776901fcaa131b8c"
  integrity sha512-OrVIOcZL0tl6xibeuGt5/+UxoT2N27KCFOPjFyfXMnchxSHZ/OW7cCX2nGlIYJrbHK/fczPcFzAwvNBB6XBNMA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-dialog" "1.0.5"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-slot" "1.0.2"

"@radix-ui/react-arrow@1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-arrow/-/react-arrow-1.0.3.tgz#c24f7968996ed934d57fe6cde5d6ec7266e1d25d"
  integrity sha512-wSP+pHsB/jQRaL6voubsQ/ZlrGBHHrOjmBnr19hxYgtS0WvAFwZhK2WP/YY5yF9uKECCEEDGxuLxq1NBK51wFA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/react-checkbox@^1.0.4":
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-checkbox/-/react-checkbox-1.0.4.tgz#98f22c38d5010dd6df4c5744cac74087e3275f4b"
  integrity sha512-CBuGQa52aAYnADZVt/KBQzXrwx6TqnlwtcIPGtVt5JkkzQwMOLJjPukimhfKEr4GQNd43C+djUh5Ikopj8pSLg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    "@radix-ui/react-use-previous" "1.0.1"
    "@radix-ui/react-use-size" "1.0.1"

"@radix-ui/react-collapsible@1.0.3", "@radix-ui/react-collapsible@^1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-collapsible/-/react-collapsible-1.0.3.tgz#df0e22e7a025439f13f62d4e4a9e92c4a0df5b81"
  integrity sha512-UBmVDkmR6IvDsloHVN+3rtx4Mi5TFvylYXpluuv0f37dtaz3H99bp8No0LGXRigVpl3UAT4l9j6bIchh42S/Gg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    "@radix-ui/react-use-layout-effect" "1.0.1"

"@radix-ui/react-collection@1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-collection/-/react-collection-1.0.3.tgz#9595a66e09026187524a36c6e7e9c7d286469159"
  integrity sha512-3SzW+0PW7yBBoQlT8wNcGtaxaD0XSu0uLUFgrtHY08Acx05TaHaOmVLR73c0j/cqpDy53KBMO7s0dx2wmOIDIA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-slot" "1.0.2"

"@radix-ui/react-compose-refs@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-compose-refs/-/react-compose-refs-1.0.1.tgz#7ed868b66946aa6030e580b1ffca386dd4d21989"
  integrity sha512-fDSBgd44FKHa1FRMU59qBMPFcl2PZE+2nmqunj+BWFyYYjnhIDWL2ItDs3rrbJDQOtzt5nIebLCQc4QRfz6LJw==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-context@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-context/-/react-context-1.0.1.tgz#fe46e67c96b240de59187dcb7a1a50ce3e2ec00c"
  integrity sha512-ebbrdFoYTcuZ0v4wG5tedGnp9tzcV8awzsxYph7gXUyvnNLuTIcCk1q17JEbnVhXAKG9oX3KtchwiMIAYp9NLg==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-dialog@1.0.5", "@radix-ui/react-dialog@^1.0.5":
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-dialog/-/react-dialog-1.0.5.tgz#71657b1b116de6c7a0b03242d7d43e01062c7300"
  integrity sha512-GjWJX/AUpB703eEBanuBnIWdIXg6NvJFCXcNlSZk4xdszCdhrJgBoUd1cGk67vFO+WdA2pfI/plOpqz/5GUP6Q==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-dismissable-layer" "1.0.5"
    "@radix-ui/react-focus-guards" "1.0.1"
    "@radix-ui/react-focus-scope" "1.0.4"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-portal" "1.0.4"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-slot" "1.0.2"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    aria-hidden "^1.1.1"
    react-remove-scroll "2.5.5"

"@radix-ui/react-direction@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-direction/-/react-direction-1.0.1.tgz#9cb61bf2ccf568f3421422d182637b7f47596c9b"
  integrity sha512-RXcvnXgyvYvBEOhCBuddKecVkoMiI10Jcm5cTI7abJRAHYfFxeu+FBQs/DvdxSYucxR5mna0dNsL6QFlds5TMA==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-dismissable-layer@1.0.5":
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-dismissable-layer/-/react-dismissable-layer-1.0.5.tgz#3f98425b82b9068dfbab5db5fff3df6ebf48b9d4"
  integrity sha512-aJeDjQhywg9LBu2t/At58hCvr7pEm0o2Ke1x33B+MhjNmmZ17sy4KImo0KPLgsnc/zN7GPdce8Cnn0SWvwZO7g==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-callback-ref" "1.0.1"
    "@radix-ui/react-use-escape-keydown" "1.0.3"

"@radix-ui/react-focus-guards@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-focus-guards/-/react-focus-guards-1.0.1.tgz#1ea7e32092216b946397866199d892f71f7f98ad"
  integrity sha512-Rect2dWbQ8waGzhMavsIbmSVCgYxkXLxxR3ZvCX79JOglzdEy4JXMb98lq4hPxUbLr77nP0UOGf4rcMU+s1pUA==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-focus-scope@1.0.4":
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-focus-scope/-/react-focus-scope-1.0.4.tgz#2ac45fce8c5bb33eb18419cdc1905ef4f1906525"
  integrity sha512-sL04Mgvf+FmyvZeYfNu1EPAaaxD+aw7cYeIB9L9Fvq8+urhltTRaEo5ysKOpHuKPclsZcSUMKlN05x4u+CINpA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-callback-ref" "1.0.1"

"@radix-ui/react-hover-card@^1.0.7":
  version "1.0.7"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-hover-card/-/react-hover-card-1.0.7.tgz#684bca2504432566357e7157e087051aa3577948"
  integrity sha512-OcUN2FU0YpmajD/qkph3XzMcK/NmSk9hGWnjV68p6QiZMgILugusgQwnLSDs3oFSJYGKf3Y49zgFedhGh04k9A==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-dismissable-layer" "1.0.5"
    "@radix-ui/react-popper" "1.1.3"
    "@radix-ui/react-portal" "1.0.4"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-controllable-state" "1.0.1"

"@radix-ui/react-icons@^1.3.0":
  version "1.3.0"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-icons/-/react-icons-1.3.0.tgz#c61af8f323d87682c5ca76b856d60c2312dbcb69"
  integrity sha512-jQxj/0LKgp+j9BiTXz3O3sgs26RNet2iLWmsPyRz2SIcR4q/4SbazXfnYwbAr+vLYKSfc7qxzyGQA1HLlYiuNw==

"@radix-ui/react-id@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-id/-/react-id-1.0.1.tgz#73cdc181f650e4df24f0b6a5b7aa426b912c88c0"
  integrity sha512-tI7sT/kqYp8p96yGWY1OAnLHrqDgzHefRBKQ2YAkBS5ja7QLcZ9Z/uY7bEjPUatf8RomoXM8/1sMj1IJaE5UzQ==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-use-layout-effect" "1.0.1"

"@radix-ui/react-label@^2.0.2":
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-label/-/react-label-2.0.2.tgz#9c72f1d334aac996fdc27b48a8bdddd82108fb6d"
  integrity sha512-N5ehvlM7qoTLx7nWPodsPYPgMzA5WM8zZChQg8nyFJKnDO5WHdba1vv5/H6IO5LtJMfD2Q3wh1qHFGNtK0w3bQ==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/react-popover@^1.0.7":
  version "1.0.7"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-popover/-/react-popover-1.0.7.tgz#23eb7e3327330cb75ec7b4092d685398c1654e3c"
  integrity sha512-shtvVnlsxT6faMnK/a7n0wptwBD23xc1Z5mdrtKLwVEfsEMXodS0r5s0/g5P0hX//EKYZS2sxUjqfzlg52ZSnQ==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-dismissable-layer" "1.0.5"
    "@radix-ui/react-focus-guards" "1.0.1"
    "@radix-ui/react-focus-scope" "1.0.4"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-popper" "1.1.3"
    "@radix-ui/react-portal" "1.0.4"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-slot" "1.0.2"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    aria-hidden "^1.1.1"
    react-remove-scroll "2.5.5"

"@radix-ui/react-popper@1.1.3":
  version "1.1.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-popper/-/react-popper-1.1.3.tgz#24c03f527e7ac348fabf18c89795d85d21b00b42"
  integrity sha512-cKpopj/5RHZWjrbF2846jBNacjQVwkP068DfmgrNJXpvVWrOvlAmE9xSiy5OqeE+Gi8D9fP+oDhUnPqNMY8/5w==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@floating-ui/react-dom" "^2.0.0"
    "@radix-ui/react-arrow" "1.0.3"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-callback-ref" "1.0.1"
    "@radix-ui/react-use-layout-effect" "1.0.1"
    "@radix-ui/react-use-rect" "1.0.1"
    "@radix-ui/react-use-size" "1.0.1"
    "@radix-ui/rect" "1.0.1"

"@radix-ui/react-portal@1.0.4":
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-portal/-/react-portal-1.0.4.tgz#df4bfd353db3b1e84e639e9c63a5f2565fb00e15"
  integrity sha512-Qki+C/EuGUVCQTOTD5vzJzJuMUlewbzuKyUy+/iHM2uwGiru9gZeBJtHAPKAEkB5KWGi9mP/CHKcY0wt1aW45Q==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/react-presence@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-presence/-/react-presence-1.0.1.tgz#491990ba913b8e2a5db1b06b203cb24b5cdef9ba"
  integrity sha512-UXLW4UAbIY5ZjcvzjfRFo5gxva8QirC9hF7wRE4U5gz+TP0DbRk+//qyuAQ1McDxBt1xNMBTaciFGvEmJvAZCg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-use-layout-effect" "1.0.1"

"@radix-ui/react-primitive@1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-primitive/-/react-primitive-1.0.3.tgz#d49ea0f3f0b2fe3ab1cb5667eb03e8b843b914d0"
  integrity sha512-yi58uVyoAcK/Nq1inRY56ZSjKypBNKTa/1mcL8qdl6oJeEaDbOldlzrGn7P6Q3Id5d+SYNGc5AJgc4vGhjs5+g==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-slot" "1.0.2"

"@radix-ui/react-progress@^1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-progress/-/react-progress-1.0.3.tgz#8380272fdc64f15cbf263a294dea70a7d5d9b4fa"
  integrity sha512-5G6Om/tYSxjSeEdrb1VfKkfZfn/1IlPWd731h2RfPuSbIfNUgfqAwbKfJCg/PP6nuUCTrYzalwHSpSinoWoCag==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/react-roving-focus@1.0.4":
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-roving-focus/-/react-roving-focus-1.0.4.tgz#e90c4a6a5f6ac09d3b8c1f5b5e81aab2f0db1974"
  integrity sha512-2mUg5Mgcu001VkGy+FfzZyzbmuUWzgWkj3rvv4yu+mLw03+mTzbxZHvfcGyFp2b8EkQeMkpRQ5FiA2Vr2O6TeQ==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-collection" "1.0.3"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-direction" "1.0.1"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-callback-ref" "1.0.1"
    "@radix-ui/react-use-controllable-state" "1.0.1"

"@radix-ui/react-scroll-area@^1.0.5":
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-scroll-area/-/react-scroll-area-1.0.5.tgz#01160c6893f24a2ddb5aa399ae5b3ba84ad4d3cc"
  integrity sha512-b6PAgH4GQf9QEn8zbT2XUHpW5z8BzqEc7Kl11TwDrvuTrxlkcjTD5qa/bxgKr+nmuXKu4L/W5UZ4mlP/VG/5Gw==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/number" "1.0.1"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-direction" "1.0.1"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-callback-ref" "1.0.1"
    "@radix-ui/react-use-layout-effect" "1.0.1"

"@radix-ui/react-select@^2.0.0":
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-select/-/react-select-2.0.0.tgz#a3511792a51a7018d6559357323a7f52e0e38887"
  integrity sha512-RH5b7af4oHtkcHS7pG6Sgv5rk5Wxa7XI8W5gvB1N/yiuDGZxko1ynvOiVhFM7Cis2A8zxF9bTOUVbRDzPepe6w==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/number" "1.0.1"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-collection" "1.0.3"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-direction" "1.0.1"
    "@radix-ui/react-dismissable-layer" "1.0.5"
    "@radix-ui/react-focus-guards" "1.0.1"
    "@radix-ui/react-focus-scope" "1.0.4"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-popper" "1.1.3"
    "@radix-ui/react-portal" "1.0.4"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-slot" "1.0.2"
    "@radix-ui/react-use-callback-ref" "1.0.1"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    "@radix-ui/react-use-layout-effect" "1.0.1"
    "@radix-ui/react-use-previous" "1.0.1"
    "@radix-ui/react-visually-hidden" "1.0.3"
    aria-hidden "^1.1.1"
    react-remove-scroll "2.5.5"

"@radix-ui/react-separator@^1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-separator/-/react-separator-1.0.3.tgz#be5a931a543d5726336b112f465f58585c04c8aa"
  integrity sha512-itYmTy/kokS21aiV5+Z56MZB54KrhPgn6eHDKkFeOLR34HMN2s8PaN47qZZAGnvupcjxHaFZnW4pQEh0BvvVuw==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/react-slot@1.0.2", "@radix-ui/react-slot@^1.0.2":
  version "1.0.2"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-slot/-/react-slot-1.0.2.tgz#a9ff4423eade67f501ffb32ec22064bc9d3099ab"
  integrity sha512-YeTpuq4deV+6DusvVUW4ivBgnkHwECUu0BiN43L5UCDFgdhsRUWAghhTF5MbvNTPzmiFOx90asDSUjWuCNapwg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-compose-refs" "1.0.1"

"@radix-ui/react-switch@^1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-switch/-/react-switch-1.0.3.tgz#6119f16656a9eafb4424c600fdb36efa5ec5837e"
  integrity sha512-mxm87F88HyHztsI7N+ZUmEoARGkC22YVW5CaC+Byc+HRpuvCrOBPTAnXgf+tZ/7i0Sg/eOePGdMhUKhPaQEqow==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-compose-refs" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-use-controllable-state" "1.0.1"
    "@radix-ui/react-use-previous" "1.0.1"
    "@radix-ui/react-use-size" "1.0.1"

"@radix-ui/react-tabs@^1.0.4":
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-tabs/-/react-tabs-1.0.4.tgz#993608eec55a5d1deddd446fa9978d2bc1053da2"
  integrity sha512-egZfYY/+wRNCflXNHx+dePvnz9FbmssDTJBtgRfDY7e8SE5oIo3Py2eCB1ckAbh1Q7cQ/6yJZThJ++sgbxibog==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/primitive" "1.0.1"
    "@radix-ui/react-context" "1.0.1"
    "@radix-ui/react-direction" "1.0.1"
    "@radix-ui/react-id" "1.0.1"
    "@radix-ui/react-presence" "1.0.1"
    "@radix-ui/react-primitive" "1.0.3"
    "@radix-ui/react-roving-focus" "1.0.4"
    "@radix-ui/react-use-controllable-state" "1.0.1"

"@radix-ui/react-use-callback-ref@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-callback-ref/-/react-use-callback-ref-1.0.1.tgz#f4bb1f27f2023c984e6534317ebc411fc181107a"
  integrity sha512-D94LjX4Sp0xJFVaoQOd3OO9k7tpBYNOXdVhkltUbGv2Qb9OXdrg/CpsjlZv7ia14Sylv398LswWBVVu5nqKzAQ==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-use-controllable-state@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-controllable-state/-/react-use-controllable-state-1.0.1.tgz#ecd2ced34e6330caf89a82854aa2f77e07440286"
  integrity sha512-Svl5GY5FQeN758fWKrjM6Qb7asvXeiZltlT4U2gVfl8Gx5UAv2sMR0LWo8yhsIZh2oQ0eFdZ59aoOOMV7b47VA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-use-callback-ref" "1.0.1"

"@radix-ui/react-use-escape-keydown@1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-escape-keydown/-/react-use-escape-keydown-1.0.3.tgz#217b840c250541609c66f67ed7bab2b733620755"
  integrity sha512-vyL82j40hcFicA+M4Ex7hVkB9vHgSse1ZWomAqV2Je3RleKGO5iM8KMOEtfoSB0PnIelMd2lATjTGMYqN5ylTg==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-use-callback-ref" "1.0.1"

"@radix-ui/react-use-layout-effect@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-layout-effect/-/react-use-layout-effect-1.0.1.tgz#be8c7bc809b0c8934acf6657b577daf948a75399"
  integrity sha512-v/5RegiJWYdoCvMnITBkNNx6bCj20fiaJnWtRkU18yITptraXjffz5Qbn05uOiQnOvi+dbkznkoaMltz1GnszQ==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-use-previous@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-previous/-/react-use-previous-1.0.1.tgz#b595c087b07317a4f143696c6a01de43b0d0ec66"
  integrity sha512-cV5La9DPwiQ7S0gf/0qiD6YgNqM5Fk97Kdrlc5yBcrF3jyEZQwm7vYFqMo4IfeHgJXsRaMvLABFtd0OVEmZhDw==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@radix-ui/react-use-rect@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-rect/-/react-use-rect-1.0.1.tgz#fde50b3bb9fd08f4a1cd204572e5943c244fcec2"
  integrity sha512-Cq5DLuSiuYVKNU8orzJMbl15TXilTnJKUCltMVQg53BQOF1/C5toAaGrowkgksdBQ9H+SRL23g0HDmg9tvmxXw==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/rect" "1.0.1"

"@radix-ui/react-use-size@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-use-size/-/react-use-size-1.0.1.tgz#1c5f5fea940a7d7ade77694bb98116fb49f870b2"
  integrity sha512-ibay+VqrgcaI6veAojjofPATwledXiSmX+C0KrBk/xgpX9rBzPV3OsfwlhQdUOFbh+LKQorLYT+xTXW9V8yd0g==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-use-layout-effect" "1.0.1"

"@radix-ui/react-visually-hidden@1.0.3":
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/@radix-ui/react-visually-hidden/-/react-visually-hidden-1.0.3.tgz#51aed9dd0fe5abcad7dee2a234ad36106a6984ac"
  integrity sha512-D4w41yN5YRKtu464TLnByKzMDG/JlMPHtfZgQAu9v6mNakUqGUI9vUrfQKz8NK41VMm/xbZbh76NUTVtIYqOMA==
  dependencies:
    "@babel/runtime" "^7.13.10"
    "@radix-ui/react-primitive" "1.0.3"

"@radix-ui/rect@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@radix-ui/rect/-/rect-1.0.1.tgz#bf8e7d947671996da2e30f4904ece343bc4a883f"
  integrity sha512-fyrgCaedtvMg9NK3en0pnOYJdtfwxUcNolezkNPUsoX57X8oQk+NkqcvzHXD2uKNij6GXmWU9NDru2IWjrO4BQ==
  dependencies:
    "@babel/runtime" "^7.13.10"

"@remix-run/router@1.13.1":
  version "1.13.1"
  resolved "https://registry.yarnpkg.com/@remix-run/router/-/router-1.13.1.tgz#07e2a8006f23a3bc898b3f317e0a58cc8076b86e"
  integrity sha512-so+DHzZKsoOcoXrILB4rqDkMDy7NLMErRdOxvzvOKb507YINKUP4Di+shbTZDhSE/pBZ+vr7XGIpcOO0VLSA+Q==

"@rollup/pluginutils@^4.2.0":
  version "4.2.1"
  resolved "https://registry.yarnpkg.com/@rollup/pluginutils/-/pluginutils-4.2.1.tgz#e6c6c3aba0744edce3fb2074922d3776c0af2a6d"
  integrity sha512-iKnFXr7NkdZAIHiIWE+BX5ULi/ucVFYWD6TbAV+rZctiRTY2PL6tsIKhoIOaoskiWAkgu+VsbXgUVDNLHf+InQ==
  dependencies:
    estree-walker "^2.0.1"
    picomatch "^2.2.2"

"@rollup/rollup-android-arm-eabi@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-android-arm-eabi/-/rollup-android-arm-eabi-4.6.1.tgz#0ea289f68ff248b50fea5716ca9f65f7d4dba3ae"
  integrity sha512-0WQ0ouLejaUCRsL93GD4uft3rOmB8qoQMU05Kb8CmMtMBe7XUDLAltxVZI1q6byNqEtU7N1ZX1Vw5lIpgulLQA==

"@rollup/rollup-android-arm64@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-android-arm64/-/rollup-android-arm64-4.6.1.tgz#27c8c67fc5de574874085a1b480ac65b3e18378e"
  integrity sha512-1TKm25Rn20vr5aTGGZqo6E4mzPicCUD79k17EgTLAsXc1zysyi4xXKACfUbwyANEPAEIxkzwue6JZ+stYzWUTA==

"@rollup/rollup-darwin-arm64@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-darwin-arm64/-/rollup-darwin-arm64-4.6.1.tgz#c5735c042980c85495411af7183dd20294763bd8"
  integrity sha512-cEXJQY/ZqMACb+nxzDeX9IPLAg7S94xouJJCNVE5BJM8JUEP4HeTF+ti3cmxWeSJo+5D+o8Tc0UAWUkfENdeyw==

"@rollup/rollup-darwin-x64@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-darwin-x64/-/rollup-darwin-x64-4.6.1.tgz#af844bd54abb73ca3c9cf89a31eec17861d1375d"
  integrity sha512-LoSU9Xu56isrkV2jLldcKspJ7sSXmZWkAxg7sW/RfF7GS4F5/v4EiqKSMCFbZtDu2Nc1gxxFdQdKwkKS4rwxNg==

"@rollup/rollup-linux-arm-gnueabihf@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-linux-arm-gnueabihf/-/rollup-linux-arm-gnueabihf-4.6.1.tgz#5e972f63c441eaf859551039b3f18db9b035977d"
  integrity sha512-EfI3hzYAy5vFNDqpXsNxXcgRDcFHUWSx5nnRSCKwXuQlI5J9dD84g2Usw81n3FLBNsGCegKGwwTVsSKK9cooSQ==

"@rollup/rollup-linux-arm64-gnu@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-linux-arm64-gnu/-/rollup-linux-arm64-gnu-4.6.1.tgz#f4cfbc71e3b6fdb395b28b1472414e181515c72d"
  integrity sha512-9lhc4UZstsegbNLhH0Zu6TqvDfmhGzuCWtcTFXY10VjLLUe4Mr0Ye2L3rrtHaDd/J5+tFMEuo5LTCSCMXWfUKw==

"@rollup/rollup-linux-arm64-musl@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-linux-arm64-musl/-/rollup-linux-arm64-musl-4.6.1.tgz#6a94c691830dc29bf708de7c640f494996130893"
  integrity sha512-FfoOK1yP5ksX3wwZ4Zk1NgyGHZyuRhf99j64I5oEmirV8EFT7+OhUZEnP+x17lcP/QHJNWGsoJwrz4PJ9fBEXw==

"@rollup/rollup-linux-x64-gnu@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-linux-x64-gnu/-/rollup-linux-x64-gnu-4.6.1.tgz#f07bae3f7dc532d9ea5ab36c9071db329f9a1efb"
  integrity sha512-DNGZvZDO5YF7jN5fX8ZqmGLjZEXIJRdJEdTFMhiyXqyXubBa0WVLDWSNlQ5JR2PNgDbEV1VQowhVRUh+74D+RA==

"@rollup/rollup-linux-x64-musl@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-linux-x64-musl/-/rollup-linux-x64-musl-4.6.1.tgz#357a34fdbf410af88ce48bd802bea6462bb9a8bc"
  integrity sha512-RkJVNVRM+piYy87HrKmhbexCHg3A6Z6MU0W9GHnJwBQNBeyhCJG9KDce4SAMdicQnpURggSvtbGo9xAWOfSvIQ==

"@rollup/rollup-win32-arm64-msvc@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-win32-arm64-msvc/-/rollup-win32-arm64-msvc-4.6.1.tgz#b6e97fd38281667e35297033393cd1101f4a31be"
  integrity sha512-v2FVT6xfnnmTe3W9bJXl6r5KwJglMK/iRlkKiIFfO6ysKs0rDgz7Cwwf3tjldxQUrHL9INT/1r4VA0n9L/F1vQ==

"@rollup/rollup-win32-ia32-msvc@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-win32-ia32-msvc/-/rollup-win32-ia32-msvc-4.6.1.tgz#a95db026c640c8128bfd38546d85342f2329beaf"
  integrity sha512-YEeOjxRyEjqcWphH9dyLbzgkF8wZSKAKUkldRY6dgNR5oKs2LZazqGB41cWJ4Iqqcy9/zqYgmzBkRoVz3Q9MLw==

"@rollup/rollup-win32-x64-msvc@4.6.1":
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/@rollup/rollup-win32-x64-msvc/-/rollup-win32-x64-msvc-4.6.1.tgz#45785b5caf83200a34a9867ba50d69560880c120"
  integrity sha512-0zfTlFAIhgz8V2G8STq8toAjsYYA6eci1hnXuyOTUFnymrtJwnS6uGKiv3v5UrPZkBlamLvrLV2iiaeqCKzb0A==

"@sinclair/typebox@^0.27.8":
  version "0.27.8"
  resolved "https://registry.yarnpkg.com/@sinclair/typebox/-/typebox-0.27.8.tgz#6667fac16c436b5434a387a34dedb013198f6e6e"
  integrity sha512-+Fj43pSMwJs4KRrH/938Uf+uAELIgVBmQzg/q1YG10djyfA3TnrU8N8XzqCh/okZdszqBQTZf96idMfE5lnwTA==

"@sinonjs/commons@^3.0.0":
  version "3.0.1"
  resolved "https://registry.yarnpkg.com/@sinonjs/commons/-/commons-3.0.1.tgz#1029357e44ca901a615585f6d27738dbc89084cd"
  integrity sha512-K3mCHKQ9sVh8o1C9cxkwxaOmXoAMlDxC1mYyHrjqOWEcBjYr76t96zL2zlj5dUGZ3HSw240X1qgH3Mjf1yJWpQ==
  dependencies:
    type-detect "4.0.8"

"@sinonjs/fake-timers@^10.0.2":
  version "10.3.0"
  resolved "https://registry.yarnpkg.com/@sinonjs/fake-timers/-/fake-timers-10.3.0.tgz#55fdff1ecab9f354019129daf4df0dd4d923ea66"
  integrity sha512-V4BG07kuYSUkTCSBHG8G8TNhM+F19jXFWnQtzj+we8DrkpSBCee9Z3Ms8yiGer/dlmhe35/Xdgyo3/0rQKg7YA==
  dependencies:
    "@sinonjs/commons" "^3.0.0"

"@tootallnate/quickjs-emscripten@^0.23.0":
  version "0.23.0"
  resolved "https://registry.yarnpkg.com/@tootallnate/quickjs-emscripten/-/quickjs-emscripten-0.23.0.tgz#db4ecfd499a9765ab24002c3b696d02e6d32a12c"
  integrity sha512-C5Mc6rdnsaJDjO3UpGW/CQTHtCKaYlScZTly4JIu97Jxo/odCiH0ITnDXSJPTOrEKk/ycSZ0AOgTmkDtkOsvIA==

"@types/babel__core@^7.1.14":
  version "7.20.5"
  resolved "https://registry.yarnpkg.com/@types/babel__core/-/babel__core-7.20.5.tgz#3df15f27ba85319caa07ba08d0721889bb39c017"
  integrity sha512-qoQprZvz5wQFJwMDqeseRXWv3rqMvhgpbXFfVyWhbx9X47POIA6i/+dXefEmZKoAgOaTdaIgNSMqMIU61yRyzA==
  dependencies:
    "@babel/parser" "^7.20.7"
    "@babel/types" "^7.20.7"
    "@types/babel__generator" "*"
    "@types/babel__template" "*"
    "@types/babel__traverse" "*"

"@types/babel__core@^7.20.3":
  version "7.20.4"
  resolved "https://registry.npmjs.org/@types/babel__core/-/babel__core-7.20.4.tgz"
  integrity sha512-mLnSC22IC4vcWiuObSRjrLd9XcBTGf59vUSoq2jkQDJ/QQ8PMI9rSuzE+aEV8karUMbskw07bKYoUJCKTUaygg==
  dependencies:
    "@babel/parser" "^7.20.7"
    "@babel/types" "^7.20.7"
    "@types/babel__generator" "*"
    "@types/babel__template" "*"
    "@types/babel__traverse" "*"

"@types/babel__generator@*":
  version "7.6.7"
  resolved "https://registry.npmjs.org/@types/babel__generator/-/babel__generator-7.6.7.tgz"
  integrity sha512-6Sfsq+EaaLrw4RmdFWE9Onp63TOUue71AWb4Gpa6JxzgTYtimbM086WnYTy2U67AofR++QKCo08ZP6pwx8YFHQ==
  dependencies:
    "@babel/types" "^7.0.0"

"@types/babel__template@*":
  version "7.4.4"
  resolved "https://registry.npmjs.org/@types/babel__template/-/babel__template-7.4.4.tgz"
  integrity sha512-h/NUaSyG5EyxBIp8YRxo4RMe2/qQgvyowRwVMzhYhBCONbW8PUsg4lkFMrhgZhUe5z3L3MiLDuvyJ/CaPa2A8A==
  dependencies:
    "@babel/parser" "^7.1.0"
    "@babel/types" "^7.0.0"

"@types/babel__traverse@*":
  version "7.20.4"
  resolved "https://registry.npmjs.org/@types/babel__traverse/-/babel__traverse-7.20.4.tgz"
  integrity sha512-mSM/iKUk5fDDrEV/e83qY+Cr3I1+Q3qqTuEn++HAWYjEa1+NxZr6CNrcJGf2ZTnq4HoFGC3zaTPZTobCzCFukA==
  dependencies:
    "@babel/types" "^7.20.7"

"@types/babel__traverse@^7.0.6":
  version "7.20.5"
  resolved "https://registry.yarnpkg.com/@types/babel__traverse/-/babel__traverse-7.20.5.tgz#7b7502be0aa80cc4ef22978846b983edaafcd4dd"
  integrity sha512-WXCyOcRtH37HAUkpXhUduaxdm82b4GSlyTqajXviN4EfiuPgNYR109xMCKvpl6zPIpua0DGlMEDCq+g8EdoheQ==
  dependencies:
    "@babel/types" "^7.20.7"

"@types/graceful-fs@^4.1.3":
  version "4.1.9"
  resolved "https://registry.yarnpkg.com/@types/graceful-fs/-/graceful-fs-4.1.9.tgz#2a06bc0f68a20ab37b3e36aa238be6abdf49e8b4"
  integrity sha512-olP3sd1qOEe5dXTSaFvQG+02VdRXcdytWLAZsAq1PecU8uqQAhkrnbli7DagjtXKW/Bl7YJbUsa8MPcuc8LHEQ==
  dependencies:
    "@types/node" "*"

"@types/istanbul-lib-coverage@*", "@types/istanbul-lib-coverage@^2.0.0", "@types/istanbul-lib-coverage@^2.0.1":
  version "2.0.6"
  resolved "https://registry.yarnpkg.com/@types/istanbul-lib-coverage/-/istanbul-lib-coverage-2.0.6.tgz#7739c232a1fee9b4d3ce8985f314c0c6d33549d7"
  integrity sha512-2QF/t/auWm0lsy8XtKVPG19v3sSOQlJe/YHZgfjb/KBBHOGSV+J2q/S671rcq9uTBrLAXmZpqJiaQbMT+zNU1w==

"@types/istanbul-lib-report@*":
  version "3.0.3"
  resolved "https://registry.yarnpkg.com/@types/istanbul-lib-report/-/istanbul-lib-report-3.0.3.tgz#53047614ae72e19fc0401d872de3ae2b4ce350bf"
  integrity sha512-NQn7AHQnk/RSLOxrBbGyJM/aVQ+pjj5HCgasFxc0K/KhoATfQ/47AyUl15I2yBUpihjmas+a+VJBOqecrFH+uA==
  dependencies:
    "@types/istanbul-lib-coverage" "*"

"@types/istanbul-reports@^3.0.0":
  version "3.0.4"
  resolved "https://registry.yarnpkg.com/@types/istanbul-reports/-/istanbul-reports-3.0.4.tgz#0f03e3d2f670fbdac586e34b433783070cc16f54"
  integrity sha512-pk2B1NWalF9toCRu6gjBzR69syFjP4Od8WRAX+0mmf9lAjCRicLOWc+ZrxZHx/0XRjotgkF9t6iaMJ+aXcOdZQ==
  dependencies:
    "@types/istanbul-lib-report" "*"

"@types/jest@^29.5.12":
  version "29.5.12"
  resolved "https://registry.yarnpkg.com/@types/jest/-/jest-29.5.12.tgz#7f7dc6eb4cf246d2474ed78744b05d06ce025544"
  integrity sha512-eDC8bTvT/QhYdxJAulQikueigY5AsdBRH2yDKW3yveW7svY3+DzN84/2NUgkw10RTiJbWqZrTtoGVdYlvFJdLw==
  dependencies:
    expect "^29.0.0"
    pretty-format "^29.0.0"

"@types/json-schema@^7.0.12":
  version "7.0.15"
  resolved "https://registry.npmjs.org/@types/json-schema/-/json-schema-7.0.15.tgz"
  integrity sha512-5+fP8P8MFNC+AyZCDxrB2pkZFPGzqQWUzpSeuuVLvm8VMcorNYavBqoFcxK8bQz4Qsbn4oUEEem4wDLfcysGHA==

"@types/node@*":
  version "20.12.7"
  resolved "https://registry.yarnpkg.com/@types/node/-/node-20.12.7.tgz#04080362fa3dd6c5822061aa3124f5c152cff384"
  integrity sha512-wq0cICSkRLVaf3UGLMGItu/PtdY7oaXaI/RVU+xliKVOtRna3PRY57ZDfztpDL0n11vfymMUnXv8QwYCO7L1wg==
  dependencies:
    undici-types "~5.26.4"

"@types/node@^20.9.0":
  version "20.9.0"
  resolved "https://registry.npmjs.org/@types/node/-/node-20.9.0.tgz"
  integrity sha512-nekiGu2NDb1BcVofVcEKMIwzlx4NjHlcjhoxxKBNLtz15Y1z7MYf549DFvkHSId02Ax6kGwWntIBPC3l/JZcmw==
  dependencies:
    undici-types "~5.26.4"

"@types/prop-types@*":
  version "15.7.10"
  resolved "https://registry.npmjs.org/@types/prop-types/-/prop-types-15.7.10.tgz"
  integrity sha512-mxSnDQxPqsZxmeShFH+uwQ4kO4gcJcGahjjMFeLbKE95IAZiiZyiEepGZjtXJ7hN/yfu0bu9xN2ajcU0JcxX6A==

"@types/puppeteer@^7.0.4":
  version "7.0.4"
  resolved "https://registry.yarnpkg.com/@types/puppeteer/-/puppeteer-7.0.4.tgz#6eb4081323e9075c1f4c353f93ee2ed6eed99487"
  integrity sha512-ja78vquZc8y+GM2al07GZqWDKQskQXygCDiu0e3uO0DMRKqE0MjrFBFmTulfPYzLB6WnL7Kl2tFPy0WXSpPomg==
  dependencies:
    puppeteer "*"

"@types/react-dom@^18.2.7":
  version "18.2.15"
  resolved "https://registry.npmjs.org/@types/react-dom/-/react-dom-18.2.15.tgz"
  integrity sha512-HWMdW+7r7MR5+PZqJF6YFNSCtjz1T0dsvo/f1BV6HkV+6erD/nA7wd9NM00KVG83zf2nJ7uATPO9ttdIPvi3gg==
  dependencies:
    "@types/react" "*"

"@types/react@*", "@types/react@^18.2.15":
  version "18.2.37"
  resolved "https://registry.npmjs.org/@types/react/-/react-18.2.37.tgz"
  integrity sha512-RGAYMi2bhRgEXT3f4B92WTohopH6bIXw05FuGlmJEnv/omEn190+QYEIYxIAuIBdKgboYYdVved2p1AxZVQnaw==
  dependencies:
    "@types/prop-types" "*"
    "@types/scheduler" "*"
    csstype "^3.0.2"

"@types/scheduler@*":
  version "0.16.6"
  resolved "https://registry.npmjs.org/@types/scheduler/-/scheduler-0.16.6.tgz"
  integrity sha512-Vlktnchmkylvc9SnwwwozTv04L/e1NykF5vgoQ0XTmI8DD+wxfjQuHuvHS3p0r2jz2x2ghPs2h1FVeDirIteWA==

"@types/semver@^7.5.0":
  version "7.5.5"
  resolved "https://registry.npmjs.org/@types/semver/-/semver-7.5.5.tgz"
  integrity sha512-+d+WYC1BxJ6yVOgUgzK8gWvp5qF8ssV5r4nsDcZWKRWcDQLQ619tvWAxJQYGgBrO1MnLJC7a5GtiYsAoQ47dJg==

"@types/stack-utils@^2.0.0":
  version "2.0.3"
  resolved "https://registry.yarnpkg.com/@types/stack-utils/-/stack-utils-2.0.3.tgz#6209321eb2c1712a7e7466422b8cb1fc0d9dd5d8"
  integrity sha512-9aEbYZ3TbYMznPdcdr3SmIrLXwC/AKZXQeCf9Pgao5CKb8CyHuEX5jzWPTkvregvhRJHcpRO6BFoGW9ycaOkYw==

"@types/yargs-parser@*":
  version "21.0.3"
  resolved "https://registry.yarnpkg.com/@types/yargs-parser/-/yargs-parser-21.0.3.tgz#815e30b786d2e8f0dcd85fd5bcf5e1a04d008f15"
  integrity sha512-I4q9QU9MQv4oEOz4tAHJtNz1cwuLxn2F3xcc2iV5WdqLPpUnj30aUuxt1mAxYTG+oe8CZMV/+6rU4S4gRDzqtQ==

"@types/yargs@^17.0.8":
  version "17.0.32"
  resolved "https://registry.yarnpkg.com/@types/yargs/-/yargs-17.0.32.tgz#030774723a2f7faafebf645f4e5a48371dca6229"
  integrity sha512-xQ67Yc/laOG5uMfX/093MRlGGCIBzZMarVa+gfNKJxWAIgykYpVGkBdbqEzGDDfCrVUj6Hiff4mTZ5BA6TmAog==
  dependencies:
    "@types/yargs-parser" "*"

"@types/yauzl@^2.9.1":
  version "2.10.3"
  resolved "https://registry.yarnpkg.com/@types/yauzl/-/yauzl-2.10.3.tgz#e9b2808b4f109504a03cda958259876f61017999"
  integrity sha512-oJoftv0LSuaDZE3Le4DbKX+KS9G36NzOeSap90UIK0yMA/NhKJhqlSGtNDORNRaIbQfzjXDrQa0ytJ6mNRGz/Q==
  dependencies:
    "@types/node" "*"

"@typescript-eslint/eslint-plugin@^6.0.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/eslint-plugin/-/eslint-plugin-6.11.0.tgz"
  integrity sha512-uXnpZDc4VRjY4iuypDBKzW1rz9T5YBBK0snMn8MaTSNd2kMlj50LnLBABELjJiOL5YHk7ZD8hbSpI9ubzqYI0w==
  dependencies:
    "@eslint-community/regexpp" "^4.5.1"
    "@typescript-eslint/scope-manager" "6.11.0"
    "@typescript-eslint/type-utils" "6.11.0"
    "@typescript-eslint/utils" "6.11.0"
    "@typescript-eslint/visitor-keys" "6.11.0"
    debug "^4.3.4"
    graphemer "^1.4.0"
    ignore "^5.2.4"
    natural-compare "^1.4.0"
    semver "^7.5.4"
    ts-api-utils "^1.0.1"

"@typescript-eslint/parser@^6.0.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/parser/-/parser-6.11.0.tgz"
  integrity sha512-+whEdjk+d5do5nxfxx73oanLL9ghKO3EwM9kBCkUtWMRwWuPaFv9ScuqlYfQ6pAD6ZiJhky7TZ2ZYhrMsfMxVQ==
  dependencies:
    "@typescript-eslint/scope-manager" "6.11.0"
    "@typescript-eslint/types" "6.11.0"
    "@typescript-eslint/typescript-estree" "6.11.0"
    "@typescript-eslint/visitor-keys" "6.11.0"
    debug "^4.3.4"

"@typescript-eslint/scope-manager@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/scope-manager/-/scope-manager-6.11.0.tgz"
  integrity sha512-0A8KoVvIURG4uhxAdjSaxy8RdRE//HztaZdG8KiHLP8WOXSk0vlF7Pvogv+vlJA5Rnjj/wDcFENvDaHb+gKd1A==
  dependencies:
    "@typescript-eslint/types" "6.11.0"
    "@typescript-eslint/visitor-keys" "6.11.0"

"@typescript-eslint/type-utils@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/type-utils/-/type-utils-6.11.0.tgz"
  integrity sha512-nA4IOXwZtqBjIoYrJcYxLRO+F9ri+leVGoJcMW1uqr4r1Hq7vW5cyWrA43lFbpRvQ9XgNrnfLpIkO3i1emDBIA==
  dependencies:
    "@typescript-eslint/typescript-estree" "6.11.0"
    "@typescript-eslint/utils" "6.11.0"
    debug "^4.3.4"
    ts-api-utils "^1.0.1"

"@typescript-eslint/types@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/types/-/types-6.11.0.tgz"
  integrity sha512-ZbEzuD4DwEJxwPqhv3QULlRj8KYTAnNsXxmfuUXFCxZmO6CF2gM/y+ugBSAQhrqaJL3M+oe4owdWunaHM6beqA==

"@typescript-eslint/typescript-estree@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/typescript-estree/-/typescript-estree-6.11.0.tgz"
  integrity sha512-Aezzv1o2tWJwvZhedzvD5Yv7+Lpu1by/U1LZ5gLc4tCx8jUmuSCMioPFRjliN/6SJIvY6HpTtJIWubKuYYYesQ==
  dependencies:
    "@typescript-eslint/types" "6.11.0"
    "@typescript-eslint/visitor-keys" "6.11.0"
    debug "^4.3.4"
    globby "^11.1.0"
    is-glob "^4.0.3"
    semver "^7.5.4"
    ts-api-utils "^1.0.1"

"@typescript-eslint/utils@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/utils/-/utils-6.11.0.tgz"
  integrity sha512-p23ibf68fxoZy605dc0dQAEoUsoiNoP3MD9WQGiHLDuTSOuqoTsa4oAy+h3KDkTcxbbfOtUjb9h3Ta0gT4ug2g==
  dependencies:
    "@eslint-community/eslint-utils" "^4.4.0"
    "@types/json-schema" "^7.0.12"
    "@types/semver" "^7.5.0"
    "@typescript-eslint/scope-manager" "6.11.0"
    "@typescript-eslint/types" "6.11.0"
    "@typescript-eslint/typescript-estree" "6.11.0"
    semver "^7.5.4"

"@typescript-eslint/visitor-keys@6.11.0":
  version "6.11.0"
  resolved "https://registry.npmjs.org/@typescript-eslint/visitor-keys/-/visitor-keys-6.11.0.tgz"
  integrity sha512-+SUN/W7WjBr05uRxPggJPSzyB8zUpaYo2hByKasWbqr3PM8AXfZt8UHdNpBS1v9SA62qnSSMF3380SwDqqprgQ==
  dependencies:
    "@typescript-eslint/types" "6.11.0"
    eslint-visitor-keys "^3.4.1"

"@ungap/structured-clone@^1.2.0":
  version "1.2.0"
  resolved "https://registry.npmjs.org/@ungap/structured-clone/-/structured-clone-1.2.0.tgz"
  integrity sha512-zuVdFrMJiuCDQUMCzQaD6KL28MjnqqN8XnAqiEq9PNm/hCPTSGfrXCOfwj1ow4LFb/tNymJPwsNbVePc1xFqrQ==

"@vitejs/plugin-react@^4.0.3":
  version "4.1.1"
  resolved "https://registry.npmjs.org/@vitejs/plugin-react/-/plugin-react-4.1.1.tgz"
  integrity sha512-Jie2HERK+uh27e+ORXXwEP5h0Y2lS9T2PRGbfebiHGlwzDO0dEnd2aNtOR/qjBlPb1YgxwAONeblL1xqLikLag==
  dependencies:
    "@babel/core" "^7.23.2"
    "@babel/plugin-transform-react-jsx-self" "^7.22.5"
    "@babel/plugin-transform-react-jsx-source" "^7.22.5"
    "@types/babel__core" "^7.20.3"
    react-refresh "^0.14.0"

"@vitest/expect@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@vitest/expect/-/expect-1.0.1.tgz#5e63902316a3c65948c6e36f284046962601fb88"
  integrity sha512-3cdrb/eKD/0tygDX75YscuHEHMUJ70u3UoLSq2eqhWks57AyzvsDQbyn53IhZ0tBN7gA8Jj2VhXiOV2lef7thw==
  dependencies:
    "@vitest/spy" "1.0.1"
    "@vitest/utils" "1.0.1"
    chai "^4.3.10"

"@vitest/runner@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@vitest/runner/-/runner-1.0.1.tgz#d94cab9e3008dba52f89e811540184334766ab61"
  integrity sha512-/+z0vhJ0MfRPT3AyTvAK6m57rzlew/ct8B2a4LMv7NhpPaiI2QLGyOBMB3lcioWdJHjRuLi9aYppfOv0B5aRQA==
  dependencies:
    "@vitest/utils" "1.0.1"
    p-limit "^5.0.0"
    pathe "^1.1.1"

"@vitest/snapshot@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@vitest/snapshot/-/snapshot-1.0.1.tgz#9d2a01c64726afa62264175554690e5ce148d4a5"
  integrity sha512-wIPtPDGSxEZ+DpNMc94AsybX6LV6uN6sosf5TojyP1m2QbKwiRuLV/5RSsjt1oWViHsTj8mlcwrQQ1zHGO0fMw==
  dependencies:
    magic-string "^0.30.5"
    pathe "^1.1.1"
    pretty-format "^29.7.0"

"@vitest/spy@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@vitest/spy/-/spy-1.0.1.tgz#d82af1c4d935e08443bf20432ba55afd001ac71f"
  integrity sha512-yXwm1uKhBVr/5MhVeSmtNqK+0q2RXIchJt8kokEKdrWLtkPeDgdbZ6SjR1VQGZuNdWL6sSBnLayIyVvcS0qLfA==
  dependencies:
    tinyspy "^2.2.0"

"@vitest/utils@1.0.1":
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/@vitest/utils/-/utils-1.0.1.tgz#ab2bf6de50845649b252a9d263765ab7f16bd6a2"
  integrity sha512-MGPCHkzXbbAyscrhwGzh8uP1HPrTYLWaj1WTDtWSGrpe2yJWLRN9mF9ooKawr6NMOg9vTBtg2JqWLfuLC7Dknw==
  dependencies:
    diff-sequences "^29.6.3"
    loupe "^2.3.7"
    pretty-format "^29.7.0"

acorn-jsx@^5.3.2:
  version "5.3.2"
  resolved "https://registry.npmjs.org/acorn-jsx/-/acorn-jsx-5.3.2.tgz"
  integrity sha512-rq9s+JNhf0IChjtDXxllJ7g41oZk5SlXtp0LHwyA5cejwn7vKmKp4pPri6YEePv2PU65sAsegbXtIinmDFDXgQ==

acorn-walk@^8.3.0:
  version "8.3.1"
  resolved "https://registry.yarnpkg.com/acorn-walk/-/acorn-walk-8.3.1.tgz#2f10f5b69329d90ae18c58bf1fa8fccd8b959a43"
  integrity sha512-TgUZgYvqZprrl7YldZNoa9OciCAyZR+Ejm9eXzKCmjsF5IKp/wgQ7Z/ZpjpGTIUPwrHQIcYeI8qDh4PsEwxMbw==

acorn@^8.10.0, acorn@^8.8.2, acorn@^8.9.0:
  version "8.11.2"
  resolved "https://registry.npmjs.org/acorn/-/acorn-8.11.2.tgz"
  integrity sha512-nc0Axzp/0FILLEVsm4fNwLCwMttvhEI263QtVPQcbpfZZ3ts0hLsZGOpE6czNlid7CJ9MlyH8reXkpsf3YUY4w==

agent-base@^7.0.2, agent-base@^7.1.0, agent-base@^7.1.1:
  version "7.1.1"
  resolved "https://registry.yarnpkg.com/agent-base/-/agent-base-7.1.1.tgz#bdbded7dfb096b751a2a087eeeb9664725b2e317"
  integrity sha512-H0TSyFNDMomMNJQBn8wFV5YC/2eJ+VXECwOadZJT554xP6cODZHPX3H9QMQECxvrgiSOP1pHjy1sMWQVYJOUOA==
  dependencies:
    debug "^4.3.4"

ajv@^6.12.4:
  version "6.12.6"
  resolved "https://registry.npmjs.org/ajv/-/ajv-6.12.6.tgz"
  integrity sha512-j3fVLgvTo527anyYyJOGTYJbG+vnnQYvE0m5mmkc1TK+nxAppkCLMIL0aZ4dblVCNoGShhm+kzE4ZUykBoMg4g==
  dependencies:
    fast-deep-equal "^3.1.1"
    fast-json-stable-stringify "^2.0.0"
    json-schema-traverse "^0.4.1"
    uri-js "^4.2.2"

ansi-escapes@^4.2.1, ansi-escapes@^4.3.0:
  version "4.3.2"
  resolved "https://registry.npmjs.org/ansi-escapes/-/ansi-escapes-4.3.2.tgz"
  integrity sha512-gKXj5ALrKWQLsYG9jlTRmR/xKluxHV+Z9QEwNIgCfM1/uwPMCuzVVnh5mwTd+OuBZcwSIMbqssNWRm1lE51QaQ==
  dependencies:
    type-fest "^0.21.3"

ansi-regex@^5.0.1:
  version "5.0.1"
  resolved "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz"
  integrity sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==

ansi-styles@^3.2.1:
  version "3.2.1"
  resolved "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz"
  integrity sha512-VT0ZI6kZRdTh8YyJw3SMbYm/u+NqfsAxEpWO0Pf9sq8/e94WxxOpPKx9FR1FlyCtOVDNOQ+8ntlqFxiRc+r5qA==
  dependencies:
    color-convert "^1.9.0"

ansi-styles@^4.0.0, ansi-styles@^4.1.0:
  version "4.3.0"
  resolved "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz"
  integrity sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==
  dependencies:
    color-convert "^2.0.1"

ansi-styles@^5.0.0:
  version "5.2.0"
  resolved "https://registry.yarnpkg.com/ansi-styles/-/ansi-styles-5.2.0.tgz#07449690ad45777d1924ac2abb2fc8895dba836b"
  integrity sha512-Cxwpt2SfTzTtXcfOlzGEee8O+c+MmUgGrNiBcXnuWxuFJHe6a5Hz7qwhwe5OgaSYI0IJvkLqWX1ASG+cJOkEiA==

any-promise@^1.0.0:
  version "1.3.0"
  resolved "https://registry.npmjs.org/any-promise/-/any-promise-1.3.0.tgz"
  integrity sha512-7UvmKalWRt1wgjL1RrGxoSJW/0QZFIegpeGvZG9kjp8vrRu55XTHbwnqq2GpXm9uLbcuhxm3IqX9OB4MZR1b2A==

anymatch@^3.0.3, anymatch@~3.1.2:
  version "3.1.3"
  resolved "https://registry.npmjs.org/anymatch/-/anymatch-3.1.3.tgz"
  integrity sha512-KMReFUr0B4t+D+OBkjR3KYqvocp2XaSzO55UcB6mgQMd3KbcE+mWTyvVV7D/zsdEbNnV6acZUutkiHQXvTr1Rw==
  dependencies:
    normalize-path "^3.0.0"
    picomatch "^2.0.4"

arg@^5.0.2:
  version "5.0.2"
  resolved "https://registry.npmjs.org/arg/-/arg-5.0.2.tgz"
  integrity sha512-PYjyFOLKQ9y57JvQ6QLo8dAgNqswh8M1RMJYdQduT6xbWSgK36P/Z/v+p888pM69jMMfS8Xd8F6I1kQ/I9HUGg==

argparse@^1.0.7:
  version "1.0.10"
  resolved "https://registry.yarnpkg.com/argparse/-/argparse-1.0.10.tgz#bcd6791ea5ae09725e17e5ad988134cd40b3d911"
  integrity sha512-o5Roy6tNG4SL/FOkCAN6RzjiakZS25RLYFrcMttJqbdd8BWrnA+fGz57iN5Pb06pvBGvl5gQ0B48dJlslXvoTg==
  dependencies:
    sprintf-js "~1.0.2"

argparse@^2.0.1:
  version "2.0.1"
  resolved "https://registry.npmjs.org/argparse/-/argparse-2.0.1.tgz"
  integrity sha512-8+9WqebbFzpX9OR+Wa6O29asIogeRMzcGtAINdpMHHyAg10f05aSFVBbcEqGf/PXw1EjAZ+q2/bEBg3DvurK3Q==

aria-hidden@^1.1.1:
  version "1.2.3"
  resolved "https://registry.yarnpkg.com/aria-hidden/-/aria-hidden-1.2.3.tgz#14aeb7fb692bbb72d69bebfa47279c1fd725e954"
  integrity sha512-xcLxITLe2HYa1cnYnwCjkOO1PqUHQpozB8x9AR0OgWN2woOBi5kSDVxKfd0b7sb1hw5qFeJhXm9H1nu3xSfLeQ==
  dependencies:
    tslib "^2.0.0"

array-union@^2.1.0:
  version "2.1.0"
  resolved "https://registry.npmjs.org/array-union/-/array-union-2.1.0.tgz"
  integrity sha512-HGyxoOTYUyCM6stUe6EJgnd4EoewAI7zMdfqO+kGjnlZmBDz/cR5pf8r/cR4Wq60sL/p0IkcjUEEPwS3GFrIyw==

assertion-error@^1.1.0:
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/assertion-error/-/assertion-error-1.1.0.tgz#e60b6b0e8f301bd97e5375215bda406c85118c0b"
  integrity sha512-jgsaNduz+ndvGyFt3uSuWqvy4lCnIJiovtouQN5JZHOKCS2QuhEdbcQHFhVksz2N2U9hXJo8odG7ETyWlEeuDw==

ast-types@^0.13.4:
  version "0.13.4"
  resolved "https://registry.yarnpkg.com/ast-types/-/ast-types-0.13.4.tgz#ee0d77b343263965ecc3fb62da16e7222b2b6782"
  integrity sha512-x1FCFnFifvYDDzTaLII71vG5uvDwgtmDTEVWAxrgeiR8VjMONcCXJx7E+USjDtHlwFmt9MysbqgF9b9Vjr6w+w==
  dependencies:
    tslib "^2.0.1"

async@^3.2.3:
  version "3.2.5"
  resolved "https://registry.yarnpkg.com/async/-/async-3.2.5.tgz#ebd52a8fdaf7a2289a24df399f8d8485c8a46b66"
  integrity sha512-baNZyqaaLhyLVKm/DlvdW051MSgO6b8eVfIezl9E5PqWxFgzLm/wQntEW4zOytVburDEr0JlALEpdOFwvErLsg==

attr-accept@^2.2.2:
  version "2.2.2"
  resolved "https://registry.npmjs.org/attr-accept/-/attr-accept-2.2.2.tgz"
  integrity sha512-7prDjvt9HmqiZ0cl5CRjtS84sEyhsHP2coDkaZKRKVfCDo9s7iw7ChVmar78Gu9pC4SoR/28wFu/G5JJhTnqEg==

autoprefixer@^10.4.16:
  version "10.4.16"
  resolved "https://registry.npmjs.org/autoprefixer/-/autoprefixer-10.4.16.tgz"
  integrity sha512-7vd3UC6xKp0HLfua5IjZlcXvGAGy7cBAXTg2lyQ/8WpNhd6SiZ8Be+xm3FyBSYJx5GKcpRCzBh7RH4/0dnY+uQ==
  dependencies:
    browserslist "^4.21.10"
    caniuse-lite "^1.0.30001538"
    fraction.js "^4.3.6"
    normalize-range "^0.1.2"
    picocolors "^1.0.0"
    postcss-value-parser "^4.2.0"

b4a@^1.6.4:
  version "1.6.6"
  resolved "https://registry.yarnpkg.com/b4a/-/b4a-1.6.6.tgz#a4cc349a3851987c3c4ac2d7785c18744f6da9ba"
  integrity sha512-5Tk1HLk6b6ctmjIkAcU/Ujv/1WqiDl0F0JdRCR80VsOcUlHcu7pWeWRlOqQLHfDEsVx9YH/aif5AG4ehoCtTmg==

babel-jest@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/babel-jest/-/babel-jest-29.7.0.tgz#f4369919225b684c56085998ac63dbd05be020d5"
  integrity sha512-BrvGY3xZSwEcCzKvKsCi2GgHqDqsYkOP4/by5xCgIwGXQxIEh+8ew3gmrE1y7XRR6LHZIj6yLYnUi/mm2KXKBg==
  dependencies:
    "@jest/transform" "^29.7.0"
    "@types/babel__core" "^7.1.14"
    babel-plugin-istanbul "^6.1.1"
    babel-preset-jest "^29.6.3"
    chalk "^4.0.0"
    graceful-fs "^4.2.9"
    slash "^3.0.0"

babel-plugin-istanbul@^6.1.1:
  version "6.1.1"
  resolved "https://registry.yarnpkg.com/babel-plugin-istanbul/-/babel-plugin-istanbul-6.1.1.tgz#fa88ec59232fd9b4e36dbbc540a8ec9a9b47da73"
  integrity sha512-Y1IQok9821cC9onCx5otgFfRm7Lm+I+wwxOx738M/WLPZ9Q42m4IG5W0FNX8WLL2gYMZo3JkuXIH2DOpWM+qwA==
  dependencies:
    "@babel/helper-plugin-utils" "^7.0.0"
    "@istanbuljs/load-nyc-config" "^1.0.0"
    "@istanbuljs/schema" "^0.1.2"
    istanbul-lib-instrument "^5.0.4"
    test-exclude "^6.0.0"

babel-plugin-jest-hoist@^29.6.3:
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/babel-plugin-jest-hoist/-/babel-plugin-jest-hoist-29.6.3.tgz#aadbe943464182a8922c3c927c3067ff40d24626"
  integrity sha512-ESAc/RJvGTFEzRwOTT4+lNDk/GNHMkKbNzsvT0qKRfDyyYTskxB5rnU2njIDYVxXCBHHEI1c0YwHob3WaYujOg==
  dependencies:
    "@babel/template" "^7.3.3"
    "@babel/types" "^7.3.3"
    "@types/babel__core" "^7.1.14"
    "@types/babel__traverse" "^7.0.6"

babel-preset-current-node-syntax@^1.0.0:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/babel-preset-current-node-syntax/-/babel-preset-current-node-syntax-1.0.1.tgz#b4399239b89b2a011f9ddbe3e4f401fc40cff73b"
  integrity sha512-M7LQ0bxarkxQoN+vz5aJPsLBn77n8QgTFmo8WK0/44auK2xlCXrYcUxHFxgU7qW5Yzw/CjmLRK2uJzaCd7LvqQ==
  dependencies:
    "@babel/plugin-syntax-async-generators" "^7.8.4"
    "@babel/plugin-syntax-bigint" "^7.8.3"
    "@babel/plugin-syntax-class-properties" "^7.8.3"
    "@babel/plugin-syntax-import-meta" "^7.8.3"
    "@babel/plugin-syntax-json-strings" "^7.8.3"
    "@babel/plugin-syntax-logical-assignment-operators" "^7.8.3"
    "@babel/plugin-syntax-nullish-coalescing-operator" "^7.8.3"
    "@babel/plugin-syntax-numeric-separator" "^7.8.3"
    "@babel/plugin-syntax-object-rest-spread" "^7.8.3"
    "@babel/plugin-syntax-optional-catch-binding" "^7.8.3"
    "@babel/plugin-syntax-optional-chaining" "^7.8.3"
    "@babel/plugin-syntax-top-level-await" "^7.8.3"

babel-preset-jest@^29.6.3:
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/babel-preset-jest/-/babel-preset-jest-29.6.3.tgz#fa05fa510e7d493896d7b0dd2033601c840f171c"
  integrity sha512-0B3bhxR6snWXJZtR/RliHTDPRgn1sNHOR0yVtq/IiQFyuOVjFS+wuio/R4gSNkyYmKmJB4wGZv2NZanmKmTnNA==
  dependencies:
    babel-plugin-jest-hoist "^29.6.3"
    babel-preset-current-node-syntax "^1.0.0"

balanced-match@^1.0.0:
  version "1.0.2"
  resolved "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz"
  integrity sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==

bare-events@^2.0.0, bare-events@^2.2.0:
  version "2.2.2"
  resolved "https://registry.yarnpkg.com/bare-events/-/bare-events-2.2.2.tgz#a98a41841f98b2efe7ecc5c5468814469b018078"
  integrity sha512-h7z00dWdG0PYOQEvChhOSWvOfkIKsdZGkWr083FgN/HyoQuebSew/cgirYqh9SCuy/hRvxc5Vy6Fw8xAmYHLkQ==

bare-fs@^2.1.1:
  version "2.2.3"
  resolved "https://registry.yarnpkg.com/bare-fs/-/bare-fs-2.2.3.tgz#34f8b81b8c79de7ef043383c05e57d4a10392a68"
  integrity sha512-amG72llr9pstfXOBOHve1WjiuKKAMnebcmMbPWDZ7BCevAoJLpugjuAPRsDINEyjT0a6tbaVx3DctkXIRbLuJw==
  dependencies:
    bare-events "^2.0.0"
    bare-path "^2.0.0"
    streamx "^2.13.0"

bare-os@^2.1.0:
  version "2.2.1"
  resolved "https://registry.yarnpkg.com/bare-os/-/bare-os-2.2.1.tgz#c94a258c7a408ca6766399e44675136c0964913d"
  integrity sha512-OwPyHgBBMkhC29Hl3O4/YfxW9n7mdTr2+SsO29XBWKKJsbgj3mnorDB80r5TiCQgQstgE5ga1qNYrpes6NvX2w==

bare-path@^2.0.0, bare-path@^2.1.0:
  version "2.1.1"
  resolved "https://registry.yarnpkg.com/bare-path/-/bare-path-2.1.1.tgz#111db5bf2db0aed40081aa4ba38b8dfc2bb782eb"
  integrity sha512-OHM+iwRDRMDBsSW7kl3dO62JyHdBKO3B25FB9vNQBPcGHMo4+eA8Yj41Lfbk3pS/seDY+siNge0LdRTulAau/A==
  dependencies:
    bare-os "^2.1.0"

base64-arraybuffer@^1.0.2:
  version "1.0.2"
  resolved "https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-1.0.2.tgz#1c37589a7c4b0746e34bd1feb951da2df01c1bdc"
  integrity sha512-I3yl4r9QB5ZRY3XuJVEPfc2XhZO6YweFPI+UovAzn+8/hb3oJ6lnysaFcjVpkCPfVWFUDvoZ8kmVDP7WyRtYtQ==

base64-js@^1.3.1:
  version "1.5.1"
  resolved "https://registry.yarnpkg.com/base64-js/-/base64-js-1.5.1.tgz#1b1b440160a5bf7ad40b650f095963481903930a"
  integrity sha512-AKpaYlHn8t4SVbOHCy+b5+KKgvR4vrsD8vbvrbiQJps7fKDTkjkDry6ji0rUJjC0kzbNePLwzxq8iypo41qeWA==

basic-ftp@^5.0.2:
  version "5.0.5"
  resolved "https://registry.yarnpkg.com/basic-ftp/-/basic-ftp-5.0.5.tgz#14a474f5fffecca1f4f406f1c26b18f800225ac0"
  integrity sha512-4Bcg1P8xhUuqcii/S0Z9wiHIrQVPMermM1any+MX5GeGD7faD3/msQUDGLol9wOcz4/jbg/WJnGqoJF6LiBdtg==

binary-extensions@^2.0.0:
  version "2.2.0"
  resolved "https://registry.npmjs.org/binary-extensions/-/binary-extensions-2.2.0.tgz"
  integrity sha512-jDctJ/IVQbZoJykoeHbhXpOlNBqGNcwXJKJog42E5HDPUwQTSdjCHdihjj0DlnheQ7blbT6dHOafNAiS8ooQKA==

boolbase@^1.0.0:
  version "1.0.0"
  resolved "https://registry.yarnpkg.com/boolbase/-/boolbase-1.0.0.tgz#68dff5fbe60c51eb37725ea9e3ed310dcc1e776e"
  integrity sha512-JZOSA7Mo9sNGB8+UjSgzdLtokWAky1zbztM3WRLCbZ70/3cTANmQmOdR7y2g+J0e2WXywy1yS468tY+IruqEww==

brace-expansion@^1.1.7:
  version "1.1.11"
  resolved "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz"
  integrity sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==
  dependencies:
    balanced-match "^1.0.0"
    concat-map "0.0.1"

brace-expansion@^2.0.1:
  version "2.0.1"
  resolved "https://registry.yarnpkg.com/brace-expansion/-/brace-expansion-2.0.1.tgz#1edc459e0f0c548486ecf9fc99f2221364b9a0ae"
  integrity sha512-XnAIvQ8eM+kC6aULx6wuQiwVsnzsi9d3WxzV3FpWTGA19F621kwdbsAcFKXgKUHZWsy+mY6iL1sHTxWEFCytDA==
  dependencies:
    balanced-match "^1.0.0"

braces@^3.0.2, braces@~3.0.2:
  version "3.0.2"
  resolved "https://registry.npmjs.org/braces/-/braces-3.0.2.tgz"
  integrity sha512-b8um+L1RzM3WDSzvhm6gIz1yfTbBt6YTlcEKAvsmqCZZFw46z626lVj9j1yEPW33H5H+lBQpZMP1k8l+78Ha0A==
  dependencies:
    fill-range "^7.0.1"

browserslist@^4.21.10, browserslist@^4.21.9:
  version "4.22.1"
  resolved "https://registry.npmjs.org/browserslist/-/browserslist-4.22.1.tgz"
  integrity sha512-FEVc202+2iuClEhZhrWy6ZiAcRLvNMyYcxZ8raemul1DYVOVdFsbqckWLdsixQZCpJlwe77Z3UTalE7jsjnKfQ==
  dependencies:
    caniuse-lite "^1.0.30001541"
    electron-to-chromium "^1.4.535"
    node-releases "^2.0.13"
    update-browserslist-db "^1.0.13"

browserslist@^4.22.2:
  version "4.23.0"
  resolved "https://registry.yarnpkg.com/browserslist/-/browserslist-4.23.0.tgz#8f3acc2bbe73af7213399430890f86c63a5674ab"
  integrity sha512-QW8HiM1shhT2GuzkvklfjcKDiWFXHOeFCIA/huJPwHsslwcydgk7X+z2zXpEijP98UCY7HbubZt5J2Zgvf0CaQ==
  dependencies:
    caniuse-lite "^1.0.30001587"
    electron-to-chromium "^1.4.668"
    node-releases "^2.0.14"
    update-browserslist-db "^1.0.13"

bs-logger@0.x:
  version "0.2.6"
  resolved "https://registry.yarnpkg.com/bs-logger/-/bs-logger-0.2.6.tgz#eb7d365307a72cf974cc6cda76b68354ad336bd8"
  integrity sha512-pd8DCoxmbgc7hyPKOvxtqNcjYoOsABPQdcCUjGp3d42VR2CX1ORhk2A87oqqu5R1kk+76nsxZupkmyd+MVtCog==
  dependencies:
    fast-json-stable-stringify "2.x"

bser@2.1.1:
  version "2.1.1"
  resolved "https://registry.yarnpkg.com/bser/-/bser-2.1.1.tgz#e6787da20ece9d07998533cfd9de6f5c38f4bc05"
  integrity sha512-gQxTNE/GAfIIrmHLUE3oJyp5FO6HRBfhjnw4/wMmA63ZGDJnWBmgY/lyQBpnDUkGmAhbSe39tx2d/iTOAfglwQ==
  dependencies:
    node-int64 "^0.4.0"

buffer-crc32@~0.2.3:
  version "0.2.13"
  resolved "https://registry.yarnpkg.com/buffer-crc32/-/buffer-crc32-0.2.13.tgz#0d333e3f00eac50aa1454abd30ef8c2a5d9a7242"
  integrity sha512-VO9Ht/+p3SN7SKWqcrgEzjGbRSJYTx+Q1pTQC0wrWqHx0vpJraQ6GtHx8tvcg1rlK1byhU5gccxgOgj7B0TDkQ==

buffer-from@^1.0.0:
  version "1.1.2"
  resolved "https://registry.yarnpkg.com/buffer-from/-/buffer-from-1.1.2.tgz#2b146a6fd72e80b4f55d255f35ed59a3a9a41bd5"
  integrity sha512-E+XQCRwSbaaiChtv6k6Dwgc+bx+Bs6vuKJHHl5kox/BaKbhiXzqQOwK4cO22yElGp2OCmjwVhT3HmxgyPGnJfQ==

buffer@^5.2.1:
  version "5.7.1"
  resolved "https://registry.yarnpkg.com/buffer/-/buffer-5.7.1.tgz#ba62e7c13133053582197160851a8f648e99eed0"
  integrity sha512-EHcyIPBQ4BSGlvjB16k5KgAJ27CIsHY/2JBmCRReo48y9rQ3MaUzWX3KVlBa4U7MyX02HdVj0K7C3WaB3ju7FQ==
  dependencies:
    base64-js "^1.3.1"
    ieee754 "^1.1.13"

buffer@^6.0.3:
  version "6.0.3"
  resolved "https://registry.yarnpkg.com/buffer/-/buffer-6.0.3.tgz#2ace578459cc8fbe2a70aaa8f52ee63b6a74c6c6"
  integrity sha512-FTiCpNxtwiZZHEZbcbTIcZjERVICn9yq/pDFkTl95/AxzD1naBctN7YO68riM/gLSDY7sdrMby8hofADYuuqOA==
  dependencies:
    base64-js "^1.3.1"
    ieee754 "^1.2.1"

cac@^6.7.14:
  version "6.7.14"
  resolved "https://registry.yarnpkg.com/cac/-/cac-6.7.14.tgz#804e1e6f506ee363cb0e3ccbb09cad5dd9870959"
  integrity sha512-b6Ilus+c3RrdDk+JhLKUAQfzzgLEPy6wcXqS7f/xe1EETvsDP6GORG7SFuOs6cID5YkqchW/LXZbX5bc8j7ZcQ==

callsites@^3.0.0:
  version "3.1.0"
  resolved "https://registry.npmjs.org/callsites/-/callsites-3.1.0.tgz"
  integrity sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==

camel-case@^4.1.2:
  version "4.1.2"
  resolved "https://registry.yarnpkg.com/camel-case/-/camel-case-4.1.2.tgz#9728072a954f805228225a6deea6b38461e1bd5a"
  integrity sha512-gxGWBrTT1JuMx6R+o5PTXMmUnhnVzLQ9SNutD4YqKtI6ap897t3tKECYla6gCWEkplXnlNybEkZg9GEGxKFCgw==
  dependencies:
    pascal-case "^3.1.2"
    tslib "^2.0.3"

camelcase-css@^2.0.1:
  version "2.0.1"
  resolved "https://registry.npmjs.org/camelcase-css/-/camelcase-css-2.0.1.tgz"
  integrity sha512-QOSvevhslijgYwRx6Rv7zKdMF8lbRmx+uQGx2+vDc+KI/eBnsy9kit5aj23AgGu3pa4t9AgwbnXWqS+iOY+2aA==

camelcase@^5.3.1:
  version "5.3.1"
  resolved "https://registry.yarnpkg.com/camelcase/-/camelcase-5.3.1.tgz#e3c9b31569e106811df242f715725a1f4c494320"
  integrity sha512-L28STB170nwWS63UjtlEOE3dldQApaJXZkOI1uMFfzf3rRuPegHaHesyee+YxQ+W6SvRDQV6UrdOdRiR153wJg==

camelcase@^6.2.0:
  version "6.3.0"
  resolved "https://registry.yarnpkg.com/camelcase/-/camelcase-6.3.0.tgz#5685b95eb209ac9c0c177467778c9c84df58ba9a"
  integrity sha512-Gmy6FhYlCY7uOElZUSbxo2UCDH8owEk996gkbrpsgGtrJLM3J7jGxl9Ic7Qwwj4ivOE5AWZWRMecDdF7hqGjFA==

caniuse-lite@^1.0.30001538, caniuse-lite@^1.0.30001541:
  version "1.0.30001562"
  resolved "https://registry.npmjs.org/caniuse-lite/-/caniuse-lite-1.0.30001562.tgz"
  integrity sha512-kfte3Hym//51EdX4239i+Rmp20EsLIYGdPkERegTgU19hQWCRhsRFGKHTliUlsry53tv17K7n077Kqa0WJU4ng==

caniuse-lite@^1.0.30001587:
  version "1.0.30001620"
  resolved "https://registry.yarnpkg.com/caniuse-lite/-/caniuse-lite-1.0.30001620.tgz#78bb6f35b8fe315b96b8590597094145d0b146b4"
  integrity sha512-WJvYsOjd1/BYUY6SNGUosK9DUidBPDTnOARHp3fSmFO1ekdxaY6nKRttEVrfMmYi80ctS0kz1wiWmm14fVc3ew==

chai@^4.3.10:
  version "4.3.10"
  resolved "https://registry.yarnpkg.com/chai/-/chai-4.3.10.tgz#d784cec635e3b7e2ffb66446a63b4e33bd390384"
  integrity sha512-0UXG04VuVbruMUYbJ6JctvH0YnC/4q3/AkT18q4NaITo91CUm0liMS9VqzT9vZhVQ/1eqPanMWjBM+Juhfb/9g==
  dependencies:
    assertion-error "^1.1.0"
    check-error "^1.0.3"
    deep-eql "^4.1.3"
    get-func-name "^2.0.2"
    loupe "^2.3.6"
    pathval "^1.1.1"
    type-detect "^4.0.8"

chalk@^2.4.2:
  version "2.4.2"
  resolved "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz"
  integrity sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==
  dependencies:
    ansi-styles "^3.2.1"
    escape-string-regexp "^1.0.5"
    supports-color "^5.3.0"

chalk@^4.0.0, chalk@^4.0.2, chalk@^4.1.1:
  version "4.1.2"
  resolved "https://registry.npmjs.org/chalk/-/chalk-4.1.2.tgz"
  integrity sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==
  dependencies:
    ansi-styles "^4.1.0"
    supports-color "^7.1.0"

char-regex@^1.0.2:
  version "1.0.2"
  resolved "https://registry.yarnpkg.com/char-regex/-/char-regex-1.0.2.tgz#d744358226217f981ed58f479b1d6bcc29545dcf"
  integrity sha512-kWWXztvZ5SBQV+eRgKFeh8q5sLuZY2+8WUIzlxWVTg+oGwY14qylx1KbKzHd8P6ZYkAg0xyIDU9JMHhyJMZ1jw==

check-error@^1.0.3:
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/check-error/-/check-error-1.0.3.tgz#a6502e4312a7ee969f646e83bb3ddd56281bd694"
  integrity sha512-iKEoDYaRmd1mxM90a2OEfWhjsjPpYPuQ+lMYsoxB126+t8fw7ySEO48nmDg5COTjxDI65/Y2OWpeEHk3ZOe8zg==
  dependencies:
    get-func-name "^2.0.2"

chokidar@^3.5.1, chokidar@^3.5.3:
  version "3.5.3"
  resolved "https://registry.npmjs.org/chokidar/-/chokidar-3.5.3.tgz"
  integrity sha512-Dr3sfKRP6oTcjf2JmUmFJfeVMvXBdegxB0iVQ5eb2V10uFJUCAS8OByZdVAyVb8xXNz3GjjTgj9kLWsZTqE6kw==
  dependencies:
    anymatch "~3.1.2"
    braces "~3.0.2"
    glob-parent "~5.1.2"
    is-binary-path "~2.1.0"
    is-glob "~4.0.1"
    normalize-path "~3.0.0"
    readdirp "~3.6.0"
  optionalDependencies:
    fsevents "~2.3.2"

chromium-bidi@0.5.17:
  version "0.5.17"
  resolved "https://registry.yarnpkg.com/chromium-bidi/-/chromium-bidi-0.5.17.tgz#04b66fa77f9ab80234b72206e71fc2af96fd08c4"
  integrity sha512-BqOuIWUgTPj8ayuBFJUYCCuwIcwjBsb3/614P7tt1bEPJ4i1M0kCdIl0Wi9xhtswBXnfO2bTpTMkHD71H8rJMg==
  dependencies:
    mitt "3.0.1"
    urlpattern-polyfill "10.0.0"
    zod "3.22.4"

chromium-bidi@0.5.19:
  version "0.5.19"
  resolved "https://registry.yarnpkg.com/chromium-bidi/-/chromium-bidi-0.5.19.tgz#e4f4951b7d9b20d668d6b387839f7b7bf2d69ef4"
  integrity sha512-UA6zL77b7RYCjJkZBsZ0wlvCTD+jTjllZ8f6wdO4buevXgTZYjV+XLB9CiEa2OuuTGGTLnI7eN9I60YxuALGQg==
  dependencies:
    mitt "3.0.1"
    urlpattern-polyfill "10.0.0"
    zod "3.22.4"

ci-info@^3.2.0:
  version "3.9.0"
  resolved "https://registry.yarnpkg.com/ci-info/-/ci-info-3.9.0.tgz#4279a62028a7b1f262f3473fc9605f5e218c59b4"
  integrity sha512-NIxF55hv4nSqQswkAeiOi1r83xy8JldOFDTWiug55KBu9Jnblncd2U6ViHmYgHf01TPZS77NJBhBMKdWj9HQMQ==

cjs-module-lexer@^1.0.0:
  version "1.3.1"
  resolved "https://registry.yarnpkg.com/cjs-module-lexer/-/cjs-module-lexer-1.3.1.tgz#c485341ae8fd999ca4ee5af2d7a1c9ae01e0099c"
  integrity sha512-a3KdPAANPbNE4ZUv9h6LckSl9zLsYOP4MBmhIPkRaeyybt+r4UghLvq+xw/YwUcC1gqylCkL4rdVs3Lwupjm4Q==

class-variance-authority@^0.7.0:
  version "0.7.0"
  resolved "https://registry.yarnpkg.com/class-variance-authority/-/class-variance-authority-0.7.0.tgz#1c3134d634d80271b1837452b06d821915954522"
  integrity sha512-jFI8IQw4hczaL4ALINxqLEXQbWcNjoSkloa4IaufXCJr6QawJyw7tuRysRsrE8w2p/4gGaxKIt/hX3qz/IbD1A==
  dependencies:
    clsx "2.0.0"

classnames@^2.3.2:
  version "2.3.2"
  resolved "https://registry.npmjs.org/classnames/-/classnames-2.3.2.tgz"
  integrity sha512-CSbhY4cFEJRe6/GQzIk5qXZ4Jeg5pcsP7b5peFSDpffpe1cqjASH/n9UTjBwOp6XpMSTwQ8Za2K5V02ueA7Tmw==

clean-css@^5.2.2:
  version "5.3.2"
  resolved "https://registry.yarnpkg.com/clean-css/-/clean-css-5.3.2.tgz#70ecc7d4d4114921f5d298349ff86a31a9975224"
  integrity sha512-JVJbM+f3d3Q704rF4bqQ5UUyTtuJ0JRKNbTKVEeujCCBoMdkEi+V+e8oktO9qGQNSvHrFTM6JZRXrUvGR1czww==
  dependencies:
    source-map "~0.6.0"

cliui@^8.0.1:
  version "8.0.1"
  resolved "https://registry.yarnpkg.com/cliui/-/cliui-8.0.1.tgz#0c04b075db02cbfe60dc8e6cf2f5486b1a3608aa"
  integrity sha512-BSeNnyus75C4//NQ9gQt1/csTXyo/8Sb+afLAkzAptFuMsod9HFokGNudZpi/oQV73hnVK+sR+5PVRMd+Dr7YQ==
  dependencies:
    string-width "^4.2.0"
    strip-ansi "^6.0.1"
    wrap-ansi "^7.0.0"

clsx@2.0.0, clsx@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/clsx/-/clsx-2.0.0.tgz#12658f3fd98fafe62075595a5c30e43d18f3d00b"
  integrity sha512-rQ1+kcj+ttHG0MKVGBUXwayCCF1oh39BF5COIpRzuCEv8Mwjv0XucrI2ExNTOn9IlLifGClWQcU9BrZORvtw6Q==

co@^4.6.0:
  version "4.6.0"
  resolved "https://registry.yarnpkg.com/co/-/co-4.6.0.tgz#6ea6bdf3d853ae54ccb8e47bfa0bf3f9031fb184"
  integrity sha512-QVb0dM5HvG+uaxitm8wONl7jltx8dqhfU33DcqtOZcLSVIKSDDLDi7+0LbAKiyI8hD9u42m2YxXSkMGWThaecQ==

codemirror@^6.0.1:
  version "6.0.1"
  resolved "https://registry.yarnpkg.com/codemirror/-/codemirror-6.0.1.tgz#62b91142d45904547ee3e0e0e4c1a79158035a29"
  integrity sha512-J8j+nZ+CdWmIeFIGXEFbFPtpiYacFMDR8GlHK3IyHQJMCaVRfGx9NT+Hxivv1ckLWPvNdZqndbr/7lVhrf/Svg==
  dependencies:
    "@codemirror/autocomplete" "^6.0.0"
    "@codemirror/commands" "^6.0.0"
    "@codemirror/language" "^6.0.0"
    "@codemirror/lint" "^6.0.0"
    "@codemirror/search" "^6.0.0"
    "@codemirror/state" "^6.0.0"
    "@codemirror/view" "^6.0.0"

collect-v8-coverage@^1.0.0:
  version "1.0.2"
  resolved "https://registry.yarnpkg.com/collect-v8-coverage/-/collect-v8-coverage-1.0.2.tgz#c0b29bcd33bcd0779a1344c2136051e6afd3d9e9"
  integrity sha512-lHl4d5/ONEbLlJvaJNtsF/Lz+WvB07u2ycqTYbdrq7UypDXailES4valYb2eWiJFxZlVmpGekfqoxQhzyFdT4Q==

color-convert@^1.9.0:
  version "1.9.3"
  resolved "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz"
  integrity sha512-QfAUtd+vFdAtFQcC8CCyYt1fYWxSqAiK2cSD6zDB8N3cpsEBAvRxp9zOGg6G/SHHJYAT88/az/IuDGALsNVbGg==
  dependencies:
    color-name "1.1.3"

color-convert@^2.0.1:
  version "2.0.1"
  resolved "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz"
  integrity sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==
  dependencies:
    color-name "~1.1.4"

color-name@1.1.3:
  version "1.1.3"
  resolved "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz"
  integrity sha512-72fSenhMw2HZMTVHeCA9KCmpEIbzWiQsjN+BHcBbS9vr1mtt+vJjPdksIBNUmKAW8TFUDPJK5SUU3QhE9NEXDw==

color-name@~1.1.4:
  version "1.1.4"
  resolved "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz"
  integrity sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==

colorette@^2.0.16:
  version "2.0.20"
  resolved "https://registry.yarnpkg.com/colorette/-/colorette-2.0.20.tgz#9eb793e6833067f7235902fcd3b09917a000a95a"
  integrity sha512-IfEDxwoWIjkeXL1eXcDiow4UbKjhLdq6/EuSVR9GMN7KVH3r9gQ83e73hsz1Nd1T3ijd5xv1wcWRYO+D6kCI2w==

commander@^2.20.0:
  version "2.20.3"
  resolved "https://registry.yarnpkg.com/commander/-/commander-2.20.3.tgz#fd485e84c03eb4881c20722ba48035e8531aeb33"
  integrity sha512-GpVkmM8vF2vQUkj2LvZmD35JxeJOLCwJ9cUkugyk2nuhbv3+mJvpLYYt+0+USMxE+oj+ey/lJEnhZw75x/OMcQ==

commander@^4.0.0:
  version "4.1.1"
  resolved "https://registry.npmjs.org/commander/-/commander-4.1.1.tgz"
  integrity sha512-NOKm8xhkzAjzFx8B2v5OAHT+u5pRQc2UCa2Vq9jYL/31o2wi9mxBA7LIFs3sV5VSC49z6pEhfbMULvShKj26WA==

commander@^8.0.0, commander@^8.3.0:
  version "8.3.0"
  resolved "https://registry.npmjs.org/commander/-/commander-8.3.0.tgz"
  integrity sha512-OkTL9umf+He2DZkUq8f8J9of7yL6RJKI24dVITBmNfZBmri9zYZQrKkuXiKhyfPSu8tUhnVBB1iKXevvnlR4Ww==

concat-map@0.0.1:
  version "0.0.1"
  resolved "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz"
  integrity sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg==

connect-history-api-fallback@^1.6.0:
  version "1.6.0"
  resolved "https://registry.yarnpkg.com/connect-history-api-fallback/-/connect-history-api-fallback-1.6.0.tgz#8b32089359308d111115d81cad3fceab888f97bc"
  integrity sha512-e54B99q/OUoH64zYYRf3HBP5z24G38h5D3qXu23JGRoigpX5Ss4r9ZnDk3g0Z8uQC2x2lPaJ+UlWBc1ZWBWdLg==

consola@^2.15.3:
  version "2.15.3"
  resolved "https://registry.yarnpkg.com/consola/-/consola-2.15.3.tgz#2e11f98d6a4be71ff72e0bdf07bd23e12cb61550"
  integrity sha512-9vAdYbHj6x2fLKC4+oPH0kFzY/orMZyG2Aj+kNylHxKGJ/Ed4dpNyAQYwJOdqO4zdM7XpVHmyejQDcQHrnuXbw==

convert-source-map@^2.0.0:
  version "2.0.0"
  resolved "https://registry.npmjs.org/convert-source-map/-/convert-source-map-2.0.0.tgz"
  integrity sha512-Kvp459HrV2FEJ1CAsi1Ku+MY3kasH19TFykTz2xWmMeq6bk2NU3XXvfJ+Q61m0xktWwt+1HSYf3JZsTms3aRJg==

copy-to-clipboard@^3.3.3:
  version "3.3.3"
  resolved "https://registry.npmjs.org/copy-to-clipboard/-/copy-to-clipboard-3.3.3.tgz#55ac43a1db8ae639a4bd99511c148cdd1b83a1b0"
  integrity sha512-2KV8NhB5JqC3ky0r9PMCAZKbUHSwtEo4CwCs0KXgruG43gX5PMqDEBbVU4OUzw2MuAWUfsuFmWvEKG5QRfSnJA==
  dependencies:
    toggle-selection "^1.0.6"

cosmiconfig@9.0.0:
  version "9.0.0"
  resolved "https://registry.yarnpkg.com/cosmiconfig/-/cosmiconfig-9.0.0.tgz#34c3fc58287b915f3ae905ab6dc3de258b55ad9d"
  integrity sha512-itvL5h8RETACmOTFc4UfIyB2RfEHi71Ax6E/PivVxq9NseKbOWpeyHEOIbmAw1rs8Ak0VursQNww7lf7YtUwzg==
  dependencies:
    env-paths "^2.2.1"
    import-fresh "^3.3.0"
    js-yaml "^4.1.0"
    parse-json "^5.2.0"

create-jest@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/create-jest/-/create-jest-29.7.0.tgz#a355c5b3cb1e1af02ba177fe7afd7feee49a5320"
  integrity sha512-Adz2bdH0Vq3F53KEMJOoftQFutWCukm6J24wbPWRO4k1kMY7gS7ds/uoJkNuV8wDCtWWnuwGcJwpWcih+zEW1Q==
  dependencies:
    "@jest/types" "^29.6.3"
    chalk "^4.0.0"
    exit "^0.1.2"
    graceful-fs "^4.2.9"
    jest-config "^29.7.0"
    jest-util "^29.7.0"
    prompts "^2.0.1"

crelt@^1.0.5:
  version "1.0.6"
  resolved "https://registry.yarnpkg.com/crelt/-/crelt-1.0.6.tgz#7cc898ea74e190fb6ef9dae57f8f81cf7302df72"
  integrity sha512-VQ2MBenTq1fWZUH9DJNGti7kKv6EeAuYr3cLwxUWhIu1baTaXh4Ib5W2CqHVqib4/MqbYGJqiL3Zb8GJZr3l4g==

cross-spawn@^7.0.2, cross-spawn@^7.0.3:
  version "7.0.3"
  resolved "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.3.tgz"
  integrity sha512-iRDPJKUPVEND7dHPO8rkbOnPpyDygcDFtWjpeWNCgy8WP2rXcxXL8TskReQl6OrB2G7+UJrags1q15Fudc7G6w==
  dependencies:
    path-key "^3.1.0"
    shebang-command "^2.0.0"
    which "^2.0.1"

css-line-break@^2.1.0:
  version "2.1.0"
  resolved "https://registry.npmjs.org/css-line-break/-/css-line-break-2.1.0.tgz#bfef660dfa6f5397ea54116bb3cb4873edbc4fa0"
  integrity sha512-FHcKFCZcAha3LwfVBhCQbW2nCNbkZXn7KVUJcsT5/P8YmfsVja0FMPJr0B903j/E69HUphKiV9iQArX8SDYA4w==
  dependencies:
    utrie "^1.0.2"

css-select@^4.2.1:
  version "4.3.0"
  resolved "https://registry.yarnpkg.com/css-select/-/css-select-4.3.0.tgz#db7129b2846662fd8628cfc496abb2b59e41529b"
  integrity sha512-wPpOYtnsVontu2mODhA19JrqWxNsfdatRKd64kmpRbQgh1KtItko5sTnEpPdpSaJszTOhEMlF/RPz28qj4HqhQ==
  dependencies:
    boolbase "^1.0.0"
    css-what "^6.0.1"
    domhandler "^4.3.1"
    domutils "^2.8.0"
    nth-check "^2.0.1"

css-what@^6.0.1:
  version "6.1.0"
  resolved "https://registry.yarnpkg.com/css-what/-/css-what-6.1.0.tgz#fb5effcf76f1ddea2c81bdfaa4de44e79bac70f4"
  integrity sha512-HTUrgRJ7r4dsZKU6GjmpfRK1O76h97Z8MfS1G0FozR+oF2kG6Vfe8JE6zwrkbxigziPHinCJ+gCPjA9EaBDtRw==

cssesc@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/cssesc/-/cssesc-3.0.0.tgz"
  integrity sha512-/Tb/JcjK111nNScGob5MNtsntNM1aCNUDipB/TkwZFhyDrrE47SOx/18wF2bbjgc3ZzCSKW1T5nt5EbFoAz/Vg==

csstype@^3.0.2:
  version "3.1.2"
  resolved "https://registry.npmjs.org/csstype/-/csstype-3.1.2.tgz"
  integrity sha512-I7K1Uu0MBPzaFKg4nI5Q7Vs2t+3gWWW648spaF+Rg7pI9ds18Ugn+lvg4SHczUdKlHI5LWBXyqfS8+DufyBsgQ==

data-uri-to-buffer@^6.0.2:
  version "6.0.2"
  resolved "https://registry.yarnpkg.com/data-uri-to-buffer/-/data-uri-to-buffer-6.0.2.tgz#8a58bb67384b261a38ef18bea1810cb01badd28b"
  integrity sha512-7hvf7/GW8e86rW0ptuwS3OcBGDjIi6SZva7hCyWC0yYry2cOPmLIjXAUHI6DK2HsnwJd9ifmt57i8eV2n4YNpw==

debug@4, debug@4.3.4, debug@^4.1.0, debug@^4.1.1, debug@^4.3.1, debug@^4.3.2, debug@^4.3.4:
  version "4.3.4"
  resolved "https://registry.npmjs.org/debug/-/debug-4.3.4.tgz"
  integrity sha512-PRWFHuSU3eDtQJPvnNY7Jcket1j0t5OuOsFzPPzsekD52Zl8qUfFIPEiswXqIvHWGVHOgX+7G/vCNNhehwxfkQ==
  dependencies:
    ms "2.1.2"

dedent@^1.0.0:
  version "1.5.3"
  resolved "https://registry.yarnpkg.com/dedent/-/dedent-1.5.3.tgz#99aee19eb9bae55a67327717b6e848d0bf777e5a"
  integrity sha512-NHQtfOOW68WD8lgypbLA5oT+Bt0xXJhiYvoR6SmmNXZfpzOGXwdKWmcwG8N7PwVVWV3eF/68nmD9BaJSsTBhyQ==

deep-eql@^4.1.3:
  version "4.1.3"
  resolved "https://registry.yarnpkg.com/deep-eql/-/deep-eql-4.1.3.tgz#7c7775513092f7df98d8df9996dd085eb668cc6d"
  integrity sha512-WaEtAOpRA1MQ0eohqZjpGD8zdI0Ovsm8mmFhaDN8dvDZzyoUMcYDnf5Y6iu7HTXxf8JDS23qWa4a+hKCDyOPzw==
  dependencies:
    type-detect "^4.0.0"

deep-is@^0.1.3:
  version "0.1.4"
  resolved "https://registry.npmjs.org/deep-is/-/deep-is-0.1.4.tgz"
  integrity sha512-oIPzksmTg4/MriiaYGO+okXDT7ztn/w3Eptv/+gSIdMdKsJo0u4CfYNFJPy+4SKMuCqGw2wxnA+URMg3t8a/bQ==

deepmerge@^4.2.2:
  version "4.3.1"
  resolved "https://registry.yarnpkg.com/deepmerge/-/deepmerge-4.3.1.tgz#44b5f2147cd3b00d4b56137685966f26fd25dd4a"
  integrity sha512-3sUqbMEc77XqpdNO7FRyRog+eW3ph+GYCbj+rK+uYyRMuwsVy0rMiVtPn+QJlKFvWP/1PYpapqYn0Me2knFn+A==

degenerator@^5.0.0:
  version "5.0.1"
  resolved "https://registry.yarnpkg.com/degenerator/-/degenerator-5.0.1.tgz#9403bf297c6dad9a1ece409b37db27954f91f2f5"
  integrity sha512-TllpMR/t0M5sqCXfj85i4XaAzxmS5tVA16dqvdkMwGmzI+dXLXnw3J+3Vdv7VKw+ThlTMboK6i9rnZ6Nntj5CQ==
  dependencies:
    ast-types "^0.13.4"
    escodegen "^2.1.0"
    esprima "^4.0.1"

detect-newline@^3.0.0:
  version "3.1.0"
  resolved "https://registry.yarnpkg.com/detect-newline/-/detect-newline-3.1.0.tgz#576f5dfc63ae1a192ff192d8ad3af6308991b651"
  integrity sha512-TLz+x/vEXm/Y7P7wn1EJFNLxYpUD4TgMosxY6fAVJUnJMbupHBOncxyWUG9OpTaH9EBD7uFI5LfEgmMOc54DsA==

detect-node-es@^1.1.0:
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/detect-node-es/-/detect-node-es-1.1.0.tgz#163acdf643330caa0b4cd7c21e7ee7755d6fa493"
  integrity sha512-ypdmJU/TbBby2Dxibuv7ZLW3Bs1QEmM7nHjEANfohJLvE0XVujisn1qPJcZxg+qDucsr+bP6fLD1rPS3AhJ7EQ==

devtools-protocol@0.0.1262051:
  version "0.0.1262051"
  resolved "https://registry.yarnpkg.com/devtools-protocol/-/devtools-protocol-0.0.1262051.tgz#670b1f8459b2a136e05bd9a8d54ec0212d543a38"
  integrity sha512-YJe4CT5SA8on3Spa+UDtNhEqtuV6Epwz3OZ4HQVLhlRccpZ9/PAYk0/cy/oKxFKRrZPBUPyxympQci4yWNWZ9g==

devtools-protocol@0.0.1286932:
  version "0.0.1286932"
  resolved "https://registry.yarnpkg.com/devtools-protocol/-/devtools-protocol-0.0.1286932.tgz#2303707034426fe0b39012713d4b7339f7dbc815"
  integrity sha512-wu58HMQll9voDjR4NlPyoDEw1syfzaBNHymMMZ/QOXiHRNluOnDgu9hp1yHOKYoMlxCh4lSSiugLITe6Fvu1eA==

didyoumean@^1.2.2:
  version "1.2.2"
  resolved "https://registry.npmjs.org/didyoumean/-/didyoumean-1.2.2.tgz"
  integrity sha512-gxtyfqMg7GKyhQmb056K7M3xszy/myH8w+B4RT+QXBQsvAOdc3XymqDDPHx1BgPgsdAA5SIifona89YtRATDzw==

diff-sequences@^29.6.3:
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/diff-sequences/-/diff-sequences-29.6.3.tgz#4deaf894d11407c51efc8418012f9e70b84ea921"
  integrity sha512-EjePK1srD3P08o2j4f0ExnylqRs5B9tJjcp9t1krH2qRi8CCdsYfwe9JgSLurFBWwq4uOlipzfk5fHNvwFKr8Q==

dir-glob@^3.0.1:
  version "3.0.1"
  resolved "https://registry.npmjs.org/dir-glob/-/dir-glob-3.0.1.tgz"
  integrity sha512-WkrWp9GR4KXfKGYzOLmTuGVi1UWFfws377n9cc55/tb6DuqyF6pcQ5AbiHEshaDpY9v6oaSr2XCDidGmMwdzIA==
  dependencies:
    path-type "^4.0.0"

dlv@^1.1.3:
  version "1.1.3"
  resolved "https://registry.npmjs.org/dlv/-/dlv-1.1.3.tgz"
  integrity sha512-+HlytyjlPKnIG8XuRG8WvmBP8xs8P71y+SKKS6ZXWoEgLuePxtDoUEiH7WkdePWrQ5JBpE6aoVqfZfJUQkjXwA==

doctrine@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/doctrine/-/doctrine-3.0.0.tgz"
  integrity sha512-yS+Q5i3hBf7GBkd4KG8a7eBNNWNGLTaEwwYWUijIYM7zrlYDM0BFXHjjPWlWZ1Rg7UaddZeIDmi9jF3HmqiQ2w==
  dependencies:
    esutils "^2.0.2"

dom-serializer@^1.0.1:
  version "1.4.1"
  resolved "https://registry.yarnpkg.com/dom-serializer/-/dom-serializer-1.4.1.tgz#de5d41b1aea290215dc45a6dae8adcf1d32e2d30"
  integrity sha512-VHwB3KfrcOOkelEG2ZOfxqLZdfkil8PtJi4P8N2MMXucZq2yLp75ClViUlOVwyoHEDjYU433Aq+5zWP61+RGag==
  dependencies:
    domelementtype "^2.0.1"
    domhandler "^4.2.0"
    entities "^2.0.0"

domelementtype@^2.0.1, domelementtype@^2.2.0:
  version "2.3.0"
  resolved "https://registry.yarnpkg.com/domelementtype/-/domelementtype-2.3.0.tgz#5c45e8e869952626331d7aab326d01daf65d589d"
  integrity sha512-OLETBj6w0OsagBwdXnPdN0cnMfF9opN69co+7ZrbfPGrdpPVNBUj02spi6B1N7wChLQiPn4CSH/zJvXw56gmHw==

domhandler@^4.2.0, domhandler@^4.3.1:
  version "4.3.1"
  resolved "https://registry.yarnpkg.com/domhandler/-/domhandler-4.3.1.tgz#8d792033416f59d68bc03a5aa7b018c1ca89279c"
  integrity sha512-GrwoxYN+uWlzO8uhUXRl0P+kHE4GtVPfYzVLcUxPL7KNdHKj66vvlhiweIHqYYXWlw+T8iLMp42Lm67ghw4WMQ==
  dependencies:
    domelementtype "^2.2.0"

domutils@^2.8.0:
  version "2.8.0"
  resolved "https://registry.yarnpkg.com/domutils/-/domutils-2.8.0.tgz#4437def5db6e2d1f5d6ee859bd95ca7d02048135"
  integrity sha512-w96Cjofp72M5IIhpjgobBimYEfoPjx1Vx0BSX9P30WBdZW2WIKU0T1Bd0kz2eNZ9ikjKgHbEyKx8BB6H1L3h3A==
  dependencies:
    dom-serializer "^1.0.1"
    domelementtype "^2.2.0"
    domhandler "^4.2.0"

dot-case@^3.0.4:
  version "3.0.4"
  resolved "https://registry.yarnpkg.com/dot-case/-/dot-case-3.0.4.tgz#9b2b670d00a431667a8a75ba29cd1b98809ce751"
  integrity sha512-Kv5nKlh6yRrdrGvxeJ2e5y2eRUpkUosIW4A2AS38zwSz27zu7ufDwQPi5Jhs3XAlGNetl3bmnGhQsMtkKJnj3w==
  dependencies:
    no-case "^3.0.4"
    tslib "^2.0.3"

dotenv-expand@^8.0.2:
  version "8.0.3"
  resolved "https://registry.yarnpkg.com/dotenv-expand/-/dotenv-expand-8.0.3.tgz#29016757455bcc748469c83a19b36aaf2b83dd6e"
  integrity sha512-SErOMvge0ZUyWd5B0NXMQlDkN+8r+HhVUsxgOO7IoPDOdDRD2JjExpN6y3KnFR66jsJMwSn1pqIivhU5rcJiNg==

dotenv@^16.0.0:
  version "16.3.1"
  resolved "https://registry.yarnpkg.com/dotenv/-/dotenv-16.3.1.tgz#369034de7d7e5b120972693352a3bf112172cc3e"
  integrity sha512-IPzF4w4/Rd94bA9imS68tZBaYyBWSCE47V1RGuMrB94iyTOIEwRmVL2x/4An+6mETpLrKJ5hQkB8W4kFAadeIQ==

dotenv@^16.4.5:
  version "16.4.5"
  resolved "https://registry.yarnpkg.com/dotenv/-/dotenv-16.4.5.tgz#cdd3b3b604cb327e286b4762e13502f717cb099f"
  integrity sha512-ZmdL2rui+eB2YwhsWzjInR8LldtZHGDoQ1ugH85ppHKwpUHL7j7rN0Ti9NCnGiQbhaZ11FpR+7ao1dNsmduNUg==

ebml-block@^1.1.2:
  version "1.1.2"
  resolved "https://registry.yarnpkg.com/ebml-block/-/ebml-block-1.1.2.tgz#fd49951b0faf5a3049bdd61c851a76b5e679c290"
  integrity sha512-HgNlIsRFP6D9VKU5atCeHRJY7XkJP8bOe8yEhd8NB7B3b4++VWTyauz6g650iiPmLfPLGlVpoJmGSgMfXDYusg==

ejs@^3.1.6:
  version "3.1.9"
  resolved "https://registry.yarnpkg.com/ejs/-/ejs-3.1.9.tgz#03c9e8777fe12686a9effcef22303ca3d8eeb361"
  integrity sha512-rC+QVNMJWv+MtPgkt0y+0rVEIdbtxVADApW9JXrUVlzHetgcyczP/E7DJmWJ4fJCZF2cPcBk0laWO9ZHMG3DmQ==
  dependencies:
    jake "^10.8.5"

electron-to-chromium@^1.4.535:
  version "1.4.582"
  resolved "https://registry.npmjs.org/electron-to-chromium/-/electron-to-chromium-1.4.582.tgz"
  integrity sha512-89o0MGoocwYbzqUUjc+VNpeOFSOK9nIdC5wY4N+PVUarUK0MtjyTjks75AZS2bW4Kl8MdewdFsWaH0jLy+JNoA==

electron-to-chromium@^1.4.668:
  version "1.4.774"
  resolved "https://registry.yarnpkg.com/electron-to-chromium/-/electron-to-chromium-1.4.774.tgz#1017d1758aaeeefe5423aa9d67b4b1e5d1d0a856"
  integrity sha512-132O1XCd7zcTkzS3FgkAzKmnBuNJjK8WjcTtNuoylj7MYbqw5eXehjQ5OK91g0zm7OTKIPeaAG4CPoRfD9M1Mg==

emittery@^0.13.1:
  version "0.13.1"
  resolved "https://registry.yarnpkg.com/emittery/-/emittery-0.13.1.tgz#c04b8c3457490e0847ae51fced3af52d338e3dad"
  integrity sha512-DeWwawk6r5yR9jFgnDKYt4sLS0LmHJJi3ZOnb5/JdbYwj3nW+FxQnHIjhBKz8YLC7oRNPVM9NQ47I3CVx34eqQ==

emoji-regex@^8.0.0:
  version "8.0.0"
  resolved "https://registry.yarnpkg.com/emoji-regex/-/emoji-regex-8.0.0.tgz#e818fd69ce5ccfcb404594f842963bf53164cc37"
  integrity sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==

end-of-stream@^1.1.0:
  version "1.4.4"
  resolved "https://registry.yarnpkg.com/end-of-stream/-/end-of-stream-1.4.4.tgz#5ae64a5f45057baf3626ec14da0ca5e4b2431eb0"
  integrity sha512-+uw1inIHVPQoaVuHzRyXd21icM+cnt4CzD5rW+NC1wjOUSTOs+Te7FOv7AhN7vS9x/oIyhLP5PR1H+phQAHu5Q==
  dependencies:
    once "^1.4.0"

entities@^2.0.0:
  version "2.2.0"
  resolved "https://registry.yarnpkg.com/entities/-/entities-2.2.0.tgz#098dc90ebb83d8dffa089d55256b351d34c4da55"
  integrity sha512-p92if5Nz619I0w+akJrLZH0MX0Pb5DX39XOwQTtXSdQQOaYH03S1uIQp4mhOZtAXrxq4ViO67YTiLBo2638o9A==

env-paths@^2.2.1:
  version "2.2.1"
  resolved "https://registry.yarnpkg.com/env-paths/-/env-paths-2.2.1.tgz#420399d416ce1fbe9bc0a07c62fa68d67fd0f8f2"
  integrity sha512-+h1lkLKhZMTYjog1VEpJNG7NZJWcuc2DDk/qsqSTRRCOXiLjeQ1d1/udrUGhqMxUgAlwKNZ0cf2uqan5GLuS2A==

error-ex@^1.3.1:
  version "1.3.2"
  resolved "https://registry.yarnpkg.com/error-ex/-/error-ex-1.3.2.tgz#b4ac40648107fdcdcfae242f428bea8a14d4f1bf"
  integrity sha512-7dFHNmqeFSEt2ZBsCriorKnn3Z2pj+fd9kmI6QoWw4//DL+icEBfc0U7qJCisqrTsKTjw4fNFy2pW9OqStD84g==
  dependencies:
    is-arrayish "^0.2.1"

esbuild@^0.18.10:
  version "0.18.20"
  resolved "https://registry.npmjs.org/esbuild/-/esbuild-0.18.20.tgz"
  integrity sha512-ceqxoedUrcayh7Y7ZX6NdbbDzGROiyVBgC4PriJThBKSVPWnnFHZAkfI1lJT8QFkOwH4qOS2SJkS4wvpGl8BpA==
  optionalDependencies:
    "@esbuild/android-arm" "0.18.20"
    "@esbuild/android-arm64" "0.18.20"
    "@esbuild/android-x64" "0.18.20"
    "@esbuild/darwin-arm64" "0.18.20"
    "@esbuild/darwin-x64" "0.18.20"
    "@esbuild/freebsd-arm64" "0.18.20"
    "@esbuild/freebsd-x64" "0.18.20"
    "@esbuild/linux-arm" "0.18.20"
    "@esbuild/linux-arm64" "0.18.20"
    "@esbuild/linux-ia32" "0.18.20"
    "@esbuild/linux-loong64" "0.18.20"
    "@esbuild/linux-mips64el" "0.18.20"
    "@esbuild/linux-ppc64" "0.18.20"
    "@esbuild/linux-riscv64" "0.18.20"
    "@esbuild/linux-s390x" "0.18.20"
    "@esbuild/linux-x64" "0.18.20"
    "@esbuild/netbsd-x64" "0.18.20"
    "@esbuild/openbsd-x64" "0.18.20"
    "@esbuild/sunos-x64" "0.18.20"
    "@esbuild/win32-arm64" "0.18.20"
    "@esbuild/win32-ia32" "0.18.20"
    "@esbuild/win32-x64" "0.18.20"

esbuild@^0.19.3:
  version "0.19.8"
  resolved "https://registry.yarnpkg.com/esbuild/-/esbuild-0.19.8.tgz#ad05b72281d84483fa6b5345bd246c27a207b8f1"
  integrity sha512-l7iffQpT2OrZfH2rXIp7/FkmaeZM0vxbxN9KfiCwGYuZqzMg/JdvX26R31Zxn/Pxvsrg3Y9N6XTcnknqDyyv4w==
  optionalDependencies:
    "@esbuild/android-arm" "0.19.8"
    "@esbuild/android-arm64" "0.19.8"
    "@esbuild/android-x64" "0.19.8"
    "@esbuild/darwin-arm64" "0.19.8"
    "@esbuild/darwin-x64" "0.19.8"
    "@esbuild/freebsd-arm64" "0.19.8"
    "@esbuild/freebsd-x64" "0.19.8"
    "@esbuild/linux-arm" "0.19.8"
    "@esbuild/linux-arm64" "0.19.8"
    "@esbuild/linux-ia32" "0.19.8"
    "@esbuild/linux-loong64" "0.19.8"
    "@esbuild/linux-mips64el" "0.19.8"
    "@esbuild/linux-ppc64" "0.19.8"
    "@esbuild/linux-riscv64" "0.19.8"
    "@esbuild/linux-s390x" "0.19.8"
    "@esbuild/linux-x64" "0.19.8"
    "@esbuild/netbsd-x64" "0.19.8"
    "@esbuild/openbsd-x64" "0.19.8"
    "@esbuild/sunos-x64" "0.19.8"
    "@esbuild/win32-arm64" "0.19.8"
    "@esbuild/win32-ia32" "0.19.8"
    "@esbuild/win32-x64" "0.19.8"

escalade@^3.1.1:
  version "3.1.1"
  resolved "https://registry.npmjs.org/escalade/-/escalade-3.1.1.tgz"
  integrity sha512-k0er2gUkLf8O0zKJiAhmkTnJlTvINGv7ygDNPbeIsX/TJjGJZHuh9B2UxbsaEkmlEo9MfhrSzmhIlhRlI2GXnw==

escape-string-regexp@^1.0.5:
  version "1.0.5"
  resolved "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz"
  integrity sha512-vbRorB5FUQWvla16U8R/qgaFIya2qGzwDrNmCZuYKrbdSUMG6I1ZCGQRefkRVhuOkIGVne7BQ35DSfo1qvJqFg==

escape-string-regexp@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/escape-string-regexp/-/escape-string-regexp-2.0.0.tgz#a30304e99daa32e23b2fd20f51babd07cffca344"
  integrity sha512-UpzcLCXolUWcNu5HtVMHYdXJjArjsF9C0aNnquZYY4uW/Vu0miy5YoWvbV345HauVvcAUnpRuhMMcqTcGOY2+w==

escape-string-regexp@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-4.0.0.tgz"
  integrity sha512-TtpcNJ3XAzx3Gq8sWRzJaVajRs0uVxA2YAkdb1jm2YkPz4G6egUFAyA3n5vtEIZefPk5Wa4UXbKuS5fKkJWdgA==

escodegen@^2.1.0:
  version "2.1.0"
  resolved "https://registry.yarnpkg.com/escodegen/-/escodegen-2.1.0.tgz#ba93bbb7a43986d29d6041f99f5262da773e2e17"
  integrity sha512-2NlIDTwUWJN0mRPQOdtQBzbUHvdGY2P1VXSyU83Q3xKxM7WHX2Ql8dKq782Q9TgQUNOLEzEYu9bzLNj1q88I5w==
  dependencies:
    esprima "^4.0.1"
    estraverse "^5.2.0"
    esutils "^2.0.2"
  optionalDependencies:
    source-map "~0.6.1"

eslint-plugin-react-hooks@^4.6.0:
  version "4.6.0"
  resolved "https://registry.npmjs.org/eslint-plugin-react-hooks/-/eslint-plugin-react-hooks-4.6.0.tgz"
  integrity sha512-oFc7Itz9Qxh2x4gNHStv3BqJq54ExXmfC+a1NjAta66IAN87Wu0R/QArgIS9qKzX3dXKPI9H5crl9QchNMY9+g==

eslint-plugin-react-refresh@^0.4.3:
  version "0.4.4"
  resolved "https://registry.npmjs.org/eslint-plugin-react-refresh/-/eslint-plugin-react-refresh-0.4.4.tgz"
  integrity sha512-eD83+65e8YPVg6603Om2iCIwcQJf/y7++MWm4tACtEswFLYMwxwVWAfwN+e19f5Ad/FOyyNg9Dfi5lXhH3Y3rA==

eslint-scope@^7.2.2:
  version "7.2.2"
  resolved "https://registry.npmjs.org/eslint-scope/-/eslint-scope-7.2.2.tgz"
  integrity sha512-dOt21O7lTMhDM+X9mB4GX+DZrZtCUJPL/wlcTqxyrx5IvO0IYtILdtrQGQp+8n5S0gwSVmOf9NQrjMOgfQZlIg==
  dependencies:
    esrecurse "^4.3.0"
    estraverse "^5.2.0"

eslint-visitor-keys@^3.3.0, eslint-visitor-keys@^3.4.1, eslint-visitor-keys@^3.4.3:
  version "3.4.3"
  resolved "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-3.4.3.tgz"
  integrity sha512-wpc+LXeiyiisxPlEkUzU6svyS1frIO3Mgxj1fdy7Pm8Ygzguax2N3Fa/D/ag1WqbOprdI+uY6wMUl8/a2G+iag==

eslint@^8.45.0:
  version "8.53.0"
  resolved "https://registry.npmjs.org/eslint/-/eslint-8.53.0.tgz"
  integrity sha512-N4VuiPjXDUa4xVeV/GC/RV3hQW9Nw+Y463lkWaKKXKYMvmRiRDAtfpuPFLN+E1/6ZhyR8J2ig+eVREnYgUsiag==
  dependencies:
    "@eslint-community/eslint-utils" "^4.2.0"
    "@eslint-community/regexpp" "^4.6.1"
    "@eslint/eslintrc" "^2.1.3"
    "@eslint/js" "8.53.0"
    "@humanwhocodes/config-array" "^0.11.13"
    "@humanwhocodes/module-importer" "^1.0.1"
    "@nodelib/fs.walk" "^1.2.8"
    "@ungap/structured-clone" "^1.2.0"
    ajv "^6.12.4"
    chalk "^4.0.0"
    cross-spawn "^7.0.2"
    debug "^4.3.2"
    doctrine "^3.0.0"
    escape-string-regexp "^4.0.0"
    eslint-scope "^7.2.2"
    eslint-visitor-keys "^3.4.3"
    espree "^9.6.1"
    esquery "^1.4.2"
    esutils "^2.0.2"
    fast-deep-equal "^3.1.3"
    file-entry-cache "^6.0.1"
    find-up "^5.0.0"
    glob-parent "^6.0.2"
    globals "^13.19.0"
    graphemer "^1.4.0"
    ignore "^5.2.0"
    imurmurhash "^0.1.4"
    is-glob "^4.0.0"
    is-path-inside "^3.0.3"
    js-yaml "^4.1.0"
    json-stable-stringify-without-jsonify "^1.0.1"
    levn "^0.4.1"
    lodash.merge "^4.6.2"
    minimatch "^3.1.2"
    natural-compare "^1.4.0"
    optionator "^0.9.3"
    strip-ansi "^6.0.1"
    text-table "^0.2.0"

espree@^9.6.0, espree@^9.6.1:
  version "9.6.1"
  resolved "https://registry.npmjs.org/espree/-/espree-9.6.1.tgz"
  integrity sha512-oruZaFkjorTpF32kDSI5/75ViwGeZginGGy2NoOSg3Q9bnwlnmDm4HLnkl0RE3n+njDXR037aY1+x58Z/zFdwQ==
  dependencies:
    acorn "^8.9.0"
    acorn-jsx "^5.3.2"
    eslint-visitor-keys "^3.4.1"

esprima@^4.0.0, esprima@^4.0.1:
  version "4.0.1"
  resolved "https://registry.yarnpkg.com/esprima/-/esprima-4.0.1.tgz#13b04cdb3e6c5d19df91ab6987a8695619b0aa71"
  integrity sha512-eGuFFw7Upda+g4p+QHvnW0RyTX/SVeJBDM/gCtMARO0cLuT2HcEKnTPvhjV6aGeqrCB/sbNop0Kszm0jsaWU4A==

esquery@^1.4.2:
  version "1.5.0"
  resolved "https://registry.npmjs.org/esquery/-/esquery-1.5.0.tgz"
  integrity sha512-YQLXUplAwJgCydQ78IMJywZCceoqk1oH01OERdSAJc/7U2AylwjhSCLDEtqwg811idIS/9fIU5GjG73IgjKMVg==
  dependencies:
    estraverse "^5.1.0"

esrecurse@^4.3.0:
  version "4.3.0"
  resolved "https://registry.npmjs.org/esrecurse/-/esrecurse-4.3.0.tgz"
  integrity sha512-KmfKL3b6G+RXvP8N1vr3Tq1kL/oCFgn2NYXEtqP8/L3pKapUA4G8cFVaoF3SU323CD4XypR/ffioHmkti6/Tag==
  dependencies:
    estraverse "^5.2.0"

estraverse@^5.1.0, estraverse@^5.2.0:
  version "5.3.0"
  resolved "https://registry.npmjs.org/estraverse/-/estraverse-5.3.0.tgz"
  integrity sha512-MMdARuVEQziNTeJD8DgMqmhwR11BRQ/cBP+pLtYdSTnf3MIO8fFeiINEbX36ZdNlfU/7A9f3gUw49B3oQsvwBA==

estree-walker@^2.0.1:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/estree-walker/-/estree-walker-2.0.2.tgz#52f010178c2a4c117a7757cfe942adb7d2da4cac"
  integrity sha512-Rfkk/Mp/DL7JVje3u18FxFujQlTNR2q6QfMSMB7AvCBx91NGj/ba3kCfza0f6dVDbw7YlRf/nDrn7pQrCCyQ/w==

esutils@^2.0.2:
  version "2.0.3"
  resolved "https://registry.npmjs.org/esutils/-/esutils-2.0.3.tgz"
  integrity sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==

events@^3.3.0:
  version "3.3.0"
  resolved "https://registry.yarnpkg.com/events/-/events-3.3.0.tgz#31a95ad0a924e2d2c419a813aeb2c4e878ea7400"
  integrity sha512-mQw+2fkQbALzQ7V0MY0IqdnXNOeTtP4r0lN9z7AAawCXgqea7bDii20AYrIBrFd/Hx0M2Ocz6S111CaFkUcb0Q==

execa@^5.0.0:
  version "5.1.1"
  resolved "https://registry.yarnpkg.com/execa/-/execa-5.1.1.tgz#f80ad9cbf4298f7bd1d4c9555c21e93741c411dd"
  integrity sha512-8uSpZZocAZRBAPIEINJj3Lo9HyGitllczc27Eh5YYojjMFMn8yHMDMaUHE2Jqfq05D/wucwI4JGURyXt1vchyg==
  dependencies:
    cross-spawn "^7.0.3"
    get-stream "^6.0.0"
    human-signals "^2.1.0"
    is-stream "^2.0.0"
    merge-stream "^2.0.0"
    npm-run-path "^4.0.1"
    onetime "^5.1.2"
    signal-exit "^3.0.3"
    strip-final-newline "^2.0.0"

execa@^8.0.1:
  version "8.0.1"
  resolved "https://registry.yarnpkg.com/execa/-/execa-8.0.1.tgz#51f6a5943b580f963c3ca9c6321796db8cc39b8c"
  integrity sha512-VyhnebXciFV2DESc+p6B+y0LjSm0krU4OgJN44qFAhBY0TJ+1V61tYD2+wHusZ6F9n5K+vl8k0sTy7PEfV4qpg==
  dependencies:
    cross-spawn "^7.0.3"
    get-stream "^8.0.1"
    human-signals "^5.0.0"
    is-stream "^3.0.0"
    merge-stream "^2.0.0"
    npm-run-path "^5.1.0"
    onetime "^6.0.0"
    signal-exit "^4.1.0"
    strip-final-newline "^3.0.0"

exit@^0.1.2:
  version "0.1.2"
  resolved "https://registry.yarnpkg.com/exit/-/exit-0.1.2.tgz#0632638f8d877cc82107d30a0fff1a17cba1cd0c"
  integrity sha512-Zk/eNKV2zbjpKzrsQ+n1G6poVbErQxJ0LBOJXaKZ1EViLzH+hrLu9cdXI4zw9dBQJslwBEpbQ2P1oS7nDxs6jQ==

expect@^29.0.0, expect@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/expect/-/expect-29.7.0.tgz#578874590dcb3214514084c08115d8aee61e11bc"
  integrity sha512-2Zks0hf1VLFYI1kbh0I5jP3KHHyCHpkfyHBzsSXRFgl/Bg9mWYfMW8oD+PdMPlEwy5HNsR9JutYy6pMeOh61nw==
  dependencies:
    "@jest/expect-utils" "^29.7.0"
    jest-get-type "^29.6.3"
    jest-matcher-utils "^29.7.0"
    jest-message-util "^29.7.0"
    jest-util "^29.7.0"

extract-zip@2.0.1:
  version "2.0.1"
  resolved "https://registry.yarnpkg.com/extract-zip/-/extract-zip-2.0.1.tgz#663dca56fe46df890d5f131ef4a06d22bb8ba13a"
  integrity sha512-GDhU9ntwuKyGXdZBUgTIe+vXnWj0fppUEtMDL0+idd5Sta8TGpHssn/eusA9mrPr9qNDym6SxAYZjNvCn/9RBg==
  dependencies:
    debug "^4.1.1"
    get-stream "^5.1.0"
    yauzl "^2.10.0"
  optionalDependencies:
    "@types/yauzl" "^2.9.1"

fast-deep-equal@^3.1.1, fast-deep-equal@^3.1.3:
  version "3.1.3"
  resolved "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-3.1.3.tgz"
  integrity sha512-f3qQ9oQy9j2AhBe/H9VC91wLmKBCCU/gDOnKNAYG5hswO7BLKj09Hc5HYNz9cGI++xlpDCIgDaitVs03ATR84Q==

fast-fifo@^1.1.0, fast-fifo@^1.2.0:
  version "1.3.2"
  resolved "https://registry.yarnpkg.com/fast-fifo/-/fast-fifo-1.3.2.tgz#286e31de96eb96d38a97899815740ba2a4f3640c"
  integrity sha512-/d9sfos4yxzpwkDkuN7k2SqFKtYNmCTzgfEpz82x34IM9/zc8KGxQoXg1liNC/izpRM/MBdt44Nmx41ZWqk+FQ==

fast-glob@^3.2.11, fast-glob@^3.2.7, fast-glob@^3.2.9, fast-glob@^3.3.0:
  version "3.3.2"
  resolved "https://registry.npmjs.org/fast-glob/-/fast-glob-3.3.2.tgz"
  integrity sha512-oX2ruAFQwf/Orj8m737Y5adxDQO0LAB7/S5MnxCdTNDd4p6BsyIVsv9JQsATbTSq8KHRpLwIHbVlUNatxd+1Ow==
  dependencies:
    "@nodelib/fs.stat" "^2.0.2"
    "@nodelib/fs.walk" "^1.2.3"
    glob-parent "^5.1.2"
    merge2 "^1.3.0"
    micromatch "^4.0.4"

fast-json-stable-stringify@2.x, fast-json-stable-stringify@^2.0.0, fast-json-stable-stringify@^2.1.0:
  version "2.1.0"
  resolved "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.1.0.tgz"
  integrity sha512-lhd/wF+Lk98HZoTCtlVraHtfh5XYijIjalXck7saUtuanSDyLMxnHhSXEDJqHxD7msR8D0uCmqlkwjCV8xvwHw==

fast-levenshtein@^2.0.6:
  version "2.0.6"
  resolved "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz"
  integrity sha512-DCXu6Ifhqcks7TZKY3Hxp3y6qphY5SJZmrWMDrKcERSOXWQdMhU9Ig/PYrzyw/ul9jOIyh0N4M0tbC5hodg8dw==

fastq@^1.6.0:
  version "1.15.0"
  resolved "https://registry.npmjs.org/fastq/-/fastq-1.15.0.tgz"
  integrity sha512-wBrocU2LCXXa+lWBt8RoIRD89Fi8OdABODa/kEnyeyjS5aZO5/GNvI5sEINADqP/h8M29UHTHUb53sUu5Ihqdw==
  dependencies:
    reusify "^1.0.4"

fb-watchman@^2.0.0:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/fb-watchman/-/fb-watchman-2.0.2.tgz#e9524ee6b5c77e9e5001af0f85f3adbb8623255c"
  integrity sha512-p5161BqbuCaSnB8jIbzQHOlpgsPmK5rJVDfDKO91Axs5NC1uu3HRQm6wt9cd9/+GtQQIO53JdGXXoyDpTAsgYA==
  dependencies:
    bser "2.1.1"

fd-slicer@~1.1.0:
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/fd-slicer/-/fd-slicer-1.1.0.tgz#25c7c89cb1f9077f8891bbe61d8f390eae256f1e"
  integrity sha512-cE1qsB/VwyQozZ+q1dGxR8LBYNZeofhEdUNGSMbQD3Gw2lAzX9Zb3uIU6Ebc/Fmyjo9AWWfnn0AUCHqtevs/8g==
  dependencies:
    pend "~1.2.0"

file-entry-cache@^6.0.1:
  version "6.0.1"
  resolved "https://registry.npmjs.org/file-entry-cache/-/file-entry-cache-6.0.1.tgz"
  integrity sha512-7Gps/XWymbLk2QLYK4NzpMOrYjMhdIxXuIvy2QBsLE6ljuodKvdkWs/cpyJJ3CVIVpH0Oi1Hvg1ovbMzLdFBBg==
  dependencies:
    flat-cache "^3.0.4"

file-selector@^0.6.0:
  version "0.6.0"
  resolved "https://registry.npmjs.org/file-selector/-/file-selector-0.6.0.tgz"
  integrity sha512-QlZ5yJC0VxHxQQsQhXvBaC7VRJ2uaxTf+Tfpu4Z/OcVQJVpZO+DGU0rkoVW5ce2SccxugvpBJoMvUs59iILYdw==
  dependencies:
    tslib "^2.4.0"

filelist@^1.0.4:
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/filelist/-/filelist-1.0.4.tgz#f78978a1e944775ff9e62e744424f215e58352b5"
  integrity sha512-w1cEuf3S+DrLCQL7ET6kz+gmlJdbq9J7yXCSjK/OZCPA+qEN1WyF4ZAf0YYJa4/shHJra2t/d/r8SV4Ji+x+8Q==
  dependencies:
    minimatch "^5.0.1"

fill-range@^7.0.1:
  version "7.0.1"
  resolved "https://registry.npmjs.org/fill-range/-/fill-range-7.0.1.tgz"
  integrity sha512-qOo9F+dMUmC2Lcb4BbVvnKJxTPjCm+RRpe4gDuGrzkL7mEVl/djYSu2OdQ2Pa302N4oqkSg9ir6jaLWJ2USVpQ==
  dependencies:
    to-regex-range "^5.0.1"

find-up@^4.0.0, find-up@^4.1.0:
  version "4.1.0"
  resolved "https://registry.yarnpkg.com/find-up/-/find-up-4.1.0.tgz#97afe7d6cdc0bc5928584b7c8d7b16e8a9aa5d19"
  integrity sha512-PpOwAdQ/YlXQ2vj8a3h8IipDuYRi3wceVQQGYWxNINccq40Anw7BlsEXCMbt1Zt+OLA6Fq9suIpIWD0OsnISlw==
  dependencies:
    locate-path "^5.0.0"
    path-exists "^4.0.0"

find-up@^5.0.0:
  version "5.0.0"
  resolved "https://registry.npmjs.org/find-up/-/find-up-5.0.0.tgz"
  integrity sha512-78/PXT1wlLLDgTzDs7sjq9hzz0vXD+zn+7wypEe4fXQxCmdmqfGsEPQxmiCSQI3ajFV91bVSsvNtrJRiW6nGng==
  dependencies:
    locate-path "^6.0.0"
    path-exists "^4.0.0"

flat-cache@^3.0.4:
  version "3.2.0"
  resolved "https://registry.npmjs.org/flat-cache/-/flat-cache-3.2.0.tgz"
  integrity sha512-CYcENa+FtcUKLmhhqyctpclsq7QF38pKjZHsGNiSQF5r4FtoKDWabFDl3hzaEQMvT1LHEysw5twgLvpYYb4vbw==
  dependencies:
    flatted "^3.2.9"
    keyv "^4.5.3"
    rimraf "^3.0.2"

flatted@^3.2.9:
  version "3.2.9"
  resolved "https://registry.npmjs.org/flatted/-/flatted-3.2.9.tgz"
  integrity sha512-36yxDn5H7OFZQla0/jFJmbIKTdZAQHngCedGxiMmpNfEZM0sdEeT+WczLQrjK6D7o2aiyLYDnkw0R3JK0Qv1RQ==

fraction.js@^4.3.6:
  version "4.3.7"
  resolved "https://registry.npmjs.org/fraction.js/-/fraction.js-4.3.7.tgz"
  integrity sha512-ZsDfxO51wGAXREY55a7la9LScWpwv9RxIrYABrlvOFBlH/ShPnrtsXeuUIfXKKOVicNxQ+o8JTbJvjS4M89yew==

fs-extra@^10.0.1:
  version "10.1.0"
  resolved "https://registry.yarnpkg.com/fs-extra/-/fs-extra-10.1.0.tgz#02873cfbc4084dde127eaa5f9905eef2325d1abf"
  integrity sha512-oRXApq54ETRj4eMiFzGnHWGy+zo5raudjuxN0b8H7s/RU2oW0Wvsx9O0ACRN/kRq9E8Vu/ReskGB5o3ji+FzHQ==
  dependencies:
    graceful-fs "^4.2.0"
    jsonfile "^6.0.1"
    universalify "^2.0.0"

fs-extra@^11.1.0:
  version "11.1.1"
  resolved "https://registry.npmjs.org/fs-extra/-/fs-extra-11.1.1.tgz"
  integrity sha512-MGIE4HOvQCeUCzmlHs0vXpih4ysz4wg9qiSAu6cd42lVwPbTM1TjV7RusoyQqMmk/95gdQZX72u+YW+c3eEpFQ==
  dependencies:
    graceful-fs "^4.2.0"
    jsonfile "^6.0.1"
    universalify "^2.0.0"

fs-extra@^11.2.0:
  version "11.2.0"
  resolved "https://registry.yarnpkg.com/fs-extra/-/fs-extra-11.2.0.tgz#e70e17dfad64232287d01929399e0ea7c86b0e5b"
  integrity sha512-PmDi3uwK5nFuXh7XDTlVnS17xJS7vW36is2+w3xcv8SVxiB4NyATf4ctkVY5bkSjX0Y4nbvZCq1/EjtEyr9ktw==
  dependencies:
    graceful-fs "^4.2.0"
    jsonfile "^6.0.1"
    universalify "^2.0.0"

fs.realpath@^1.0.0:
  version "1.0.0"
  resolved "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz"
  integrity sha512-OO0pH2lK6a0hZnAdau5ItzHPI6pUlvI7jMVnxUQRtw4owF2wk8lOSabtGDCTP4Ggrg2MbGnWO9X8K1t4+fGMDw==

fsevents@^2.3.2, fsevents@~2.3.2, fsevents@~2.3.3:
  version "2.3.3"
  resolved "https://registry.npmjs.org/fsevents/-/fsevents-2.3.3.tgz"
  integrity sha512-5xoDfX+fL7faATnagmWPpbFtwh/R77WmMMqqHGS65C3vvB0YHrgF+B1YmZ3441tMj5n63k0212XNoJwzlhffQw==

function-bind@^1.1.2:
  version "1.1.2"
  resolved "https://registry.npmjs.org/function-bind/-/function-bind-1.1.2.tgz"
  integrity sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==

gensync@^1.0.0-beta.2:
  version "1.0.0-beta.2"
  resolved "https://registry.npmjs.org/gensync/-/gensync-1.0.0-beta.2.tgz"
  integrity sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==

get-caller-file@^2.0.5:
  version "2.0.5"
  resolved "https://registry.yarnpkg.com/get-caller-file/-/get-caller-file-2.0.5.tgz#4f94412a82db32f36e3b0b9741f8a97feb031f7e"
  integrity sha512-DyFP3BM/3YHTQOCUL/w0OZHR0lpKeGrxotcHWcqNEdnltqFwXVfhEBQ94eIo34AfQpo0rGki4cyIiftY06h2Fg==

get-func-name@^2.0.1, get-func-name@^2.0.2:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/get-func-name/-/get-func-name-2.0.2.tgz#0d7cf20cd13fda808669ffa88f4ffc7a3943fc41"
  integrity sha512-8vXOvuE167CtIc3OyItco7N/dpRtBbYOsPsXCz7X/PMnlGjYjSGuZJgM1Y7mmew7BKf9BqvLX2tnOVy1BBUsxQ==

get-nonce@^1.0.0:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/get-nonce/-/get-nonce-1.0.1.tgz#fdf3f0278073820d2ce9426c18f07481b1e0cdf3"
  integrity sha512-FJhYRoDaiatfEkUK8HKlicmu/3SGFD51q3itKDGoSTysQJBnfOcxU5GxnhE1E6soB76MbT0MBtnKJuXyAx+96Q==

get-package-type@^0.1.0:
  version "0.1.0"
  resolved "https://registry.yarnpkg.com/get-package-type/-/get-package-type-0.1.0.tgz#8de2d803cff44df3bc6c456e6668b36c3926e11a"
  integrity sha512-pjzuKtY64GYfWizNAJ0fr9VqttZkNiK2iS430LtIHzjBEr6bX8Am2zm4sW4Ro5wjWW5cAlRL1qAMTcXbjNAO2Q==

get-stream@^5.1.0:
  version "5.2.0"
  resolved "https://registry.yarnpkg.com/get-stream/-/get-stream-5.2.0.tgz#4966a1795ee5ace65e706c4b7beb71257d6e22d3"
  integrity sha512-nBF+F1rAZVCu/p7rjzgA+Yb4lfYXrpl7a6VmJrU8wF9I1CKvP/QwPNZHnOlwbTkY6dvtFIzFMSyQXbLoTQPRpA==
  dependencies:
    pump "^3.0.0"

get-stream@^6.0.0:
  version "6.0.1"
  resolved "https://registry.yarnpkg.com/get-stream/-/get-stream-6.0.1.tgz#a262d8eef67aced57c2852ad6167526a43cbf7b7"
  integrity sha512-ts6Wi+2j3jQjqi70w5AlN8DFnkSwC+MqmxEzdEALB2qXZYV3X/b1CTfgPLGJNMeAWxdPfU8FO1ms3NUfaHCPYg==

get-stream@^8.0.1:
  version "8.0.1"
  resolved "https://registry.yarnpkg.com/get-stream/-/get-stream-8.0.1.tgz#def9dfd71742cd7754a7761ed43749a27d02eca2"
  integrity sha512-VaUJspBffn/LMCJVoMvSAdmscJyS1auj5Zulnn5UoYcY531UWmdwhRWkcGKnGU93m5HSXP9LP2usOryrBtQowA==

get-uri@^6.0.1:
  version "6.0.3"
  resolved "https://registry.yarnpkg.com/get-uri/-/get-uri-6.0.3.tgz#0d26697bc13cf91092e519aa63aa60ee5b6f385a"
  integrity sha512-BzUrJBS9EcUb4cFol8r4W3v1cPsSyajLSthNkz5BxbpDcHN5tIrM10E2eNvfnvBn3DaT3DUgx0OpsBKkaOpanw==
  dependencies:
    basic-ftp "^5.0.2"
    data-uri-to-buffer "^6.0.2"
    debug "^4.3.4"
    fs-extra "^11.2.0"

glob-parent@^5.1.2, glob-parent@~5.1.2:
  version "5.1.2"
  resolved "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz"
  integrity sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==
  dependencies:
    is-glob "^4.0.1"

glob-parent@^6.0.2:
  version "6.0.2"
  resolved "https://registry.npmjs.org/glob-parent/-/glob-parent-6.0.2.tgz"
  integrity sha512-XxwI8EOhVQgWp6iDL+3b0r86f4d6AX6zSU55HfB4ydCEuXLXc5FcYeOu+nnGftS4TEju/11rt4KJPTMgbfmv4A==
  dependencies:
    is-glob "^4.0.3"

glob@7.1.6:
  version "7.1.6"
  resolved "https://registry.npmjs.org/glob/-/glob-7.1.6.tgz"
  integrity sha512-LwaxwyZ72Lk7vZINtNNrywX0ZuLyStrdDtabefZKAY5ZGJhVtgdznluResxNmPitE0SAO+O26sWTHeKSI2wMBA==
  dependencies:
    fs.realpath "^1.0.0"
    inflight "^1.0.4"
    inherits "2"
    minimatch "^3.0.4"
    once "^1.3.0"
    path-is-absolute "^1.0.0"

glob@^7.1.3, glob@^7.1.4:
  version "7.2.3"
  resolved "https://registry.npmjs.org/glob/-/glob-7.2.3.tgz"
  integrity sha512-nFR0zLpU2YCaRxwoCJvL6UvCH2JFyFVIvwTLsIf21AuHlMskA1hhTdk+LlYJtOlYt9v6dvszD2BGRqBL+iQK9Q==
  dependencies:
    fs.realpath "^1.0.0"
    inflight "^1.0.4"
    inherits "2"
    minimatch "^3.1.1"
    once "^1.3.0"
    path-is-absolute "^1.0.0"

globals@^11.1.0:
  version "11.12.0"
  resolved "https://registry.npmjs.org/globals/-/globals-11.12.0.tgz"
  integrity sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==

globals@^13.19.0:
  version "13.23.0"
  resolved "https://registry.npmjs.org/globals/-/globals-13.23.0.tgz"
  integrity sha512-XAmF0RjlrjY23MA51q3HltdlGxUpXPvg0GioKiD9X6HD28iMjo2dKC8Vqwm7lne4GNr78+RHTfliktR6ZH09wA==
  dependencies:
    type-fest "^0.20.2"

globby@^11.1.0:
  version "11.1.0"
  resolved "https://registry.npmjs.org/globby/-/globby-11.1.0.tgz"
  integrity sha512-jhIXaOzy1sb8IyocaruWSn1TjmnBVs8Ayhcy83rmxNJ8q2uWKCAj3CnJY+KpGSXCueAPc0i05kVvVKtP1t9S3g==
  dependencies:
    array-union "^2.1.0"
    dir-glob "^3.0.1"
    fast-glob "^3.2.9"
    ignore "^5.2.0"
    merge2 "^1.4.1"
    slash "^3.0.0"

goober@^2.1.10:
  version "2.1.13"
  resolved "https://registry.npmjs.org/goober/-/goober-2.1.13.tgz"
  integrity sha512-jFj3BQeleOoy7t93E9rZ2de+ScC4lQICLwiAQmKMg9F6roKGaLSHoCDYKkWlSafg138jejvq/mTdvmnwDQgqoQ==

graceful-fs@^4.1.6, graceful-fs@^4.2.0, graceful-fs@^4.2.9:
  version "4.2.11"
  resolved "https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.2.11.tgz"
  integrity sha512-RbJ5/jmFcNNCcDV5o9eTnBLJ/HszWV0P73bc+Ff4nS/rJj+YaS6IGyiOL0VoBYX+l1Wrl3k63h/KrH+nhJ0XvQ==

graphemer@^1.4.0:
  version "1.4.0"
  resolved "https://registry.npmjs.org/graphemer/-/graphemer-1.4.0.tgz"
  integrity sha512-EtKwoO6kxCL9WO5xipiHTZlSzBm7WLT627TqC/uVRd0HKmq8NXyebnNYxDoBi7wt8eTWrUrKXCOVaFq9x1kgag==

has-flag@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz"
  integrity sha512-sKJf1+ceQBr4SMkvQnBDNDtf4TXpVhVGateu0t918bl30FnbE2m4vNLX+VWe/dpjlb+HugGYzW7uQXH98HPEYw==

has-flag@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz"
  integrity sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==

hasown@^2.0.0:
  version "2.0.0"
  resolved "https://registry.npmjs.org/hasown/-/hasown-2.0.0.tgz"
  integrity sha512-vUptKVTpIJhcczKBbgnS+RtcuYMB8+oNzPK2/Hp3hanz8JmpATdmmgLgSaadVREkDm+e2giHwY3ZRkyjSIDDFA==
  dependencies:
    function-bind "^1.1.2"

he@1.2.0, he@^1.2.0:
  version "1.2.0"
  resolved "https://registry.yarnpkg.com/he/-/he-1.2.0.tgz#84ae65fa7eafb165fddb61566ae14baf05664f0f"
  integrity sha512-F/1DnUGPopORZi0ni+CvrCgHQ5FyEAHRLSApuYWMmrbSwoN2Mn/7k+Gl38gJnR7yyDZk6WLXwiGod1JOWNDKGw==

html-escaper@^2.0.0:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/html-escaper/-/html-escaper-2.0.2.tgz#dfd60027da36a36dfcbe236262c00a5822681453"
  integrity sha512-H2iMtd0I4Mt5eYiapRdIDjp+XzelXQ0tFE4JS7YFwFevXXMmOp9myNrUvCg0D6ws8iqkRPBfKHgbwig1SmlLfg==

html-minifier-terser@^6.1.0:
  version "6.1.0"
  resolved "https://registry.yarnpkg.com/html-minifier-terser/-/html-minifier-terser-6.1.0.tgz#bfc818934cc07918f6b3669f5774ecdfd48f32ab"
  integrity sha512-YXxSlJBZTP7RS3tWnQw74ooKa6L9b9i9QYXY21eUEvhZ3u9XLfv6OnFsQq6RxkhHygsaUMvYsZRV5rU/OVNZxw==
  dependencies:
    camel-case "^4.1.2"
    clean-css "^5.2.2"
    commander "^8.3.0"
    he "^1.2.0"
    param-case "^3.0.4"
    relateurl "^0.2.7"
    terser "^5.10.0"

html2canvas@^1.4.1:
  version "1.4.1"
  resolved "https://registry.npmjs.org/html2canvas/-/html2canvas-1.4.1.tgz#7cef1888311b5011d507794a066041b14669a543"
  integrity sha512-fPU6BHNpsyIhr8yyMpTLLxAbkaK8ArIBcmZIRiBLiDhjeqvXolaEmDGmELFuX9I4xDcaKKcJl+TKZLqruBbmWA==
  dependencies:
    css-line-break "^2.1.0"
    text-segmentation "^1.0.3"

http-proxy-agent@^7.0.0, http-proxy-agent@^7.0.1:
  version "7.0.2"
  resolved "https://registry.yarnpkg.com/http-proxy-agent/-/http-proxy-agent-7.0.2.tgz#9a8b1f246866c028509486585f62b8f2c18c270e"
  integrity sha512-T1gkAiYYDWYx3V5Bmyu7HcfcvL7mUrTWiM6yOfa3PIphViJ/gFPbvidQ+veqSOHci/PxBcDabeUNCzpOODJZig==
  dependencies:
    agent-base "^7.1.0"
    debug "^4.3.4"

https-proxy-agent@^7.0.2, https-proxy-agent@^7.0.3:
  version "7.0.4"
  resolved "https://registry.yarnpkg.com/https-proxy-agent/-/https-proxy-agent-7.0.4.tgz#8e97b841a029ad8ddc8731f26595bad868cb4168"
  integrity sha512-wlwpilI7YdjSkWaQ/7omYBMTliDcmCN8OLihO6I9B86g06lMyAoqgoDpV0XqoaPOKj+0DIdAvnsWfyAAhmimcg==
  dependencies:
    agent-base "^7.0.2"
    debug "4"

human-signals@^2.1.0:
  version "2.1.0"
  resolved "https://registry.yarnpkg.com/human-signals/-/human-signals-2.1.0.tgz#dc91fcba42e4d06e4abaed33b3e7a3c02f514ea0"
  integrity sha512-B4FFZ6q/T2jhhksgkbEW3HBvWIfDW85snkQgawt07S7J5QXTk6BkNV+0yAeZrM5QpMAdYlocGoljn0sJ/WQkFw==

human-signals@^5.0.0:
  version "5.0.0"
  resolved "https://registry.yarnpkg.com/human-signals/-/human-signals-5.0.0.tgz#42665a284f9ae0dade3ba41ebc37eb4b852f3a28"
  integrity sha512-AXcZb6vzzrFAUE61HnN4mpLqd/cSIwNQjtNWR0euPm6y0iqx3G4gOXaIDdtdDwZmhwe82LA6+zinmW4UBWVePQ==

ieee754@^1.1.13, ieee754@^1.2.1:
  version "1.2.1"
  resolved "https://registry.yarnpkg.com/ieee754/-/ieee754-1.2.1.tgz#8eb7a10a63fff25d15a57b001586d177d1b0d352"
  integrity sha512-dcyqhDvX1C46lXZcVqCpK+FtMRQVdIMN6/Df5js2zouUsqG7I6sFxitIC+7KYK29KdXOLHdu9zL4sFnoVQnqaA==

ignore@^5.2.0, ignore@^5.2.4:
  version "5.2.4"
  resolved "https://registry.npmjs.org/ignore/-/ignore-5.2.4.tgz"
  integrity sha512-MAb38BcSbH0eHNBxn7ql2NH/kX33OkB3lZ1BNdh7ENeRChHTYsTvWrMubiIAMNS2llXEEgZ1MUOBtXChP3kaFQ==

import-fresh@^3.2.1, import-fresh@^3.3.0:
  version "3.3.0"
  resolved "https://registry.npmjs.org/import-fresh/-/import-fresh-3.3.0.tgz"
  integrity sha512-veYYhQa+D1QBKznvhUHxb8faxlrwUnxseDAbAp457E0wLNio2bOSKnjYDhMj+YiAq61xrMGhQk9iXVk5FzgQMw==
  dependencies:
    parent-module "^1.0.0"
    resolve-from "^4.0.0"

import-local@^3.0.2:
  version "3.1.0"
  resolved "https://registry.yarnpkg.com/import-local/-/import-local-3.1.0.tgz#b4479df8a5fd44f6cdce24070675676063c95cb4"
  integrity sha512-ASB07uLtnDs1o6EHjKpX34BKYDSqnFerfTOJL2HvMqF70LnxpjkzDB8J44oT9pu4AMPkQwf8jl6szgvNd2tRIg==
  dependencies:
    pkg-dir "^4.2.0"
    resolve-cwd "^3.0.0"

imurmurhash@^0.1.4:
  version "0.1.4"
  resolved "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz"
  integrity sha512-JmXMZ6wuvDmLiHEml9ykzqO6lwFbof0GG4IkcGaENdCRDDmMVnny7s5HsIgHCbaq0w2MyPhDqkhTUgS2LU2PHA==

inflight@^1.0.4:
  version "1.0.6"
  resolved "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz"
  integrity sha512-k92I/b08q4wvFscXCLvqfsHCrjrF7yiXsQuIVvVE7N82W3+aqpzuUdBbfhWcy/FZR3/4IgflMgKLOsvPDrGCJA==
  dependencies:
    once "^1.3.0"
    wrappy "1"

inherits@2:
  version "2.0.4"
  resolved "https://registry.npmjs.org/inherits/-/inherits-2.0.4.tgz"
  integrity sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ==

int64-buffer@^1.0.1:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/int64-buffer/-/int64-buffer-1.0.1.tgz#c78d841b444cadf036cd04f8683696c740f15dca"
  integrity sha512-+3azY4pXrjAupJHU1V9uGERWlhoqNswJNji6aD/02xac7oxol508AsMC5lxKhEqyZeDFy3enq5OGWXF4u75hiw==

invariant@^2.2.4:
  version "2.2.4"
  resolved "https://registry.yarnpkg.com/invariant/-/invariant-2.2.4.tgz#610f3c92c9359ce1db616e538008d23ff35158e6"
  integrity sha512-phJfQVBuaJM5raOpJjSfkiD6BpbCE4Ns//LaXl6wGYtUBY83nWS6Rf9tXm2e8VaK60JEjYldbPif/A2B1C2gNA==
  dependencies:
    loose-envify "^1.0.0"

ip-address@^9.0.5:
  version "9.0.5"
  resolved "https://registry.yarnpkg.com/ip-address/-/ip-address-9.0.5.tgz#117a960819b08780c3bd1f14ef3c1cc1d3f3ea5a"
  integrity sha512-zHtQzGojZXTwZTHQqra+ETKd4Sn3vgi7uBmlPoXVWZqYvuKmtI0l/VZTjqGmJY9x88GGOaZ9+G9ES8hC4T4X8g==
  dependencies:
    jsbn "1.1.0"
    sprintf-js "^1.1.3"

is-arrayish@^0.2.1:
  version "0.2.1"
  resolved "https://registry.yarnpkg.com/is-arrayish/-/is-arrayish-0.2.1.tgz#77c99840527aa8ecb1a8ba697b80645a7a926a9d"
  integrity sha512-zz06S8t0ozoDXMG+ube26zeCTNXcKIPJZJi8hBrF4idCLms4CG9QtK7qBl1boi5ODzFpjswb5JPmHCbMpjaYzg==

is-binary-path@~2.1.0:
  version "2.1.0"
  resolved "https://registry.npmjs.org/is-binary-path/-/is-binary-path-2.1.0.tgz"
  integrity sha512-ZMERYes6pDydyuGidse7OsHxtbI7WVeUEozgR/g7rd0xUimYNlvZRE/K2MgZTjWy725IfelLeVcEM97mmtRGXw==
  dependencies:
    binary-extensions "^2.0.0"

is-core-module@^2.13.0:
  version "2.13.1"
  resolved "https://registry.npmjs.org/is-core-module/-/is-core-module-2.13.1.tgz"
  integrity sha512-hHrIjvZsftOsvKSn2TRYl63zvxsgE0K+0mYMoH6gD4omR5IWB2KynivBQczo3+wF1cCkjzvptnI9Q0sPU66ilw==
  dependencies:
    hasown "^2.0.0"

is-extglob@^2.1.1:
  version "2.1.1"
  resolved "https://registry.npmjs.org/is-extglob/-/is-extglob-2.1.1.tgz"
  integrity sha512-SbKbANkN603Vi4jEZv49LeVJMn4yGwsbzZworEoyEiutsN3nJYdbO36zfhGJ6QEDpOZIFkDtnq5JRxmvl3jsoQ==

is-fullwidth-code-point@^3.0.0:
  version "3.0.0"
  resolved "https://registry.yarnpkg.com/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz#f116f8064fe90b3f7844a38997c0b75051269f1d"
  integrity sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==

is-generator-fn@^2.0.0:
  version "2.1.0"
  resolved "https://registry.yarnpkg.com/is-generator-fn/-/is-generator-fn-2.1.0.tgz#7d140adc389aaf3011a8f2a2a4cfa6faadffb118"
  integrity sha512-cTIB4yPYL/Grw0EaSzASzg6bBy9gqCofvWN8okThAYIxKJZC+udlRAmGbM0XLeniEJSs8uEgHPGuHSe1XsOLSQ==

is-glob@^4.0.0, is-glob@^4.0.1, is-glob@^4.0.3, is-glob@~4.0.1:
  version "4.0.3"
  resolved "https://registry.npmjs.org/is-glob/-/is-glob-4.0.3.tgz"
  integrity sha512-xelSayHH36ZgE7ZWhli7pW34hNbNl8Ojv5KVmkJD4hBdD3th8Tfk9vYasLM+mXWOZhFkgZfxhLSnrwRr4elSSg==
  dependencies:
    is-extglob "^2.1.1"

is-number@^7.0.0:
  version "7.0.0"
  resolved "https://registry.npmjs.org/is-number/-/is-number-7.0.0.tgz"
  integrity sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==

is-path-inside@^3.0.3:
  version "3.0.3"
  resolved "https://registry.npmjs.org/is-path-inside/-/is-path-inside-3.0.3.tgz"
  integrity sha512-Fd4gABb+ycGAmKou8eMftCupSir5lRxqf4aD/vd0cD2qc4HL07OjCeuHMr8Ro4CoMaeCKDB0/ECBOVWjTwUvPQ==

is-stream@^2.0.0:
  version "2.0.1"
  resolved "https://registry.yarnpkg.com/is-stream/-/is-stream-2.0.1.tgz#fac1e3d53b97ad5a9d0ae9cef2389f5810a5c077"
  integrity sha512-hFoiJiTl63nn+kstHGBtewWSKnQLpyb155KHheA1l39uvtO9nWIop1p3udqPcUd/xbF1VLMO4n7OI6p7RbngDg==

is-stream@^3.0.0:
  version "3.0.0"
  resolved "https://registry.yarnpkg.com/is-stream/-/is-stream-3.0.0.tgz#e6bfd7aa6bef69f4f472ce9bb681e3e57b4319ac"
  integrity sha512-LnQR4bZ9IADDRSkvpqMGvt/tEJWclzklNgSw48V5EAaAeDd6qGvN8ei6k5p0tvxSR171VmGyHuTiAOfxAbr8kA==

isexe@^2.0.0:
  version "2.0.0"
  resolved "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz"
  integrity sha512-RHxMLp9lnKHGHRng9QFhRCMbYAcVpn69smSGcq3f36xjgVVWThj4qqLbTLlq7Ssj8B+fIQ1EuCEGI2lKsyQeIw==

istanbul-lib-coverage@^3.0.0, istanbul-lib-coverage@^3.2.0:
  version "3.2.2"
  resolved "https://registry.yarnpkg.com/istanbul-lib-coverage/-/istanbul-lib-coverage-3.2.2.tgz#2d166c4b0644d43a39f04bf6c2edd1e585f31756"
  integrity sha512-O8dpsF+r0WV/8MNRKfnmrtCWhuKjxrq2w+jpzBL5UZKTi2LeVWnWOmWRxFlesJONmc+wLAGvKQZEOanko0LFTg==

istanbul-lib-instrument@^5.0.4:
  version "5.2.1"
  resolved "https://registry.yarnpkg.com/istanbul-lib-instrument/-/istanbul-lib-instrument-5.2.1.tgz#d10c8885c2125574e1c231cacadf955675e1ce3d"
  integrity sha512-pzqtp31nLv/XFOzXGuvhCb8qhjmTVo5vjVk19XE4CRlSWz0KoeJ3bw9XsA7nOp9YBf4qHjwBxkDzKcME/J29Yg==
  dependencies:
    "@babel/core" "^7.12.3"
    "@babel/parser" "^7.14.7"
    "@istanbuljs/schema" "^0.1.2"
    istanbul-lib-coverage "^3.2.0"
    semver "^6.3.0"

istanbul-lib-instrument@^6.0.0:
  version "6.0.2"
  resolved "https://registry.yarnpkg.com/istanbul-lib-instrument/-/istanbul-lib-instrument-6.0.2.tgz#91655936cf7380e4e473383081e38478b69993b1"
  integrity sha512-1WUsZ9R1lA0HtBSohTkm39WTPlNKSJ5iFk7UwqXkBLoHQT+hfqPsfsTDVuZdKGaBwn7din9bS7SsnoAr943hvw==
  dependencies:
    "@babel/core" "^7.23.9"
    "@babel/parser" "^7.23.9"
    "@istanbuljs/schema" "^0.1.3"
    istanbul-lib-coverage "^3.2.0"
    semver "^7.5.4"

istanbul-lib-report@^3.0.0:
  version "3.0.1"
  resolved "https://registry.yarnpkg.com/istanbul-lib-report/-/istanbul-lib-report-3.0.1.tgz#908305bac9a5bd175ac6a74489eafd0fc2445a7d"
  integrity sha512-GCfE1mtsHGOELCU8e/Z7YWzpmybrx/+dSTfLrvY8qRmaY6zXTKWn6WQIjaAFw069icm6GVMNkgu0NzI4iPZUNw==
  dependencies:
    istanbul-lib-coverage "^3.0.0"
    make-dir "^4.0.0"
    supports-color "^7.1.0"

istanbul-lib-source-maps@^4.0.0:
  version "4.0.1"
  resolved "https://registry.yarnpkg.com/istanbul-lib-source-maps/-/istanbul-lib-source-maps-4.0.1.tgz#895f3a709fcfba34c6de5a42939022f3e4358551"
  integrity sha512-n3s8EwkdFIJCG3BPKBYvskgXGoy88ARzvegkitk60NxRdwltLOTaH7CUiMRXvwYorl0Q712iEjcWB+fK/MrWVw==
  dependencies:
    debug "^4.1.1"
    istanbul-lib-coverage "^3.0.0"
    source-map "^0.6.1"

istanbul-reports@^3.1.3:
  version "3.1.7"
  resolved "https://registry.yarnpkg.com/istanbul-reports/-/istanbul-reports-3.1.7.tgz#daed12b9e1dca518e15c056e1e537e741280fa0b"
  integrity sha512-BewmUXImeuRk2YY0PVbxgKAysvhRPUQE0h5QRM++nVWyubKGV0l8qQ5op8+B2DOmwSe63Jivj0BjkPQVf8fP5g==
  dependencies:
    html-escaper "^2.0.0"
    istanbul-lib-report "^3.0.0"

jake@^10.8.5:
  version "10.8.7"
  resolved "https://registry.yarnpkg.com/jake/-/jake-10.8.7.tgz#63a32821177940c33f356e0ba44ff9d34e1c7d8f"
  integrity sha512-ZDi3aP+fG/LchyBzUM804VjddnwfSfsdeYkwt8NcbKRvo4rFkjhs456iLFn3k2ZUWvNe4i48WACDbza8fhq2+w==
  dependencies:
    async "^3.2.3"
    chalk "^4.0.2"
    filelist "^1.0.4"
    minimatch "^3.1.2"

jest-changed-files@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-changed-files/-/jest-changed-files-29.7.0.tgz#1c06d07e77c78e1585d020424dedc10d6e17ac3a"
  integrity sha512-fEArFiwf1BpQ+4bXSprcDc3/x4HSzL4al2tozwVpDFpsxALjLYdyiIK4e5Vz66GQJIbXJ82+35PtysofptNX2w==
  dependencies:
    execa "^5.0.0"
    jest-util "^29.7.0"
    p-limit "^3.1.0"

jest-circus@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-circus/-/jest-circus-29.7.0.tgz#b6817a45fcc835d8b16d5962d0c026473ee3668a"
  integrity sha512-3E1nCMgipcTkCocFwM90XXQab9bS+GMsjdpmPrlelaxwD93Ad8iVEjX/vvHPdLPnFf+L40u+5+iutRdA1N9myw==
  dependencies:
    "@jest/environment" "^29.7.0"
    "@jest/expect" "^29.7.0"
    "@jest/test-result" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    chalk "^4.0.0"
    co "^4.6.0"
    dedent "^1.0.0"
    is-generator-fn "^2.0.0"
    jest-each "^29.7.0"
    jest-matcher-utils "^29.7.0"
    jest-message-util "^29.7.0"
    jest-runtime "^29.7.0"
    jest-snapshot "^29.7.0"
    jest-util "^29.7.0"
    p-limit "^3.1.0"
    pretty-format "^29.7.0"
    pure-rand "^6.0.0"
    slash "^3.0.0"
    stack-utils "^2.0.3"

jest-cli@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-cli/-/jest-cli-29.7.0.tgz#5592c940798e0cae677eec169264f2d839a37995"
  integrity sha512-OVVobw2IubN/GSYsxETi+gOe7Ka59EFMR/twOU3Jb2GnKKeMGJB5SGUUrEz3SFVmJASUdZUzy83sLNNQ2gZslg==
  dependencies:
    "@jest/core" "^29.7.0"
    "@jest/test-result" "^29.7.0"
    "@jest/types" "^29.6.3"
    chalk "^4.0.0"
    create-jest "^29.7.0"
    exit "^0.1.2"
    import-local "^3.0.2"
    jest-config "^29.7.0"
    jest-util "^29.7.0"
    jest-validate "^29.7.0"
    yargs "^17.3.1"

jest-config@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-config/-/jest-config-29.7.0.tgz#bcbda8806dbcc01b1e316a46bb74085a84b0245f"
  integrity sha512-uXbpfeQ7R6TZBqI3/TxCU4q4ttk3u0PJeC+E0zbfSoSjq6bJ7buBPxzQPL0ifrkY4DNu4JUdk0ImlBUYi840eQ==
  dependencies:
    "@babel/core" "^7.11.6"
    "@jest/test-sequencer" "^29.7.0"
    "@jest/types" "^29.6.3"
    babel-jest "^29.7.0"
    chalk "^4.0.0"
    ci-info "^3.2.0"
    deepmerge "^4.2.2"
    glob "^7.1.3"
    graceful-fs "^4.2.9"
    jest-circus "^29.7.0"
    jest-environment-node "^29.7.0"
    jest-get-type "^29.6.3"
    jest-regex-util "^29.6.3"
    jest-resolve "^29.7.0"
    jest-runner "^29.7.0"
    jest-util "^29.7.0"
    jest-validate "^29.7.0"
    micromatch "^4.0.4"
    parse-json "^5.2.0"
    pretty-format "^29.7.0"
    slash "^3.0.0"
    strip-json-comments "^3.1.1"

jest-diff@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-diff/-/jest-diff-29.7.0.tgz#017934a66ebb7ecf6f205e84699be10afd70458a"
  integrity sha512-LMIgiIrhigmPrs03JHpxUh2yISK3vLFPkAodPeo0+BuF7wA2FoQbkEg1u8gBYBThncu7e1oEDUfIXVuTqLRUjw==
  dependencies:
    chalk "^4.0.0"
    diff-sequences "^29.6.3"
    jest-get-type "^29.6.3"
    pretty-format "^29.7.0"

jest-docblock@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-docblock/-/jest-docblock-29.7.0.tgz#8fddb6adc3cdc955c93e2a87f61cfd350d5d119a"
  integrity sha512-q617Auw3A612guyaFgsbFeYpNP5t2aoUNLwBUbc/0kD1R4t9ixDbyFTHd1nok4epoVFpr7PmeWHrhvuV3XaJ4g==
  dependencies:
    detect-newline "^3.0.0"

jest-each@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-each/-/jest-each-29.7.0.tgz#162a9b3f2328bdd991beaabffbb74745e56577d1"
  integrity sha512-gns+Er14+ZrEoC5fhOfYCY1LOHHr0TI+rQUHZS8Ttw2l7gl+80eHc/gFf2Ktkw0+SIACDTeWvpFcv3B04VembQ==
  dependencies:
    "@jest/types" "^29.6.3"
    chalk "^4.0.0"
    jest-get-type "^29.6.3"
    jest-util "^29.7.0"
    pretty-format "^29.7.0"

jest-environment-node@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-environment-node/-/jest-environment-node-29.7.0.tgz#0b93e111dda8ec120bc8300e6d1fb9576e164376"
  integrity sha512-DOSwCRqXirTOyheM+4d5YZOrWcdu0LNZ87ewUoywbcb2XR4wKgqiG8vNeYwhjFMbEkfju7wx2GYH0P2gevGvFw==
  dependencies:
    "@jest/environment" "^29.7.0"
    "@jest/fake-timers" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    jest-mock "^29.7.0"
    jest-util "^29.7.0"

jest-get-type@^29.6.3:
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/jest-get-type/-/jest-get-type-29.6.3.tgz#36f499fdcea197c1045a127319c0481723908fd1"
  integrity sha512-zrteXnqYxfQh7l5FHyL38jL39di8H8rHoecLH3JNxH3BwOrBsNeabdap5e0I23lD4HHI8W5VFBZqG4Eaq5LNcw==

jest-haste-map@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-haste-map/-/jest-haste-map-29.7.0.tgz#3c2396524482f5a0506376e6c858c3bbcc17b104"
  integrity sha512-fP8u2pyfqx0K1rGn1R9pyE0/KTn+G7PxktWidOBTqFPLYX0b9ksaMFkhK5vrS3DVun09pckLdlx90QthlW7AmA==
  dependencies:
    "@jest/types" "^29.6.3"
    "@types/graceful-fs" "^4.1.3"
    "@types/node" "*"
    anymatch "^3.0.3"
    fb-watchman "^2.0.0"
    graceful-fs "^4.2.9"
    jest-regex-util "^29.6.3"
    jest-util "^29.7.0"
    jest-worker "^29.7.0"
    micromatch "^4.0.4"
    walker "^1.0.8"
  optionalDependencies:
    fsevents "^2.3.2"

jest-leak-detector@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-leak-detector/-/jest-leak-detector-29.7.0.tgz#5b7ec0dadfdfec0ca383dc9aa016d36b5ea4c728"
  integrity sha512-kYA8IJcSYtST2BY9I+SMC32nDpBT3J2NvWJx8+JCuCdl/CR1I4EKUJROiP8XtCcxqgTTBGJNdbB1A8XRKbTetw==
  dependencies:
    jest-get-type "^29.6.3"
    pretty-format "^29.7.0"

jest-matcher-utils@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-matcher-utils/-/jest-matcher-utils-29.7.0.tgz#ae8fec79ff249fd592ce80e3ee474e83a6c44f12"
  integrity sha512-sBkD+Xi9DtcChsI3L3u0+N0opgPYnCRPtGcQYrgXmR+hmt/fYfWAL0xRXYU8eWOdfuLgBe0YCW3AFtnRLagq/g==
  dependencies:
    chalk "^4.0.0"
    jest-diff "^29.7.0"
    jest-get-type "^29.6.3"
    pretty-format "^29.7.0"

jest-message-util@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-message-util/-/jest-message-util-29.7.0.tgz#8bc392e204e95dfe7564abbe72a404e28e51f7f3"
  integrity sha512-GBEV4GRADeP+qtB2+6u61stea8mGcOT4mCtrYISZwfu9/ISHFJ/5zOMXYbpBE9RsS5+Gb63DW4FgmnKJ79Kf6w==
  dependencies:
    "@babel/code-frame" "^7.12.13"
    "@jest/types" "^29.6.3"
    "@types/stack-utils" "^2.0.0"
    chalk "^4.0.0"
    graceful-fs "^4.2.9"
    micromatch "^4.0.4"
    pretty-format "^29.7.0"
    slash "^3.0.0"
    stack-utils "^2.0.3"

jest-mock@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-mock/-/jest-mock-29.7.0.tgz#4e836cf60e99c6fcfabe9f99d017f3fdd50a6347"
  integrity sha512-ITOMZn+UkYS4ZFh83xYAOzWStloNzJFO2s8DWrE4lhtGD+AorgnbkiKERe4wQVBydIGPx059g6riW5Btp6Llnw==
  dependencies:
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    jest-util "^29.7.0"

jest-pnp-resolver@^1.2.2:
  version "1.2.3"
  resolved "https://registry.yarnpkg.com/jest-pnp-resolver/-/jest-pnp-resolver-1.2.3.tgz#930b1546164d4ad5937d5540e711d4d38d4cad2e"
  integrity sha512-+3NpwQEnRoIBtx4fyhblQDPgJI0H1IEIkX7ShLUjPGA7TtUTvI1oiKi3SR4oBR0hQhQR80l4WAe5RrXBwWMA8w==

jest-regex-util@^29.6.3:
  version "29.6.3"
  resolved "https://registry.yarnpkg.com/jest-regex-util/-/jest-regex-util-29.6.3.tgz#4a556d9c776af68e1c5f48194f4d0327d24e8a52"
  integrity sha512-KJJBsRCyyLNWCNBOvZyRDnAIfUiRJ8v+hOBQYGn8gDyF3UegwiP4gwRR3/SDa42g1YbVycTidUF3rKjyLFDWbg==

jest-resolve-dependencies@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-resolve-dependencies/-/jest-resolve-dependencies-29.7.0.tgz#1b04f2c095f37fc776ff40803dc92921b1e88428"
  integrity sha512-un0zD/6qxJ+S0et7WxeI3H5XSe9lTBBR7bOHCHXkKR6luG5mwDDlIzVQ0V5cZCuoTgEdcdwzTghYkTWfubi+nA==
  dependencies:
    jest-regex-util "^29.6.3"
    jest-snapshot "^29.7.0"

jest-resolve@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-resolve/-/jest-resolve-29.7.0.tgz#64d6a8992dd26f635ab0c01e5eef4399c6bcbc30"
  integrity sha512-IOVhZSrg+UvVAshDSDtHyFCCBUl/Q3AAJv8iZ6ZjnZ74xzvwuzLXid9IIIPgTnY62SJjfuupMKZsZQRsCvxEgA==
  dependencies:
    chalk "^4.0.0"
    graceful-fs "^4.2.9"
    jest-haste-map "^29.7.0"
    jest-pnp-resolver "^1.2.2"
    jest-util "^29.7.0"
    jest-validate "^29.7.0"
    resolve "^1.20.0"
    resolve.exports "^2.0.0"
    slash "^3.0.0"

jest-runner@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-runner/-/jest-runner-29.7.0.tgz#809af072d408a53dcfd2e849a4c976d3132f718e"
  integrity sha512-fsc4N6cPCAahybGBfTRcq5wFR6fpLznMg47sY5aDpsoejOcVYFb07AHuSnR0liMcPTgBsA3ZJL6kFOjPdoNipQ==
  dependencies:
    "@jest/console" "^29.7.0"
    "@jest/environment" "^29.7.0"
    "@jest/test-result" "^29.7.0"
    "@jest/transform" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    chalk "^4.0.0"
    emittery "^0.13.1"
    graceful-fs "^4.2.9"
    jest-docblock "^29.7.0"
    jest-environment-node "^29.7.0"
    jest-haste-map "^29.7.0"
    jest-leak-detector "^29.7.0"
    jest-message-util "^29.7.0"
    jest-resolve "^29.7.0"
    jest-runtime "^29.7.0"
    jest-util "^29.7.0"
    jest-watcher "^29.7.0"
    jest-worker "^29.7.0"
    p-limit "^3.1.0"
    source-map-support "0.5.13"

jest-runtime@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-runtime/-/jest-runtime-29.7.0.tgz#efecb3141cf7d3767a3a0cc8f7c9990587d3d817"
  integrity sha512-gUnLjgwdGqW7B4LvOIkbKs9WGbn+QLqRQQ9juC6HndeDiezIwhDP+mhMwHWCEcfQ5RUXa6OPnFF8BJh5xegwwQ==
  dependencies:
    "@jest/environment" "^29.7.0"
    "@jest/fake-timers" "^29.7.0"
    "@jest/globals" "^29.7.0"
    "@jest/source-map" "^29.6.3"
    "@jest/test-result" "^29.7.0"
    "@jest/transform" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    chalk "^4.0.0"
    cjs-module-lexer "^1.0.0"
    collect-v8-coverage "^1.0.0"
    glob "^7.1.3"
    graceful-fs "^4.2.9"
    jest-haste-map "^29.7.0"
    jest-message-util "^29.7.0"
    jest-mock "^29.7.0"
    jest-regex-util "^29.6.3"
    jest-resolve "^29.7.0"
    jest-snapshot "^29.7.0"
    jest-util "^29.7.0"
    slash "^3.0.0"
    strip-bom "^4.0.0"

jest-snapshot@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-snapshot/-/jest-snapshot-29.7.0.tgz#c2c574c3f51865da1bb329036778a69bf88a6be5"
  integrity sha512-Rm0BMWtxBcioHr1/OX5YCP8Uov4riHvKPknOGs804Zg9JGZgmIBkbtlxJC/7Z4msKYVbIJtfU+tKb8xlYNfdkw==
  dependencies:
    "@babel/core" "^7.11.6"
    "@babel/generator" "^7.7.2"
    "@babel/plugin-syntax-jsx" "^7.7.2"
    "@babel/plugin-syntax-typescript" "^7.7.2"
    "@babel/types" "^7.3.3"
    "@jest/expect-utils" "^29.7.0"
    "@jest/transform" "^29.7.0"
    "@jest/types" "^29.6.3"
    babel-preset-current-node-syntax "^1.0.0"
    chalk "^4.0.0"
    expect "^29.7.0"
    graceful-fs "^4.2.9"
    jest-diff "^29.7.0"
    jest-get-type "^29.6.3"
    jest-matcher-utils "^29.7.0"
    jest-message-util "^29.7.0"
    jest-util "^29.7.0"
    natural-compare "^1.4.0"
    pretty-format "^29.7.0"
    semver "^7.5.3"

jest-util@^29.0.0, jest-util@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-util/-/jest-util-29.7.0.tgz#23c2b62bfb22be82b44de98055802ff3710fc0bc"
  integrity sha512-z6EbKajIpqGKU56y5KBUgy1dt1ihhQJgWzUlZHArA/+X2ad7Cb5iF+AK1EWVL/Bo7Rz9uurpqw6SiBCefUbCGA==
  dependencies:
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    chalk "^4.0.0"
    ci-info "^3.2.0"
    graceful-fs "^4.2.9"
    picomatch "^2.2.3"

jest-validate@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-validate/-/jest-validate-29.7.0.tgz#7bf705511c64da591d46b15fce41400d52147d9c"
  integrity sha512-ZB7wHqaRGVw/9hST/OuFUReG7M8vKeq0/J2egIGLdvjHCmYqGARhzXmtgi+gVeZ5uXFF219aOc3Ls2yLg27tkw==
  dependencies:
    "@jest/types" "^29.6.3"
    camelcase "^6.2.0"
    chalk "^4.0.0"
    jest-get-type "^29.6.3"
    leven "^3.1.0"
    pretty-format "^29.7.0"

jest-watcher@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-watcher/-/jest-watcher-29.7.0.tgz#7810d30d619c3a62093223ce6bb359ca1b28a2f2"
  integrity sha512-49Fg7WXkU3Vl2h6LbLtMQ/HyB6rXSIX7SqvBLQmssRBGN9I0PNvPmAmCWSOY6SOvrjhI/F7/bGAv9RtnsPA03g==
  dependencies:
    "@jest/test-result" "^29.7.0"
    "@jest/types" "^29.6.3"
    "@types/node" "*"
    ansi-escapes "^4.2.1"
    chalk "^4.0.0"
    emittery "^0.13.1"
    jest-util "^29.7.0"
    string-length "^4.0.1"

jest-worker@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest-worker/-/jest-worker-29.7.0.tgz#acad073acbbaeb7262bd5389e1bcf43e10058d4a"
  integrity sha512-eIz2msL/EzL9UFTFFx7jBTkeZfku0yUAyZZZmJ93H2TYEiroIx2PQjEXcwYtYl8zXCxb+PAmA2hLIt/6ZEkPHw==
  dependencies:
    "@types/node" "*"
    jest-util "^29.7.0"
    merge-stream "^2.0.0"
    supports-color "^8.0.0"

jest@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/jest/-/jest-29.7.0.tgz#994676fc24177f088f1c5e3737f5697204ff2613"
  integrity sha512-NIy3oAFp9shda19hy4HK0HRTWKtPJmGdnvywu01nOqNC2vZg+Z+fvJDxpMQA88eb2I9EcafcdjYgsDthnYTvGw==
  dependencies:
    "@jest/core" "^29.7.0"
    "@jest/types" "^29.6.3"
    import-local "^3.0.2"
    jest-cli "^29.7.0"

jiti@^1.19.1:
  version "1.21.0"
  resolved "https://registry.npmjs.org/jiti/-/jiti-1.21.0.tgz"
  integrity sha512-gFqAIbuKyyso/3G2qhiO2OM6shY6EPP/R0+mkDbyspxKazh8BXDC5FiFsUjlczgdNz/vfra0da2y+aHrusLG/Q==

"js-tokens@^3.0.0 || ^4.0.0", js-tokens@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz"
  integrity sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ==

js-yaml@^3.13.1:
  version "3.14.1"
  resolved "https://registry.yarnpkg.com/js-yaml/-/js-yaml-3.14.1.tgz#dae812fdb3825fa306609a8717383c50c36a0537"
  integrity sha512-okMH7OXXJ7YrN9Ok3/SXrnu4iX9yOk+25nqX4imS2npuvTYDmo/QEZoqwZkYaIDk3jVvBOTOIEgEhaLOynBS9g==
  dependencies:
    argparse "^1.0.7"
    esprima "^4.0.0"

js-yaml@^4.1.0:
  version "4.1.0"
  resolved "https://registry.npmjs.org/js-yaml/-/js-yaml-4.1.0.tgz"
  integrity sha512-wpxZs9NoxZaJESJGIZTyDEaYpl0FKSA+FB9aJiyemKhMwkxQg63h4T1KJgUGHpTqPDNRcmmYLugrRjJlBtWvRA==
  dependencies:
    argparse "^2.0.1"

jsbn@1.1.0:
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/jsbn/-/jsbn-1.1.0.tgz#b01307cb29b618a1ed26ec79e911f803c4da0040"
  integrity sha512-4bYVV3aAMtDTTu4+xsDYa6sy9GyJ69/amsu9sYF2zqjiEoZA5xJi3BrfX3uY+/IekIu7MwdObdbDWpoZdBv3/A==

jsesc@^2.5.1:
  version "2.5.2"
  resolved "https://registry.npmjs.org/jsesc/-/jsesc-2.5.2.tgz"
  integrity sha512-OYu7XEzjkCQ3C5Ps3QIZsQfNpqoJyZZA99wd9aWd05NCtC5pWOkShK2mkL6HXQR6/Cy2lbNdPlZBpuQHXE63gA==

json-buffer@3.0.1:
  version "3.0.1"
  resolved "https://registry.npmjs.org/json-buffer/-/json-buffer-3.0.1.tgz"
  integrity sha512-4bV5BfR2mqfQTJm+V5tPPdf+ZpuhiIvTuAB5g8kcrXOZpTT/QwwVRWBywX1ozr6lEuPdbHxwaJlm9G6mI2sfSQ==

json-parse-even-better-errors@^2.3.0:
  version "2.3.1"
  resolved "https://registry.yarnpkg.com/json-parse-even-better-errors/-/json-parse-even-better-errors-2.3.1.tgz#7c47805a94319928e05777405dc12e1f7a4ee02d"
  integrity sha512-xyFwyhro/JEof6Ghe2iz2NcXoj2sloNsWr/XsERDK/oiPCfaNhl5ONfp+jQdAZRQQ0IJWNzH9zIZF7li91kh2w==

json-schema-traverse@^0.4.1:
  version "0.4.1"
  resolved "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz"
  integrity sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg==

json-stable-stringify-without-jsonify@^1.0.1:
  version "1.0.1"
  resolved "https://registry.npmjs.org/json-stable-stringify-without-jsonify/-/json-stable-stringify-without-jsonify-1.0.1.tgz"
  integrity sha512-Bdboy+l7tA3OGW6FjyFHWkP5LuByj1Tk33Ljyq0axyzdk9//JSi2u3fP1QSmd1KNwq6VOKYGlAu87CisVir6Pw==

json5@^2.2.3:
  version "2.2.3"
  resolved "https://registry.npmjs.org/json5/-/json5-2.2.3.tgz"
  integrity sha512-XmOWe7eyHYH14cLdVPoyg+GOH3rYX++KpzrylJwSW98t3Nk+U8XOl8FWKOgwtzdb8lXGf6zYwDUzeHMWfxasyg==

jsonc-parser@^3.2.0:
  version "3.2.0"
  resolved "https://registry.yarnpkg.com/jsonc-parser/-/jsonc-parser-3.2.0.tgz#31ff3f4c2b9793f89c67212627c51c6394f88e76"
  integrity sha512-gfFQZrcTc8CnKXp6Y4/CBT3fTc0OVuDofpre4aEeEpSBPV5X5v4+Vmx+8snU7RLPrNHPKSgLxGo9YuQzz20o+w==

jsonfile@^6.0.1:
  version "6.1.0"
  resolved "https://registry.npmjs.org/jsonfile/-/jsonfile-6.1.0.tgz"
  integrity sha512-5dgndWOriYSm5cnYaJNhalLNDKOqFwyDB/rr1E9ZsGciGvKPs8R2xYGCacuf3z6K1YKDz182fd+fY3cn3pMqXQ==
  dependencies:
    universalify "^2.0.0"
  optionalDependencies:
    graceful-fs "^4.1.6"

keyv@^4.5.3:
  version "4.5.4"
  resolved "https://registry.npmjs.org/keyv/-/keyv-4.5.4.tgz"
  integrity sha512-oxVHkHR/EJf2CNXnWxRLW6mg7JyCCUcG0DtEGmL2ctUo1PNTin1PUil+r/+4r5MpVgC/fn1kjsx7mjSujKqIpw==
  dependencies:
    json-buffer "3.0.1"

kleur@^3.0.3:
  version "3.0.3"
  resolved "https://registry.yarnpkg.com/kleur/-/kleur-3.0.3.tgz#a79c9ecc86ee1ce3fa6206d1216c501f147fc07e"
  integrity sha512-eTIzlVOSUR+JxdDFepEYcBMtZ9Qqdef+rnzWdRZuMbOywu5tO2w2N7rqjoANZ5k9vywhL6Br1VRjUIgTQx4E8w==

leven@^3.1.0:
  version "3.1.0"
  resolved "https://registry.yarnpkg.com/leven/-/leven-3.1.0.tgz#77891de834064cccba82ae7842bb6b14a13ed7f2"
  integrity sha512-qsda+H8jTaUaN/x5vzW2rzc+8Rw4TAQ/4KjB46IwK5VH+IlVeeeje/EoZRpiXvIqjFgK84QffqPztGI3VBLG1A==

levn@^0.4.1:
  version "0.4.1"
  resolved "https://registry.npmjs.org/levn/-/levn-0.4.1.tgz"
  integrity sha512-+bT2uH4E5LGE7h/n3evcS/sQlJXCpIp6ym8OWJ5eV6+67Dsql/LaaT7qJBAt2rzfoa/5QBGBhxDix1dMt2kQKQ==
  dependencies:
    prelude-ls "^1.2.1"
    type-check "~0.4.0"

lilconfig@^2.0.5, lilconfig@^2.1.0:
  version "2.1.0"
  resolved "https://registry.npmjs.org/lilconfig/-/lilconfig-2.1.0.tgz"
  integrity sha512-utWOt/GHzuUxnLKxB6dk81RoOeoNeHgbrXiuGk4yyF5qlRz+iIVWu56E2fqGHFrXz0QNUhLB/8nKqvRH66JKGQ==

lines-and-columns@^1.1.6:
  version "1.2.4"
  resolved "https://registry.npmjs.org/lines-and-columns/-/lines-and-columns-1.2.4.tgz"
  integrity sha512-7ylylesZQ/PV29jhEDl3Ufjo6ZX7gCqJr5F7PKrqc93v7fzSymt1BpwEU8nAUXs8qzzvqhbjhK5QZg6Mt/HkBg==

local-pkg@^0.5.0:
  version "0.5.0"
  resolved "https://registry.yarnpkg.com/local-pkg/-/local-pkg-0.5.0.tgz#093d25a346bae59a99f80e75f6e9d36d7e8c925c"
  integrity sha512-ok6z3qlYyCDS4ZEU27HaU6x/xZa9Whf8jD4ptH5UZTQYZVYeb9bnZ3ojVhiJNLiXK1Hfc0GNbLXcmZ5plLDDBg==
  dependencies:
    mlly "^1.4.2"
    pkg-types "^1.0.3"

locate-path@^5.0.0:
  version "5.0.0"
  resolved "https://registry.yarnpkg.com/locate-path/-/locate-path-5.0.0.tgz#1afba396afd676a6d42504d0a67a3a7eb9f62aa0"
  integrity sha512-t7hw9pI+WvuwNJXwk5zVHpyhIqzg2qTlklJOf0mVxGSbe3Fp2VieZcduNYjaLDoy6p9uGpQEGWG87WpMKlNq8g==
  dependencies:
    p-locate "^4.1.0"

locate-path@^6.0.0:
  version "6.0.0"
  resolved "https://registry.npmjs.org/locate-path/-/locate-path-6.0.0.tgz"
  integrity sha512-iPZK6eYjbxRu3uB4/WZ3EsEIMJFMqAoopl3R+zuq0UjcAm/MO6KCweDgPfP3elTztoKP3KtnVHxTn2NHBSDVUw==
  dependencies:
    p-locate "^5.0.0"

lodash.debounce@^4.0.8:
  version "4.0.8"
  resolved "https://registry.npmjs.org/lodash.debounce/-/lodash.debounce-4.0.8.tgz"
  integrity sha512-FT1yDzDYEoYWhnSGnpE/4Kj1fLZkDFyqRb7fNt6FdYOSxlUWAtp42Eh6Wb0rGIv/m9Bgo7x4GhQbm5Ys4SG5ow==

lodash.memoize@4.x:
  version "4.1.2"
  resolved "https://registry.yarnpkg.com/lodash.memoize/-/lodash.memoize-4.1.2.tgz#bcc6c49a42a2840ed997f323eada5ecd182e0bfe"
  integrity sha512-t7j+NzmgnQzTAYXcsHYLgimltOV1MXHtlOWf6GjL9Kj8GK5FInw5JotxvbOs+IvV1/Dzo04/fCGfLVs7aXb4Ag==

lodash.merge@^4.6.2:
  version "4.6.2"
  resolved "https://registry.npmjs.org/lodash.merge/-/lodash.merge-4.6.2.tgz"
  integrity sha512-0KpjqXRVvrYyCsX1swR/XTK0va6VQkQM6MNo7PqW77ByjAhoARA8EfrP1N4+KlKj8YS0ZUCtRT/YUuhyYDujIQ==

lodash.pick@^4.4.0:
  version "4.4.0"
  resolved "https://registry.npmjs.org/lodash.pick/-/lodash.pick-4.4.0.tgz"
  integrity sha512-hXt6Ul/5yWjfklSGvLQl8vM//l3FtyHZeuelpzK6mm99pNvN9yTDruNZPEJZD1oWrqo+izBmB7oUfWgcCX7s4Q==

loose-envify@^1.0.0, loose-envify@^1.1.0, loose-envify@^1.4.0:
  version "1.4.0"
  resolved "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz"
  integrity sha512-lyuxPGr/Wfhrlem2CL/UcnUc1zcqKAImBDzukY7Y5F/yQiNdko6+fRLevlw1HgMySw7f611UIY408EtxRSoK3Q==
  dependencies:
    js-tokens "^3.0.0 || ^4.0.0"

loupe@^2.3.6, loupe@^2.3.7:
  version "2.3.7"
  resolved "https://registry.yarnpkg.com/loupe/-/loupe-2.3.7.tgz#6e69b7d4db7d3ab436328013d37d1c8c3540c697"
  integrity sha512-zSMINGVYkdpYSOBmLi0D1Uo7JU9nVdQKrHxC8eYlV+9YKK9WePqAlL7lSlorG/U2Fw1w0hTBmaa/jrQ3UbPHtA==
  dependencies:
    get-func-name "^2.0.1"

lower-case@^2.0.2:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/lower-case/-/lower-case-2.0.2.tgz#6fa237c63dbdc4a82ca0fd882e4722dc5e634e28"
  integrity sha512-7fm3l3NAF9WfN6W3JOmf5drwpVqX78JtoGJ3A6W0a6ZnldM41w2fV5D490psKFTpMds8TJse/eHLFFsNHHjHgg==
  dependencies:
    tslib "^2.0.3"

lru-cache@^5.1.1:
  version "5.1.1"
  resolved "https://registry.npmjs.org/lru-cache/-/lru-cache-5.1.1.tgz"
  integrity sha512-KpNARQA3Iwv+jTA0utUVVbrh+Jlrr1Fv0e56GGzAFOXN7dk/FviaDW8LHmK52DlcH4WP2n6gI8vN1aesBFgo9w==
  dependencies:
    yallist "^3.0.2"

lru-cache@^6.0.0:
  version "6.0.0"
  resolved "https://registry.npmjs.org/lru-cache/-/lru-cache-6.0.0.tgz"
  integrity sha512-Jo6dJ04CmSjuznwJSS3pUeWmd/H0ffTlkXXgwZi+eq1UCmqQwCh+eLsYOYCwY991i2Fah4h1BEMCx4qThGbsiA==
  dependencies:
    yallist "^4.0.0"

lru-cache@^7.14.1:
  version "7.18.3"
  resolved "https://registry.yarnpkg.com/lru-cache/-/lru-cache-7.18.3.tgz#f793896e0fd0e954a59dfdd82f0773808df6aa89"
  integrity sha512-jumlc0BIUrS3qJGgIkWZsyfAM7NCWiBcCDhnd+3NNM5KbBmLTgHVfWBcg6W+rLUsIpzpERPsvwUP7CckAQSOoA==

magic-string@^0.30.5:
  version "0.30.5"
  resolved "https://registry.yarnpkg.com/magic-string/-/magic-string-0.30.5.tgz#1994d980bd1c8835dc6e78db7cbd4ae4f24746f9"
  integrity sha512-7xlpfBaQaP/T6Vh8MO/EqXSW5En6INHEvEXQiuff7Gku0PWjU3uf6w/j9o7O+SpB5fOAkrI5HeoNgwjEO0pFsA==
  dependencies:
    "@jridgewell/sourcemap-codec" "^1.4.15"

make-dir@^4.0.0:
  version "4.0.0"
  resolved "https://registry.yarnpkg.com/make-dir/-/make-dir-4.0.0.tgz#c3c2307a771277cd9638305f915c29ae741b614e"
  integrity sha512-hXdUTZYIVOt1Ex//jAQi+wTZZpUpwBj/0QsOzqegb3rGMMeJiSEu5xLHnYfBrRV4RH2+OCSOO95Is/7x1WJ4bw==
  dependencies:
    semver "^7.5.3"

make-error@1.x:
  version "1.3.6"
  resolved "https://registry.yarnpkg.com/make-error/-/make-error-1.3.6.tgz#2eb2e37ea9b67c4891f684a1394799af484cf7a2"
  integrity sha512-s8UhlNe7vPKomQhC1qFelMokr/Sc3AgNbso3n74mVPA5LTZwkB9NlXf4XPamLxJE8h0gh73rM94xvwRT2CVInw==

makeerror@1.0.12:
  version "1.0.12"
  resolved "https://registry.yarnpkg.com/makeerror/-/makeerror-1.0.12.tgz#3e5dd2079a82e812e983cc6610c4a2cb0eaa801a"
  integrity sha512-JmqCvUhmt43madlpFzG4BQzG2Z3m6tvQDNKdClZnO3VbIudJYmxsT0FNJMeiB2+JTSlTQTSbU8QdesVmwJcmLg==
  dependencies:
    tmpl "1.0.5"

merge-stream@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/merge-stream/-/merge-stream-2.0.0.tgz#52823629a14dd00c9770fb6ad47dc6310f2c1f60"
  integrity sha512-abv/qOcuPfk3URPfDzmZU1LKmuw8kT+0nIHvKrKgFrwifol/doWcdA4ZqsWQ8ENrFKkd67Mfpo/LovbIUsbt3w==

merge2@^1.3.0, merge2@^1.4.1:
  version "1.4.1"
  resolved "https://registry.npmjs.org/merge2/-/merge2-1.4.1.tgz"
  integrity sha512-8q7VEgMJW4J8tcfVPy8g09NcQwZdbwFEqhe/WZkoIzjn/3TGDwtOCYtXGxA3O8tPzpczCCDgv+P2P5y00ZJOOg==

micromatch@^4.0.4, micromatch@^4.0.5:
  version "4.0.5"
  resolved "https://registry.npmjs.org/micromatch/-/micromatch-4.0.5.tgz"
  integrity sha512-DMy+ERcEW2q8Z2Po+WNXuw3c5YaUSFjAO5GsJqfEl7UjvtIuFKO6ZrKvcItdy98dwFI2N1tg3zNIdKaQT+aNdA==
  dependencies:
    braces "^3.0.2"
    picomatch "^2.3.1"

mimic-fn@^2.1.0:
  version "2.1.0"
  resolved "https://registry.yarnpkg.com/mimic-fn/-/mimic-fn-2.1.0.tgz#7ed2c2ccccaf84d3ffcb7a69b57711fc2083401b"
  integrity sha512-OqbOk5oEQeAZ8WXWydlu9HJjz9WVdEIvamMCcXmuqUYjTknH/sqsWvhQ3vgwKFRR1HpjvNBKQ37nbJgYzGqGcg==

mimic-fn@^4.0.0:
  version "4.0.0"
  resolved "https://registry.yarnpkg.com/mimic-fn/-/mimic-fn-4.0.0.tgz#60a90550d5cb0b239cca65d893b1a53b29871ecc"
  integrity sha512-vqiC06CuhBTUdZH+RYl8sFrL096vA45Ok5ISO6sE/Mr1jRbGH4Csnhi8f3wKVl7x8mO4Au7Ir9D3Oyv1VYMFJw==

minimatch@^3.0.4, minimatch@^3.0.5, minimatch@^3.1.1, minimatch@^3.1.2:
  version "3.1.2"
  resolved "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz"
  integrity sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==
  dependencies:
    brace-expansion "^1.1.7"

minimatch@^5.0.1:
  version "5.1.6"
  resolved "https://registry.yarnpkg.com/minimatch/-/minimatch-5.1.6.tgz#1cfcb8cf5522ea69952cd2af95ae09477f122a96"
  integrity sha512-lKwV/1brpG6mBUFHtb7NUmtABCb2WZZmm2wNiOA5hAb8VdCS4B3dtMWyvcoViccwAW/COERjXLt0zP1zXUN26g==
  dependencies:
    brace-expansion "^2.0.1"

mitt@3.0.1:
  version "3.0.1"
  resolved "https://registry.yarnpkg.com/mitt/-/mitt-3.0.1.tgz#ea36cf0cc30403601ae074c8f77b7092cdab36d1"
  integrity sha512-vKivATfr97l2/QBCYAkXYDbrIWPM2IIKEl7YPhjCvKlG3kE2gm+uBo6nEXK3M5/Ffh/FLpKExzOQ3JJoJGFKBw==

mlly@^1.2.0, mlly@^1.4.2:
  version "1.4.2"
  resolved "https://registry.yarnpkg.com/mlly/-/mlly-1.4.2.tgz#7cf406aa319ff6563d25da6b36610a93f2a8007e"
  integrity sha512-i/Ykufi2t1EZ6NaPLdfnZk2AX8cs0d+mTzVKuPfqPKPatxLApaBoxJQ9x1/uckXtrS/U5oisPMDkNs0yQTaBRg==
  dependencies:
    acorn "^8.10.0"
    pathe "^1.1.1"
    pkg-types "^1.0.3"
    ufo "^1.3.0"

ms@2.1.2:
  version "2.1.2"
  resolved "https://registry.npmjs.org/ms/-/ms-2.1.2.tgz"
  integrity sha512-sGkPx+VjMtmA6MX27oA4FBFELFCZZ4S4XqeGOXCv68tT+jb3vk/RyaKWP0PTKyWtmLSM0b+adUTEvbs1PEaH2w==

mz@^2.7.0:
  version "2.7.0"
  resolved "https://registry.npmjs.org/mz/-/mz-2.7.0.tgz"
  integrity sha512-z81GNO7nnYMEhrGh9LeymoE4+Yr0Wn5McHIZMK5cfQCl+NDX08sCZgUc9/6MHni9IWuFLm1Z3HTCXu2z9fN62Q==
  dependencies:
    any-promise "^1.0.0"
    object-assign "^4.0.1"
    thenify-all "^1.0.0"

nanoid@^3.3.6, nanoid@^3.3.7:
  version "3.3.7"
  resolved "https://registry.npmjs.org/nanoid/-/nanoid-3.3.7.tgz"
  integrity sha512-eSRppjcPIatRIMC1U6UngP8XFcz8MQWGQdt1MTBQ7NaAmvXDfvNxbvWV3x2y6CdEUciCSsDHDQZbhYaB8QEo2g==

nanoid@^5.0.7:
  version "5.0.7"
  resolved "https://registry.yarnpkg.com/nanoid/-/nanoid-5.0.7.tgz#6452e8c5a816861fd9d2b898399f7e5fd6944cc6"
  integrity sha512-oLxFY2gd2IqnjcYyOXD8XGCftpGtZP2AbHbOkthDkvRywH5ayNtPVy9YlOPcHckXzbLTCHpkb7FB+yuxKV13pQ==

natural-compare@^1.4.0:
  version "1.4.0"
  resolved "https://registry.npmjs.org/natural-compare/-/natural-compare-1.4.0.tgz"
  integrity sha512-OWND8ei3VtNC9h7V60qff3SVobHr996CTwgxubgyQYEpg290h9J0buyECNNJexkFm5sOajh5G116RYA1c8ZMSw==

netmask@^2.0.2:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/netmask/-/netmask-2.0.2.tgz#8b01a07644065d536383835823bc52004ebac5e7"
  integrity sha512-dBpDMdxv9Irdq66304OLfEmQ9tbNRFnFTuZiLo+bD+r332bBmMJ8GBLXklIXXgxd3+v9+KUnZaUR5PJMa75Gsg==

no-case@^3.0.4:
  version "3.0.4"
  resolved "https://registry.yarnpkg.com/no-case/-/no-case-3.0.4.tgz#d361fd5c9800f558551a8369fc0dcd4662b6124d"
  integrity sha512-fgAN3jGAh+RoxUGZHTSOLJIqUc2wmoBwGR4tbpNAKmmovFoWq0OdRkb0VkldReO2a2iBT/OEulG9XSUc10r3zg==
  dependencies:
    lower-case "^2.0.2"
    tslib "^2.0.3"

node-html-parser@^5.3.3:
  version "5.4.2"
  resolved "https://registry.yarnpkg.com/node-html-parser/-/node-html-parser-5.4.2.tgz#93e004038c17af80226c942336990a0eaed8136a"
  integrity sha512-RaBPP3+51hPne/OolXxcz89iYvQvKOydaqoePpOgXcrOKZhjVIzmpKZz+Hd/RBO2/zN2q6CNJhQzucVz+u3Jyw==
  dependencies:
    css-select "^4.2.1"
    he "1.2.0"

node-int64@^0.4.0:
  version "0.4.0"
  resolved "https://registry.yarnpkg.com/node-int64/-/node-int64-0.4.0.tgz#87a9065cdb355d3182d8f94ce11188b825c68a3b"
  integrity sha512-O5lz91xSOeoXP6DulyHfllpq+Eg00MWitZIbtPfoSEvqIHdl5gfcY6hYzDWnj0qD5tz52PI08u9qUvSVeUBeHw==

node-releases@^2.0.13:
  version "2.0.13"
  resolved "https://registry.npmjs.org/node-releases/-/node-releases-2.0.13.tgz"
  integrity sha512-uYr7J37ae/ORWdZeQ1xxMJe3NtdmqMC/JZK+geofDrkLUApKRHPd18/TxtBOJ4A0/+uUIliorNrfYV6s1b02eQ==

node-releases@^2.0.14:
  version "2.0.14"
  resolved "https://registry.yarnpkg.com/node-releases/-/node-releases-2.0.14.tgz#2ffb053bceb8b2be8495ece1ab6ce600c4461b0b"
  integrity sha512-y10wOWt8yZpqXmOgRo77WaHEmhYQYGNA6y421PKsKYWEK8aW+cqAphborZDhqfyKrbZEN92CN1X2KbafY2s7Yw==

normalize-path@^3.0.0, normalize-path@~3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/normalize-path/-/normalize-path-3.0.0.tgz"
  integrity sha512-6eZs5Ls3WtCisHWp9S2GUy8dqkpGi4BVSz3GaqiE6ezub0512ESztXUwUB6C6IKbQkY2Pnb/mD4WYojCRwcwLA==

normalize-range@^0.1.2:
  version "0.1.2"
  resolved "https://registry.npmjs.org/normalize-range/-/normalize-range-0.1.2.tgz"
  integrity sha512-bdok/XvKII3nUpklnV6P2hxtMNrCboOjAcyBuQnWEhO665FwrSNRxU+AqpsyvO6LgGYPspN+lu5CLtw4jPRKNA==

npm-run-path@^4.0.1:
  version "4.0.1"
  resolved "https://registry.npmjs.org/npm-run-path/-/npm-run-path-4.0.1.tgz"
  integrity sha512-S48WzZW777zhNIrn7gxOlISNAqi9ZC/uQFnRdbeIHhZhCA6UqpkOT8T1G7BvfdgP4Er8gF4sUbaS0i7QvIfCWw==
  dependencies:
    path-key "^3.0.0"

npm-run-path@^5.1.0:
  version "5.1.0"
  resolved "https://registry.yarnpkg.com/npm-run-path/-/npm-run-path-5.1.0.tgz#bc62f7f3f6952d9894bd08944ba011a6ee7b7e00"
  integrity sha512-sJOdmRGrY2sjNTRMbSvluQqg+8X7ZK61yvzBEIDhz4f8z1TZFYABsqjjCBd/0PUNE9M6QDgHJXQkGUEm7Q+l9Q==
  dependencies:
    path-key "^4.0.0"

nth-check@^2.0.1:
  version "2.1.1"
  resolved "https://registry.yarnpkg.com/nth-check/-/nth-check-2.1.1.tgz#c9eab428effce36cd6b92c924bdb000ef1f1ed1d"
  integrity sha512-lqjrjmaOoAnWfMmBPL+XNnynZh2+swxiX3WUE0s4yEHI6m+AwrK2UZOimIRl3X/4QctVqS8AiZjFqyOGrMXb/w==
  dependencies:
    boolbase "^1.0.0"

object-assign@^4.0.1, object-assign@^4.1.1:
  version "4.1.1"
  resolved "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz"
  integrity sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==

object-hash@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/object-hash/-/object-hash-3.0.0.tgz"
  integrity sha512-RSn9F68PjH9HqtltsSnqYC1XXoWe9Bju5+213R98cNGttag9q9yAOTzdbsqvIa7aNm5WffBZFpWYr2aWrklWAw==

once@^1.3.0, once@^1.3.1, once@^1.4.0:
  version "1.4.0"
  resolved "https://registry.npmjs.org/once/-/once-1.4.0.tgz"
  integrity sha512-lNaJgI+2Q5URQBkccEKHTQOPaXdUxnZZElQTZY0MFUAuaEqe1E+Nyvgdz/aIyNi6Z9MzO5dv1H8n58/GELp3+w==
  dependencies:
    wrappy "1"

onetime@^5.1.2:
  version "5.1.2"
  resolved "https://registry.yarnpkg.com/onetime/-/onetime-5.1.2.tgz#d0e96ebb56b07476df1dd9c4806e5237985ca45e"
  integrity sha512-kbpaSSGJTWdAY5KPVeMOKXSrPtr8C8C7wodJbcsd51jRnmD+GZu8Y0VoU6Dm5Z4vWr0Ig/1NKuWRKf7j5aaYSg==
  dependencies:
    mimic-fn "^2.1.0"

onetime@^6.0.0:
  version "6.0.0"
  resolved "https://registry.yarnpkg.com/onetime/-/onetime-6.0.0.tgz#7c24c18ed1fd2e9bca4bd26806a33613c77d34b4"
  integrity sha512-1FlR+gjXK7X+AsAHso35MnyN5KqGwJRi/31ft6x0M194ht7S+rWAvd7PHss9xSKMzE0asv1pyIHaJYq+BbacAQ==
  dependencies:
    mimic-fn "^4.0.0"

optionator@^0.9.3:
  version "0.9.3"
  resolved "https://registry.npmjs.org/optionator/-/optionator-0.9.3.tgz"
  integrity sha512-JjCoypp+jKn1ttEFExxhetCKeJt9zhAgAve5FXHixTvFDW/5aEktX9bufBKLRRMdU7bNtpLfcGu94B3cdEJgjg==
  dependencies:
    "@aashutoshrathi/word-wrap" "^1.2.3"
    deep-is "^0.1.3"
    fast-levenshtein "^2.0.6"
    levn "^0.4.1"
    prelude-ls "^1.2.1"
    type-check "^0.4.0"

p-limit@^2.2.0:
  version "2.3.0"
  resolved "https://registry.yarnpkg.com/p-limit/-/p-limit-2.3.0.tgz#3dd33c647a214fdfffd835933eb086da0dc21db1"
  integrity sha512-//88mFWSJx8lxCzwdAABTJL2MyWB12+eIY7MDL2SqLmAkeKU9qxRvWuSyTjm3FUmpBEMuFfckAIqEaVGUDxb6w==
  dependencies:
    p-try "^2.0.0"

p-limit@^3.0.2, p-limit@^3.1.0:
  version "3.1.0"
  resolved "https://registry.npmjs.org/p-limit/-/p-limit-3.1.0.tgz"
  integrity sha512-TYOanM3wGwNGsZN2cVTYPArw454xnXj5qmWF1bEoAc4+cU/ol7GVh7odevjp1FNHduHc3KZMcFduxU5Xc6uJRQ==
  dependencies:
    yocto-queue "^0.1.0"

p-limit@^5.0.0:
  version "5.0.0"
  resolved "https://registry.yarnpkg.com/p-limit/-/p-limit-5.0.0.tgz#6946d5b7140b649b7a33a027d89b4c625b3a5985"
  integrity sha512-/Eaoq+QyLSiXQ4lyYV23f14mZRQcXnxfHrN0vCai+ak9G0pp9iEQukIIZq5NccEvwRB8PUnZT0KsOoDCINS1qQ==
  dependencies:
    yocto-queue "^1.0.0"

p-locate@^4.1.0:
  version "4.1.0"
  resolved "https://registry.yarnpkg.com/p-locate/-/p-locate-4.1.0.tgz#a3428bb7088b3a60292f66919278b7c297ad4f07"
  integrity sha512-R79ZZ/0wAxKGu3oYMlz8jy/kbhsNrS7SKZ7PxEHBgJ5+F2mtFW2fK2cOtBh1cHYkQsbzFV7I+EoRKe6Yt0oK7A==
  dependencies:
    p-limit "^2.2.0"

p-locate@^5.0.0:
  version "5.0.0"
  resolved "https://registry.npmjs.org/p-locate/-/p-locate-5.0.0.tgz"
  integrity sha512-LaNjtRWUBY++zB5nE/NwcaoMylSPk+S+ZHNB1TzdbMJMny6dynpAGt7X/tl/QYq3TIeE6nxHppbo2LGymrG5Pw==
  dependencies:
    p-limit "^3.0.2"

p-try@^2.0.0:
  version "2.2.0"
  resolved "https://registry.yarnpkg.com/p-try/-/p-try-2.2.0.tgz#cb2868540e313d61de58fafbe35ce9004d5540e6"
  integrity sha512-R4nPAVTAU0B9D35/Gk3uJf/7XYbQcyohSKdvAxIRSNghFl4e71hVoGnBNQz9cWaXxO2I10KTC+3jMdvvoKw6dQ==

pac-proxy-agent@^7.0.1:
  version "7.0.1"
  resolved "https://registry.yarnpkg.com/pac-proxy-agent/-/pac-proxy-agent-7.0.1.tgz#6b9ddc002ec3ff0ba5fdf4a8a21d363bcc612d75"
  integrity sha512-ASV8yU4LLKBAjqIPMbrgtaKIvxQri/yh2OpI+S6hVa9JRkUI3Y3NPFbfngDtY7oFtSMD3w31Xns89mDa3Feo5A==
  dependencies:
    "@tootallnate/quickjs-emscripten" "^0.23.0"
    agent-base "^7.0.2"
    debug "^4.3.4"
    get-uri "^6.0.1"
    http-proxy-agent "^7.0.0"
    https-proxy-agent "^7.0.2"
    pac-resolver "^7.0.0"
    socks-proxy-agent "^8.0.2"

pac-resolver@^7.0.0:
  version "7.0.1"
  resolved "https://registry.yarnpkg.com/pac-resolver/-/pac-resolver-7.0.1.tgz#54675558ea368b64d210fd9c92a640b5f3b8abb6"
  integrity sha512-5NPgf87AT2STgwa2ntRMr45jTKrYBGkVU36yT0ig/n/GMAa3oPqhZfIQ2kMEimReg0+t9kZViDVZ83qfVUlckg==
  dependencies:
    degenerator "^5.0.0"
    netmask "^2.0.2"

param-case@^3.0.4:
  version "3.0.4"
  resolved "https://registry.yarnpkg.com/param-case/-/param-case-3.0.4.tgz#7d17fe4aa12bde34d4a77d91acfb6219caad01c5"
  integrity sha512-RXlj7zCYokReqWpOPH9oYivUzLYZ5vAPIfEmCTNViosC78F8F0H9y7T7gG2M39ymgutxF5gcFEsyZQSph9Bp3A==
  dependencies:
    dot-case "^3.0.4"
    tslib "^2.0.3"

parent-module@^1.0.0:
  version "1.0.1"
  resolved "https://registry.npmjs.org/parent-module/-/parent-module-1.0.1.tgz"
  integrity sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==
  dependencies:
    callsites "^3.0.0"

parse-json@^5.2.0:
  version "5.2.0"
  resolved "https://registry.yarnpkg.com/parse-json/-/parse-json-5.2.0.tgz#c76fc66dee54231c962b22bcc8a72cf2f99753cd"
  integrity sha512-ayCKvm/phCGxOkYRSCM82iDwct8/EonSEgCSxWxD7ve6jHggsFl4fZVQBPRNgQoKiuV/odhFrGzQXZwbifC8Rg==
  dependencies:
    "@babel/code-frame" "^7.0.0"
    error-ex "^1.3.1"
    json-parse-even-better-errors "^2.3.0"
    lines-and-columns "^1.1.6"

pascal-case@^3.1.2:
  version "3.1.2"
  resolved "https://registry.yarnpkg.com/pascal-case/-/pascal-case-3.1.2.tgz#b48e0ef2b98e205e7c1dae747d0b1508237660eb"
  integrity sha512-uWlGT3YSnK9x3BQJaOdcZwrnV6hPpd8jFH1/ucpiLRPh/2zCVJKS19E4GvYHvaCcACn3foXZ0cLB9Wrx1KGe5g==
  dependencies:
    no-case "^3.0.4"
    tslib "^2.0.3"

path-exists@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/path-exists/-/path-exists-4.0.0.tgz"
  integrity sha512-ak9Qy5Q7jYb2Wwcey5Fpvg2KoAc/ZIhLSLOSBmRmygPsGwkVVt0fZa0qrtMz+m6tJTAHfZQ8FnmB4MG4LWy7/w==

path-is-absolute@^1.0.0:
  version "1.0.1"
  resolved "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz"
  integrity sha512-AVbw3UJ2e9bq64vSaS9Am0fje1Pa8pbGqTTsmXfaIiMpnr5DlDhfJOuLj9Sf95ZPVDAUerDfEk88MPmPe7UCQg==

path-key@^3.0.0, path-key@^3.1.0:
  version "3.1.1"
  resolved "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz"
  integrity sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==

path-key@^4.0.0:
  version "4.0.0"
  resolved "https://registry.yarnpkg.com/path-key/-/path-key-4.0.0.tgz#295588dc3aee64154f877adb9d780b81c554bf18"
  integrity sha512-haREypq7xkM7ErfgIyA0z+Bj4AGKlMSdlQE2jvJo6huWD1EdkKYV+G/T4nq0YEF2vgTT8kqMFKo1uHn950r4SQ==

path-parse@^1.0.7:
  version "1.0.7"
  resolved "https://registry.npmjs.org/path-parse/-/path-parse-1.0.7.tgz"
  integrity sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==

path-type@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/path-type/-/path-type-4.0.0.tgz"
  integrity sha512-gDKb8aZMDeD/tZWs9P6+q0J9Mwkdl6xMV8TjnGP3qJVJ06bdMgkbBlLU8IdfOsIsFz2BW1rNVT3XuNEl8zPAvw==

pathe@^0.2.0:
  version "0.2.0"
  resolved "https://registry.yarnpkg.com/pathe/-/pathe-0.2.0.tgz#30fd7bbe0a0d91f0e60bae621f5d19e9e225c339"
  integrity sha512-sTitTPYnn23esFR3RlqYBWn4c45WGeLcsKzQiUpXJAyfcWkolvlYpV8FLo7JishK946oQwMFUCHXQ9AjGPKExw==

pathe@^1.1.0, pathe@^1.1.1:
  version "1.1.1"
  resolved "https://registry.yarnpkg.com/pathe/-/pathe-1.1.1.tgz#1dd31d382b974ba69809adc9a7a347e65d84829a"
  integrity sha512-d+RQGp0MAYTIaDBIMmOfMwz3E+LOZnxx1HZd5R18mmCZY0QBlK0LDZfPc8FW8Ed2DlvsuE6PRjroDY+wg4+j/Q==

pathval@^1.1.1:
  version "1.1.1"
  resolved "https://registry.yarnpkg.com/pathval/-/pathval-1.1.1.tgz#8534e77a77ce7ac5a2512ea21e0fdb8fcf6c3d8d"
  integrity sha512-Dp6zGqpTdETdR63lehJYPeIOqpiNBNtc7BpWSLrOje7UaIsE5aY92r/AunQA7rsXvet3lrJ3JnZX29UPTKXyKQ==

pend@~1.2.0:
  version "1.2.0"
  resolved "https://registry.yarnpkg.com/pend/-/pend-1.2.0.tgz#7a57eb550a6783f9115331fcf4663d5c8e007a50"
  integrity sha512-F3asv42UuXchdzt+xXqfW1OGlVBe+mxa2mqI0pg5yAHZPvFmY3Y6drSf/GQ1A86WgWEN9Kzh/WrgKa6iGcHXLg==

picocolors@^1.0.0:
  version "1.0.0"
  resolved "https://registry.npmjs.org/picocolors/-/picocolors-1.0.0.tgz"
  integrity sha512-1fygroTLlHu66zi26VoTDv8yRgm0Fccecssto+MhsZ0D/DGW2sm8E8AjW7NU5VVTRt5GxbeZ5qBuJr+HyLYkjQ==

picomatch@^2.0.4, picomatch@^2.2.1, picomatch@^2.2.2, picomatch@^2.2.3, picomatch@^2.3.1:
  version "2.3.1"
  resolved "https://registry.npmjs.org/picomatch/-/picomatch-2.3.1.tgz"
  integrity sha512-JU3teHTNjmE2VCGFzuY8EXzCDVwEqB2a8fsIvwaStHhAWJEeVd1o1QD80CU6+ZdEXXSLbSsuLwJjkCBWqRQUVA==

pify@^2.3.0:
  version "2.3.0"
  resolved "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz"
  integrity sha512-udgsAY+fTnvv7kI7aaxbqwWNb0AHiB0qBO89PZKPkoTmGOgdbrHDKD+0B2X4uTfJ/FT1R09r9gTsjUjNJotuog==

pirates@^4.0.1, pirates@^4.0.4:
  version "4.0.6"
  resolved "https://registry.npmjs.org/pirates/-/pirates-4.0.6.tgz"
  integrity sha512-saLsH7WeYYPiD25LDuLRRY/i+6HaPYr6G1OUlN39otzkSTxKnubR9RTxS3/Kk50s1g2JTgFwWQDQyplC5/SHZg==

pkg-dir@^4.2.0:
  version "4.2.0"
  resolved "https://registry.yarnpkg.com/pkg-dir/-/pkg-dir-4.2.0.tgz#f099133df7ede422e81d1d8448270eeb3e4261f3"
  integrity sha512-HRDzbaKjC+AOWVXxAU/x54COGeIv9eb+6CkDSQoNTt4XyWoIJvuPsXizxu/Fr23EiekbtZwmh1IcIG/l/a10GQ==
  dependencies:
    find-up "^4.0.0"

pkg-types@^1.0.3:
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/pkg-types/-/pkg-types-1.0.3.tgz#988b42ab19254c01614d13f4f65a2cfc7880f868"
  integrity sha512-nN7pYi0AQqJnoLPC9eHFQ8AcyaixBUOwvqc5TDnIKCMEE6I0y8P7OKA7fPexsXGCGxQDl/cmrLAp26LhcwxZ4A==
  dependencies:
    jsonc-parser "^3.2.0"
    mlly "^1.2.0"
    pathe "^1.1.0"

postcss-import@^15.1.0:
  version "15.1.0"
  resolved "https://registry.npmjs.org/postcss-import/-/postcss-import-15.1.0.tgz"
  integrity sha512-hpr+J05B2FVYUAXHeK1YyI267J/dDDhMU6B6civm8hSY1jYJnBXxzKDKDswzJmtLHryrjhnDjqqp/49t8FALew==
  dependencies:
    postcss-value-parser "^4.0.0"
    read-cache "^1.0.0"
    resolve "^1.1.7"

postcss-js@^4.0.1:
  version "4.0.1"
  resolved "https://registry.npmjs.org/postcss-js/-/postcss-js-4.0.1.tgz"
  integrity sha512-dDLF8pEO191hJMtlHFPRa8xsizHaM82MLfNkUHdUtVEV3tgTp5oj+8qbEqYM57SLfc74KSbw//4SeJma2LRVIw==
  dependencies:
    camelcase-css "^2.0.1"

postcss-load-config@^4.0.1:
  version "4.0.1"
  resolved "https://registry.npmjs.org/postcss-load-config/-/postcss-load-config-4.0.1.tgz"
  integrity sha512-vEJIc8RdiBRu3oRAI0ymerOn+7rPuMvRXslTvZUKZonDHFIczxztIyJ1urxM1x9JXEikvpWWTUUqal5j/8QgvA==
  dependencies:
    lilconfig "^2.0.5"
    yaml "^2.1.1"

postcss-nested@^6.0.1:
  version "6.0.1"
  resolved "https://registry.npmjs.org/postcss-nested/-/postcss-nested-6.0.1.tgz"
  integrity sha512-mEp4xPMi5bSWiMbsgoPfcP74lsWLHkQbZc3sY+jWYd65CUwXrUaTp0fmNpa01ZcETKlIgUdFN/MpS2xZtqL9dQ==
  dependencies:
    postcss-selector-parser "^6.0.11"

postcss-selector-parser@^6.0.11:
  version "6.0.13"
  resolved "https://registry.npmjs.org/postcss-selector-parser/-/postcss-selector-parser-6.0.13.tgz"
  integrity sha512-EaV1Gl4mUEV4ddhDnv/xtj7sxwrwxdetHdWUGnT4VJQf+4d05v6lHYZr8N573k5Z0BViss7BDhfWtKS3+sfAqQ==
  dependencies:
    cssesc "^3.0.0"
    util-deprecate "^1.0.2"

postcss-value-parser@^4.0.0, postcss-value-parser@^4.2.0:
  version "4.2.0"
  resolved "https://registry.npmjs.org/postcss-value-parser/-/postcss-value-parser-4.2.0.tgz"
  integrity sha512-1NNCs6uurfkVbeXG4S8JFT9t19m45ICnif8zWLd5oPSZ50QnwMfK+H3jv408d4jw/7Bttv5axS5IiHoLaVNHeQ==

postcss@^8.4.23, postcss@^8.4.27, postcss@^8.4.31:
  version "8.4.31"
  resolved "https://registry.npmjs.org/postcss/-/postcss-8.4.31.tgz"
  integrity sha512-PS08Iboia9mts/2ygV3eLpY5ghnUcfLV/EXTOW1E2qYxJKGGBUtNjN76FYHnMs36RmARn41bC0AZmn+rR0OVpQ==
  dependencies:
    nanoid "^3.3.6"
    picocolors "^1.0.0"
    source-map-js "^1.0.2"

postcss@^8.4.32:
  version "8.4.32"
  resolved "https://registry.yarnpkg.com/postcss/-/postcss-8.4.32.tgz#1dac6ac51ab19adb21b8b34fd2d93a86440ef6c9"
  integrity sha512-D/kj5JNu6oo2EIy+XL/26JEDTlIbB8hw85G8StOE6L74RQAVVP5rej6wxCNqyMbR4RkPfqvezVbPw81Ngd6Kcw==
  dependencies:
    nanoid "^3.3.7"
    picocolors "^1.0.0"
    source-map-js "^1.0.2"

prelude-ls@^1.2.1:
  version "1.2.1"
  resolved "https://registry.npmjs.org/prelude-ls/-/prelude-ls-1.2.1.tgz"
  integrity sha512-vkcDPrRZo1QZLbn5RLGPpg/WmIQ65qoWWhcGKf/b5eplkkarX0m9z8ppCat4mlOqUsWpyNuYgO3VRyrYHSzX5g==

pretty-format@^29.0.0, pretty-format@^29.7.0:
  version "29.7.0"
  resolved "https://registry.yarnpkg.com/pretty-format/-/pretty-format-29.7.0.tgz#ca42c758310f365bfa71a0bda0a807160b776812"
  integrity sha512-Pdlw/oPxN+aXdmM9R00JVC9WVFoCLTKJvDVLgmJ+qAffBMxsV85l/Lu7sNx4zSzPyoL2euImuEwHhOXdEgNFZQ==
  dependencies:
    "@jest/schemas" "^29.6.3"
    ansi-styles "^5.0.0"
    react-is "^18.0.0"

progress@2.0.3:
  version "2.0.3"
  resolved "https://registry.yarnpkg.com/progress/-/progress-2.0.3.tgz#7e8cf8d8f5b8f239c1bc68beb4eb78567d572ef8"
  integrity sha512-7PiHtLll5LdnKIMw100I+8xJXR5gW2QwWYkT6iJva0bXitZKa/XMrSbdmg3r2Xnaidz9Qumd0VPaMrZlF9V9sA==

prompts@^2.0.1:
  version "2.4.2"
  resolved "https://registry.yarnpkg.com/prompts/-/prompts-2.4.2.tgz#7b57e73b3a48029ad10ebd44f74b01722a4cb069"
  integrity sha512-NxNv/kLguCA7p3jE8oL2aEBsrJWgAakBpgmgK6lpPWV+WuOmY6r2/zbAVnP+T8bQlA0nzHXSJSJW0Hq7ylaD2Q==
  dependencies:
    kleur "^3.0.3"
    sisteransi "^1.0.5"

prop-types@^15.8.1:
  version "15.8.1"
  resolved "https://registry.npmjs.org/prop-types/-/prop-types-15.8.1.tgz"
  integrity sha512-oj87CgZICdulUohogVAR7AjlC0327U4el4L6eAvOqCeudMDVU0NThNaV+b9Df4dXgSP1gXMTnPdhfe/2qDH5cg==
  dependencies:
    loose-envify "^1.4.0"
    object-assign "^4.1.1"
    react-is "^16.13.1"

proxy-agent@6.4.0:
  version "6.4.0"
  resolved "https://registry.yarnpkg.com/proxy-agent/-/proxy-agent-6.4.0.tgz#b4e2dd51dee2b377748aef8d45604c2d7608652d"
  integrity sha512-u0piLU+nCOHMgGjRbimiXmA9kM/L9EHh3zL81xCdp7m+Y2pHIsnmbdDoEDoAz5geaonNR6q6+yOPQs6n4T6sBQ==
  dependencies:
    agent-base "^7.0.2"
    debug "^4.3.4"
    http-proxy-agent "^7.0.1"
    https-proxy-agent "^7.0.3"
    lru-cache "^7.14.1"
    pac-proxy-agent "^7.0.1"
    proxy-from-env "^1.1.0"
    socks-proxy-agent "^8.0.2"

proxy-from-env@^1.1.0:
  version "1.1.0"
  resolved "https://registry.yarnpkg.com/proxy-from-env/-/proxy-from-env-1.1.0.tgz#e102f16ca355424865755d2c9e8ea4f24d58c3e2"
  integrity sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg==

pump@^3.0.0:
  version "3.0.0"
  resolved "https://registry.yarnpkg.com/pump/-/pump-3.0.0.tgz#b4a2116815bde2f4e1ea602354e8c75565107a64"
  integrity sha512-LwZy+p3SFs1Pytd/jYct4wpv49HiYCqd9Rlc5ZVdk0V+8Yzv6jR5Blk3TRmPL1ft69TxP0IMZGJ+WPFU2BFhww==
  dependencies:
    end-of-stream "^1.1.0"
    once "^1.3.1"

punycode@^2.1.0:
  version "2.3.1"
  resolved "https://registry.npmjs.org/punycode/-/punycode-2.3.1.tgz"
  integrity sha512-vYt7UD1U9Wg6138shLtLOvdAu+8DsC/ilFtEVHcH+wydcSpNE20AfSOduf6MkRFahL5FY7X1oU7nKVZFtfq8Fg==

puppeteer-core@22.6.4:
  version "22.6.4"
  resolved "https://registry.yarnpkg.com/puppeteer-core/-/puppeteer-core-22.6.4.tgz#b0f9b3c7e90013e892fc34f0a3685543aa7b6326"
  integrity sha512-QtfJwPmqQec3EHc6LqbEz03vSiuVAr9bYp0TV87dLoreev6ZevsXdLgOfQgoA3GocrsSe/eUf7NRPQ1lQfsc3w==
  dependencies:
    "@puppeteer/browsers" "2.2.1"
    chromium-bidi "0.5.17"
    debug "4.3.4"
    devtools-protocol "0.0.1262051"
    ws "8.16.0"

puppeteer-core@22.9.0:
  version "22.9.0"
  resolved "https://registry.yarnpkg.com/puppeteer-core/-/puppeteer-core-22.9.0.tgz#df7ef6c285f4eed938911322184f9cd21d892b39"
  integrity sha512-Q2SYVZ1SIE7jCd/Pp+1/mNLFtdJfGvAF+CqOTDG8HcCNCiBvoXfopXfOfMHQ/FueXhGfJW/I6DartWv6QzpNGg==
  dependencies:
    "@puppeteer/browsers" "2.2.3"
    chromium-bidi "0.5.19"
    debug "4.3.4"
    devtools-protocol "0.0.1286932"
    ws "8.17.0"

puppeteer@*:
  version "22.9.0"
  resolved "https://registry.yarnpkg.com/puppeteer/-/puppeteer-22.9.0.tgz#ef404de6c1f6a5b32e01ede20258acf4aa826bf9"
  integrity sha512-yNux2cm6Sfik4lNLNjJ25Cdn9spJRbMXxl1YZtVZCEhEeej1sFlCvZ/Cr64LhgyJOuvz3iq2uk+RLFpQpGwrjw==
  dependencies:
    "@puppeteer/browsers" "2.2.3"
    cosmiconfig "9.0.0"
    devtools-protocol "0.0.1286932"
    puppeteer-core "22.9.0"

puppeteer@^22.6.4:
  version "22.6.4"
  resolved "https://registry.yarnpkg.com/puppeteer/-/puppeteer-22.6.4.tgz#478028ff522e51b5456d9c4a2a0df6ee3a5b2a72"
  integrity sha512-J9hXNwZmuqKDmNMj6kednZH8jzbdX9735NQfQJrq5LRD4nHisAMyW9pCD7glKi+iM7RV9JkesI1MYhdsN+0ZSQ==
  dependencies:
    "@puppeteer/browsers" "2.2.1"
    cosmiconfig "9.0.0"
    devtools-protocol "0.0.1262051"
    puppeteer-core "22.6.4"

pure-rand@^6.0.0:
  version "6.1.0"
  resolved "https://registry.yarnpkg.com/pure-rand/-/pure-rand-6.1.0.tgz#d173cf23258231976ccbdb05247c9787957604f2"
  integrity sha512-bVWawvoZoBYpp6yIoQtQXHZjmz35RSVHnUOTefl8Vcjr8snTPY1wnpSPMWekcFwbxI6gtmT7rSYPFvz71ldiOA==

queue-microtask@^1.2.2:
  version "1.2.3"
  resolved "https://registry.npmjs.org/queue-microtask/-/queue-microtask-1.2.3.tgz"
  integrity sha512-NuaNSa6flKT5JaSYQzJok04JzTL1CA6aGhv5rfLW3PgqA+M2ChpZQnAC8h8i4ZFkBS8X5RqkDBHA7r4hej3K9A==

queue-tick@^1.0.1:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/queue-tick/-/queue-tick-1.0.1.tgz#f6f07ac82c1fd60f82e098b417a80e52f1f4c142"
  integrity sha512-kJt5qhMxoszgU/62PLP1CJytzd2NKetjSRnyuj31fDd3Rlcz3fzlFdFLD1SItunPwyqEOkca6GbV612BWfaBag==

react-dom@^18.2.0:
  version "18.2.0"
  resolved "https://registry.npmjs.org/react-dom/-/react-dom-18.2.0.tgz"
  integrity sha512-6IMTriUmvsjHUjNtEDudZfuDQUoWXVxKHhlEGSk81n4YFS+r/Kl99wXiwlVXtPBtJenozv2P+hxDsw9eA7Xo6g==
  dependencies:
    loose-envify "^1.1.0"
    scheduler "^0.23.0"

react-dropzone@^14.2.3:
  version "14.2.3"
  resolved "https://registry.npmjs.org/react-dropzone/-/react-dropzone-14.2.3.tgz"
  integrity sha512-O3om8I+PkFKbxCukfIR3QAGftYXDZfOE2N1mr/7qebQJHs7U+/RSL/9xomJNpRg9kM5h9soQSdf0Gc7OHF5Fug==
  dependencies:
    attr-accept "^2.2.2"
    file-selector "^0.6.0"
    prop-types "^15.8.1"

react-hot-toast@^2.4.1:
  version "2.4.1"
  resolved "https://registry.npmjs.org/react-hot-toast/-/react-hot-toast-2.4.1.tgz"
  integrity sha512-j8z+cQbWIM5LY37pR6uZR6D4LfseplqnuAO4co4u8917hBUvXlEqyP1ZzqVLcqoyUesZZv/ImreoCeHVDpE5pQ==
  dependencies:
    goober "^2.1.10"

react-icons@^4.12.0:
  version "4.12.0"
  resolved "https://registry.npmjs.org/react-icons/-/react-icons-4.12.0.tgz"
  integrity sha512-IBaDuHiShdZqmfc/TwHu6+d6k2ltNCf3AszxNmjJc1KUfXdEeRJOKyNvLmAHaarhzGmTSVygNdyu8/opXv2gaw==

react-is@^16.13.1:
  version "16.13.1"
  resolved "https://registry.npmjs.org/react-is/-/react-is-16.13.1.tgz"
  integrity sha512-24e6ynE2H+OKt4kqsOvNd8kBpV65zoxbA4BVsEOB3ARVWQki/DHzaUoC5KuON/BiccDaCCTZBuOcfZs70kR8bQ==

react-is@^18.0.0:
  version "18.2.0"
  resolved "https://registry.yarnpkg.com/react-is/-/react-is-18.2.0.tgz#199431eeaaa2e09f86427efbb4f1473edb47609b"
  integrity sha512-xWGDIW6x921xtzPkhiULtthJHoJvBbF3q26fzloPCK0hsvxtPVelvftw3zjbHWSkR2km9Z+4uxbDDK/6Zw9B8w==

react-refresh@^0.14.0:
  version "0.14.0"
  resolved "https://registry.npmjs.org/react-refresh/-/react-refresh-0.14.0.tgz"
  integrity sha512-wViHqhAd8OHeLS/IRMJjTSDHF3U9eWi62F/MledQGPdJGDhodXJ9PBLNGr6WWL7qlH12Mt3TyTpbS+hGXMjCzQ==

react-remove-scroll-bar@^2.3.3:
  version "2.3.4"
  resolved "https://registry.yarnpkg.com/react-remove-scroll-bar/-/react-remove-scroll-bar-2.3.4.tgz#53e272d7a5cb8242990c7f144c44d8bd8ab5afd9"
  integrity sha512-63C4YQBUt0m6ALadE9XV56hV8BgJWDmmTPY758iIJjfQKt2nYwoUrPk0LXRXcB/yIj82T1/Ixfdpdk68LwIB0A==
  dependencies:
    react-style-singleton "^2.2.1"
    tslib "^2.0.0"

react-remove-scroll@2.5.5:
  version "2.5.5"
  resolved "https://registry.yarnpkg.com/react-remove-scroll/-/react-remove-scroll-2.5.5.tgz#1e31a1260df08887a8a0e46d09271b52b3a37e77"
  integrity sha512-ImKhrzJJsyXJfBZ4bzu8Bwpka14c/fQt0k+cyFp/PBhTfyDnU5hjOtM4AG/0AMyy8oKzOTR0lDgJIM7pYXI0kw==
  dependencies:
    react-remove-scroll-bar "^2.3.3"
    react-style-singleton "^2.2.1"
    tslib "^2.1.0"
    use-callback-ref "^1.3.0"
    use-sidecar "^1.1.2"

react-router-dom@^6.20.1:
  version "6.20.1"
  resolved "https://registry.yarnpkg.com/react-router-dom/-/react-router-dom-6.20.1.tgz#e34f8075b9304221420de3609e072bb349824984"
  integrity sha512-npzfPWcxfQN35psS7rJgi/EW0Gx6EsNjfdJSAk73U/HqMEJZ2k/8puxfwHFgDQhBGmS3+sjnGbMdMSV45axPQw==
  dependencies:
    "@remix-run/router" "1.13.1"
    react-router "6.20.1"

react-router@6.20.1:
  version "6.20.1"
  resolved "https://registry.yarnpkg.com/react-router/-/react-router-6.20.1.tgz#e8cc326031d235aaeec405bb234af77cf0fe75ef"
  integrity sha512-ccvLrB4QeT5DlaxSFFYi/KR8UMQ4fcD8zBcR71Zp1kaYTC5oJKYAp1cbavzGrogwxca+ubjkd7XjFZKBW8CxPA==
  dependencies:
    "@remix-run/router" "1.13.1"

react-style-singleton@^2.2.1:
  version "2.2.1"
  resolved "https://registry.yarnpkg.com/react-style-singleton/-/react-style-singleton-2.2.1.tgz#f99e420492b2d8f34d38308ff660b60d0b1205b4"
  integrity sha512-ZWj0fHEMyWkHzKYUr2Bs/4zU6XLmq9HsgBURm7g5pAVfyn49DgUiNgY2d4lXRlYSiCif9YBGpQleewkcqddc7g==
  dependencies:
    get-nonce "^1.0.0"
    invariant "^2.2.4"
    tslib "^2.0.0"

react@^18.2.0:
  version "18.2.0"
  resolved "https://registry.npmjs.org/react/-/react-18.2.0.tgz"
  integrity sha512-/3IjMdb2L9QbBdWiW5e3P2/npwMBaU9mHCSCUzNln0ZCYbcfTsGbTJrU/kGemdH2IWmB2ioZ+zkxtmq6g09fGQ==
  dependencies:
    loose-envify "^1.1.0"

read-cache@^1.0.0:
  version "1.0.0"
  resolved "https://registry.npmjs.org/read-cache/-/read-cache-1.0.0.tgz"
  integrity sha512-Owdv/Ft7IjOgm/i0xvNDZ1LrRANRfew4b2prF3OWMQLxLfu3bS8FVhCsrSCMK4lR56Y9ya+AThoTpDCTxCmpRA==
  dependencies:
    pify "^2.3.0"

readdirp@~3.6.0:
  version "3.6.0"
  resolved "https://registry.npmjs.org/readdirp/-/readdirp-3.6.0.tgz"
  integrity sha512-hOS089on8RduqdbhvQ5Z37A0ESjsqz6qnRcffsMU3495FuTdqSm+7bhJ29JvIOsBDEEnan5DPu9t3To9VRlMzA==
  dependencies:
    picomatch "^2.2.1"

regenerator-runtime@^0.14.0:
  version "0.14.0"
  resolved "https://registry.yarnpkg.com/regenerator-runtime/-/regenerator-runtime-0.14.0.tgz#5e19d68eb12d486f797e15a3c6a918f7cec5eb45"
  integrity sha512-srw17NI0TUWHuGa5CFGGmhfNIeja30WMBfbslPNhf6JrqQlLN5gcrvig1oqPxiVaXb0oW0XRKtH6Nngs5lKCIA==

relateurl@^0.2.7:
  version "0.2.7"
  resolved "https://registry.yarnpkg.com/relateurl/-/relateurl-0.2.7.tgz#54dbf377e51440aca90a4cd274600d3ff2d888a9"
  integrity sha512-G08Dxvm4iDN3MLM0EsP62EDV9IuhXPR6blNz6Utcp7zyV3tr4HVNINt6MpaRWbxoOHT3Q7YN2P+jaHX8vUbgog==

require-directory@^2.1.1:
  version "2.1.1"
  resolved "https://registry.yarnpkg.com/require-directory/-/require-directory-2.1.1.tgz#8c64ad5fd30dab1c976e2344ffe7f792a6a6df42"
  integrity sha512-fGxEI7+wsG9xrvdjsrlmL22OMTTiHRwAMroiEeMgq8gzoLC/PQr7RsRDSTLUg/bZAZtF+TVIkHc6/4RIKrui+Q==

resolve-cwd@^3.0.0:
  version "3.0.0"
  resolved "https://registry.yarnpkg.com/resolve-cwd/-/resolve-cwd-3.0.0.tgz#0f0075f1bb2544766cf73ba6a6e2adfebcb13f2d"
  integrity sha512-OrZaX2Mb+rJCpH/6CpSqt9xFVpN++x01XnN2ie9g6P5/3xelLAkXWVADpdz1IHD/KFfEXyE6V0U01OQ3UO2rEg==
  dependencies:
    resolve-from "^5.0.0"

resolve-from@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/resolve-from/-/resolve-from-4.0.0.tgz"
  integrity sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==

resolve-from@^5.0.0:
  version "5.0.0"
  resolved "https://registry.yarnpkg.com/resolve-from/-/resolve-from-5.0.0.tgz#c35225843df8f776df21c57557bc087e9dfdfc69"
  integrity sha512-qYg9KP24dD5qka9J47d0aVky0N+b4fTU89LN9iDnjB5waksiC49rvMB0PrUJQGoTmH50XPiqOvAjDfaijGxYZw==

resolve.exports@^2.0.0:
  version "2.0.2"
  resolved "https://registry.yarnpkg.com/resolve.exports/-/resolve.exports-2.0.2.tgz#f8c934b8e6a13f539e38b7098e2e36134f01e800"
  integrity sha512-X2UW6Nw3n/aMgDVy+0rSqgHlv39WZAlZrXCdnbyEiKm17DSqHX4MmQMaST3FbeWR5FTuRcUwYAziZajji0Y7mg==

resolve@^1.1.7, resolve@^1.20.0, resolve@^1.22.2:
  version "1.22.8"
  resolved "https://registry.npmjs.org/resolve/-/resolve-1.22.8.tgz"
  integrity sha512-oKWePCxqpd6FlLvGV1VU0x7bkPmmCNolxzjMf4NczoDnQcIWrAF+cPtZn5i6n+RfD2d9i0tzpKnG6Yk168yIyw==
  dependencies:
    is-core-module "^2.13.0"
    path-parse "^1.0.7"
    supports-preserve-symlinks-flag "^1.0.0"

reusify@^1.0.4:
  version "1.0.4"
  resolved "https://registry.npmjs.org/reusify/-/reusify-1.0.4.tgz"
  integrity sha512-U9nH88a3fc/ekCF1l0/UP1IosiuIjyTh7hBvXVMHYgVcfGvt897Xguj2UOLDeI5BG2m7/uwyaLVT6fbtCwTyzw==

rimraf@^3.0.2:
  version "3.0.2"
  resolved "https://registry.npmjs.org/rimraf/-/rimraf-3.0.2.tgz"
  integrity sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==
  dependencies:
    glob "^7.1.3"

rollup@^3.27.1:
  version "3.29.4"
  resolved "https://registry.npmjs.org/rollup/-/rollup-3.29.4.tgz"
  integrity sha512-oWzmBZwvYrU0iJHtDmhsm662rC15FRXmcjCk1xD771dFDx5jJ02ufAQQTn0etB2emNk4J9EZg/yWKpsn9BWGRw==
  optionalDependencies:
    fsevents "~2.3.2"

rollup@^4.2.0:
  version "4.6.1"
  resolved "https://registry.yarnpkg.com/rollup/-/rollup-4.6.1.tgz#351501c86b5b4f976dde8c5837516452b59921f8"
  integrity sha512-jZHaZotEHQaHLgKr8JnQiDT1rmatjgKlMekyksz+yk9jt/8z9quNjnKNRoaM0wd9DC2QKXjmWWuDYtM3jfF8pQ==
  optionalDependencies:
    "@rollup/rollup-android-arm-eabi" "4.6.1"
    "@rollup/rollup-android-arm64" "4.6.1"
    "@rollup/rollup-darwin-arm64" "4.6.1"
    "@rollup/rollup-darwin-x64" "4.6.1"
    "@rollup/rollup-linux-arm-gnueabihf" "4.6.1"
    "@rollup/rollup-linux-arm64-gnu" "4.6.1"
    "@rollup/rollup-linux-arm64-musl" "4.6.1"
    "@rollup/rollup-linux-x64-gnu" "4.6.1"
    "@rollup/rollup-linux-x64-musl" "4.6.1"
    "@rollup/rollup-win32-arm64-msvc" "4.6.1"
    "@rollup/rollup-win32-ia32-msvc" "4.6.1"
    "@rollup/rollup-win32-x64-msvc" "4.6.1"
    fsevents "~2.3.2"

run-parallel@^1.1.9:
  version "1.2.0"
  resolved "https://registry.npmjs.org/run-parallel/-/run-parallel-1.2.0.tgz"
  integrity sha512-5l4VyZR86LZ/lDxZTR6jqL8AFE2S0IFLMP26AbjsLVADxHdhB/c0GUsH+y39UfCi3dzz8OlQuPmnaJOMoDHQBA==
  dependencies:
    queue-microtask "^1.2.2"

scheduler@^0.23.0:
  version "0.23.0"
  resolved "https://registry.npmjs.org/scheduler/-/scheduler-0.23.0.tgz"
  integrity sha512-CtuThmgHNg7zIZWAXi3AsyIzA3n4xx7aNyjwC2VJldO2LMVDhFK+63xGqq6CsJH4rTAt6/M+N4GhZiDYPx9eUw==
  dependencies:
    loose-envify "^1.1.0"

semver@7.6.0:
  version "7.6.0"
  resolved "https://registry.yarnpkg.com/semver/-/semver-7.6.0.tgz#1a46a4db4bffcccd97b743b5005c8325f23d4e2d"
  integrity sha512-EnwXhrlwXMk9gKu5/flx5sv/an57AkRplG3hTK68W7FRDN+k+OWBj65M7719OkA82XLBxrcX0KSHj+X5COhOVg==
  dependencies:
    lru-cache "^6.0.0"

semver@^6.3.0, semver@^6.3.1:
  version "6.3.1"
  resolved "https://registry.npmjs.org/semver/-/semver-6.3.1.tgz"
  integrity sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==

semver@^7.3.4, semver@^7.5.0, semver@^7.5.4:
  version "7.5.4"
  resolved "https://registry.npmjs.org/semver/-/semver-7.5.4.tgz"
  integrity sha512-1bCSESV6Pv+i21Hvpxp3Dx+pSD8lIPt8uVjRrxAUt/nbswYc+tK6Y2btiULjd4+fnq15PX+nqQDC7Oft7WkwcA==
  dependencies:
    lru-cache "^6.0.0"

semver@^7.5.3:
  version "7.6.2"
  resolved "https://registry.yarnpkg.com/semver/-/semver-7.6.2.tgz#1e3b34759f896e8f14d6134732ce798aeb0c6e13"
  integrity sha512-FNAIBWCx9qcRhoHcgcJ0gvU7SN1lYU2ZXuSfl04bSC5OpvDHFyJCjdNHomPXxjQlCBU67YW64PzY7/VIEH7F2w==

shebang-command@^2.0.0:
  version "2.0.0"
  resolved "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz"
  integrity sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==
  dependencies:
    shebang-regex "^3.0.0"

shebang-regex@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz"
  integrity sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==

siginfo@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/siginfo/-/siginfo-2.0.0.tgz#32e76c70b79724e3bb567cb9d543eb858ccfaf30"
  integrity sha512-ybx0WO1/8bSBLEWXZvEd7gMW3Sn3JFlW3TvX1nREbDLRNQNaeNN8WK0meBwPdAaOI7TtRRRJn/Es1zhrrCHu7g==

signal-exit@^3.0.3, signal-exit@^3.0.7:
  version "3.0.7"
  resolved "https://registry.yarnpkg.com/signal-exit/-/signal-exit-3.0.7.tgz#a9a1767f8af84155114eaabd73f99273c8f59ad9"
  integrity sha512-wnD2ZE+l+SPC/uoS0vXeE9L1+0wuaMqKlfz9AMUo38JsyLSBWSFcHR1Rri62LZc12vLr1gb3jl7iwQhgwpAbGQ==

signal-exit@^4.1.0:
  version "4.1.0"
  resolved "https://registry.yarnpkg.com/signal-exit/-/signal-exit-4.1.0.tgz#952188c1cbd546070e2dd20d0f41c0ae0530cb04"
  integrity sha512-bzyZ1e88w9O1iNJbKnOlvYTrWPDl46O1bG0D3XInv+9tkPrxrN8jUUTiFlDkkmKWgn1M6CfIA13SuGqOa9Korw==

sisteransi@^1.0.5:
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/sisteransi/-/sisteransi-1.0.5.tgz#134d681297756437cc05ca01370d3a7a571075ed"
  integrity sha512-bLGGlR1QxBcynn2d5YmDX4MGjlZvy2MRBDRNHLJ8VI6l6+9FUiyTFNJ0IveOSP0bcXgVDPRcfGqA0pjaqUpfVg==

slash@^3.0.0:
  version "3.0.0"
  resolved "https://registry.npmjs.org/slash/-/slash-3.0.0.tgz"
  integrity sha512-g9Q1haeby36OSStwb4ntCGGGaKsaVSjQ68fBxoQcutl5fS1vuY18H3wSt3jFyFtrkx+Kz0V1G85A4MyAdDMi2Q==

smart-buffer@^4.2.0:
  version "4.2.0"
  resolved "https://registry.yarnpkg.com/smart-buffer/-/smart-buffer-4.2.0.tgz#6e1d71fa4f18c05f7d0ff216dd16a481d0e8d9ae"
  integrity sha512-94hK0Hh8rPqQl2xXc3HsaBoOXKV20MToPkcXvwbISWLEs+64sBq5kFgn2kJDHb1Pry9yrP0dxrCI9RRci7RXKg==

socks-proxy-agent@^8.0.2:
  version "8.0.3"
  resolved "https://registry.yarnpkg.com/socks-proxy-agent/-/socks-proxy-agent-8.0.3.tgz#6b2da3d77364fde6292e810b496cb70440b9b89d"
  integrity sha512-VNegTZKhuGq5vSD6XNKlbqWhyt/40CgoEw8XxD6dhnm8Jq9IEa3nIa4HwnM8XOqU0CdB0BwWVXusqiFXfHB3+A==
  dependencies:
    agent-base "^7.1.1"
    debug "^4.3.4"
    socks "^2.7.1"

socks@^2.7.1:
  version "2.8.3"
  resolved "https://registry.yarnpkg.com/socks/-/socks-2.8.3.tgz#1ebd0f09c52ba95a09750afe3f3f9f724a800cb5"
  integrity sha512-l5x7VUUWbjVFbafGLxPWkYsHIhEvmF85tbIeFZWc8ZPtoMyybuEhL7Jye/ooC4/d48FgOjSJXgsF/AJPYCW8Zw==
  dependencies:
    ip-address "^9.0.5"
    smart-buffer "^4.2.0"

source-map-js@^1.0.2:
  version "1.0.2"
  resolved "https://registry.npmjs.org/source-map-js/-/source-map-js-1.0.2.tgz"
  integrity sha512-R0XvVJ9WusLiqTCEiGCmICCMplcCkIwwR11mOSD9CR5u+IXYdiseeEuXCVAjS54zqwkLcPNnmU4OeJ6tUrWhDw==

source-map-support@0.5.13:
  version "0.5.13"
  resolved "https://registry.yarnpkg.com/source-map-support/-/source-map-support-0.5.13.tgz#31b24a9c2e73c2de85066c0feb7d44767ed52932"
  integrity sha512-SHSKFHadjVA5oR4PPqhtAVdcBWwRYVd6g6cAXnIbRiIwc2EhPrTuKUBdSLvlEKyIP3GCf89fltvcZiP9MMFA1w==
  dependencies:
    buffer-from "^1.0.0"
    source-map "^0.6.0"

source-map-support@~0.5.20:
  version "0.5.21"
  resolved "https://registry.yarnpkg.com/source-map-support/-/source-map-support-0.5.21.tgz#04fe7c7f9e1ed2d662233c28cb2b35b9f63f6e4f"
  integrity sha512-uBHU3L3czsIyYXKX88fdrGovxdSCoTGDRZ6SYXtSRxLZUzHg5P/66Ht6uoUlHu9EZod+inXhKo3qQgwXUT/y1w==
  dependencies:
    buffer-from "^1.0.0"
    source-map "^0.6.0"

source-map@^0.6.0, source-map@^0.6.1, source-map@~0.6.0, source-map@~0.6.1:
  version "0.6.1"
  resolved "https://registry.yarnpkg.com/source-map/-/source-map-0.6.1.tgz#74722af32e9614e9c287a8d0bbde48b5e2f1a263"
  integrity sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g==

sprintf-js@^1.1.3:
  version "1.1.3"
  resolved "https://registry.yarnpkg.com/sprintf-js/-/sprintf-js-1.1.3.tgz#4914b903a2f8b685d17fdf78a70e917e872e444a"
  integrity sha512-Oo+0REFV59/rz3gfJNKQiBlwfHaSESl1pcGyABQsnnIfWOFt6JNj5gCog2U6MLZ//IGYD+nA8nI+mTShREReaA==

sprintf-js@~1.0.2:
  version "1.0.3"
  resolved "https://registry.yarnpkg.com/sprintf-js/-/sprintf-js-1.0.3.tgz#04e6926f662895354f3dd015203633b857297e2c"
  integrity sha512-D9cPgkvLlV3t3IzL0D0YLvGA9Ahk4PcvVwUbN0dSGr1aP0Nrt4AEnTUbuGvquEC0mA64Gqt1fzirlRs5ibXx8g==

stack-utils@^2.0.3:
  version "2.0.6"
  resolved "https://registry.yarnpkg.com/stack-utils/-/stack-utils-2.0.6.tgz#aaf0748169c02fc33c8232abccf933f54a1cc34f"
  integrity sha512-XlkWvfIm6RmsWtNJx+uqtKLS8eqFbxUg0ZzLXqY0caEy9l7hruX8IpiDnjsLavoBgqCCR71TqWO8MaXYheJ3RQ==
  dependencies:
    escape-string-regexp "^2.0.0"

stackback@0.0.2:
  version "0.0.2"
  resolved "https://registry.yarnpkg.com/stackback/-/stackback-0.0.2.tgz#1ac8a0d9483848d1695e418b6d031a3c3ce68e3b"
  integrity sha512-1XMJE5fQo1jGH6Y/7ebnwPOBEkIEnT4QF32d5R1+VXdXveM0IBMJt8zfaxX1P3QhVwrYe+576+jkANtSS2mBbw==

std-env@^3.5.0:
  version "3.6.0"
  resolved "https://registry.yarnpkg.com/std-env/-/std-env-3.6.0.tgz#94807562bddc68fa90f2e02c5fd5b6865bb4e98e"
  integrity sha512-aFZ19IgVmhdB2uX599ve2kE6BIE3YMnQ6Gp6BURhW/oIzpXGKr878TQfAQZn1+i0Flcc/UKUy1gOlcfaUBCryg==

streamx@^2.13.0, streamx@^2.15.0:
  version "2.16.1"
  resolved "https://registry.yarnpkg.com/streamx/-/streamx-2.16.1.tgz#2b311bd34832f08aa6bb4d6a80297c9caef89614"
  integrity sha512-m9QYj6WygWyWa3H1YY69amr4nVgy61xfjys7xO7kviL5rfIEc2naf+ewFiOA+aEJD7y0JO3h2GoiUv4TDwEGzQ==
  dependencies:
    fast-fifo "^1.1.0"
    queue-tick "^1.0.1"
  optionalDependencies:
    bare-events "^2.2.0"

string-length@^4.0.1:
  version "4.0.2"
  resolved "https://registry.yarnpkg.com/string-length/-/string-length-4.0.2.tgz#a8a8dc7bd5c1a82b9b3c8b87e125f66871b6e57a"
  integrity sha512-+l6rNN5fYHNhZZy41RXsYptCjA2Igmq4EG7kZAYFQI1E1VTXarr6ZPXBg6eq7Y6eK4FEhY6AJlyuFIb/v/S0VQ==
  dependencies:
    char-regex "^1.0.2"
    strip-ansi "^6.0.0"

string-width@^4.1.0, string-width@^4.2.0, string-width@^4.2.3:
  version "4.2.3"
  resolved "https://registry.yarnpkg.com/string-width/-/string-width-4.2.3.tgz#269c7117d27b05ad2e536830a8ec895ef9c6d010"
  integrity sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==
  dependencies:
    emoji-regex "^8.0.0"
    is-fullwidth-code-point "^3.0.0"
    strip-ansi "^6.0.1"

strip-ansi@^6.0.0, strip-ansi@^6.0.1:
  version "6.0.1"
  resolved "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz"
  integrity sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==
  dependencies:
    ansi-regex "^5.0.1"

strip-bom@^4.0.0:
  version "4.0.0"
  resolved "https://registry.yarnpkg.com/strip-bom/-/strip-bom-4.0.0.tgz#9c3505c1db45bcedca3d9cf7a16f5c5aa3901878"
  integrity sha512-3xurFv5tEgii33Zi8Jtp55wEIILR9eh34FAW00PZf+JnSsTmV/ioewSgQl97JHvgjoRGwPShsWm+IdrxB35d0w==

strip-final-newline@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/strip-final-newline/-/strip-final-newline-2.0.0.tgz#89b852fb2fcbe936f6f4b3187afb0a12c1ab58ad"
  integrity sha512-BrpvfNAE3dcvq7ll3xVumzjKjZQ5tI1sEUIKr3Uoks0XUl45St3FlatVqef9prk4jRDzhW6WZg+3bk93y6pLjA==

strip-final-newline@^3.0.0:
  version "3.0.0"
  resolved "https://registry.yarnpkg.com/strip-final-newline/-/strip-final-newline-3.0.0.tgz#52894c313fbff318835280aed60ff71ebf12b8fd"
  integrity sha512-dOESqjYr96iWYylGObzd39EuNTa5VJxyvVAEm5Jnh7KGo75V43Hk1odPQkNDyXNmUR6k+gEiDVXnjB8HJ3crXw==

strip-json-comments@^3.1.1:
  version "3.1.1"
  resolved "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-3.1.1.tgz"
  integrity sha512-6fPc+R4ihwqP6N/aIv2f1gMH8lOVtWQHoqC4yK6oSDVVocumAsfCqjkXnqiYMhmMwS/mEHLp7Vehlt3ql6lEig==

strip-literal@^1.3.0:
  version "1.3.0"
  resolved "https://registry.yarnpkg.com/strip-literal/-/strip-literal-1.3.0.tgz#db3942c2ec1699e6836ad230090b84bb458e3a07"
  integrity sha512-PugKzOsyXpArk0yWmUwqOZecSO0GH0bPoctLcqNDH9J04pVW3lflYE0ujElBGTloevcxF5MofAOZ7C5l2b+wLg==
  dependencies:
    acorn "^8.10.0"

style-mod@^4.0.0, style-mod@^4.1.0:
  version "4.1.0"
  resolved "https://registry.yarnpkg.com/style-mod/-/style-mod-4.1.0.tgz#a313a14f4ae8bb4d52878c0053c4327fb787ec09"
  integrity sha512-Ca5ib8HrFn+f+0n4N4ScTIA9iTOQ7MaGS1ylHcoVqW9J7w2w8PzN6g9gKmTYgGEBH8e120+RCmhpje6jC5uGWA==

sucrase@^3.32.0:
  version "3.34.0"
  resolved "https://registry.npmjs.org/sucrase/-/sucrase-3.34.0.tgz"
  integrity sha512-70/LQEZ07TEcxiU2dz51FKaE6hCTWC6vr7FOk3Gr0U60C3shtAN+H+BFr9XlYe5xqf3RA8nrc+VIwzCfnxuXJw==
  dependencies:
    "@jridgewell/gen-mapping" "^0.3.2"
    commander "^4.0.0"
    glob "7.1.6"
    lines-and-columns "^1.1.6"
    mz "^2.7.0"
    pirates "^4.0.1"
    ts-interface-checker "^0.1.9"

supports-color@^5.3.0:
  version "5.5.0"
  resolved "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz"
  integrity sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==
  dependencies:
    has-flag "^3.0.0"

supports-color@^7.1.0:
  version "7.2.0"
  resolved "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz"
  integrity sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==
  dependencies:
    has-flag "^4.0.0"

supports-color@^8.0.0:
  version "8.1.1"
  resolved "https://registry.yarnpkg.com/supports-color/-/supports-color-8.1.1.tgz#cd6fc17e28500cff56c1b86c0a7fd4a54a73005c"
  integrity sha512-MpUEN2OodtUzxvKQl72cUF7RQ5EiHsGvSsVG0ia9c5RbWGL2CI4C7EpPS8UTBIplnlzZiNuV56w+FuNxy3ty2Q==
  dependencies:
    has-flag "^4.0.0"

supports-preserve-symlinks-flag@^1.0.0:
  version "1.0.0"
  resolved "https://registry.npmjs.org/supports-preserve-symlinks-flag/-/supports-preserve-symlinks-flag-1.0.0.tgz"
  integrity sha512-ot0WnXS9fgdkgIcePe6RHNk1WA8+muPa6cSjeR3V8K27q9BB1rTE3R1p7Hv0z1ZyAc8s6Vvv8DIyWf681MAt0w==

tailwind-merge@^2.0.0:
  version "2.0.0"
  resolved "https://registry.yarnpkg.com/tailwind-merge/-/tailwind-merge-2.0.0.tgz#a0f3a8c874ebae5feec5595614d08245a5f88a39"
  integrity sha512-WO8qghn9yhsldLSg80au+3/gY9E4hFxIvQ3qOmlpXnqpDKoMruKfi/56BbbMg6fHTQJ9QD3cc79PoWqlaQE4rw==
  dependencies:
    "@babel/runtime" "^7.23.1"

tailwindcss-animate@^1.0.7:
  version "1.0.7"
  resolved "https://registry.yarnpkg.com/tailwindcss-animate/-/tailwindcss-animate-1.0.7.tgz#318b692c4c42676cc9e67b19b78775742388bef4"
  integrity sha512-bl6mpH3T7I3UFxuvDEXLxy/VuFxBk5bbzplh7tXI68mwMokNYd1t9qPBHlnyTwfa4JGC4zP516I1hYYtQ/vspA==

tailwindcss@^3.3.5:
  version "3.3.5"
  resolved "https://registry.npmjs.org/tailwindcss/-/tailwindcss-3.3.5.tgz"
  integrity sha512-5SEZU4J7pxZgSkv7FP1zY8i2TIAOooNZ1e/OGtxIEv6GltpoiXUqWvLy89+a10qYTB1N5Ifkuw9lqQkN9sscvA==
  dependencies:
    "@alloc/quick-lru" "^5.2.0"
    arg "^5.0.2"
    chokidar "^3.5.3"
    didyoumean "^1.2.2"
    dlv "^1.1.3"
    fast-glob "^3.3.0"
    glob-parent "^6.0.2"
    is-glob "^4.0.3"
    jiti "^1.19.1"
    lilconfig "^2.1.0"
    micromatch "^4.0.5"
    normalize-path "^3.0.0"
    object-hash "^3.0.0"
    picocolors "^1.0.0"
    postcss "^8.4.23"
    postcss-import "^15.1.0"
    postcss-js "^4.0.1"
    postcss-load-config "^4.0.1"
    postcss-nested "^6.0.1"
    postcss-selector-parser "^6.0.11"
    resolve "^1.22.2"
    sucrase "^3.32.0"

tar-fs@3.0.5:
  version "3.0.5"
  resolved "https://registry.yarnpkg.com/tar-fs/-/tar-fs-3.0.5.tgz#f954d77767e4e6edf973384e1eb95f8f81d64ed9"
  integrity sha512-JOgGAmZyMgbqpLwct7ZV8VzkEB6pxXFBVErLtb+XCOqzc6w1xiWKI9GVd6bwk68EX7eJ4DWmfXVmq8K2ziZTGg==
  dependencies:
    pump "^3.0.0"
    tar-stream "^3.1.5"
  optionalDependencies:
    bare-fs "^2.1.1"
    bare-path "^2.1.0"

tar-stream@^3.1.5:
  version "3.1.7"
  resolved "https://registry.yarnpkg.com/tar-stream/-/tar-stream-3.1.7.tgz#24b3fb5eabada19fe7338ed6d26e5f7c482e792b"
  integrity sha512-qJj60CXt7IU1Ffyc3NJMjh6EkuCFej46zUqJ4J7pqYlThyd9bO0XBTmcOIhSzZJVWfsLks0+nle/j538YAW9RQ==
  dependencies:
    b4a "^1.6.4"
    fast-fifo "^1.2.0"
    streamx "^2.15.0"

terser@^5.10.0:
  version "5.24.0"
  resolved "https://registry.yarnpkg.com/terser/-/terser-5.24.0.tgz#4ae50302977bca4831ccc7b4fef63a3c04228364"
  integrity sha512-ZpGR4Hy3+wBEzVEnHvstMvqpD/nABNelQn/z2r0fjVWGQsN3bpOLzQlqDxmb4CDZnXq5lpjnQ+mHQLAOpfM5iw==
  dependencies:
    "@jridgewell/source-map" "^0.3.3"
    acorn "^8.8.2"
    commander "^2.20.0"
    source-map-support "~0.5.20"

test-exclude@^6.0.0:
  version "6.0.0"
  resolved "https://registry.yarnpkg.com/test-exclude/-/test-exclude-6.0.0.tgz#04a8698661d805ea6fa293b6cb9e63ac044ef15e"
  integrity sha512-cAGWPIyOHU6zlmg88jwm7VRyXnMN7iV68OGAbYDk/Mh/xC/pzVPlQtY6ngoIH/5/tciuhGfvESU8GrHrcxD56w==
  dependencies:
    "@istanbuljs/schema" "^0.1.2"
    glob "^7.1.4"
    minimatch "^3.0.4"

text-segmentation@^1.0.3:
  version "1.0.3"
  resolved "https://registry.npmjs.org/text-segmentation/-/text-segmentation-1.0.3.tgz#52a388159efffe746b24a63ba311b6ac9f2d7943"
  integrity sha512-iOiPUo/BGnZ6+54OsWxZidGCsdU8YbE4PSpdPinp7DeMtUJNJBoJ/ouUSTJjHkh1KntHaltHl/gDs2FC4i5+Nw==
  dependencies:
    utrie "^1.0.2"

text-table@^0.2.0:
  version "0.2.0"
  resolved "https://registry.npmjs.org/text-table/-/text-table-0.2.0.tgz"
  integrity sha512-N+8UisAXDGk8PFXP4HAzVR9nbfmVJ3zYLAWiTIoqC5v5isinhr+r5uaO8+7r3BMfuNIufIsA7RdpVgacC2cSpw==

thememirror@^2.0.1:
  version "2.0.1"
  resolved "https://registry.yarnpkg.com/thememirror/-/thememirror-2.0.1.tgz#ae9eb4ce7e8d0303d4fbabcc860ed38a0b45b079"
  integrity sha512-d5i6FVvWWPkwrm4cHLI3t9AT1OrkAt7Ig8dtdYSofgF7C/eiyNuq6zQzSTusWTde3jpW9WLvA9J/fzNKMUsd0w==

thenify-all@^1.0.0:
  version "1.6.0"
  resolved "https://registry.npmjs.org/thenify-all/-/thenify-all-1.6.0.tgz"
  integrity sha512-RNxQH/qI8/t3thXJDwcstUO4zeqo64+Uy/+sNVRBx4Xn2OX+OZ9oP+iJnNFqplFra2ZUVeKCSa2oVWi3T4uVmA==
  dependencies:
    thenify ">= 3.1.0 < 4"

"thenify@>= 3.1.0 < 4":
  version "3.3.1"
  resolved "https://registry.npmjs.org/thenify/-/thenify-3.3.1.tgz"
  integrity sha512-RVZSIV5IG10Hk3enotrhvz0T9em6cyHBLkH/YAZuKqd8hRkKhSfCGIcP2KUY0EPxndzANBmNllzWPwak+bheSw==
  dependencies:
    any-promise "^1.0.0"

through@^2.3.8:
  version "2.3.8"
  resolved "https://registry.yarnpkg.com/through/-/through-2.3.8.tgz#0dd4c9ffaabc357960b1b724115d7e0e86a2e1f5"
  integrity sha512-w89qg7PI8wAdvX60bMDP+bFoD5Dvhm9oLheFp5O4a2QF0cSBGsBX4qZmadPMvVqlLJBBci+WqGGOAPvcDeNSVg==

tiny-invariant@^1.1.0:
  version "1.3.1"
  resolved "https://registry.npmjs.org/tiny-invariant/-/tiny-invariant-1.3.1.tgz"
  integrity sha512-AD5ih2NlSssTCwsMznbvwMZpJ1cbhkGd2uueNxzv2jDlEeZdU04JQfRnggJQ8DrcVBGjAsCKwFBbDlVNtEMlzw==

tinybench@^2.5.1:
  version "2.5.1"
  resolved "https://registry.yarnpkg.com/tinybench/-/tinybench-2.5.1.tgz#3408f6552125e53a5a48adee31261686fd71587e"
  integrity sha512-65NKvSuAVDP/n4CqH+a9w2kTlLReS9vhsAP06MWx+/89nMinJyB2icyl58RIcqCmIggpojIGeuJGhjU1aGMBSg==

tinypool@^0.8.1:
  version "0.8.1"
  resolved "https://registry.yarnpkg.com/tinypool/-/tinypool-0.8.1.tgz#b6c4e4972ede3e3e5cda74a3da1679303d386b03"
  integrity sha512-zBTCK0cCgRROxvs9c0CGK838sPkeokNGdQVUUwHAbynHFlmyJYj825f/oRs528HaIJ97lo0pLIlDUzwN+IorWg==

tinyspy@^2.2.0:
  version "2.2.0"
  resolved "https://registry.yarnpkg.com/tinyspy/-/tinyspy-2.2.0.tgz#9dc04b072746520b432f77ea2c2d17933de5d6ce"
  integrity sha512-d2eda04AN/cPOR89F7Xv5bK/jrQEhmcLFe6HFldoeO9AJtps+fqEnh486vnT/8y4bw38pSyxDcTCAq+Ks2aJTg==

tmpl@1.0.5:
  version "1.0.5"
  resolved "https://registry.yarnpkg.com/tmpl/-/tmpl-1.0.5.tgz#8683e0b902bb9c20c4f726e3c0b69f36518c07cc"
  integrity sha512-3f0uOEAQwIqGuWW2MVzYg8fV/QNnc/IpuJNG837rLuczAaLVHslWHZQj4IGiEl5Hs3kkbhwL9Ab7Hrsmuj+Smw==

to-fast-properties@^2.0.0:
  version "2.0.0"
  resolved "https://registry.npmjs.org/to-fast-properties/-/to-fast-properties-2.0.0.tgz"
  integrity sha512-/OaKK0xYrs3DmxRYqL/yDc+FxFUVYhDlXMhRmv3z915w2HF1tnN1omB354j8VUGO/hbRzyD6Y3sA7v7GS/ceog==

to-regex-range@^5.0.1:
  version "5.0.1"
  resolved "https://registry.npmjs.org/to-regex-range/-/to-regex-range-5.0.1.tgz"
  integrity sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==
  dependencies:
    is-number "^7.0.0"

toggle-selection@^1.0.6:
  version "1.0.6"
  resolved "https://registry.npmjs.org/toggle-selection/-/toggle-selection-1.0.6.tgz#6e45b1263f2017fa0acc7d89d78b15b8bf77da32"
  integrity sha512-BiZS+C1OS8g/q2RRbJmy59xpyghNBqrr6k5L/uKBGRsTfxmu3ffiRnd8mlGPUVayg8pvfi5urfnu8TU7DVOkLQ==

ts-api-utils@^1.0.1:
  version "1.0.3"
  resolved "https://registry.npmjs.org/ts-api-utils/-/ts-api-utils-1.0.3.tgz"
  integrity sha512-wNMeqtMz5NtwpT/UZGY5alT+VoKdSsOOP/kqHFcUW1P/VRhH2wJ48+DN2WwUliNbQ976ETwDL0Ifd2VVvgonvg==

ts-interface-checker@^0.1.9:
  version "0.1.13"
  resolved "https://registry.npmjs.org/ts-interface-checker/-/ts-interface-checker-0.1.13.tgz"
  integrity sha512-Y/arvbn+rrz3JCKl9C4kVNfTfSm2/mEp5FSz5EsZSANGPSlQrpRI5M4PKF+mJnE52jOO90PnPSc3Ur3bTQw0gA==

ts-jest@^29.1.2:
  version "29.1.2"
  resolved "https://registry.yarnpkg.com/ts-jest/-/ts-jest-29.1.2.tgz#7613d8c81c43c8cb312c6904027257e814c40e09"
  integrity sha512-br6GJoH/WUX4pu7FbZXuWGKGNDuU7b8Uj77g/Sp7puZV6EXzuByl6JrECvm0MzVzSTkSHWTihsXt+5XYER5b+g==
  dependencies:
    bs-logger "0.x"
    fast-json-stable-stringify "2.x"
    jest-util "^29.0.0"
    json5 "^2.2.3"
    lodash.memoize "4.x"
    make-error "1.x"
    semver "^7.5.3"
    yargs-parser "^21.0.1"

tslib@^2.0.0, tslib@^2.0.1, tslib@^2.0.3, tslib@^2.1.0, tslib@^2.4.0:
  version "2.6.2"
  resolved "https://registry.npmjs.org/tslib/-/tslib-2.6.2.tgz"
  integrity sha512-AEYxH93jGFPn/a2iVAwW87VuUIkR1FVUKB77NwMF7nBTDkDrrT/Hpt/IrCJ0QXhW27jTBDcf5ZY7w6RiqTMw2Q==

type-check@^0.4.0, type-check@~0.4.0:
  version "0.4.0"
  resolved "https://registry.npmjs.org/type-check/-/type-check-0.4.0.tgz"
  integrity sha512-XleUoc9uwGXqjWwXaUTZAmzMcFZ5858QA2vvx1Ur5xIcixXIP+8LnFDgRplU30us6teqdlskFfu+ae4K79Ooew==
  dependencies:
    prelude-ls "^1.2.1"

type-detect@4.0.8, type-detect@^4.0.0, type-detect@^4.0.8:
  version "4.0.8"
  resolved "https://registry.yarnpkg.com/type-detect/-/type-detect-4.0.8.tgz#7646fb5f18871cfbb7749e69bd39a6388eb7450c"
  integrity sha512-0fr/mIH1dlO+x7TlcMy+bIDqKPsw/70tVyeHW787goQjhmqaZe10uwLujubK9q9Lg6Fiho1KUKDYz0Z7k7g5/g==

type-fest@^0.20.2:
  version "0.20.2"
  resolved "https://registry.npmjs.org/type-fest/-/type-fest-0.20.2.tgz"
  integrity sha512-Ne+eE4r0/iWnpAxD852z3A+N0Bt5RN//NjJwRd2VFHEmrywxf5vsZlh4R6lixl6B+wz/8d+maTSAkN1FIkI3LQ==

type-fest@^0.21.3:
  version "0.21.3"
  resolved "https://registry.npmjs.org/type-fest/-/type-fest-0.21.3.tgz"
  integrity sha512-t0rzBq87m3fVcduHDUFhKmyyX+9eo6WQjZvf51Ea/M0Q7+T374Jp1aUiyUl0GKxp8M/OETVHSDvmkyPgvX+X2w==

typescript@^5.0.2:
  version "5.2.2"
  resolved "https://registry.npmjs.org/typescript/-/typescript-5.2.2.tgz"
  integrity sha512-mI4WrpHsbCIcwT9cF4FZvr80QUeKvsUsUvKDoR+X/7XHQH98xYD8YHZg7ANtz2GtZt/CBq2QJ0thkGJMHfqc1w==

ufo@^1.3.0:
  version "1.3.2"
  resolved "https://registry.yarnpkg.com/ufo/-/ufo-1.3.2.tgz#c7d719d0628a1c80c006d2240e0d169f6e3c0496"
  integrity sha512-o+ORpgGwaYQXgqGDwd+hkS4PuZ3QnmqMMxRuajK/a38L6fTpcE5GPIfrf+L/KemFzfUpeUQc1rRS1iDBozvnFA==

unbzip2-stream@1.4.3:
  version "1.4.3"
  resolved "https://registry.yarnpkg.com/unbzip2-stream/-/unbzip2-stream-1.4.3.tgz#b0da04c4371311df771cdc215e87f2130991ace7"
  integrity sha512-mlExGW4w71ebDJviH16lQLtZS32VKqsSfk80GCfUlwT/4/hNRFsoscrF/c++9xinkMzECL1uL9DDwXqFWkruPg==
  dependencies:
    buffer "^5.2.1"
    through "^2.3.8"

undici-types@~5.26.4:
  version "5.26.5"
  resolved "https://registry.npmjs.org/undici-types/-/undici-types-5.26.5.tgz"
  integrity sha512-JlCMO+ehdEIKqlFxk6IfVoAUVmgz7cU7zD/h9XZ0qzeosSHmUJVOzSQvvYSYWXkFXC+IfLKSIffhv0sVZup6pA==

universalify@^2.0.0:
  version "2.0.1"
  resolved "https://registry.npmjs.org/universalify/-/universalify-2.0.1.tgz"
  integrity sha512-gptHNQghINnc/vTGIk0SOFGFNXw7JVrlRUtConJRlvaw6DuX0wO5Jeko9sWrMBhh+PsYAZ7oXAiOnf/UKogyiw==

update-browserslist-db@^1.0.13:
  version "1.0.13"
  resolved "https://registry.npmjs.org/update-browserslist-db/-/update-browserslist-db-1.0.13.tgz"
  integrity sha512-xebP81SNcPuNpPP3uzeW1NYXxI3rxyJzF3pD6sH4jE7o/IX+WtSpwnVU+qIsDPyk0d3hmFQ7mjqc6AtV604hbg==
  dependencies:
    escalade "^3.1.1"
    picocolors "^1.0.0"

uri-js@^4.2.2:
  version "4.4.1"
  resolved "https://registry.npmjs.org/uri-js/-/uri-js-4.4.1.tgz"
  integrity sha512-7rKUyy33Q1yc98pQ1DAmLtwX109F7TIfWlW1Ydo8Wl1ii1SeHieeh0HHfPeL2fMXK6z0s8ecKs9frCuLJvndBg==
  dependencies:
    punycode "^2.1.0"

urlpattern-polyfill@10.0.0:
  version "10.0.0"
  resolved "https://registry.yarnpkg.com/urlpattern-polyfill/-/urlpattern-polyfill-10.0.0.tgz#f0a03a97bfb03cdf33553e5e79a2aadd22cac8ec"
  integrity sha512-H/A06tKD7sS1O1X2SshBVeA5FLycRpjqiBeqGKmBwBDBy28EnRjORxTNe269KSSr5un5qyWi1iL61wLxpd+ZOg==

use-callback-ref@^1.3.0:
  version "1.3.0"
  resolved "https://registry.yarnpkg.com/use-callback-ref/-/use-callback-ref-1.3.0.tgz#772199899b9c9a50526fedc4993fc7fa1f7e32d5"
  integrity sha512-3FT9PRuRdbB9HfXhEq35u4oZkvpJ5kuYbpqhCfmiZyReuRgpnhDlbr2ZEnnuS0RrJAPn6l23xjFg9kpDM+Ms7w==
  dependencies:
    tslib "^2.0.0"

use-sidecar@^1.1.2:
  version "1.1.2"
  resolved "https://registry.yarnpkg.com/use-sidecar/-/use-sidecar-1.1.2.tgz#2f43126ba2d7d7e117aa5855e5d8f0276dfe73c2"
  integrity sha512-epTbsLuzZ7lPClpz2TyryBfztm7m+28DlEv2ZCQ3MDr5ssiwyOwGH/e5F9CkfWjJ1t4clvI58yF822/GUkjjhw==
  dependencies:
    detect-node-es "^1.1.0"
    tslib "^2.0.0"

use-sync-external-store@1.2.0:
  version "1.2.0"
  resolved "https://registry.yarnpkg.com/use-sync-external-store/-/use-sync-external-store-1.2.0.tgz#7dbefd6ef3fe4e767a0cf5d7287aacfb5846928a"
  integrity sha512-eEgnFxGQ1Ife9bzYs6VLi8/4X6CObHMw9Qr9tPY43iKwsPw8xE8+EFsf/2cFZ5S3esXgpWgtSCtLNS41F+sKPA==

util-deprecate@^1.0.2:
  version "1.0.2"
  resolved "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz"
  integrity sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw==

utrie@^1.0.2:
  version "1.0.2"
  resolved "https://registry.npmjs.org/utrie/-/utrie-1.0.2.tgz#d42fe44de9bc0119c25de7f564a6ed1b2c87a645"
  integrity sha512-1MLa5ouZiOmQzUbjbu9VmjLzn1QLXBhwpUa7kdLUQK+KQ5KA9I1vk5U4YHe/X2Ch7PYnJfWuWT+VbuxbGwljhw==
  dependencies:
    base64-arraybuffer "^1.0.2"

v8-to-istanbul@^9.0.1:
  version "9.2.0"
  resolved "https://registry.yarnpkg.com/v8-to-istanbul/-/v8-to-istanbul-9.2.0.tgz#2ed7644a245cddd83d4e087b9b33b3e62dfd10ad"
  integrity sha512-/EH/sDgxU2eGxajKdwLCDmQ4FWq+kpi3uCmBGpw1xJtnAxEjlD8j8PEiGWpCIMIs3ciNAgH0d3TTJiUkYzyZjA==
  dependencies:
    "@jridgewell/trace-mapping" "^0.3.12"
    "@types/istanbul-lib-coverage" "^2.0.1"
    convert-source-map "^2.0.0"

vite-node@1.0.1:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/vite-node/-/vite-node-1.0.1.tgz#c16c9df9b5d47b74156a6501c9db5b380d992768"
  integrity sha512-Y2Jnz4cr2azsOMMYuVPrQkp3KMnS/0WV8ezZjCy4hU7O5mUHCAVOnFmoEvs1nvix/4mYm74Len8bYRWZJMNP6g==
  dependencies:
    cac "^6.7.14"
    debug "^4.3.4"
    pathe "^1.1.1"
    picocolors "^1.0.0"
    vite "^5.0.0-beta.15 || ^5.0.0"

vite-plugin-checker@^0.6.2:
  version "0.6.2"
  resolved "https://registry.npmjs.org/vite-plugin-checker/-/vite-plugin-checker-0.6.2.tgz"
  integrity sha512-YvvvQ+IjY09BX7Ab+1pjxkELQsBd4rPhWNw8WLBeFVxu/E7O+n6VYAqNsKdK/a2luFlX/sMpoWdGFfg4HvwdJQ==
  dependencies:
    "@babel/code-frame" "^7.12.13"
    ansi-escapes "^4.3.0"
    chalk "^4.1.1"
    chokidar "^3.5.1"
    commander "^8.0.0"
    fast-glob "^3.2.7"
    fs-extra "^11.1.0"
    lodash.debounce "^4.0.8"
    lodash.pick "^4.4.0"
    npm-run-path "^4.0.1"
    semver "^7.5.0"
    strip-ansi "^6.0.0"
    tiny-invariant "^1.1.0"
    vscode-languageclient "^7.0.0"
    vscode-languageserver "^7.0.0"
    vscode-languageserver-textdocument "^1.0.1"
    vscode-uri "^3.0.2"

vite-plugin-html@^3.2.0:
  version "3.2.0"
  resolved "https://registry.yarnpkg.com/vite-plugin-html/-/vite-plugin-html-3.2.0.tgz#0d4df9900642a321a139f1c25c05195ba9d0ec79"
  integrity sha512-2VLCeDiHmV/BqqNn5h2V+4280KRgQzCFN47cst3WiNK848klESPQnzuC3okH5XHtgwHH/6s1Ho/YV6yIO0pgoQ==
  dependencies:
    "@rollup/pluginutils" "^4.2.0"
    colorette "^2.0.16"
    connect-history-api-fallback "^1.6.0"
    consola "^2.15.3"
    dotenv "^16.0.0"
    dotenv-expand "^8.0.2"
    ejs "^3.1.6"
    fast-glob "^3.2.11"
    fs-extra "^10.0.1"
    html-minifier-terser "^6.1.0"
    node-html-parser "^5.3.3"
    pathe "^0.2.0"

vite@^4.4.5:
  version "4.5.0"
  resolved "https://registry.npmjs.org/vite/-/vite-4.5.0.tgz"
  integrity sha512-ulr8rNLA6rkyFAlVWw2q5YJ91v098AFQ2R0PRFwPzREXOUJQPtFUG0t+/ZikhaOCDqFoDhN6/v8Sq0o4araFAw==
  dependencies:
    esbuild "^0.18.10"
    postcss "^8.4.27"
    rollup "^3.27.1"
  optionalDependencies:
    fsevents "~2.3.2"

"vite@^5.0.0-beta.15 || ^5.0.0", "vite@^5.0.0-beta.19 || ^5.0.0":
  version "5.0.6"
  resolved "https://registry.yarnpkg.com/vite/-/vite-5.0.6.tgz#f9e13503a4c5ccd67312c67803dec921f3bdea7c"
  integrity sha512-MD3joyAEBtV7QZPl2JVVUai6zHms3YOmLR+BpMzLlX2Yzjfcc4gTgNi09d/Rua3F4EtC8zdwPU8eQYyib4vVMQ==
  dependencies:
    esbuild "^0.19.3"
    postcss "^8.4.32"
    rollup "^4.2.0"
  optionalDependencies:
    fsevents "~2.3.3"

vitest@^1.0.1:
  version "1.0.1"
  resolved "https://registry.yarnpkg.com/vitest/-/vitest-1.0.1.tgz#3ba1307066842bc801084fa384ce0b23941b91f7"
  integrity sha512-MHsOj079S28hDsvdDvyD1pRj4dcS51EC5Vbe0xvOYX+WryP8soiK2dm8oULi+oA/8Xa/h6GoJEMTmcmBy5YM+Q==
  dependencies:
    "@vitest/expect" "1.0.1"
    "@vitest/runner" "1.0.1"
    "@vitest/snapshot" "1.0.1"
    "@vitest/spy" "1.0.1"
    "@vitest/utils" "1.0.1"
    acorn-walk "^8.3.0"
    cac "^6.7.14"
    chai "^4.3.10"
    debug "^4.3.4"
    execa "^8.0.1"
    local-pkg "^0.5.0"
    magic-string "^0.30.5"
    pathe "^1.1.1"
    picocolors "^1.0.0"
    std-env "^3.5.0"
    strip-literal "^1.3.0"
    tinybench "^2.5.1"
    tinypool "^0.8.1"
    vite "^5.0.0-beta.19 || ^5.0.0"
    vite-node "1.0.1"
    why-is-node-running "^2.2.2"

vscode-jsonrpc@6.0.0:
  version "6.0.0"
  resolved "https://registry.npmjs.org/vscode-jsonrpc/-/vscode-jsonrpc-6.0.0.tgz"
  integrity sha512-wnJA4BnEjOSyFMvjZdpiOwhSq9uDoK8e/kpRJDTaMYzwlkrhG1fwDIZI94CLsLzlCK5cIbMMtFlJlfR57Lavmg==

vscode-languageclient@^7.0.0:
  version "7.0.0"
  resolved "https://registry.npmjs.org/vscode-languageclient/-/vscode-languageclient-7.0.0.tgz"
  integrity sha512-P9AXdAPlsCgslpP9pRxYPqkNYV7Xq8300/aZDpO35j1fJm/ncize8iGswzYlcvFw5DQUx4eVk+KvfXdL0rehNg==
  dependencies:
    minimatch "^3.0.4"
    semver "^7.3.4"
    vscode-languageserver-protocol "3.16.0"

vscode-languageserver-protocol@3.16.0:
  version "3.16.0"
  resolved "https://registry.npmjs.org/vscode-languageserver-protocol/-/vscode-languageserver-protocol-3.16.0.tgz"
  integrity sha512-sdeUoAawceQdgIfTI+sdcwkiK2KU+2cbEYA0agzM2uqaUy2UpnnGHtWTHVEtS0ES4zHU0eMFRGN+oQgDxlD66A==
  dependencies:
    vscode-jsonrpc "6.0.0"
    vscode-languageserver-types "3.16.0"

vscode-languageserver-textdocument@^1.0.1:
  version "1.0.11"
  resolved "https://registry.npmjs.org/vscode-languageserver-textdocument/-/vscode-languageserver-textdocument-1.0.11.tgz"
  integrity sha512-X+8T3GoiwTVlJbicx/sIAF+yuJAqz8VvwJyoMVhwEMoEKE/fkDmrqUgDMyBECcM2A2frVZIUj5HI/ErRXCfOeA==

vscode-languageserver-types@3.16.0:
  version "3.16.0"
  resolved "https://registry.npmjs.org/vscode-languageserver-types/-/vscode-languageserver-types-3.16.0.tgz"
  integrity sha512-k8luDIWJWyenLc5ToFQQMaSrqCHiLwyKPHKPQZ5zz21vM+vIVUSvsRpcbiECH4WR88K2XZqc4ScRcZ7nk/jbeA==

vscode-languageserver@^7.0.0:
  version "7.0.0"
  resolved "https://registry.npmjs.org/vscode-languageserver/-/vscode-languageserver-7.0.0.tgz"
  integrity sha512-60HTx5ID+fLRcgdHfmz0LDZAXYEV68fzwG0JWwEPBode9NuMYTIxuYXPg4ngO8i8+Ou0lM7y6GzaYWbiDL0drw==
  dependencies:
    vscode-languageserver-protocol "3.16.0"

vscode-uri@^3.0.2:
  version "3.0.8"
  resolved "https://registry.npmjs.org/vscode-uri/-/vscode-uri-3.0.8.tgz"
  integrity sha512-AyFQ0EVmsOZOlAnxoFOGOq1SQDWAB7C6aqMGS23svWAllfOaxbuFvcT8D1i8z3Gyn8fraVeZNNmN6e9bxxXkKw==

w3c-keyname@^2.2.4:
  version "2.2.8"
  resolved "https://registry.yarnpkg.com/w3c-keyname/-/w3c-keyname-2.2.8.tgz#7b17c8c6883d4e8b86ac8aba79d39e880f8869c5"
  integrity sha512-dpojBhNsCNN7T82Tm7k26A6G9ML3NkhDsnw9n/eoxSRlVBB4CEtIQ/KTCLI2Fwf3ataSXRhYFkQi3SlnFwPvPQ==

walker@^1.0.8:
  version "1.0.8"
  resolved "https://registry.yarnpkg.com/walker/-/walker-1.0.8.tgz#bd498db477afe573dc04185f011d3ab8a8d7653f"
  integrity sha512-ts/8E8l5b7kY0vlWLewOkDXMmPdLcVV4GmOQLyxuSswIJsweeFZtAsMF7k1Nszz+TYBQrlYRmzOnr398y1JemQ==
  dependencies:
    makeerror "1.0.12"

webm-duration-fix@^1.0.4:
  version "1.0.4"
  resolved "https://registry.yarnpkg.com/webm-duration-fix/-/webm-duration-fix-1.0.4.tgz#fef235cb3d3ed3363507f705a7577dbb9fdedae6"
  integrity sha512-kvhmSmEnuohtK+j+mJswqCCM2ViKb9W8Ch0oAxcaeUvpok5CsMORQLnea+CYKDXPG6JH12H0CbRK85qhfeZLew==
  dependencies:
    buffer "^6.0.3"
    ebml-block "^1.1.2"
    events "^3.3.0"
    int64-buffer "^1.0.1"

which@^2.0.1:
  version "2.0.2"
  resolved "https://registry.npmjs.org/which/-/which-2.0.2.tgz"
  integrity sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==
  dependencies:
    isexe "^2.0.0"

why-is-node-running@^2.2.2:
  version "2.2.2"
  resolved "https://registry.yarnpkg.com/why-is-node-running/-/why-is-node-running-2.2.2.tgz#4185b2b4699117819e7154594271e7e344c9973e"
  integrity sha512-6tSwToZxTOcotxHeA+qGCq1mVzKR3CwcJGmVcY+QE8SHy6TnpFnh8PAvPNHYr7EcuVeG0QSMxtYCuO1ta/G/oA==
  dependencies:
    siginfo "^2.0.0"
    stackback "0.0.2"

wrap-ansi@^7.0.0:
  version "7.0.0"
  resolved "https://registry.yarnpkg.com/wrap-ansi/-/wrap-ansi-7.0.0.tgz#67e145cff510a6a6984bdf1152911d69d2eb9e43"
  integrity sha512-YVGIj2kamLSTxw6NsZjoBxfSwsn0ycdesmc4p+Q21c5zPuZ1pl+NfxVdxPtdHvmNVOQ6XSYG4AUtyt/Fi7D16Q==
  dependencies:
    ansi-styles "^4.0.0"
    string-width "^4.1.0"
    strip-ansi "^6.0.0"

wrappy@1:
  version "1.0.2"
  resolved "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz"
  integrity sha512-l4Sp/DRseor9wL6EvV2+TuQn63dMkPjZ/sp9XkghTEbV9KlPS1xUsZ3u7/IQO4wxtcFB4bgpQPRcR3QCvezPcQ==

write-file-atomic@^4.0.2:
  version "4.0.2"
  resolved "https://registry.yarnpkg.com/write-file-atomic/-/write-file-atomic-4.0.2.tgz#a9df01ae5b77858a027fd2e80768ee433555fcfd"
  integrity sha512-7KxauUdBmSdWnmpaGFg+ppNjKF8uNLry8LyzjauQDOVONfFLNKrKvQOxZ/VuTIcS/gge/YNahf5RIIQWTSarlg==
  dependencies:
    imurmurhash "^0.1.4"
    signal-exit "^3.0.7"

ws@8.16.0:
  version "8.16.0"
  resolved "https://registry.yarnpkg.com/ws/-/ws-8.16.0.tgz#d1cd774f36fbc07165066a60e40323eab6446fd4"
  integrity sha512-HS0c//TP7Ina87TfiPUz1rQzMhHrl/SG2guqRcTOIUYD2q8uhUdNHZYJUaQ8aTGPzCh+c6oawMKW35nFl1dxyQ==

ws@8.17.0:
  version "8.17.0"
  resolved "https://registry.yarnpkg.com/ws/-/ws-8.17.0.tgz#d145d18eca2ed25aaf791a183903f7be5e295fea"
  integrity sha512-uJq6108EgZMAl20KagGkzCKfMEjxmKvZHG7Tlq0Z6nOky7YF7aq4mOx6xK8TJ/i1LeK4Qus7INktacctDgY8Ow==

y18n@^5.0.5:
  version "5.0.8"
  resolved "https://registry.yarnpkg.com/y18n/-/y18n-5.0.8.tgz#7f4934d0f7ca8c56f95314939ddcd2dd91ce1d55"
  integrity sha512-0pfFzegeDWJHJIAmTLRP2DwHjdF5s7jo9tuztdQxAhINCdvS+3nGINqPd00AphqJR/0LhANUS6/+7SCb98YOfA==

yallist@^3.0.2:
  version "3.1.1"
  resolved "https://registry.npmjs.org/yallist/-/yallist-3.1.1.tgz"
  integrity sha512-a4UGQaWPH59mOXUYnAG2ewncQS4i4F43Tv3JoAM+s2VDAmS9NsK8GpDMLrCHPksFT7h3K6TOoUNn2pb7RoXx4g==

yallist@^4.0.0:
  version "4.0.0"
  resolved "https://registry.npmjs.org/yallist/-/yallist-4.0.0.tgz"
  integrity sha512-3wdGidZyq5PB084XLES5TpOSRA3wjXAlIWMhum2kRcv/41Sn2emQ0dycQW4uZXLejwKvg6EsvbdlVL+FYEct7A==

yaml@^2.1.1:
  version "2.3.4"
  resolved "https://registry.npmjs.org/yaml/-/yaml-2.3.4.tgz"
  integrity sha512-8aAvwVUSHpfEqTQ4w/KMlf3HcRdt50E5ODIQJBw1fQ5RL34xabzxtUlzTXVqc4rkZsPbvrXKWnABCD7kWSmocA==

yargs-parser@^21.0.1, yargs-parser@^21.1.1:
  version "21.1.1"
  resolved "https://registry.yarnpkg.com/yargs-parser/-/yargs-parser-21.1.1.tgz#9096bceebf990d21bb31fa9516e0ede294a77d35"
  integrity sha512-tVpsJW7DdjecAiFpbIB1e3qxIQsE6NoPc5/eTdrbbIC4h0LVsWhnoa3g+m2HclBIujHzsxZ4VJVA+GUuc2/LBw==

yargs@17.7.2, yargs@^17.3.1:
  version "17.7.2"
  resolved "https://registry.yarnpkg.com/yargs/-/yargs-17.7.2.tgz#991df39aca675a192b816e1e0363f9d75d2aa269"
  integrity sha512-7dSzzRQ++CKnNI/krKnYRV7JKKPUXMEh61soaHKg9mrWEhzFWhFnxPxGl+69cD1Ou63C13NUPCnmIcrvqCuM6w==
  dependencies:
    cliui "^8.0.1"
    escalade "^3.1.1"
    get-caller-file "^2.0.5"
    require-directory "^2.1.1"
    string-width "^4.2.3"
    y18n "^5.0.5"
    yargs-parser "^21.1.1"

yauzl@^2.10.0:
  version "2.10.0"
  resolved "https://registry.yarnpkg.com/yauzl/-/yauzl-2.10.0.tgz#c7eb17c93e112cb1086fa6d8e51fb0667b79a5f9"
  integrity sha512-p4a9I6X6nu6IhoGmBqAcbJy1mlC4j27vEPZX9F4L4/vZT3Lyq1VkFHw/V/PUcB9Buo+DG3iHkT0x3Qya58zc3g==
  dependencies:
    buffer-crc32 "~0.2.3"
    fd-slicer "~1.1.0"

yocto-queue@^0.1.0:
  version "0.1.0"
  resolved "https://registry.npmjs.org/yocto-queue/-/yocto-queue-0.1.0.tgz"
  integrity sha512-rVksvsnNCdJ/ohGc6xgPwyN8eheCxsiLM8mxuE/t/mOVqJewPuO1miLpTHQiRgTKCLexL4MeAFVagts7HmNZ2Q==

yocto-queue@^1.0.0:
  version "1.0.0"
  resolved "https://registry.yarnpkg.com/yocto-queue/-/yocto-queue-1.0.0.tgz#7f816433fb2cbc511ec8bf7d263c3b58a1a3c251"
  integrity sha512-9bnSc/HEW2uRy67wc+T8UwauLuPJVn28jb+GtJY16iiKWyvmYJRXVT4UamsAEGQfPohgr2q4Tq0sQbQlxTfi1g==

zod@3.22.4:
  version "3.22.4"
  resolved "https://registry.yarnpkg.com/zod/-/zod-3.22.4.tgz#f31c3a9386f61b1f228af56faa9255e845cf3fff"
  integrity sha512-iC+8Io04lddc+mVqQ9AZ7OQ2MrUKGN+oIQyq1vemgt46jwCwLfhq7/pwnBnNXXXZb8VTVLKwp9EDkx+ryxIWmg==

zustand@^4.5.2:
  version "4.5.2"
  resolved "https://registry.yarnpkg.com/zustand/-/zustand-4.5.2.tgz#fddbe7cac1e71d45413b3682cdb47b48034c3848"
  integrity sha512-2cN1tPkDVkwCy5ickKrI7vijSjPksFRfqS6237NzT0vqSsztTNnQdHw9mmN7uBdk3gceVXU0a+21jFzFzAc9+g==
  dependencies:
    use-sync-external-store "1.2.0"

```

## File: frontend/.gitignore

- Extension: 
- Language: unknown
- Size: 305 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
lerna-debug.log*

node_modules
dist
dist-ssr
*.local

# Editor directories and files
.vscode/*
!.vscode/extensions.json
.idea
.DS_Store
*.suo
*.ntvs*
*.njsproj
*.sln
*.sw?

# Env files
.env*

# Test files
src/tests/results/

```

## File: frontend/package.json

- Extension: .json
- Language: json
- Size: 2487 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "name": "screenshot-to-code",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "dev-hosted": "vite --mode prod",
    "build": "tsc && vite build",
    "build-hosted": "tsc && vite build --mode prod",
    "lint": "eslint . --ext ts,tsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview",
    "test": "jest"
  },
  "dependencies": {
    "@codemirror/lang-html": "^6.4.6",
    "@radix-ui/react-accordion": "^1.1.2",
    "@radix-ui/react-alert-dialog": "^1.0.5",
    "@radix-ui/react-checkbox": "^1.0.4",
    "@radix-ui/react-collapsible": "^1.0.3",
    "@radix-ui/react-dialog": "^1.0.5",
    "@radix-ui/react-hover-card": "^1.0.7",
    "@radix-ui/react-icons": "^1.3.0",
    "@radix-ui/react-label": "^2.0.2",
    "@radix-ui/react-popover": "^1.0.7",
    "@radix-ui/react-progress": "^1.0.3",
    "@radix-ui/react-scroll-area": "^1.0.5",
    "@radix-ui/react-select": "^2.0.0",
    "@radix-ui/react-separator": "^1.0.3",
    "@radix-ui/react-slot": "^1.0.2",
    "@radix-ui/react-switch": "^1.0.3",
    "@radix-ui/react-tabs": "^1.0.4",
    "class-variance-authority": "^0.7.0",
    "classnames": "^2.3.2",
    "clsx": "^2.0.0",
    "codemirror": "^6.0.1",
    "copy-to-clipboard": "^3.3.3",
    "html2canvas": "^1.4.1",
    "nanoid": "^5.0.7",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-dropzone": "^14.2.3",
    "react-hot-toast": "^2.4.1",
    "react-icons": "^4.12.0",
    "react-router-dom": "^6.20.1",
    "tailwind-merge": "^2.0.0",
    "tailwindcss-animate": "^1.0.7",
    "thememirror": "^2.0.1",
    "vite-plugin-checker": "^0.6.2",
    "webm-duration-fix": "^1.0.4",
    "zustand": "^4.5.2"
  },
  "devDependencies": {
    "@types/jest": "^29.5.12",
    "@types/node": "^20.9.0",
    "@types/puppeteer": "^7.0.4",
    "@types/react": "^18.2.15",
    "@types/react-dom": "^18.2.7",
    "@typescript-eslint/eslint-plugin": "^6.0.0",
    "@typescript-eslint/parser": "^6.0.0",
    "@vitejs/plugin-react": "^4.0.3",
    "autoprefixer": "^10.4.16",
    "dotenv": "^16.4.5",
    "eslint": "^8.45.0",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.3",
    "jest": "^29.7.0",
    "postcss": "^8.4.31",
    "puppeteer": "^22.6.4",
    "tailwindcss": "^3.3.5",
    "ts-jest": "^29.1.2",
    "typescript": "^5.0.2",
    "vite": "^4.4.5",
    "vite-plugin-html": "^3.2.0",
    "vitest": "^1.0.1"
  },
  "engines": {
    "node": ">=14.18.0"
  }
}

```

## File: frontend/components.json

- Extension: .json
- Language: json
- Size: 324 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "$schema": "https://ui.shadcn.com/schema.json",
  "style": "new-york",
  "rsc": false,
  "tsx": true,
  "tailwind": {
    "config": "tailwind.config.js",
    "css": "src/index.css",
    "baseColor": "slate",
    "cssVariables": true
  },
  "aliases": {
    "components": "@/components",
    "utils": "@/lib/utils"
  }
}

```

## File: frontend/tsconfig.json

- Extension: .json
- Language: json
- Size: 673 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "compilerOptions": {
    "target": "ES2020",
    "useDefineForClassFields": true,
    "lib": ["ES2020", "DOM", "DOM.Iterable"],
    "module": "ESNext",
    "skipLibCheck": true,

    /* Bundler mode */
    "moduleResolution": "bundler",
    "allowImportingTsExtensions": true,
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "react-jsx",

    /* Linting */
    "strict": true,
    "noUnusedLocals": true,
    "noUnusedParameters": true,
    "noFallthroughCasesInSwitch": true,

    "baseUrl": ".",
    "paths": {
      "@/*": ["./src/*"]
    }
  },
  "include": ["src"],
  "references": [{ "path": "./tsconfig.node.json" }]
}

```

## File: frontend/.env.example

- Extension: .example
- Language: unknown
- Size: 40 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
VITE_WS_BACKEND_URL=ws://127.0.0.1:7001

```

## File: frontend/vite.config.ts

- Extension: .ts
- Language: typescript
- Size: 842 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import path from "path";
import { defineConfig, loadEnv } from "vite";
import checker from "vite-plugin-checker";
import react from "@vitejs/plugin-react";
import { createHtmlPlugin } from "vite-plugin-html";

// https://vitejs.dev/config/
export default ({ mode }) => {
  process.env = { ...process.env, ...loadEnv(mode, process.cwd()) };
  return defineConfig({
    base: "",
    plugins: [
      react(),
      checker({ typescript: true }),
      createHtmlPlugin({
        inject: {
          data: {
            injectHead: process.env.VITE_IS_DEPLOYED
              ? '<script defer="" data-domain="screenshottocode.com" src="https://plausible.io/js/script.js"></script>'
              : "",
          },
        },
      }),
    ],
    resolve: {
      alias: {
        "@": path.resolve(__dirname, "./src"),
      },
    },
  });
};

```

## File: frontend/postcss.config.js

- Extension: .js
- Language: javascript
- Size: 80 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```javascript
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}

```

## File: frontend/src/App.tsx

- Extension: .tsx
- Language: typescript
- Size: 11684 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useEffect, useRef } from "react";
import { generateCode } from "./generateCode";
import SettingsDialog from "./components/settings/SettingsDialog";
import { AppState, CodeGenerationParams, EditorTheme, Settings } from "./types";
import { IS_RUNNING_ON_CLOUD } from "./config";
import { PicoBadge } from "./components/messages/PicoBadge";
import { OnboardingNote } from "./components/messages/OnboardingNote";
import { usePersistedState } from "./hooks/usePersistedState";
import TermsOfServiceDialog from "./components/TermsOfServiceDialog";
import { USER_CLOSE_WEB_SOCKET_CODE } from "./constants";
import { extractHistory } from "./components/history/utils";
import toast from "react-hot-toast";
import { Stack } from "./lib/stacks";
import { CodeGenerationModel } from "./lib/models";
import useBrowserTabIndicator from "./hooks/useBrowserTabIndicator";
// import TipLink from "./components/messages/TipLink";
import { useAppStore } from "./store/app-store";
import { useProjectStore } from "./store/project-store";
import Sidebar from "./components/sidebar/Sidebar";
import PreviewPane from "./components/preview/PreviewPane";
import DeprecationMessage from "./components/messages/DeprecationMessage";
import { GenerationSettings } from "./components/settings/GenerationSettings";
import StartPane from "./components/start-pane/StartPane";
import { Commit } from "./components/commits/types";
import { createCommit } from "./components/commits/utils";

function App() {
  const {
    // Inputs
    inputMode,
    setInputMode,
    isImportedFromCode,
    setIsImportedFromCode,
    referenceImages,
    setReferenceImages,

    head,
    commits,
    addCommit,
    removeCommit,
    setHead,
    appendCommitCode,
    setCommitCode,
    resetCommits,
    resetHead,

    // Outputs
    appendExecutionConsole,
    resetExecutionConsoles,
  } = useProjectStore();

  const {
    disableInSelectAndEditMode,
    setUpdateInstruction,
    appState,
    setAppState,
  } = useAppStore();

  // Settings
  const [settings, setSettings] = usePersistedState<Settings>(
    {
      openAiApiKey: null,
      openAiBaseURL: null,
      anthropicApiKey: null,
      screenshotOneApiKey: null,
      isImageGenerationEnabled: true,
      editorTheme: EditorTheme.COBALT,
      generatedCodeConfig: Stack.HTML_TAILWIND,
      codeGenerationModel: CodeGenerationModel.CLAUDE_3_5_SONNET_2024_06_20,
      // Only relevant for hosted version
      isTermOfServiceAccepted: false,
    },
    "setting"
  );

  const wsRef = useRef<WebSocket>(null);

  // Code generation model from local storage or the default value
  const model =
    settings.codeGenerationModel || CodeGenerationModel.GPT_4_VISION;

  const showBetterModelMessage =
    model !== CodeGenerationModel.GPT_4O_2024_05_13 &&
    model !== CodeGenerationModel.CLAUDE_3_5_SONNET_2024_06_20 &&
    appState === AppState.INITIAL;

  const showSelectAndEditFeature =
    (model === CodeGenerationModel.GPT_4O_2024_05_13 ||
      model === CodeGenerationModel.CLAUDE_3_5_SONNET_2024_06_20) &&
    (settings.generatedCodeConfig === Stack.HTML_TAILWIND ||
      settings.generatedCodeConfig === Stack.HTML_CSS);

  // Indicate coding state using the browser tab's favicon and title
  useBrowserTabIndicator(appState === AppState.CODING);

  // When the user already has the settings in local storage, newly added keys
  // do not get added to the settings so if it's falsy, we populate it with the default
  // value
  useEffect(() => {
    if (!settings.generatedCodeConfig) {
      setSettings((prev) => ({
        ...prev,
        generatedCodeConfig: Stack.HTML_TAILWIND,
      }));
    }
  }, [settings.generatedCodeConfig, setSettings]);

  // Functions
  const reset = () => {
    setAppState(AppState.INITIAL);
    setUpdateInstruction("");
    disableInSelectAndEditMode();
    resetExecutionConsoles();

    resetCommits();
    resetHead();

    // Inputs
    setInputMode("image");
    setReferenceImages([]);
    setIsImportedFromCode(false);
  };

  const regenerate = () => {
    if (head === null) {
      toast.error(
        "No current version set. Please contact support via chat or Github."
      );
      throw new Error("Regenerate called with no head");
    }

    // Retrieve the previous command
    const currentCommit = commits[head];
    if (currentCommit.type !== "ai_create") {
      toast.error("Only the first version can be regenerated.");
      return;
    }

    // Re-run the create
    doCreate(referenceImages, inputMode);
  };

  // Used when the user cancels the code generation
  const cancelCodeGeneration = () => {
    wsRef.current?.close?.(USER_CLOSE_WEB_SOCKET_CODE);
  };

  // Used for code generation failure as well
  const cancelCodeGenerationAndReset = (commit: Commit) => {
    // When the current commit is the first version, reset the entire app state
    if (commit.type === "ai_create") {
      reset();
    } else {
      // Otherwise, remove current commit from commits
      removeCommit(commit.hash);

      // Revert to parent commit
      const parentCommitHash = commit.parentHash;
      if (parentCommitHash) {
        setHead(parentCommitHash);
      } else {
        throw new Error("Parent commit not found");
      }

      setAppState(AppState.CODE_READY);
    }
  };

  function doGenerateCode(params: CodeGenerationParams) {
    // Reset the execution console
    resetExecutionConsoles();

    // Set the app state
    setAppState(AppState.CODING);

    // Merge settings with params
    const updatedParams = { ...params, ...settings };

    const baseCommitObject = {
      variants: [{ code: "" }, { code: "" }],
    };

    const commitInputObject =
      params.generationType === "create"
        ? {
            ...baseCommitObject,
            type: "ai_create" as const,
            parentHash: null,
            inputs: { image_url: referenceImages[0] },
          }
        : {
            ...baseCommitObject,
            type: "ai_edit" as const,
            parentHash: head,
            inputs: {
              prompt: params.history
                ? params.history[params.history.length - 1]
                : "",
            },
          };

    // Create a new commit and set it as the head
    const commit = createCommit(commitInputObject);
    addCommit(commit);
    setHead(commit.hash);

    generateCode(
      wsRef,
      updatedParams,
      // On change
      (token, variantIndex) => {
        appendCommitCode(commit.hash, variantIndex, token);
      },
      // On set code
      (code, variantIndex) => {
        setCommitCode(commit.hash, variantIndex, code);
      },
      // On status update
      (line, variantIndex) => appendExecutionConsole(variantIndex, line),
      // On cancel
      () => {
        cancelCodeGenerationAndReset(commit);
      },
      // On complete
      () => {
        setAppState(AppState.CODE_READY);
      }
    );
  }

  // Initial version creation
  function doCreate(referenceImages: string[], inputMode: "image" | "video") {
    // Reset any existing state
    reset();

    // Set the input states
    setReferenceImages(referenceImages);
    setInputMode(inputMode);

    // Kick off the code generation
    if (referenceImages.length > 0) {
      doGenerateCode({
        generationType: "create",
        image: referenceImages[0],
        inputMode,
      });
    }
  }

  // Subsequent updates
  async function doUpdate(
    updateInstruction: string,
    selectedElement?: HTMLElement
  ) {
    if (updateInstruction.trim() === "") {
      toast.error("Please include some instructions for AI on what to update.");
      return;
    }

    if (head === null) {
      toast.error(
        "No current version set. Contact support or open a Github issue."
      );
      throw new Error("Update called with no head");
    }

    let historyTree;
    try {
      historyTree = extractHistory(head, commits);
    } catch {
      toast.error(
        "Version history is invalid. This shouldn't happen. Please contact support or open a Github issue."
      );
      throw new Error("Invalid version history");
    }

    let modifiedUpdateInstruction = updateInstruction;

    // Send in a reference to the selected element if it exists
    if (selectedElement) {
      modifiedUpdateInstruction =
        updateInstruction +
        " referring to this element specifically: " +
        selectedElement.outerHTML;
    }

    const updatedHistory = [...historyTree, modifiedUpdateInstruction];

    doGenerateCode({
      generationType: "update",
      inputMode,
      image: referenceImages[0],
      history: updatedHistory,
      isImportedFromCode,
    });

    setUpdateInstruction("");
  }

  const handleTermDialogOpenChange = (open: boolean) => {
    setSettings((s) => ({
      ...s,
      isTermOfServiceAccepted: !open,
    }));
  };

  function setStack(stack: Stack) {
    setSettings((prev) => ({
      ...prev,
      generatedCodeConfig: stack,
    }));
  }

  function importFromCode(code: string, stack: Stack) {
    // Reset any existing state
    reset();

    // Set input state
    setIsImportedFromCode(true);

    // Set up this project
    setStack(stack);

    // Create a new commit and set it as the head
    const commit = createCommit({
      type: "code_create",
      parentHash: null,
      variants: [{ code }],
      inputs: null,
    });
    addCommit(commit);
    setHead(commit.hash);

    // Set the app state
    setAppState(AppState.CODE_READY);
  }

  return (
    <div className="mt-2 dark:bg-black dark:text-white">
      {IS_RUNNING_ON_CLOUD && <PicoBadge />}
      {IS_RUNNING_ON_CLOUD && (
        <TermsOfServiceDialog
          open={!settings.isTermOfServiceAccepted}
          onOpenChange={handleTermDialogOpenChange}
        />
      )}
      <div className="lg:fixed lg:inset-y-0 lg:z-40 lg:flex lg:w-96 lg:flex-col">
        <div className="flex grow flex-col gap-y-2 overflow-y-auto border-r border-gray-200 bg-white px-6 dark:bg-zinc-950 dark:text-white">
          {/* Header with access to settings */}
          <div className="flex items-center justify-between mt-10 mb-2">
            <h1 className="text-2xl ">Screenshot to Code</h1>
            <SettingsDialog settings={settings} setSettings={setSettings} />
          </div>

          {/* Generation settings like stack and model */}
          <GenerationSettings settings={settings} setSettings={setSettings} />

          {/* Show auto updated message when older models are choosen */}
          {showBetterModelMessage && <DeprecationMessage />}

          {/* Show tip link until coding is complete */}
          {/* {appState !== AppState.CODE_READY && <TipLink />} */}

          {IS_RUNNING_ON_CLOUD && !settings.openAiApiKey && <OnboardingNote />}

          {/* Rest of the sidebar when we're not in the initial state */}
          {(appState === AppState.CODING ||
            appState === AppState.CODE_READY) && (
            <Sidebar
              showSelectAndEditFeature={showSelectAndEditFeature}
              doUpdate={doUpdate}
              regenerate={regenerate}
              cancelCodeGeneration={cancelCodeGeneration}
            />
          )}
        </div>
      </div>

      <main className="py-2 lg:pl-96">
        {appState === AppState.INITIAL && (
          <StartPane
            doCreate={doCreate}
            importFromCode={importFromCode}
            settings={settings}
          />
        )}

        {(appState === AppState.CODING || appState === AppState.CODE_READY) && (
          <PreviewPane doUpdate={doUpdate} reset={reset} settings={settings} />
        )}
      </main>
    </div>
  );
}

export default App;

```

## File: frontend/src/main.tsx

- Extension: .tsx
- Language: typescript
- Size: 1186 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import ReactDOM from "react-dom/client";
import App from "./App.tsx";
import "./index.css";
import { Toaster } from "react-hot-toast";
import EvalsPage from "./components/evals/EvalsPage.tsx";
import { BrowserRouter as Router, Routes, Route } from "react-router-dom";
import PairwiseEvalsPage from "./components/evals/PairwiseEvalsPage";
import RunEvalsPage from "./components/evals/RunEvalsPage.tsx";
import BestOfNEvalsPage from "./components/evals/BestOfNEvalsPage.tsx";
import AllEvalsPage from "./components/evals/AllEvalsPage.tsx";

ReactDOM.createRoot(document.getElementById("root")!).render(
  <React.StrictMode>
    <Router>
      <Routes>
        <Route path="/" element={<App />} />
        <Route path="/all-evals" element={<AllEvalsPage />} />
        <Route path="/evals" element={<EvalsPage />} />
        <Route path="/pairwise-evals" element={<PairwiseEvalsPage />} />
        <Route path="/best-of-n-evals" element={<BestOfNEvalsPage />} />
        <Route path="/run-evals" element={<RunEvalsPage />} />
      </Routes>
    </Router>
    <Toaster toastOptions={{ className: "dark:bg-zinc-950 dark:text-white" }} />
  </React.StrictMode>
);

```

## File: frontend/src/urls.ts

- Extension: .ts
- Language: typescript
- Size: 159 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export const URLS = {
  "intro-to-video":
    "https://github.com/abi/screenshot-to-code/wiki/Screen-Recording-to-Code",
  tips: "https://git.new/s5ywP0e",
};

```

## File: frontend/src/index.css

- Extension: .css
- Language: unknown
- Size: 2280 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
@tailwind base;
@tailwind components;
@tailwind utilities;

/* Image Scanning animation */
.scanning::after {
  content: "";
  position: absolute;
  top: 0px;
  left: 0px;
  width: 5px;
  height: 100%;
  background-image: linear-gradient(
    to right,
    rgba(19, 161, 14, 0.2),
    /* Darker matrix green with full transparency */ rgba(19, 161, 14, 0.8)
      /* The same green with 80% opacity */
  );
  animation: scanning 3s ease-in-out infinite;
}

@keyframes scanning {
  0%,
  100% {
    transform: translateX(0px);
  }
  50% {
    transform: translateX(340px);
  }
}

@layer base {
  :root {
    --background: 0 0% 100%;
    --foreground: 222.2 84% 4.9%;

    --card: 0 0% 100%;
    --card-foreground: 222.2 84% 4.9%;

    --popover: 0 0% 100%;
    --popover-foreground: 222.2 84% 4.9%;

    --primary: 222.2 47.4% 11.2%;
    --primary-foreground: 210 40% 98%;

    --secondary: 210 40% 96.1%;
    --secondary-foreground: 222.2 47.4% 11.2%;

    --muted: 210 40% 96.1%;
    --muted-foreground: 215.4 16.3% 46.9%;

    --accent: 210 40% 96.1%;
    --accent-foreground: 222.2 47.4% 11.2%;

    --destructive: 0 84.2% 60.2%;
    --destructive-foreground: 210 40% 98%;

    --border: 214.3 31.8% 91.4%;
    --input: 214.3 31.8% 91.4%;
    --ring: 222.2 84% 4.9%;

    --radius: 0.5rem;
  }
  
  body.dark {
    background-color: black;
  }

  div[role="presentation"].dark {
    background-color: #09090b !important;
  }

  iframe {
    background-color: white !important; 
  }

  .dark {
    --background: 222.2 0% 0%;
    --foreground: 210 40% 98%;

    --card: 222.2 84% 4.9%;
    --card-foreground: 210 40% 98%;

    --popover: 222.2 84% 4.9%;
    --popover-foreground: 210 40% 98%;

    --primary: 210 40% 98%;
    --primary-foreground: 222.2 47.4% 11.2%;

    --secondary: 217.2 32.6% 17.5%;
    --secondary-foreground: 210 40% 98%;

    --muted: 217.2 32.6% 17.5%;
    --muted-foreground: 215 20.2% 65.1%;

    --accent: 217.2 32.6% 17.5%;
    --accent-foreground: 210 40% 98%;

    --destructive: 0 62.8% 30.6%;
    --destructive-foreground: 210 40% 98%;

    --border: 217.2 32.6% 17.5%;
    --input: 217.2 32.6% 17.5%;
    --ring: 212.7 26.8% 83.9%;
  }
}

@layer base {
  * {
    @apply border-border;
  }
  body {
    @apply bg-background text-foreground;
  }
}

```

## File: frontend/src/setupTests.ts

- Extension: .ts
- Language: typescript
- Size: 120 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
// So jest test runner can read env vars from .env file
import { config } from "dotenv";
config({ path: ".env.jest" });

```

## File: frontend/src/types.ts

- Extension: .ts
- Language: typescript
- Size: 1051 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { Stack } from "./lib/stacks";
import { CodeGenerationModel } from "./lib/models";

export enum EditorTheme {
  ESPRESSO = "espresso",
  COBALT = "cobalt",
}

export interface Settings {
  openAiApiKey: string | null;
  openAiBaseURL: string | null;
  screenshotOneApiKey: string | null;
  isImageGenerationEnabled: boolean;
  editorTheme: EditorTheme;
  generatedCodeConfig: Stack;
  codeGenerationModel: CodeGenerationModel;
  // Only relevant for hosted version
  isTermOfServiceAccepted: boolean;
  anthropicApiKey: string | null; // Added property for anthropic API key
}

export enum AppState {
  INITIAL = "INITIAL",
  CODING = "CODING",
  CODE_READY = "CODE_READY",
}

export enum ScreenRecorderState {
  INITIAL = "initial",
  RECORDING = "recording",
  FINISHED = "finished",
}

export interface CodeGenerationParams {
  generationType: "create" | "update";
  inputMode: "image" | "video";
  image: string;
  history?: string[];
  isImportedFromCode?: boolean;
}

export type FullGenerationSettings = CodeGenerationParams & Settings;

```

## File: frontend/src/vite-env.d.ts

- Extension: .ts
- Language: typescript
- Size: 38 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
/// <reference types="vite/client" />

```

## File: frontend/src/constants.ts

- Extension: .ts
- Language: typescript
- Size: 193 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
//  WebSocket protocol (RFC 6455) allows for the use of custom close codes in the range 4000-4999
export const APP_ERROR_WEB_SOCKET_CODE = 4332;
export const USER_CLOSE_WEB_SOCKET_CODE = 4333;

```

## File: frontend/src/.env.jest.example

- Extension: .example
- Language: unknown
- Size: 44 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
TEST_SCREENSHOTONE_API_KEY=
TEST_ROOT_PATH=

```

## File: frontend/src/config.ts

- Extension: .ts
- Language: typescript
- Size: 451 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
// Default to false if set to anything other than "true" or unset
export const IS_RUNNING_ON_CLOUD =
  import.meta.env.VITE_IS_DEPLOYED === "true" || false;

export const WS_BACKEND_URL =
  import.meta.env.VITE_WS_BACKEND_URL || "ws://127.0.0.1:7001";

export const HTTP_BACKEND_URL =
  import.meta.env.VITE_HTTP_BACKEND_URL || "http://127.0.0.1:7001";

export const PICO_BACKEND_FORM_SECRET =
  import.meta.env.VITE_PICO_BACKEND_FORM_SECRET || null;

```

## File: frontend/src/generateCode.ts

- Extension: .ts
- Language: typescript
- Size: 2397 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import toast from "react-hot-toast";
import { WS_BACKEND_URL } from "./config";
import {
  APP_ERROR_WEB_SOCKET_CODE,
  USER_CLOSE_WEB_SOCKET_CODE,
} from "./constants";
import { FullGenerationSettings } from "./types";

const ERROR_MESSAGE =
  "Error generating code. Check the Developer Console AND the backend logs for details. Feel free to open a Github issue.";

const CANCEL_MESSAGE = "Code generation cancelled";

type WebSocketResponse = {
  type: "chunk" | "status" | "setCode" | "error";
  value: string;
  variantIndex: number;
};

export function generateCode(
  wsRef: React.MutableRefObject<WebSocket | null>,
  params: FullGenerationSettings,
  onChange: (chunk: string, variantIndex: number) => void,
  onSetCode: (code: string, variantIndex: number) => void,
  onStatusUpdate: (status: string, variantIndex: number) => void,
  onCancel: () => void,
  onComplete: () => void
) {
  const wsUrl = `${WS_BACKEND_URL}/generate-code`;
  console.log("Connecting to backend @ ", wsUrl);

  const ws = new WebSocket(wsUrl);
  wsRef.current = ws;

  ws.addEventListener("open", () => {
    ws.send(JSON.stringify(params));
  });

  ws.addEventListener("message", async (event: MessageEvent) => {
    const response = JSON.parse(event.data) as WebSocketResponse;
    if (response.type === "chunk") {
      onChange(response.value, response.variantIndex);
    } else if (response.type === "status") {
      onStatusUpdate(response.value, response.variantIndex);
    } else if (response.type === "setCode") {
      onSetCode(response.value, response.variantIndex);
    } else if (response.type === "error") {
      console.error("Error generating code", response.value);
      toast.error(response.value);
    }
  });

  ws.addEventListener("close", (event) => {
    console.log("Connection closed", event.code, event.reason);
    if (event.code === USER_CLOSE_WEB_SOCKET_CODE) {
      toast.success(CANCEL_MESSAGE);
      onCancel();
    } else if (event.code === APP_ERROR_WEB_SOCKET_CODE) {
      console.error("Known server error", event);
      onCancel();
    } else if (event.code !== 1000) {
      console.error("Unknown server or connection error", event);
      toast.error(ERROR_MESSAGE);
      onCancel();
    } else {
      onComplete();
    }
  });

  ws.addEventListener("error", (error) => {
    console.error("WebSocket error", error);
    toast.error(ERROR_MESSAGE);
  });
}

```

## File: frontend/src/tests/qa.test.ts

- Extension: .ts
- Language: typescript
- Size: 7883 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import puppeteer, { Browser, Page, ElementHandle } from "puppeteer";
import { Stack } from "../lib/stacks";
import { CodeGenerationModel } from "../lib/models";

const TESTS_ROOT_PATH = process.env.TEST_ROOT_PATH;

// Fixtures
const FIXTURES_PATH = `${TESTS_ROOT_PATH}/fixtures`;
const SIMPLE_SCREENSHOT = FIXTURES_PATH + "/simple_button.png";
const SCREENSHOT_WITH_IMAGES = `${FIXTURES_PATH}/simple_ui_with_image.png`;

// Results
const RESULTS_DIR = `${TESTS_ROOT_PATH}/results`;

describe("e2e tests", () => {
  let browser: Browser;
  let page: Page;

  const DEBUG = true;
  const IS_HEADLESS = true;

  const stacks = Object.values(Stack).slice(0, DEBUG ? 1 : undefined);
  const models = DEBUG
    ? [
        CodeGenerationModel.GPT_4O_2024_05_13,
        // CodeGenerationModel.CLAUDE_3_5_SONNET_2024_06_20,
      ]
    : Object.values(CodeGenerationModel);

  beforeAll(async () => {
    browser = await puppeteer.launch({ headless: IS_HEADLESS });
    page = await browser.newPage();
    await page.goto("http://localhost:5173/");

    // Set screen size
    await page.setViewport({ width: 1080, height: 1024 });

    // TODO: Does this need to be moved?
    // const client = await page.createCDPSession();
    // Set download behavior path
    // await client.send("Page.setDownloadBehavior", {
    //   behavior: "allow",
    //   downloadPath: DOWNLOAD_PATH,
    // });
  });

  afterAll(async () => {
    await browser.close();
  });

  // Create tests
  models.forEach((model) => {
    stacks.forEach((stack) => {
      it(
        `Create for : ${model} & ${stack}`,
        async () => {
          const app = new App(
            page,
            stack,
            model,
            `create_screenshot_${model}_${stack}`
          );
          await app.init();
          // Generate from screenshot
          await app.uploadImage(SCREENSHOT_WITH_IMAGES);
        },
        60 * 1000
      );

      it(
        `Create from URL for : ${model} & ${stack}`,
        async () => {
          const app = new App(
            page,
            stack,
            model,
            `create_url_${model}_${stack}`
          );
          await app.init();
          // Generate from screenshot
          await app.generateFromUrl("https://a.picoapps.xyz/design-fear");
        },
        60 * 1000
      );
    });
  });

  // Update tests - for every model (doesn’t need to be repeated for each stack - fix to HTML Tailwind only)
  models.forEach((model) => {
    ["html_tailwind"].forEach((stack) => {
      it(
        `update: ${model}`,
        async () => {
          const app = new App(page, stack, model, `update_${model}_${stack}`);
          await app.init();

          // Generate from screenshot
          await app.uploadImage(SIMPLE_SCREENSHOT);
          // Regenerate works for v1
          await app.regenerate();
          // Make an update
          await app.edit("make the button background blue", "v2");
          // Make another update
          await app.edit("make the text italic", "v3");
          // Branch off v2 and make an update
          await app.clickVersion("v2");
          await app.edit("make the text yellow", "v4");
        },
        90 * 1000
      );
    });
  });

  // Start from code tests - for every model
  models.forEach((model) => {
    ["html_tailwind"].forEach((stack) => {
      it.skip(
        `Start from code: ${model}`,
        async () => {
          const app = new App(
            page,
            stack,
            model,
            `start_from_code_${model}_${stack}`
          );
          await app.init();

          await app.importFromCode();

          // Regenerate works for v1
          // await app.regenerate();
          // // Make an update
          // await app.edit("make the header blue", "v2");
          // // Make another update
          // await app.edit("make all text italic", "v3");
          // // Branch off v2 and make an update
          // await app.clickVersion("v2");
          // await app.edit("make all text red", "v4");
        },
        90 * 1000
      );
    });
  });
});

class App {
  private screenshotPathPrefix: string;
  private page: Page;
  private stack: string;
  private model: string;

  constructor(page: Page, stack: string, model: string, testId: string) {
    this.page = page;
    this.stack = stack;
    this.model = model;
    this.screenshotPathPrefix = `${RESULTS_DIR}/${testId}`;
  }

  async init() {
    await this.setupLocalStorage();
  }

  async setupLocalStorage() {
    const setting = {
      openAiApiKey: null,
      openAiBaseURL: null,
      screenshotOneApiKey: process.env.TEST_SCREENSHOTONE_API_KEY,
      isImageGenerationEnabled: true,
      editorTheme: "cobalt",
      generatedCodeConfig: this.stack,
      codeGenerationModel: this.model,
      isTermOfServiceAccepted: false,
      accessCode: null,
    };

    await this.page.evaluate((setting) => {
      localStorage.setItem("setting", JSON.stringify(setting));
    }, setting);

    // Reload the page to apply the local storage
    await this.page.reload();
  }

  async _screenshot(step: string) {
    await this.page.screenshot({
      path: `${this.screenshotPathPrefix}_${step}.png`,
    });
  }

  async _waitUntilVersionIsReady(version: string) {
    await this.page.waitForNetworkIdle();
    await this.page.waitForFunction(
      (version) => document.body.innerText.includes(version),
      {
        timeout: 30000,
      },
      version
    );
    // Wait for 3s so that the HTML and JS has time to render before screenshotting
    await new Promise((resolve) => setTimeout(resolve, 3000));
  }

  async generateFromUrl(url: string) {
    // Type in the URL
    await this.page.type('input[placeholder="Enter URL"]', url);
    await this._screenshot("typed_url");

    // Click the capture button and wait for the code to be generated
    await this.page.click("button.capture-btn");
    await this._waitUntilVersionIsReady("v1");
    await this._screenshot("url_result");
  }

  // Uploads a screenshot and generates the image
  async uploadImage(screenshotPath: string) {
    // Upload file
    const fileInput = (await this.page.$(
      ".file-input"
    )) as ElementHandle<HTMLInputElement>;
    if (!fileInput) {
      throw new Error("File input element not found");
    }
    await fileInput.uploadFile(screenshotPath);
    await this._screenshot("image_uploaded");

    // Click the generate button and wait for the code to be generated
    await this._waitUntilVersionIsReady("v1");
    await this._screenshot("image_results");
  }

  // Makes a text edit and waits for a new version
  async edit(edit: string, version: string) {
    // Type in the edit
    await this.page.type(
      'textarea[placeholder="Tell the AI what to change..."]',
      edit
    );
    await this._screenshot(`typed_${version}`);

    // Click the update button and wait for the code to be generated
    await this.page.click(".update-btn");
    await this._waitUntilVersionIsReady(version);
    await this._screenshot(`done_${version}`);
  }

  async clickVersion(version: string) {
    await this.page.evaluate((version) => {
      document.querySelectorAll("div").forEach((div) => {
        if (div.innerText.includes(version)) {
          div.click();
        }
      });
    }, version);
  }

  async regenerate() {
    await this.page.click(".regenerate-btn");
    await this._waitUntilVersionIsReady("v1");
    await this._screenshot("regenerate_results");
  }

  // Work in progress
  async importFromCode() {
    await this.page.click(".import-from-code-btn");

    await this.page.type("textarea", "<html>hello world</html>");

    await this.page.select("#output-settings-js", "HTML + Tailwind");

    await this._screenshot("typed_code");

    await this.page.click(".import-btn");

    await this._waitUntilVersionIsReady("v1");
  }
}

```

## File: frontend/src/components/UrlInputSection.tsx

- Extension: .tsx
- Language: typescript
- Size: 2200 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useState } from "react";
import { HTTP_BACKEND_URL } from "../config";
import { Button } from "./ui/button";
import { Input } from "./ui/input";
import { toast } from "react-hot-toast";

interface Props {
  screenshotOneApiKey: string | null;
  doCreate: (urls: string[], inputMode: "image" | "video") => void;
}

export function UrlInputSection({ doCreate, screenshotOneApiKey }: Props) {
  const [isLoading, setIsLoading] = useState(false);
  const [referenceUrl, setReferenceUrl] = useState("");

  async function takeScreenshot() {
    if (!screenshotOneApiKey) {
      toast.error(
        "Please add a ScreenshotOne API key in the Settings dialog. This is optional - you can also drag/drop and upload images directly.",
        { duration: 8000 }
      );
      return;
    }

    if (!referenceUrl) {
      toast.error("Please enter a URL");
      return;
    }

    if (referenceUrl) {
      try {
        setIsLoading(true);
        const response = await fetch(`${HTTP_BACKEND_URL}/api/screenshot`, {
          method: "POST",
          body: JSON.stringify({
            url: referenceUrl,
            apiKey: screenshotOneApiKey,
          }),
          headers: {
            "Content-Type": "application/json",
          },
        });

        if (!response.ok) {
          throw new Error("Failed to capture screenshot");
        }

        const res = await response.json();
        doCreate([res.url], "image");
      } catch (error) {
        console.error(error);
        toast.error(
          "Failed to capture screenshot. Look at the console and your backend logs for more details."
        );
      } finally {
        setIsLoading(false);
      }
    }
  }

  return (
    <div className="max-w-[90%] min-w-[40%] gap-y-2 flex flex-col">
      <div className="text-gray-500 text-sm">Or screenshot a URL...</div>
      <Input
        placeholder="Enter URL"
        onChange={(e) => setReferenceUrl(e.target.value)}
        value={referenceUrl}
      />
      <Button
        onClick={takeScreenshot}
        disabled={isLoading}
        className="bg-slate-400 capture-btn"
      >
        {isLoading ? "Capturing..." : "Capture"}
      </Button>
    </div>
  );
}

```

## File: frontend/src/components/ImportCodeSection.tsx

- Extension: .tsx
- Language: typescript
- Size: 1950 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useState } from "react";
import { Button } from "./ui/button";
import {
  Dialog,
  DialogContent,
  DialogDescription,
  DialogFooter,
  DialogHeader,
  DialogTitle,
  DialogTrigger,
} from "./ui/dialog";
import { Textarea } from "./ui/textarea";
import OutputSettingsSection from "./settings/OutputSettingsSection";
import toast from "react-hot-toast";
import { Stack } from "../lib/stacks";

interface Props {
  importFromCode: (code: string, stack: Stack) => void;
}

function ImportCodeSection({ importFromCode }: Props) {
  const [code, setCode] = useState("");
  const [stack, setStack] = useState<Stack | undefined>(undefined);

  const doImport = () => {
    if (code === "") {
      toast.error("Please paste in some code");
      return;
    }

    if (stack === undefined) {
      toast.error("Please select your stack");
      return;
    }

    importFromCode(code, stack);
  };
  return (
    <Dialog>
      <DialogTrigger asChild>
        <Button className="import-from-code-btn" variant="secondary">
          Import from Code
        </Button>
      </DialogTrigger>
      <DialogContent className="sm:max-w-[425px]">
        <DialogHeader>
          <DialogTitle>Paste in your HTML code</DialogTitle>
          <DialogDescription>
            Make sure that the code you're importing is valid HTML.
          </DialogDescription>
        </DialogHeader>

        <Textarea
          value={code}
          onChange={(e) => setCode(e.target.value)}
          className="w-full h-64"
        />

        <OutputSettingsSection
          stack={stack}
          setStack={(config: Stack) => setStack(config)}
          label="Stack:"
          shouldDisableUpdates={false}
        />

        <DialogFooter>
          <Button className="import-btn" type="submit" onClick={doImport}>
            Import
          </Button>
        </DialogFooter>
      </DialogContent>
    </Dialog>
  );
}

export default ImportCodeSection;

```

## File: frontend/src/components/TermsOfServiceDialog.tsx

- Extension: .tsx
- Language: typescript
- Size: 3526 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import {
  AlertDialog,
  AlertDialogAction,
  AlertDialogContent,
  AlertDialogFooter,
  AlertDialogHeader,
  AlertDialogTitle,
} from "./ui/alert-dialog";
import { Input } from "./ui/input";
import toast from "react-hot-toast";
import { PICO_BACKEND_FORM_SECRET } from "../config";

const LOGOS = ["microsoft", "amazon", "mit", "stanford", "bytedance", "baidu"];

const TermsOfServiceDialog: React.FC<{
  open: boolean;
  onOpenChange: (open: boolean) => void;
}> = ({ open, onOpenChange }) => {
  const [email, setEmail] = React.useState("");

  const onSubscribe = async () => {
    await fetch("https://backend.buildpicoapps.com/form", {
      method: "POST",
      headers: {
        "Content-Type": "application/json",
      },
      body: JSON.stringify({ email, secret: PICO_BACKEND_FORM_SECRET }),
    });
  };

  return (
    <AlertDialog open={open} onOpenChange={onOpenChange}>
      <AlertDialogContent>
        <AlertDialogHeader>
          <AlertDialogTitle className="mb-2 text-xl">
            Enter your email to get started
          </AlertDialogTitle>
        </AlertDialogHeader>

        <div className="mb-2">
          <Input
            placeholder="Email"
            value={email}
            onChange={(e) => {
              setEmail(e.target.value);
            }}
          />
        </div>
        <div className="flex flex-col space-y-3 text-sm">
          <p>
            By providing your email, you consent to receiving occasional product
            updates, and you accept the{" "}
            <a
              href="https://a.picoapps.xyz/camera-write"
              target="_blank"
              className="underline"
            >
              terms of service
            </a>
            .{" "}
          </p>

          <p>
            {" "}
            Prefer to run it yourself locally? This project is open source.{" "}
            <a
              href="https://github.com/abi/screenshot-to-code"
              target="_blank"
              className="underline"
            >
              Download the code and get started on Github.
            </a>
          </p>
        </div>

        <AlertDialogFooter>
          <AlertDialogAction
            onClick={(e) => {
              if (!email.trim() || !email.trim().includes("@")) {
                e.preventDefault();
                toast.error("Please enter your email");
              } else {
                onSubscribe();
              }
            }}
          >
            Agree & Continue
          </AlertDialogAction>
        </AlertDialogFooter>

        {/* Logos */}
        <div>
          <div
            className="mx-auto grid max-w-lg items-center gap-x-2 
          gap-y-10 sm:max-w-xl grid-cols-6 lg:mx-0 lg:max-w-none mt-10"
          >
            {LOGOS.map((companyName) => (
              <img
                key={companyName}
                className="col-span-1 max-h-12 w-full object-contain grayscale opacity-50 hover:opacity-100"
                src={`https://picoapps.xyz/logos/${companyName}.png`}
                alt={companyName}
                width={120}
                height={48}
              />
            ))}
          </div>
          <div className="text-gray-500 text-xs mt-4 text-center">
            Designers and engineers from these organizations use Screenshot to
            Code to build interfaces faster.
          </div>
        </div>
      </AlertDialogContent>
    </AlertDialog>
  );
};

export default TermsOfServiceDialog;

```

## File: frontend/src/components/ImageUpload.tsx

- Extension: .tsx
- Language: typescript
- Size: 5727 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useState, useEffect, useMemo } from "react";
import { useDropzone } from "react-dropzone";
import { toast } from "react-hot-toast";
import { URLS } from "../urls";
import ScreenRecorder from "./recording/ScreenRecorder";
import { ScreenRecorderState } from "../types";

const baseStyle = {
  flex: 1,
  width: "80%",
  margin: "0 auto",
  minHeight: "400px",
  display: "flex",
  flexDirection: "column",
  alignItems: "center",
  justifyContent: "center",
  padding: "20px",
  borderWidth: 2,
  borderRadius: 2,
  borderColor: "#eeeeee",
  borderStyle: "dashed",
  backgroundColor: "#fafafa",
  color: "#bdbdbd",
  outline: "none",
  transition: "border .24s ease-in-out",
};

const focusedStyle = {
  borderColor: "#2196f3",
};

const acceptStyle = {
  borderColor: "#00e676",
};

const rejectStyle = {
  borderColor: "#ff1744",
};

// TODO: Move to a separate file
function fileToDataURL(file: File) {
  return new Promise((resolve, reject) => {
    const reader = new FileReader();
    reader.onload = () => resolve(reader.result);
    reader.onerror = (error) => reject(error);
    reader.readAsDataURL(file);
  });
}

type FileWithPreview = {
  preview: string;
} & File;

interface Props {
  setReferenceImages: (
    referenceImages: string[],
    inputMode: "image" | "video"
  ) => void;
}

function ImageUpload({ setReferenceImages }: Props) {
  const [files, setFiles] = useState<FileWithPreview[]>([]);
  // TODO: Switch to Zustand
  const [screenRecorderState, setScreenRecorderState] =
    useState<ScreenRecorderState>(ScreenRecorderState.INITIAL);

  const { getRootProps, getInputProps, isFocused, isDragAccept, isDragReject } =
    useDropzone({
      maxFiles: 1,
      maxSize: 1024 * 1024 * 20, // 20 MB
      accept: {
        // Image formats
        "image/png": [".png"],
        "image/jpeg": [".jpeg"],
        "image/jpg": [".jpg"],
        // Video formats
        "video/quicktime": [".mov"],
        "video/mp4": [".mp4"],
        "video/webm": [".webm"],
      },
      onDrop: (acceptedFiles) => {
        // Set up the preview thumbnail images
        setFiles(
          acceptedFiles.map((file: File) =>
            Object.assign(file, {
              preview: URL.createObjectURL(file),
            })
          ) as FileWithPreview[]
        );

        // Convert images to data URLs and set the prompt images state
        Promise.all(acceptedFiles.map((file) => fileToDataURL(file)))
          .then((dataUrls) => {
            if (dataUrls.length > 0) {
              setReferenceImages(
                dataUrls.map((dataUrl) => dataUrl as string),
                (dataUrls[0] as string).startsWith("data:video")
                  ? "video"
                  : "image"
              );
            }
          })
          .catch((error) => {
            toast.error("Error reading files" + error);
            console.error("Error reading files:", error);
          });
      },
      onDropRejected: (rejectedFiles) => {
        toast.error(rejectedFiles[0].errors[0].message);
      },
    });

  // const pasteEvent = useCallback(
  //   (event: ClipboardEvent) => {
  //     const clipboardData = event.clipboardData;
  //     if (!clipboardData) return;

  //     const items = clipboardData.items;
  //     const files = [];
  //     for (let i = 0; i < items.length; i++) {
  //       const file = items[i].getAsFile();
  //       if (file && file.type.startsWith("image/")) {
  //         files.push(file);
  //       }
  //     }

  //     // Convert images to data URLs and set the prompt images state
  //     Promise.all(files.map((file) => fileToDataURL(file)))
  //       .then((dataUrls) => {
  //         if (dataUrls.length > 0) {
  //           setReferenceImages(dataUrls.map((dataUrl) => dataUrl as string));
  //         }
  //       })
  //       .catch((error) => {
  //         // TODO: Display error to user
  //         console.error("Error reading files:", error);
  //       });
  //   },
  //   [setReferenceImages]
  // );

  // TODO: Make sure we don't listen to paste events in text input components
  // useEffect(() => {
  //   window.addEventListener("paste", pasteEvent);
  // }, [pasteEvent]);

  useEffect(() => {
    return () => files.forEach((file) => URL.revokeObjectURL(file.preview));
  }, [files]); // Added files as a dependency

  const style = useMemo(
    () => ({
      ...baseStyle,
      ...(isFocused ? focusedStyle : {}),
      ...(isDragAccept ? acceptStyle : {}),
      ...(isDragReject ? rejectStyle : {}),
    }),
    [isFocused, isDragAccept, isDragReject]
  );

  return (
    <section className="container">
      {screenRecorderState === ScreenRecorderState.INITIAL && (
        /* eslint-disable-next-line @typescript-eslint/no-explicit-any */
        <div {...getRootProps({ style: style as any })}>
          <input {...getInputProps()} className="file-input" />
          <p className="text-slate-700 text-lg">
            Drag & drop a screenshot here, <br />
            or click to upload
          </p>
        </div>
      )}
      {screenRecorderState === ScreenRecorderState.INITIAL && (
        <div className="text-center text-sm text-slate-800 mt-4">
          Upload a screen recording (.mp4, .mov) or record your screen to clone
          a whole app (experimental).{" "}
          <a
            className="underline"
            href={URLS["intro-to-video"]}
            target="_blank"
          >
            Learn more.
          </a>
        </div>
      )}
      <ScreenRecorder
        screenRecorderState={screenRecorderState}
        setScreenRecorderState={setScreenRecorderState}
        generateCode={setReferenceImages}
      />
    </section>
  );
}

export default ImageUpload;

```

## File: frontend/src/components/commits/utils.ts

- Extension: .ts
- Language: typescript
- Size: 675 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { nanoid } from "nanoid";
import {
  AiCreateCommit,
  AiEditCommit,
  CodeCreateCommit,
  Commit,
} from "./types";

export function createCommit(
  commit:
    | Omit<
        AiCreateCommit,
        "hash" | "dateCreated" | "selectedVariantIndex" | "isCommitted"
      >
    | Omit<
        AiEditCommit,
        "hash" | "dateCreated" | "selectedVariantIndex" | "isCommitted"
      >
    | Omit<
        CodeCreateCommit,
        "hash" | "dateCreated" | "selectedVariantIndex" | "isCommitted"
      >
): Commit {
  const hash = nanoid();
  return {
    ...commit,
    hash,
    isCommitted: false,
    dateCreated: new Date(),
    selectedVariantIndex: 0,
  };
}

```

## File: frontend/src/components/commits/types.ts

- Extension: .ts
- Language: typescript
- Size: 700 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export type CommitHash = string;

export type Variant = {
  code: string;
};

export type BaseCommit = {
  hash: CommitHash;
  parentHash: CommitHash | null;
  dateCreated: Date;
  isCommitted: boolean;
  variants: Variant[];
  selectedVariantIndex: number;
};

export type CommitType = "ai_create" | "ai_edit" | "code_create";

export type AiCreateCommit = BaseCommit & {
  type: "ai_create";
  inputs: {
    image_url: string;
  };
};

export type AiEditCommit = BaseCommit & {
  type: "ai_edit";
  inputs: {
    prompt: string;
  };
};

export type CodeCreateCommit = BaseCommit & {
  type: "code_create";
  inputs: null;
};

export type Commit = AiCreateCommit | AiEditCommit | CodeCreateCommit;

```

## File: frontend/src/components/sidebar/Sidebar.tsx

- Extension: .tsx
- Language: typescript
- Size: 5951 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import classNames from "classnames";
import { useAppStore } from "../../store/app-store";
import { useProjectStore } from "../../store/project-store";
import { AppState } from "../../types";
import CodePreview from "../preview/CodePreview";
import Spinner from "../core/Spinner";
import KeyboardShortcutBadge from "../core/KeyboardShortcutBadge";
// import TipLink from "../messages/TipLink";
import SelectAndEditModeToggleButton from "../select-and-edit/SelectAndEditModeToggleButton";
import { Button } from "../ui/button";
import { Textarea } from "../ui/textarea";
import { useEffect, useRef } from "react";
import HistoryDisplay from "../history/HistoryDisplay";
import Variants from "../variants/Variants";

interface SidebarProps {
  showSelectAndEditFeature: boolean;
  doUpdate: (instruction: string) => void;
  regenerate: () => void;
  cancelCodeGeneration: () => void;
}

function Sidebar({
  showSelectAndEditFeature,
  doUpdate,
  regenerate,
  cancelCodeGeneration,
}: SidebarProps) {
  const textareaRef = useRef<HTMLTextAreaElement>(null);

  const { appState, updateInstruction, setUpdateInstruction } = useAppStore();

  const { inputMode, referenceImages, executionConsoles, head, commits } =
    useProjectStore();

  const viewedCode =
    head && commits[head]
      ? commits[head].variants[commits[head].selectedVariantIndex].code
      : "";

  const executionConsole =
    (head && executionConsoles[commits[head].selectedVariantIndex]) || [];

  // When coding is complete, focus on the update instruction textarea
  useEffect(() => {
    if (appState === AppState.CODE_READY && textareaRef.current) {
      textareaRef.current.focus();
    }
  }, [appState]);

  return (
    <>
      <Variants />

      {/* Show code preview only when coding */}
      {appState === AppState.CODING && (
        <div className="flex flex-col">
          {/* Speed disclaimer for video mode */}
          {inputMode === "video" && (
            <div
              className="bg-yellow-100 border-l-4 border-yellow-500 text-yellow-700
            p-2 text-xs mb-4 mt-1"
            >
              Code generation from videos can take 3-4 minutes. We do multiple
              passes to get the best result. Please be patient.
            </div>
          )}

          <div className="flex items-center gap-x-1">
            <Spinner />
            {executionConsole.slice(-1)[0]}
          </div>

          <CodePreview code={viewedCode} />

          <div className="flex w-full">
            <Button
              onClick={cancelCodeGeneration}
              className="w-full dark:text-white dark:bg-gray-700"
            >
              Cancel
            </Button>
          </div>
        </div>
      )}

      {appState === AppState.CODE_READY && (
        <div>
          <div className="grid w-full gap-2">
            <Textarea
              ref={textareaRef}
              placeholder="Tell the AI what to change..."
              onChange={(e) => setUpdateInstruction(e.target.value)}
              onKeyDown={(e) => {
                if (e.key === "Enter" && !e.shiftKey) {
                  doUpdate(updateInstruction);
                }
              }}
              value={updateInstruction}
            />
            <Button
              onClick={() => doUpdate(updateInstruction)}
              className="dark:text-white dark:bg-gray-700 update-btn"
            >
              Update <KeyboardShortcutBadge letter="enter" />
            </Button>
          </div>
          <div className="flex items-center justify-end gap-x-2 mt-2">
            <Button
              onClick={regenerate}
              className="flex items-center gap-x-2 dark:text-white dark:bg-gray-700 regenerate-btn"
            >
              🔄 Regenerate
            </Button>
            {showSelectAndEditFeature && <SelectAndEditModeToggleButton />}
          </div>
          {/* <div className="flex justify-end items-center mt-2">
            <TipLink />
          </div> */}
        </div>
      )}

      {/* Reference image display */}
      <div className="flex gap-x-2 mt-2">
        {referenceImages.length > 0 && (
          <div className="flex flex-col">
            <div
              className={classNames({
                "scanning relative": appState === AppState.CODING,
              })}
            >
              {inputMode === "image" && (
                <img
                  className="w-[340px] border border-gray-200 rounded-md"
                  src={referenceImages[0]}
                  alt="Reference"
                />
              )}
              {inputMode === "video" && (
                <video
                  muted
                  autoPlay
                  loop
                  className="w-[340px] border border-gray-200 rounded-md"
                  src={referenceImages[0]}
                />
              )}
            </div>
            <div className="text-gray-400 uppercase text-sm text-center mt-1">
              {inputMode === "video" ? "Original Video" : "Original Screenshot"}
            </div>
          </div>
        )}
        <div className="bg-gray-400 px-4 py-2 rounded text-sm hidden">
          <h2 className="text-lg mb-4 border-b border-gray-800">Console</h2>
          {Object.entries(executionConsoles).map(([index, lines]) => (
            <div key={index}>
              {lines.map((line, lineIndex) => (
                <div
                  key={`${index}-${lineIndex}`}
                  className="border-b border-gray-400 mb-2 text-gray-600 font-mono"
                >
                  <span className="font-bold mr-2">{`${index}:${
                    lineIndex + 1
                  }`}</span>
                  {line}
                </div>
              ))}
            </div>
          ))}
        </div>
      </div>

      <HistoryDisplay shouldDisableReverts={appState === AppState.CODING} />
    </>
  );
}

export default Sidebar;

```

## File: frontend/src/components/ui/alert-dialog.tsx

- Extension: .tsx
- Language: typescript
- Size: 4441 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as AlertDialogPrimitive from "@radix-ui/react-alert-dialog"

import { cn } from "@/lib/utils"
import { buttonVariants } from "@/components/ui/button"

const AlertDialog = AlertDialogPrimitive.Root

const AlertDialogTrigger = AlertDialogPrimitive.Trigger

const AlertDialogPortal = AlertDialogPrimitive.Portal

const AlertDialogOverlay = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Overlay>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Overlay>
>(({ className, ...props }, ref) => (
  <AlertDialogPrimitive.Overlay
    className={cn(
      "fixed inset-0 z-50 bg-background/80 backdrop-blur-sm data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0",
      className
    )}
    {...props}
    ref={ref}
  />
))
AlertDialogOverlay.displayName = AlertDialogPrimitive.Overlay.displayName

const AlertDialogContent = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Content>
>(({ className, ...props }, ref) => (
  <AlertDialogPortal>
    <AlertDialogOverlay />
    <AlertDialogPrimitive.Content
      ref={ref}
      className={cn(
        "fixed left-[50%] top-[50%] z-50 grid w-full max-w-lg translate-x-[-50%] translate-y-[-50%] gap-4 border bg-background p-6 shadow-lg duration-200 data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0 data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-95 data-[state=closed]:slide-out-to-left-1/2 data-[state=closed]:slide-out-to-top-[48%] data-[state=open]:slide-in-from-left-1/2 data-[state=open]:slide-in-from-top-[48%] sm:rounded-lg",
        className
      )}
      {...props}
    />
  </AlertDialogPortal>
))
AlertDialogContent.displayName = AlertDialogPrimitive.Content.displayName

const AlertDialogHeader = ({
  className,
  ...props
}: React.HTMLAttributes<HTMLDivElement>) => (
  <div
    className={cn(
      "flex flex-col space-y-2 text-center sm:text-left",
      className
    )}
    {...props}
  />
)
AlertDialogHeader.displayName = "AlertDialogHeader"

const AlertDialogFooter = ({
  className,
  ...props
}: React.HTMLAttributes<HTMLDivElement>) => (
  <div
    className={cn(
      "flex flex-col-reverse sm:flex-row sm:justify-end sm:space-x-2",
      className
    )}
    {...props}
  />
)
AlertDialogFooter.displayName = "AlertDialogFooter"

const AlertDialogTitle = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Title>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Title>
>(({ className, ...props }, ref) => (
  <AlertDialogPrimitive.Title
    ref={ref}
    className={cn("text-lg font-semibold", className)}
    {...props}
  />
))
AlertDialogTitle.displayName = AlertDialogPrimitive.Title.displayName

const AlertDialogDescription = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Description>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Description>
>(({ className, ...props }, ref) => (
  <AlertDialogPrimitive.Description
    ref={ref}
    className={cn("text-sm text-muted-foreground", className)}
    {...props}
  />
))
AlertDialogDescription.displayName =
  AlertDialogPrimitive.Description.displayName

const AlertDialogAction = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Action>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Action>
>(({ className, ...props }, ref) => (
  <AlertDialogPrimitive.Action
    ref={ref}
    className={cn(buttonVariants(), className)}
    {...props}
  />
))
AlertDialogAction.displayName = AlertDialogPrimitive.Action.displayName

const AlertDialogCancel = React.forwardRef<
  React.ElementRef<typeof AlertDialogPrimitive.Cancel>,
  React.ComponentPropsWithoutRef<typeof AlertDialogPrimitive.Cancel>
>(({ className, ...props }, ref) => (
  <AlertDialogPrimitive.Cancel
    ref={ref}
    className={cn(
      buttonVariants({ variant: "outline" }),
      "mt-2 sm:mt-0",
      className
    )}
    {...props}
  />
))
AlertDialogCancel.displayName = AlertDialogPrimitive.Cancel.displayName

export {
  AlertDialog,
  AlertDialogPortal,
  AlertDialogOverlay,
  AlertDialogTrigger,
  AlertDialogContent,
  AlertDialogHeader,
  AlertDialogFooter,
  AlertDialogTitle,
  AlertDialogDescription,
  AlertDialogAction,
  AlertDialogCancel,
}

```

## File: frontend/src/components/ui/tabs.tsx

- Extension: .tsx
- Language: typescript
- Size: 1877 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as TabsPrimitive from "@radix-ui/react-tabs"

import { cn } from "@/lib/utils"

const Tabs = TabsPrimitive.Root

const TabsList = React.forwardRef<
  React.ElementRef<typeof TabsPrimitive.List>,
  React.ComponentPropsWithoutRef<typeof TabsPrimitive.List>
>(({ className, ...props }, ref) => (
  <TabsPrimitive.List
    ref={ref}
    className={cn(
      "inline-flex h-9 items-center justify-center rounded-lg bg-muted p-1 text-muted-foreground",
      className
    )}
    {...props}
  />
))
TabsList.displayName = TabsPrimitive.List.displayName

const TabsTrigger = React.forwardRef<
  React.ElementRef<typeof TabsPrimitive.Trigger>,
  React.ComponentPropsWithoutRef<typeof TabsPrimitive.Trigger>
>(({ className, ...props }, ref) => (
  <TabsPrimitive.Trigger
    ref={ref}
    className={cn(
      "inline-flex items-center justify-center whitespace-nowrap rounded-md px-3 py-1 text-sm font-medium ring-offset-background transition-all focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 data-[state=active]:bg-background data-[state=active]:text-foreground data-[state=active]:shadow",
      className
    )}
    {...props}
  />
))
TabsTrigger.displayName = TabsPrimitive.Trigger.displayName

const TabsContent = React.forwardRef<
  React.ElementRef<typeof TabsPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof TabsPrimitive.Content>
>(({ className, ...props }, ref) => (
  <TabsPrimitive.Content
    ref={ref}
    className={cn(
      "mt-2 ring-offset-background focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2",
      className
    )}
    {...props}
  />
))
TabsContent.displayName = TabsPrimitive.Content.displayName

export { Tabs, TabsList, TabsTrigger, TabsContent }

```

## File: frontend/src/components/ui/popover.tsx

- Extension: .tsx
- Language: typescript
- Size: 1230 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as PopoverPrimitive from "@radix-ui/react-popover"

import { cn } from "@/lib/utils"

const Popover = PopoverPrimitive.Root

const PopoverTrigger = PopoverPrimitive.Trigger

const PopoverContent = React.forwardRef<
  React.ElementRef<typeof PopoverPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof PopoverPrimitive.Content>
>(({ className, align = "center", sideOffset = 4, ...props }, ref) => (
  <PopoverPrimitive.Portal>
    <PopoverPrimitive.Content
      ref={ref}
      align={align}
      sideOffset={sideOffset}
      className={cn(
        "z-50 w-72 rounded-md border bg-popover p-4 text-popover-foreground shadow-md outline-none data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0 data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-95 data-[side=bottom]:slide-in-from-top-2 data-[side=left]:slide-in-from-right-2 data-[side=right]:slide-in-from-left-2 data-[side=top]:slide-in-from-bottom-2",
        className
      )}
      {...props}
    />
  </PopoverPrimitive.Portal>
))
PopoverContent.displayName = PopoverPrimitive.Content.displayName

export { Popover, PopoverTrigger, PopoverContent }

```

## File: frontend/src/components/ui/progress.tsx

- Extension: .tsx
- Language: typescript
- Size: 778 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as ProgressPrimitive from "@radix-ui/react-progress"

import { cn } from "@/lib/utils"

const Progress = React.forwardRef<
  React.ElementRef<typeof ProgressPrimitive.Root>,
  React.ComponentPropsWithoutRef<typeof ProgressPrimitive.Root>
>(({ className, value, ...props }, ref) => (
  <ProgressPrimitive.Root
    ref={ref}
    className={cn(
      "relative h-2 w-full overflow-hidden rounded-full bg-primary/20",
      className
    )}
    {...props}
  >
    <ProgressPrimitive.Indicator
      className="h-full w-full flex-1 bg-primary transition-all"
      style={{ transform: `translateX(-${100 - (value || 0)}%)` }}
    />
  </ProgressPrimitive.Root>
))
Progress.displayName = ProgressPrimitive.Root.displayName

export { Progress }

```

## File: frontend/src/components/ui/hover-card.tsx

- Extension: .tsx
- Language: typescript
- Size: 1184 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as HoverCardPrimitive from "@radix-ui/react-hover-card"

import { cn } from "@/lib/utils"

const HoverCard = HoverCardPrimitive.Root

const HoverCardTrigger = HoverCardPrimitive.Trigger

const HoverCardContent = React.forwardRef<
  React.ElementRef<typeof HoverCardPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof HoverCardPrimitive.Content>
>(({ className, align = "center", sideOffset = 4, ...props }, ref) => (
  <HoverCardPrimitive.Content
    ref={ref}
    align={align}
    sideOffset={sideOffset}
    className={cn(
      "z-50 w-64 rounded-md border bg-popover p-4 text-popover-foreground shadow-md outline-none data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0 data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-95 data-[side=bottom]:slide-in-from-top-2 data-[side=left]:slide-in-from-right-2 data-[side=right]:slide-in-from-left-2 data-[side=top]:slide-in-from-bottom-2",
      className
    )}
    {...props}
  />
))
HoverCardContent.displayName = HoverCardPrimitive.Content.displayName

export { HoverCard, HoverCardTrigger, HoverCardContent }

```

## File: frontend/src/components/ui/scroll-area.tsx

- Extension: .tsx
- Language: typescript
- Size: 1642 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as ScrollAreaPrimitive from "@radix-ui/react-scroll-area"

import { cn } from "@/lib/utils"

const ScrollArea = React.forwardRef<
  React.ElementRef<typeof ScrollAreaPrimitive.Root>,
  React.ComponentPropsWithoutRef<typeof ScrollAreaPrimitive.Root>
>(({ className, children, ...props }, ref) => (
  <ScrollAreaPrimitive.Root
    ref={ref}
    className={cn("relative overflow-hidden", className)}
    {...props}
  >
    <ScrollAreaPrimitive.Viewport className="h-full w-full rounded-[inherit]">
      {children}
    </ScrollAreaPrimitive.Viewport>
    <ScrollBar />
    <ScrollAreaPrimitive.Corner />
  </ScrollAreaPrimitive.Root>
))
ScrollArea.displayName = ScrollAreaPrimitive.Root.displayName

const ScrollBar = React.forwardRef<
  React.ElementRef<typeof ScrollAreaPrimitive.ScrollAreaScrollbar>,
  React.ComponentPropsWithoutRef<typeof ScrollAreaPrimitive.ScrollAreaScrollbar>
>(({ className, orientation = "vertical", ...props }, ref) => (
  <ScrollAreaPrimitive.ScrollAreaScrollbar
    ref={ref}
    orientation={orientation}
    className={cn(
      "flex touch-none select-none transition-colors",
      orientation === "vertical" &&
        "h-full w-2.5 border-l border-l-transparent p-[1px]",
      orientation === "horizontal" &&
        "h-2.5 flex-col border-t border-t-transparent p-[1px]",
      className
    )}
    {...props}
  >
    <ScrollAreaPrimitive.ScrollAreaThumb className="relative flex-1 rounded-full bg-border" />
  </ScrollAreaPrimitive.ScrollAreaScrollbar>
))
ScrollBar.displayName = ScrollAreaPrimitive.ScrollAreaScrollbar.displayName

export { ScrollArea, ScrollBar }

```

## File: frontend/src/components/ui/label.tsx

- Extension: .tsx
- Language: typescript
- Size: 710 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as LabelPrimitive from "@radix-ui/react-label"
import { cva, type VariantProps } from "class-variance-authority"

import { cn } from "@/lib/utils"

const labelVariants = cva(
  "text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
)

const Label = React.forwardRef<
  React.ElementRef<typeof LabelPrimitive.Root>,
  React.ComponentPropsWithoutRef<typeof LabelPrimitive.Root> &
    VariantProps<typeof labelVariants>
>(({ className, ...props }, ref) => (
  <LabelPrimitive.Root
    ref={ref}
    className={cn(labelVariants(), className)}
    {...props}
  />
))
Label.displayName = LabelPrimitive.Root.displayName

export { Label }

```

## File: frontend/src/components/ui/accordion.tsx

- Extension: .tsx
- Language: typescript
- Size: 2008 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as AccordionPrimitive from "@radix-ui/react-accordion"
import { ChevronDownIcon } from "@radix-ui/react-icons"

import { cn } from "@/lib/utils"

const Accordion = AccordionPrimitive.Root

const AccordionItem = React.forwardRef<
  React.ElementRef<typeof AccordionPrimitive.Item>,
  React.ComponentPropsWithoutRef<typeof AccordionPrimitive.Item>
>(({ className, ...props }, ref) => (
  <AccordionPrimitive.Item
    ref={ref}
    className={cn("border-b", className)}
    {...props}
  />
))
AccordionItem.displayName = "AccordionItem"

const AccordionTrigger = React.forwardRef<
  React.ElementRef<typeof AccordionPrimitive.Trigger>,
  React.ComponentPropsWithoutRef<typeof AccordionPrimitive.Trigger>
>(({ className, children, ...props }, ref) => (
  <AccordionPrimitive.Header className="flex">
    <AccordionPrimitive.Trigger
      ref={ref}
      className={cn(
        "flex flex-1 items-center justify-between py-4 text-sm font-medium transition-all hover:underline [&[data-state=open]>svg]:rotate-180",
        className
      )}
      {...props}
    >
      {children}
      <ChevronDownIcon className="h-4 w-4 shrink-0 text-muted-foreground transition-transform duration-200" />
    </AccordionPrimitive.Trigger>
  </AccordionPrimitive.Header>
))
AccordionTrigger.displayName = AccordionPrimitive.Trigger.displayName

const AccordionContent = React.forwardRef<
  React.ElementRef<typeof AccordionPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof AccordionPrimitive.Content>
>(({ className, children, ...props }, ref) => (
  <AccordionPrimitive.Content
    ref={ref}
    className="overflow-hidden text-sm data-[state=closed]:animate-accordion-up data-[state=open]:animate-accordion-down"
    {...props}
  >
    <div className={cn("pb-4 pt-0", className)}>{children}</div>
  </AccordionPrimitive.Content>
))
AccordionContent.displayName = AccordionPrimitive.Content.displayName

export { Accordion, AccordionItem, AccordionTrigger, AccordionContent }

```

## File: frontend/src/components/ui/switch.tsx

- Extension: .tsx
- Language: typescript
- Size: 1154 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react";
import * as SwitchPrimitives from "@radix-ui/react-switch";

import { cn } from "@/lib/utils";

const Switch = React.forwardRef<
  React.ElementRef<typeof SwitchPrimitives.Root>,
  React.ComponentPropsWithoutRef<typeof SwitchPrimitives.Root>
>(({ className, ...props }, ref) => (
  <SwitchPrimitives.Root
    className={cn(
      "peer inline-flex h-5 w-9 shrink-0 cursor-pointer items-center rounded-full border-2 border-transparent shadow-sm transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 focus-visible:ring-offset-background disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=unchecked]:bg-input",
      className
    )}
    {...props}
    ref={ref}
  >
    <SwitchPrimitives.Thumb
      className={cn(
        "pointer-events-none block h-4 w-4 rounded-full bg-background shadow-lg ring-0 transition-transform data-[state=checked]:translate-x-4 data-[state=unchecked]:translate-x-0"
      )}
    />
  </SwitchPrimitives.Root>
));
Switch.displayName = SwitchPrimitives.Root.displayName;

export { Switch };

```

## File: frontend/src/components/ui/dialog.tsx

- Extension: .tsx
- Language: typescript
- Size: 3883 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as DialogPrimitive from "@radix-ui/react-dialog"
import { Cross2Icon } from "@radix-ui/react-icons"

import { cn } from "@/lib/utils"

const Dialog = DialogPrimitive.Root

const DialogTrigger = DialogPrimitive.Trigger

const DialogPortal = DialogPrimitive.Portal

const DialogClose = DialogPrimitive.Close

const DialogOverlay = React.forwardRef<
  React.ElementRef<typeof DialogPrimitive.Overlay>,
  React.ComponentPropsWithoutRef<typeof DialogPrimitive.Overlay>
>(({ className, ...props }, ref) => (
  <DialogPrimitive.Overlay
    ref={ref}
    className={cn(
      "fixed inset-0 z-50 bg-background/80 backdrop-blur-sm data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0",
      className
    )}
    {...props}
  />
))
DialogOverlay.displayName = DialogPrimitive.Overlay.displayName

const DialogContent = React.forwardRef<
  React.ElementRef<typeof DialogPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof DialogPrimitive.Content>
>(({ className, children, ...props }, ref) => (
  <DialogPortal>
    <DialogOverlay />
    <DialogPrimitive.Content
      ref={ref}
      className={cn(
        "fixed left-[50%] top-[50%] z-50 grid w-full max-w-lg translate-x-[-50%] translate-y-[-50%] gap-4 border bg-background p-6 shadow-lg duration-200 data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0 data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-95 data-[state=closed]:slide-out-to-left-1/2 data-[state=closed]:slide-out-to-top-[48%] data-[state=open]:slide-in-from-left-1/2 data-[state=open]:slide-in-from-top-[48%] sm:rounded-lg",
        className
      )}
      {...props}
    >
      {children}
      <DialogPrimitive.Close className="absolute right-4 top-4 rounded-sm opacity-70 ring-offset-background transition-opacity hover:opacity-100 focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 disabled:pointer-events-none data-[state=open]:bg-accent data-[state=open]:text-muted-foreground">
        <Cross2Icon className="h-4 w-4" />
        <span className="sr-only">Close</span>
      </DialogPrimitive.Close>
    </DialogPrimitive.Content>
  </DialogPortal>
))
DialogContent.displayName = DialogPrimitive.Content.displayName

const DialogHeader = ({
  className,
  ...props
}: React.HTMLAttributes<HTMLDivElement>) => (
  <div
    className={cn(
      "flex flex-col space-y-1.5 text-center sm:text-left",
      className
    )}
    {...props}
  />
)
DialogHeader.displayName = "DialogHeader"

const DialogFooter = ({
  className,
  ...props
}: React.HTMLAttributes<HTMLDivElement>) => (
  <div
    className={cn(
      "flex flex-col-reverse sm:flex-row sm:justify-end sm:space-x-2",
      className
    )}
    {...props}
  />
)
DialogFooter.displayName = "DialogFooter"

const DialogTitle = React.forwardRef<
  React.ElementRef<typeof DialogPrimitive.Title>,
  React.ComponentPropsWithoutRef<typeof DialogPrimitive.Title>
>(({ className, ...props }, ref) => (
  <DialogPrimitive.Title
    ref={ref}
    className={cn(
      "text-lg font-semibold leading-none tracking-tight",
      className
    )}
    {...props}
  />
))
DialogTitle.displayName = DialogPrimitive.Title.displayName

const DialogDescription = React.forwardRef<
  React.ElementRef<typeof DialogPrimitive.Description>,
  React.ComponentPropsWithoutRef<typeof DialogPrimitive.Description>
>(({ className, ...props }, ref) => (
  <DialogPrimitive.Description
    ref={ref}
    className={cn("text-sm text-muted-foreground", className)}
    {...props}
  />
))
DialogDescription.displayName = DialogPrimitive.Description.displayName

export {
  Dialog,
  DialogPortal,
  DialogOverlay,
  DialogTrigger,
  DialogClose,
  DialogContent,
  DialogHeader,
  DialogFooter,
  DialogTitle,
  DialogDescription,
}

```

## File: frontend/src/components/ui/badge.tsx

- Extension: .tsx
- Language: typescript
- Size: 1140 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import { cva, type VariantProps } from "class-variance-authority"

import { cn } from "@/lib/utils"

const badgeVariants = cva(
  "inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2",
  {
    variants: {
      variant: {
        default:
          "border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80",
        secondary:
          "border-transparent bg-secondary text-secondary-foreground hover:bg-secondary/80",
        destructive:
          "border-transparent bg-destructive text-destructive-foreground shadow hover:bg-destructive/80",
        outline: "text-foreground",
      },
    },
    defaultVariants: {
      variant: "default",
    },
  }
)

export interface BadgeProps
  extends React.HTMLAttributes<HTMLDivElement>,
    VariantProps<typeof badgeVariants> {}

function Badge({ className, variant, ...props }: BadgeProps) {
  return (
    <div className={cn(badgeVariants({ variant }), className)} {...props} />
  )
}

export { Badge, badgeVariants }

```

## File: frontend/src/components/ui/separator.tsx

- Extension: .tsx
- Language: typescript
- Size: 756 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as SeparatorPrimitive from "@radix-ui/react-separator"

import { cn } from "@/lib/utils"

const Separator = React.forwardRef<
  React.ElementRef<typeof SeparatorPrimitive.Root>,
  React.ComponentPropsWithoutRef<typeof SeparatorPrimitive.Root>
>(
  (
    { className, orientation = "horizontal", decorative = true, ...props },
    ref
  ) => (
    <SeparatorPrimitive.Root
      ref={ref}
      decorative={decorative}
      orientation={orientation}
      className={cn(
        "shrink-0 bg-border",
        orientation === "horizontal" ? "h-[1px] w-full" : "h-full w-[1px]",
        className
      )}
      {...props}
    />
  )
)
Separator.displayName = SeparatorPrimitive.Root.displayName

export { Separator }

```

## File: frontend/src/components/ui/button.tsx

- Extension: .tsx
- Language: typescript
- Size: 1848 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react";
import { Slot } from "@radix-ui/react-slot";
import { cva, type VariantProps } from "class-variance-authority";

import { cn } from "@/lib/utils";

const buttonVariants = cva(
  "inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50",
  {
    variants: {
      variant: {
        default:
          "bg-primary text-primary-foreground shadow hover:bg-primary/90",
        destructive:
          "bg-destructive text-destructive-foreground shadow-sm hover:bg-destructive/90",
        outline:
          "border border-input bg-transparent shadow-sm hover:bg-accent hover:text-accent-foreground",
        secondary:
          "bg-secondary text-secondary-foreground shadow-sm hover:bg-secondary/80",
        ghost: "hover:bg-accent hover:text-accent-foreground",
        link: "text-primary underline-offset-4 hover:underline",
      },
      size: {
        default: "h-9 px-4 py-2",
        sm: "h-8 rounded-md px-3 text-xs",
        lg: "h-10 rounded-md px-8",
        icon: "h-9 w-9",
      },
    },
    defaultVariants: {
      variant: "default",
      size: "default",
    },
  }
);

export interface ButtonProps
  extends React.ButtonHTMLAttributes<HTMLButtonElement>,
    VariantProps<typeof buttonVariants> {
  asChild?: boolean;
}

const Button = React.forwardRef<HTMLButtonElement, ButtonProps>(
  ({ className, variant, size, asChild = false, ...props }, ref) => {
    const Comp = asChild ? Slot : "button";
    return (
      <Comp
        className={cn(buttonVariants({ variant, size, className }))}
        ref={ref}
        {...props}
      />
    );
  }
);
Button.displayName = "Button";

export { Button, buttonVariants };

```

## File: frontend/src/components/ui/checkbox.tsx

- Extension: .tsx
- Language: typescript
- Size: 1029 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import * as CheckboxPrimitive from "@radix-ui/react-checkbox"
import { CheckIcon } from "@radix-ui/react-icons"

import { cn } from "@/lib/utils"

const Checkbox = React.forwardRef<
  React.ElementRef<typeof CheckboxPrimitive.Root>,
  React.ComponentPropsWithoutRef<typeof CheckboxPrimitive.Root>
>(({ className, ...props }, ref) => (
  <CheckboxPrimitive.Root
    ref={ref}
    className={cn(
      "peer h-4 w-4 shrink-0 rounded-sm border border-primary shadow focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-primary data-[state=checked]:text-primary-foreground",
      className
    )}
    {...props}
  >
    <CheckboxPrimitive.Indicator
      className={cn("flex items-center justify-center text-current")}
    >
      <CheckIcon className="h-4 w-4" />
    </CheckboxPrimitive.Indicator>
  </CheckboxPrimitive.Root>
))
Checkbox.displayName = CheckboxPrimitive.Root.displayName

export { Checkbox }

```

## File: frontend/src/components/ui/collapsible.tsx

- Extension: .tsx
- Language: typescript
- Size: 315 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as CollapsiblePrimitive from "@radix-ui/react-collapsible"

const Collapsible = CollapsiblePrimitive.Root

const CollapsibleTrigger = CollapsiblePrimitive.CollapsibleTrigger

const CollapsibleContent = CollapsiblePrimitive.CollapsibleContent

export { Collapsible, CollapsibleTrigger, CollapsibleContent }

```

## File: frontend/src/components/ui/select.tsx

- Extension: .tsx
- Language: typescript
- Size: 5637 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"
import {
  CaretSortIcon,
  CheckIcon,
  ChevronDownIcon,
  ChevronUpIcon,
} from "@radix-ui/react-icons"
import * as SelectPrimitive from "@radix-ui/react-select"

import { cn } from "@/lib/utils"

const Select = SelectPrimitive.Root

const SelectGroup = SelectPrimitive.Group

const SelectValue = SelectPrimitive.Value

const SelectTrigger = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.Trigger>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.Trigger>
>(({ className, children, ...props }, ref) => (
  <SelectPrimitive.Trigger
    ref={ref}
    className={cn(
      "flex h-9 w-full items-center justify-between whitespace-nowrap rounded-md border border-input bg-transparent px-3 py-2 text-sm shadow-sm ring-offset-background placeholder:text-muted-foreground focus:outline-none focus:ring-1 focus:ring-ring disabled:cursor-not-allowed disabled:opacity-50 [&>span]:line-clamp-1",
      className
    )}
    {...props}
  >
    {children}
    <SelectPrimitive.Icon asChild>
      <CaretSortIcon className="h-4 w-4 opacity-50" />
    </SelectPrimitive.Icon>
  </SelectPrimitive.Trigger>
))
SelectTrigger.displayName = SelectPrimitive.Trigger.displayName

const SelectScrollUpButton = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.ScrollUpButton>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.ScrollUpButton>
>(({ className, ...props }, ref) => (
  <SelectPrimitive.ScrollUpButton
    ref={ref}
    className={cn(
      "flex cursor-default items-center justify-center py-1",
      className
    )}
    {...props}
  >
    <ChevronUpIcon />
  </SelectPrimitive.ScrollUpButton>
))
SelectScrollUpButton.displayName = SelectPrimitive.ScrollUpButton.displayName

const SelectScrollDownButton = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.ScrollDownButton>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.ScrollDownButton>
>(({ className, ...props }, ref) => (
  <SelectPrimitive.ScrollDownButton
    ref={ref}
    className={cn(
      "flex cursor-default items-center justify-center py-1",
      className
    )}
    {...props}
  >
    <ChevronDownIcon />
  </SelectPrimitive.ScrollDownButton>
))
SelectScrollDownButton.displayName =
  SelectPrimitive.ScrollDownButton.displayName

const SelectContent = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.Content>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.Content>
>(({ className, children, position = "popper", ...props }, ref) => (
  <SelectPrimitive.Portal>
    <SelectPrimitive.Content
      ref={ref}
      className={cn(
        "relative z-50 max-h-96 min-w-[8rem] overflow-hidden rounded-md border bg-popover text-popover-foreground shadow-md data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:fade-out-0 data-[state=open]:fade-in-0 data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-95 data-[side=bottom]:slide-in-from-top-2 data-[side=left]:slide-in-from-right-2 data-[side=right]:slide-in-from-left-2 data-[side=top]:slide-in-from-bottom-2",
        position === "popper" &&
          "data-[side=bottom]:translate-y-1 data-[side=left]:-translate-x-1 data-[side=right]:translate-x-1 data-[side=top]:-translate-y-1",
        className
      )}
      position={position}
      {...props}
    >
      <SelectScrollUpButton />
      <SelectPrimitive.Viewport
        className={cn(
          "p-1",
          position === "popper" &&
            "h-[var(--radix-select-trigger-height)] w-full min-w-[var(--radix-select-trigger-width)]"
        )}
      >
        {children}
      </SelectPrimitive.Viewport>
      <SelectScrollDownButton />
    </SelectPrimitive.Content>
  </SelectPrimitive.Portal>
))
SelectContent.displayName = SelectPrimitive.Content.displayName

const SelectLabel = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.Label>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.Label>
>(({ className, ...props }, ref) => (
  <SelectPrimitive.Label
    ref={ref}
    className={cn("px-2 py-1.5 text-sm font-semibold", className)}
    {...props}
  />
))
SelectLabel.displayName = SelectPrimitive.Label.displayName

const SelectItem = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.Item>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.Item>
>(({ className, children, ...props }, ref) => (
  <SelectPrimitive.Item
    ref={ref}
    className={cn(
      "relative flex w-full cursor-default select-none items-center rounded-sm py-1.5 pl-2 pr-8 text-sm outline-none focus:bg-accent focus:text-accent-foreground data-[disabled]:pointer-events-none data-[disabled]:opacity-50",
      className
    )}
    {...props}
  >
    <span className="absolute right-2 flex h-3.5 w-3.5 items-center justify-center">
      <SelectPrimitive.ItemIndicator>
        <CheckIcon className="h-4 w-4" />
      </SelectPrimitive.ItemIndicator>
    </span>
    <SelectPrimitive.ItemText>{children}</SelectPrimitive.ItemText>
  </SelectPrimitive.Item>
))
SelectItem.displayName = SelectPrimitive.Item.displayName

const SelectSeparator = React.forwardRef<
  React.ElementRef<typeof SelectPrimitive.Separator>,
  React.ComponentPropsWithoutRef<typeof SelectPrimitive.Separator>
>(({ className, ...props }, ref) => (
  <SelectPrimitive.Separator
    ref={ref}
    className={cn("-mx-1 my-1 h-px bg-muted", className)}
    {...props}
  />
))
SelectSeparator.displayName = SelectPrimitive.Separator.displayName

export {
  Select,
  SelectGroup,
  SelectValue,
  SelectTrigger,
  SelectContent,
  SelectLabel,
  SelectItem,
  SelectSeparator,
  SelectScrollUpButton,
  SelectScrollDownButton,
}

```

## File: frontend/src/components/ui/textarea.tsx

- Extension: .tsx
- Language: typescript
- Size: 732 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"

import { cn } from "@/lib/utils"

export interface TextareaProps
  extends React.TextareaHTMLAttributes<HTMLTextAreaElement> {}

const Textarea = React.forwardRef<HTMLTextAreaElement, TextareaProps>(
  ({ className, ...props }, ref) => {
    return (
      <textarea
        className={cn(
          "flex min-h-[60px] w-full rounded-md border border-input bg-transparent px-3 py-2 text-sm shadow-sm placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:cursor-not-allowed disabled:opacity-50",
          className
        )}
        ref={ref}
        {...props}
      />
    )
  }
)
Textarea.displayName = "Textarea"

export { Textarea }

```

## File: frontend/src/components/ui/input.tsx

- Extension: .tsx
- Language: typescript
- Size: 801 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import * as React from "react"

import { cn } from "@/lib/utils"

export interface InputProps
  extends React.InputHTMLAttributes<HTMLInputElement> {}

const Input = React.forwardRef<HTMLInputElement, InputProps>(
  ({ className, type, ...props }, ref) => {
    return (
      <input
        type={type}
        className={cn(
          "flex h-9 w-full rounded-md border border-input bg-transparent px-3 py-1 text-sm shadow-sm transition-colors file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:cursor-not-allowed disabled:opacity-50",
          className
        )}
        ref={ref}
        {...props}
      />
    )
  }
)
Input.displayName = "Input"

export { Input }

```

## File: frontend/src/components/settings/GenerationSettings.tsx

- Extension: .tsx
- Language: typescript
- Size: 981 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import { useAppStore } from "../../store/app-store";
import { AppState, Settings } from "../../types";
import OutputSettingsSection from "./OutputSettingsSection";
import { Stack } from "../../lib/stacks";

interface GenerationSettingsProps {
  settings: Settings;
  setSettings: React.Dispatch<React.SetStateAction<Settings>>;
}

export const GenerationSettings: React.FC<GenerationSettingsProps> = ({
  settings,
  setSettings,
}) => {
  const { appState } = useAppStore();

  function setStack(stack: Stack) {
    setSettings((prev: Settings) => ({
      ...prev,
      generatedCodeConfig: stack,
    }));
  }

  const shouldDisableUpdates =
    appState === AppState.CODING || appState === AppState.CODE_READY;

  return (
    <div className="flex flex-col gap-y-2">
      <OutputSettingsSection
        stack={settings.generatedCodeConfig}
        setStack={setStack}
        shouldDisableUpdates={shouldDisableUpdates}
      />
    </div>
  );
};

```

## File: frontend/src/components/settings/OutputSettingsSection.tsx

- Extension: .tsx
- Language: typescript
- Size: 1698 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import {
  Select,
  SelectContent,
  SelectGroup,
  SelectItem,
  SelectTrigger,
} from "../ui/select";
import { Badge } from "../ui/badge";
import { Stack, STACK_DESCRIPTIONS } from "../../lib/stacks";
import StackLabel from "../core/StackLabel";

interface Props {
  stack: Stack | undefined;
  setStack: (config: Stack) => void;
  label?: string;
  shouldDisableUpdates?: boolean;
}

function OutputSettingsSection({
  stack,
  setStack,
  label = "Generating:",
  shouldDisableUpdates = false,
}: Props) {
  return (
    <div className="flex flex-col gap-y-2 justify-between text-sm">
      <div className="grid grid-cols-3 items-center gap-4">
        <span>{label}</span>
        <Select
          value={stack}
          onValueChange={(value: string) => setStack(value as Stack)}
          disabled={shouldDisableUpdates}
        >
          <SelectTrigger className="col-span-2" id="output-settings-js">
            {stack ? <StackLabel stack={stack} /> : "Select a stack"}
          </SelectTrigger>
          <SelectContent>
            <SelectGroup>
              {Object.values(Stack).map((stack) => (
                <SelectItem key={stack} value={stack}>
                  <div className="flex items-center">
                    <StackLabel stack={stack} />
                    {STACK_DESCRIPTIONS[stack].inBeta && (
                      <Badge className="ml-2" variant="secondary">
                        Beta
                      </Badge>
                    )}
                  </div>
                </SelectItem>
              ))}
            </SelectGroup>
          </SelectContent>
        </Select>
      </div>
    </div>
  );
}

export default OutputSettingsSection;

```

## File: frontend/src/components/settings/SettingsDialog.tsx

- Extension: .tsx
- Language: typescript
- Size: 8205 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import {
  Dialog,
  DialogClose,
  DialogContent,
  DialogFooter,
  DialogHeader,
  DialogTitle,
  DialogTrigger,
} from "@/components/ui/dialog";
import { FaCog } from "react-icons/fa";
import { EditorTheme, Settings } from "../../types";
import { Switch } from "../ui/switch";
import { Label } from "../ui/label";
import { Input } from "../ui/input";
import { Select, SelectContent, SelectItem, SelectTrigger } from "../ui/select";
import { capitalize } from "../../lib/utils";
import { IS_RUNNING_ON_CLOUD } from "../../config";
import {
  Accordion,
  AccordionContent,
  AccordionItem,
  AccordionTrigger,
} from "../ui/accordion";

interface Props {
  settings: Settings;
  setSettings: React.Dispatch<React.SetStateAction<Settings>>;
}

function SettingsDialog({ settings, setSettings }: Props) {
  const handleThemeChange = (theme: EditorTheme) => {
    setSettings((s) => ({
      ...s,
      editorTheme: theme,
    }));
  };

  return (
    <Dialog>
      <DialogTrigger>
        <FaCog />
      </DialogTrigger>
      <DialogContent>
        <DialogHeader>
          <DialogTitle className="mb-4">Settings</DialogTitle>
        </DialogHeader>

        <div className="flex items-center space-x-2">
          <Label htmlFor="image-generation">
            <div>DALL-E Placeholder Image Generation</div>
            <div className="font-light mt-2 text-xs">
              More fun with it but if you want to save money, turn it off.
            </div>
          </Label>
          <Switch
            id="image-generation"
            checked={settings.isImageGenerationEnabled}
            onCheckedChange={() =>
              setSettings((s) => ({
                ...s,
                isImageGenerationEnabled: !s.isImageGenerationEnabled,
              }))
            }
          />
        </div>
        <div className="flex flex-col space-y-6">
          <div>
            <Label htmlFor="openai-api-key">
              <div>OpenAI API key</div>
              <div className="font-light mt-1 mb-2 text-xs leading-relaxed">
                Only stored in your browser. Never stored on servers. Overrides
                your .env config.
              </div>
            </Label>

            <Input
              id="openai-api-key"
              placeholder="OpenAI API key"
              value={settings.openAiApiKey || ""}
              onChange={(e) =>
                setSettings((s) => ({
                  ...s,
                  openAiApiKey: e.target.value,
                }))
              }
            />
          </div>

          {!IS_RUNNING_ON_CLOUD && (
            <div>
              <Label htmlFor="openai-api-key">
                <div>OpenAI Base URL (optional)</div>
                <div className="font-light mt-2 leading-relaxed">
                  Replace with a proxy URL if you don't want to use the default.
                </div>
              </Label>

              <Input
                id="openai-base-url"
                placeholder="OpenAI Base URL"
                value={settings.openAiBaseURL || ""}
                onChange={(e) =>
                  setSettings((s) => ({
                    ...s,
                    openAiBaseURL: e.target.value,
                  }))
                }
              />
            </div>
          )}

          <div>
            <Label htmlFor="anthropic-api-key">
              <div>Anthropic API key</div>
              <div className="font-light mt-1 text-xs leading-relaxed">
                Only stored in your browser. Never stored on servers. Overrides
                your .env config.
              </div>
            </Label>

            <Input
              id="anthropic-api-key"
              placeholder="Anthropic API key"
              value={settings.anthropicApiKey || ""}
              onChange={(e) =>
                setSettings((s) => ({
                  ...s,
                  anthropicApiKey: e.target.value,
                }))
              }
            />
          </div>

          <Accordion type="single" collapsible className="w-full">
            <AccordionItem value="item-1">
              <AccordionTrigger>Screenshot by URL Config</AccordionTrigger>
              <AccordionContent>
                <Label htmlFor="screenshot-one-api-key">
                  <div className="leading-normal font-normal text-xs">
                    If you want to use URLs directly instead of taking the
                    screenshot yourself, add a ScreenshotOne API key.{" "}
                    <a
                      href="https://screenshotone.com?via=screenshot-to-code"
                      className="underline"
                      target="_blank"
                    >
                      Get 100 screenshots/mo for free.
                    </a>
                  </div>
                </Label>

                <Input
                  id="screenshot-one-api-key"
                  className="mt-2"
                  placeholder="ScreenshotOne API key"
                  value={settings.screenshotOneApiKey || ""}
                  onChange={(e) =>
                    setSettings((s) => ({
                      ...s,
                      screenshotOneApiKey: e.target.value,
                    }))
                  }
                />
              </AccordionContent>
            </AccordionItem>
          </Accordion>

          <Accordion type="single" collapsible className="w-full">
            <AccordionItem value="item-1">
              <AccordionTrigger>Theme Settings</AccordionTrigger>
              <AccordionContent className="space-y-4 flex flex-col">
                <div className="flex items-center justify-between">
                  <Label htmlFor="app-theme">
                    <div>App Theme</div>
                  </Label>
                  <div>
                    <button
                      className="flex rounded-md border border-input bg-transparent px-3 py-1 text-sm shadow-sm transition-colors file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:cursor-not-allowed disabled:opacity-50t"
                      onClick={() => {
                        document
                          .querySelector("div.mt-2")
                          ?.classList.toggle("dark"); // enable dark mode for sidebar
                        document.body.classList.toggle("dark");
                        document
                          .querySelector('div[role="presentation"]')
                          ?.classList.toggle("dark"); // enable dark mode for upload container
                      }}
                    >
                      Toggle dark mode
                    </button>
                  </div>
                </div>
                <div className="flex items-center justify-between">
                  <Label htmlFor="editor-theme">
                    <div>
                      Code Editor Theme - requires page refresh to update
                    </div>
                  </Label>
                  <div>
                    <Select // Use the custom Select component here
                      name="editor-theme"
                      value={settings.editorTheme}
                      onValueChange={(value) =>
                        handleThemeChange(value as EditorTheme)
                      }
                    >
                      <SelectTrigger className="w-[180px]">
                        {capitalize(settings.editorTheme)}
                      </SelectTrigger>
                      <SelectContent>
                        <SelectItem value="cobalt">Cobalt</SelectItem>
                        <SelectItem value="espresso">Espresso</SelectItem>
                      </SelectContent>
                    </Select>
                  </div>
                </div>
              </AccordionContent>
            </AccordionItem>
          </Accordion>
        </div>

        <DialogFooter>
          <DialogClose>Save</DialogClose>
        </DialogFooter>
      </DialogContent>
    </Dialog>
  );
}

export default SettingsDialog;

```

## File: frontend/src/components/evals/BestOfNEvalsPage.tsx

- Extension: .tsx
- Language: typescript
- Size: 8374 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React, { useState } from "react";
import { HTTP_BACKEND_URL } from "../../config";
import { Dialog, DialogContent, DialogTrigger } from "../ui/dialog";

interface Eval {
  input: string;
  outputs: string[];
}

// Update type to support any folder as winner
type Outcome = number | "tie" | null;

interface BestOfNEvalsResponse {
  evals: Eval[];
  folder_names: string[];
}

function BestOfNEvalsPage() {
  const [evals, setEvals] = React.useState<Eval[]>([]);
  const [outcomes, setOutcomes] = React.useState<Outcome[]>([]);
  const [folderNames, setFolderNames] = useState<string[]>([]);
  // Track multiple folder paths
  const [folderPaths, setFolderPaths] = useState<string[]>([""]);
  const [isLoading, setIsLoading] = useState(false);
  const [selectedHtml, setSelectedHtml] = useState<string>("");

  // Add/remove folder input fields
  const addFolderInput = () => {
    setFolderPaths([...folderPaths, ""]);
  };

  const removeFolderInput = (index: number) => {
    setFolderPaths(folderPaths.filter((_, i) => i !== index));
  };

  const updateFolderPath = (index: number, value: string) => {
    const newPaths = [...folderPaths];
    newPaths[index] = value;
    setFolderPaths(newPaths);
  };

  // Calculate statistics for N models
  const calculateStats = () => {
    const totalVotes = outcomes.filter((o) => o !== null).length;
    const stats = folderNames.map((name, index) => {
      const wins = outcomes.filter((o) => o === index).length;
      const percentage = totalVotes
        ? ((wins / totalVotes) * 100).toFixed(2)
        : "0.00";
      return { name, wins, percentage };
    });
    const ties = outcomes.filter((o) => o === "tie").length;
    const tiePercentage = totalVotes
      ? ((ties / totalVotes) * 100).toFixed(2)
      : "0.00";

    return { stats, ties, tiePercentage, totalVotes };
  };

  const loadEvals = async () => {
    if (folderPaths.some((path) => !path)) {
      alert("Please enter all folder paths");
      return;
    }

    setIsLoading(true);
    try {
      const queryParams = new URLSearchParams();
      folderPaths.forEach((path, index) => {
        queryParams.append(
          `folder${index + 1}`,
          `/Users/abi/Downloads/${path}`
        );
      });

      const response = await fetch(
        `${HTTP_BACKEND_URL}/best-of-n-evals?${queryParams}`
      );
      const data: BestOfNEvalsResponse = await response.json();

      console.log(data.evals);

      setEvals(data.evals);
      setOutcomes(new Array(data.evals.length).fill(null));
      setFolderNames(data.folder_names);
    } catch (error) {
      console.error("Error loading evals:", error);
      alert(
        "Error loading evals. Please check the folder paths and try again."
      );
    } finally {
      setIsLoading(false);
    }
  };

  const handleVote = (index: number, outcome: Outcome) => {
    const newOutcomes = [...outcomes];
    newOutcomes[index] = outcome;
    setOutcomes(newOutcomes);
  };

  const stats = calculateStats();

  return (
    <div className="mx-auto">
      <div className="flex flex-col items-center justify-center w-full py-4 bg-zinc-950 text-white">
        <div className="flex flex-col gap-4 mb-4 w-full max-w-2xl px-4">
          {folderPaths.map((path, index) => (
            <div key={index} className="flex gap-2">
              <input
                type="text"
                value={path}
                onChange={(e) => updateFolderPath(index, e.target.value)}
                placeholder="Enter folder name in Downloads"
                className="w-full px-4 py-2 rounded text-black"
              />
              {index > 0 && (
                <button
                  onClick={() => removeFolderInput(index)}
                  className="bg-red-500 px-3 py-2 rounded"
                >
                  ✕
                </button>
              )}
            </div>
          ))}

          <button
            onClick={addFolderInput}
            className="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded"
          >
            Add Model
          </button>

          <button
            onClick={loadEvals}
            disabled={isLoading}
            className="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded disabled:bg-blue-300"
          >
            {isLoading ? "Loading..." : "Start Comparison"}
          </button>
        </div>

        {evals.length > 0 && (
          <>
            <span className="text-2xl font-semibold">
              Total votes: {stats.totalVotes}
            </span>
            <div className="text-lg mt-2">
              {stats.stats.map((stat, i) => (
                <span key={i}>
                  {stat.name}: {stat.wins} ({stat.percentage}%) |{" "}
                </span>
              ))}
              <span>
                Ties: {stats.ties} ({stats.tiePercentage}%)
              </span>
            </div>
          </>
        )}
      </div>

      <div className="flex flex-col gap-y-8 mt-4 mx-auto justify-center">
        {evals.map((e, index) => (
          <div className="flex flex-col justify-center" key={index}>
            <h2 className="font-bold text-lg ml-4 mb-2">
              Comparison {index + 1}
            </h2>

            <div className="w-full flex justify-center mb-4">
              <div className="w-1/2 max-w-2xl p-1 border">
                <img src={e.input} alt={`Input for comparison ${index}`} />
              </div>
            </div>

            <div className="flex flex-wrap gap-4 justify-center px-4">
              {e.outputs.map((output, outputIndex) => (
                <div
                  className={`w-full sm:w-[calc(50%-1rem)] p-1 border ${
                    outcomes[index] === outputIndex
                      ? "border-green-500 border-4"
                      : ""
                  }`}
                  key={outputIndex}
                >
                  <div className="relative">
                    <div className="absolute top-0 left-0 bg-black text-white px-2 py-1 z-10">
                      {folderNames[outputIndex]}
                    </div>
                    <iframe
                      srcDoc={output}
                      className="w-full aspect-[3/2] transform scale-100"
                      style={{ minHeight: "400px" }}
                    ></iframe>
                    <Dialog>
                      <DialogTrigger asChild>
                        <button
                          className="absolute top-2 right-2 bg-blue-500 text-white px-2 py-1 rounded text-sm"
                          onClick={() => setSelectedHtml(output)}
                        >
                          Full Screen
                        </button>
                      </DialogTrigger>
                      <DialogContent className="w-[95vw] max-w-[95vw] h-[95vh] max-h-[95vh]">
                        <div className="absolute top-2 left-2 bg-black text-white px-2 py-1 z-10">
                          {folderNames[outputIndex]}
                        </div>
                        <iframe
                          srcDoc={selectedHtml}
                          className="w-full h-full"
                        ></iframe>
                      </DialogContent>
                    </Dialog>
                  </div>
                </div>
              ))}
            </div>

            <div className="flex flex-wrap justify-center gap-2 mt-4 px-4">
              {folderNames.map((name, i) => (
                <button
                  key={i}
                  className={`px-4 py-2 rounded ${
                    outcomes[index] === i
                      ? "bg-green-500 text-white"
                      : "bg-gray-200 hover:bg-gray-300"
                  }`}
                  onClick={() => handleVote(index, i)}
                >
                  {name} Wins
                </button>
              ))}
              <button
                className={`px-4 py-2 rounded ${
                  outcomes[index] === "tie"
                    ? "bg-green-500 text-white"
                    : "bg-gray-200 hover:bg-gray-300"
                }`}
                onClick={() => handleVote(index, "tie")}
              >
                Tie
              </button>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

export default BestOfNEvalsPage;

```

## File: frontend/src/components/evals/AllEvalsPage.tsx

- Extension: .tsx
- Language: typescript
- Size: 2064 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { Link } from "react-router-dom";

function AllEvalsPage() {
  return (
    <div className="flex flex-col items-center justify-center min-h-screen bg-gray-50">
      <div className="max-w-md w-full space-y-8 p-8">
        <h1 className="text-3xl font-bold text-center text-gray-900">
          Evals Dashboard
        </h1>
        <div className="space-y-4">
          <Link
            to="/run-evals"
            className="block w-full p-4 bg-white rounded-lg shadow hover:shadow-md transition-shadow border border-gray-200"
          >
            <h2 className="text-xl font-semibold text-gray-800">Run Evals</h2>
            <p className="text-gray-600">
              Generate evaluations for multiple models
            </p>
          </Link>

          <Link
            to="/pairwise-evals"
            className="block w-full p-4 bg-white rounded-lg shadow hover:shadow-md transition-shadow border border-gray-200"
          >
            <h2 className="text-xl font-semibold text-gray-800">
              Pairwise Comparison
            </h2>
            <p className="text-gray-600">
              Compare outputs from two different models
            </p>
          </Link>

          <Link
            to="/best-of-n-evals"
            className="block w-full p-4 bg-white rounded-lg shadow hover:shadow-md transition-shadow border border-gray-200"
          >
            <h2 className="text-xl font-semibold text-gray-800">Best of N</h2>
            <p className="text-gray-600">
              Compare multiple model outputs side by side
            </p>
          </Link>

          <Link
            to="/evals"
            className="block w-full p-4 bg-white rounded-lg shadow hover:shadow-md transition-shadow border border-gray-200"
          >
            <h2 className="text-xl font-semibold text-gray-800">
              Single Model Eval
            </h2>
            <p className="text-gray-600">Score outputs from a single model</p>
          </Link>
        </div>
      </div>
    </div>
  );
}

export default AllEvalsPage;

```

## File: frontend/src/components/evals/EvalsPage.tsx

- Extension: .tsx
- Language: typescript
- Size: 9108 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React, { useState } from "react";
import { HTTP_BACKEND_URL } from "../../config";
import RatingPicker from "./RatingPicker";

interface Eval {
  input: string;
  outputs: string[];
}

interface RatingCriteria {
  stackAdherence: number;
  accuracy: number;
  codeQuality: number;
  mobileResponsiveness: number;
  imageCaptionQuality: number;
}

interface OutputDisplay {
  showSource: boolean;
}

function EvalsPage() {
  const [evals, setEvals] = React.useState<Eval[]>([]);
  const [ratings, setRatings] = React.useState<RatingCriteria[]>([]);
  const [folderPath, setFolderPath] = useState("");
  const [isLoading, setIsLoading] = useState(false);
  const [outputDisplays, setOutputDisplays] = useState<OutputDisplay[]>([]);

  const calculateScores = () => {
    if (ratings.length === 0) {
      return {
        stackAdherence: { total: 0, max: 0, percentage: "0.00" },
        accuracy: { total: 0, max: 0, percentage: "0.00" },
        codeQuality: { total: 0, max: 0, percentage: "0.00" },
        mobileResponsiveness: { total: 0, max: 0, percentage: "0.00" },
        imageCaptionQuality: { total: 0, max: 0, percentage: "0.00" },
      };
    }

    const maxPerCriterion = ratings.length * 5; // max score of 5 * number of evals

    const totals = ratings.reduce(
      (acc, rating) => ({
        stackAdherence: acc.stackAdherence + rating.stackAdherence,
        accuracy: acc.accuracy + rating.accuracy,
        codeQuality: acc.codeQuality + rating.codeQuality,
        mobileResponsiveness:
          acc.mobileResponsiveness + rating.mobileResponsiveness,
        imageCaptionQuality:
          acc.imageCaptionQuality + rating.imageCaptionQuality,
      }),
      {
        stackAdherence: 0,
        accuracy: 0,
        codeQuality: 0,
        mobileResponsiveness: 0,
        imageCaptionQuality: 0,
      }
    );

    return Object.entries(totals).reduce(
      (acc, [key, total]) => ({
        ...acc,
        [key]: {
          total,
          max: maxPerCriterion,
          percentage: ((total / maxPerCriterion) * 100).toFixed(2),
        },
      }),
      {} as Record<
        keyof RatingCriteria,
        { total: number; max: number; percentage: string }
      >
    );
  };

  const loadEvals = async () => {
    if (!folderPath) {
      alert("Please enter a folder path");
      return;
    }

    setIsLoading(true);
    try {
      const queryParams = new URLSearchParams({
        folder: `/Users/abi/Downloads/${folderPath}`,
      });

      const response = await fetch(`${HTTP_BACKEND_URL}/evals?${queryParams}`);
      const data = await response.json();

      console.log(data);

      setEvals(data);
      setRatings(
        data.map(() => ({
          stackAdherence: 0,
          accuracy: 0,
          codeQuality: 0,
          mobileResponsiveness: 0,
          imageCaptionQuality: 0,
        }))
      );
    } catch (error) {
      console.error("Error loading evals:", error);
      alert("Error loading evals. Please check the folder path and try again.");
    } finally {
      setIsLoading(false);
    }
  };

  const updateRating = (
    index: number,
    criterion: keyof RatingCriteria,
    value: number
  ) => {
    const newRatings = [...ratings];
    newRatings[index] = {
      ...newRatings[index],
      [criterion]: value,
    };
    setRatings(newRatings);
  };

  const toggleSourceView = (evalIndex: number) => {
    const newDisplays = [...outputDisplays];
    if (!newDisplays[evalIndex]) {
      newDisplays[evalIndex] = { showSource: false };
    }
    newDisplays[evalIndex] = { showSource: !newDisplays[evalIndex].showSource };
    setOutputDisplays(newDisplays);
  };

  return (
    <div className="mx-auto">
      <div className="flex flex-col items-center justify-center w-full py-4 bg-zinc-950 text-white">
        <div className="flex flex-col gap-4 mb-4 w-full max-w-2xl px-4">
          <input
            type="text"
            value={folderPath}
            onChange={(e) => setFolderPath(e.target.value)}
            placeholder="Enter folder name in Downloads"
            className="w-full px-4 py-2 rounded text-black"
          />
          <button
            onClick={loadEvals}
            disabled={isLoading}
            className="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded disabled:bg-blue-300"
          >
            {isLoading ? "Loading..." : "Load Evals"}
          </button>
        </div>

        {evals.length > 0 && (
          <div className="flex flex-col items-center gap-2 text-lg">
            <h2 className="text-2xl font-semibold mb-2">Scores by Category</h2>
            {Object.entries(calculateScores()).map(([criterion, score]) => (
              <div key={criterion} className="flex gap-x-4 items-center">
                <span className="min-w-[200px] text-right capitalize">
                  {criterion.replace(/([A-Z])/g, " $1").trim()}:
                </span>
                <span>
                  {score.total} / {score.max} ({score.percentage}%)
                </span>
              </div>
            ))}
          </div>
        )}
      </div>

      <div className="flex flex-col gap-y-8 mt-4 mx-auto justify-center">
        {evals.map((e, index) => (
          <div className="flex flex-col justify-center" key={index}>
            <h2 className="font-bold text-lg ml-4">Evaluation {index + 1}</h2>
            <div className="flex gap-x-2 justify-center ml-4">
              <div className="w-1/2 p-1 border">
                <img src={e.input} alt={`Input for eval ${index}`} />
              </div>
              {e.outputs.map((output, outputIndex) => (
                <div className="w-1/2 p-1 border" key={outputIndex}>
                  <div className="mb-2">
                    <button
                      onClick={() => toggleSourceView(index)}
                      className="bg-gray-500 hover:bg-gray-600 text-white px-2 py-1 rounded text-sm"
                    >
                      {outputDisplays[index]?.showSource ? "Show Preview" : "Show Source"}
                    </button>
                  </div>
                  {outputDisplays[index]?.showSource ? (
                    <pre className="whitespace-pre-wrap text-sm p-2 bg-gray-100 max-h-[480px] overflow-auto">
                      {output}
                    </pre>
                  ) : (
                    <iframe
                      srcDoc={output}
                      className="w-[1200px] h-[800px] transform scale-[0.60]"
                      style={{ transformOrigin: "top left" }}
                    ></iframe>
                  )}
                </div>
              ))}
            </div>
            <div className="ml-8 mt-4 space-y-2">
              <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div className="flex items-center gap-x-4">
                  <span className="min-w-[160px]">Stack Adherence:</span>
                  <RatingPicker
                    onSelect={(rating) =>
                      updateRating(index, "stackAdherence", rating)
                    }
                    maxRating={5}
                    value={ratings[index].stackAdherence}
                  />
                </div>
                <div className="flex items-center gap-x-4">
                  <span className="min-w-[160px]">Accuracy:</span>
                  <RatingPicker
                    onSelect={(rating) =>
                      updateRating(index, "accuracy", rating)
                    }
                    maxRating={5}
                    value={ratings[index].accuracy}
                  />
                </div>
                <div className="flex items-center gap-x-4">
                  <span className="min-w-[160px]">Code Quality:</span>
                  <RatingPicker
                    onSelect={(rating) =>
                      updateRating(index, "codeQuality", rating)
                    }
                    maxRating={5}
                    value={ratings[index].codeQuality}
                  />
                </div>
                <div className="flex items-center gap-x-4">
                  <span className="min-w-[160px]">Mobile Responsiveness:</span>
                  <RatingPicker
                    onSelect={(rating) =>
                      updateRating(index, "mobileResponsiveness", rating)
                    }
                    maxRating={5}
                    value={ratings[index].mobileResponsiveness}
                  />
                </div>
                <div className="flex items-center gap-x-4">
                  <span className="min-w-[160px]">Image Caption Quality:</span>
                  <RatingPicker
                    onSelect={(rating) =>
                      updateRating(index, "imageCaptionQuality", rating)
                    }
                    maxRating={5}
                    value={ratings[index].imageCaptionQuality}
                  />
                </div>
              </div>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

export default EvalsPage;

```

## File: frontend/src/components/evals/RunEvalsPage.tsx

- Extension: .tsx
- Language: typescript
- Size: 5597 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useState, useEffect } from "react";
import { Button } from "../ui/button";
import { HTTP_BACKEND_URL } from "../../config";
import { BsCheckLg } from "react-icons/bs";

interface ModelResponse {
  models: string[];
  stacks: string[];
}

function RunEvalsPage() {
  const [isRunning, setIsRunning] = useState(false);
  const [models, setModels] = useState<string[]>([]);
  const [stacks, setStacks] = useState<string[]>([]);
  const [selectedModels, setSelectedModels] = useState<string[]>([]);
  const [selectedStack, setSelectedStack] = useState<string>("html_tailwind");

  useEffect(() => {
    const fetchModels = async () => {
      const response = await fetch(`${HTTP_BACKEND_URL}/models`);
      const data: ModelResponse = await response.json();
      setModels(data.models);
      setStacks(data.stacks);
    };
    fetchModels();
  }, []);

  useEffect(() => {
    return () => {
      document.title = "Screenshot to Code";
    };
  }, []);

  const runEvals = async () => {
    try {
      setIsRunning(true);
      document.title = "Running Evals...";

      const response = await fetch(`${HTTP_BACKEND_URL}/run_evals`, {
        method: "POST",
        headers: {
          "Content-Type": "application/json",
        },
        body: JSON.stringify({
          models: selectedModels,
          stack: selectedStack,
        }),
      });

      if (!response.ok) {
        throw new Error("Failed to run evals");
      }

      const outputFiles = await response.json();
      console.log("Generated files:", outputFiles);

      document.title = "✓ Evals Complete";
    } catch (error) {
      console.error("Error running evals:", error);
      document.title = "❌ Eval Error";
      setTimeout(() => {
        document.title = "Screenshot to Code";
      }, 5000);
    } finally {
      setIsRunning(false);
    }
  };

  const handleModelToggle = (model: string) => {
    setSelectedModels((prev) => {
      if (prev.includes(model)) {
        return prev.filter((m) => m !== model);
      }
      return [...prev, model];
    });
  };

  const handleSelectAll = () => {
    setSelectedModels(models);
  };

  return (
    <div className="flex flex-col items-center justify-center min-h-screen">
      <h1 className="text-2xl font-bold mb-8">Run Evaluations</h1>

      <div className="max-w-md text-center mb-8 text-gray-600">
        <p className="mb-2">
          Evaluation inputs will be read from:
          <code className="block bg-gray-100 p-1 mt-1 rounded">
            backend/evals_data/inputs
          </code>
        </p>
        <p>
          Results will be saved to:
          <code className="block bg-gray-100 p-1 mt-1 rounded">
            backend/evals_data/outputs
          </code>
        </p>
      </div>

      <div className="space-y-4 w-full max-w-md">
        <div>
          <label className="block text-gray-700 text-sm font-bold mb-2">
            Select Models
          </label>
          <div className="border rounded-md p-2 space-y-2">
            {models.map((model) => (
              <div
                key={model}
                className={`flex items-center justify-between p-2 rounded cursor-pointer hover:bg-gray-50 ${
                  selectedModels.includes(model)
                    ? "bg-blue-50 border border-blue-200"
                    : ""
                }`}
                onClick={() => handleModelToggle(model)}
              >
                <span className="text-sm">{model}</span>
                {selectedModels.includes(model) ? (
                  <BsCheckLg className="h-4 w-4 text-blue-500" />
                ) : (
                  <div className="h-4 w-4 border rounded-sm" />
                )}
              </div>
            ))}
          </div>
          <div className="flex justify-between mt-2">
            <p className="text-sm text-gray-500">
              Selected: {selectedModels.length} model
              {selectedModels.length !== 1 ? "s" : ""}
            </p>
            <div className="space-x-2">
              {selectedModels.length < models.length && (
                <Button
                  variant="ghost"
                  size="sm"
                  onClick={handleSelectAll}
                  className="text-sm text-gray-500 hover:text-gray-700"
                >
                  Select all
                </Button>
              )}
              {selectedModels.length > 0 && (
                <Button
                  variant="ghost"
                  size="sm"
                  onClick={() => setSelectedModels([])}
                  className="text-sm text-gray-500 hover:text-gray-700"
                >
                  Clear all
                </Button>
              )}
            </div>
          </div>
        </div>

        <div>
          <label className="block text-gray-700 text-sm font-bold mb-2">
            Select Stack
          </label>
          <select
            value={selectedStack}
            onChange={(e) => setSelectedStack(e.target.value)}
            className="shadow border rounded w-full py-2 px-3 text-gray-700"
            required
          >
            {stacks.map((stack) => (
              <option key={stack} value={stack}>
                {stack}
              </option>
            ))}
          </select>
        </div>
      </div>

      <Button
        onClick={runEvals}
        disabled={isRunning || selectedModels.length === 0}
        className="w-48 mt-6"
      >
        {isRunning ? "Running Evals..." : "Run Evals"}
      </Button>
    </div>
  );
}

export default RunEvalsPage;

```

## File: frontend/src/components/evals/PairwiseEvalsPage.tsx

- Extension: .tsx
- Language: typescript
- Size: 7561 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React, { useState } from "react";
import { HTTP_BACKEND_URL } from "../../config";
import { Dialog, DialogContent, DialogTrigger } from "../ui/dialog";

interface Eval {
  input: string;
  outputs: string[];
}

type Outcome = "left" | "right" | "tie" | null;

interface PairwiseEvalsResponse {
  evals: Eval[];
  folder1_name: string;
  folder2_name: string;
}

function PairwiseEvalsPage() {
  const [evals, setEvals] = React.useState<Eval[]>([]);
  const [outcomes, setOutcomes] = React.useState<Outcome[]>([]);
  const [folderNames, setFolderNames] = useState<{
    left: string;
    right: string;
  }>({
    left: "",
    right: "",
  });
  const [folder1Path, setFolder1Path] = useState("");
  const [folder2Path, setFolder2Path] = useState("");
  const [isLoading, setIsLoading] = useState(false);
  const [selectedHtml, setSelectedHtml] = useState<string>("");

  // Calculate statistics
  const totalVotes = outcomes.filter((o) => o !== null).length;
  const leftWins = outcomes.filter((o) => o === "left").length;
  const rightWins = outcomes.filter((o) => o === "right").length;
  const ties = outcomes.filter((o) => o === "tie").length;
  // Calculate percentages
  const leftPercentage = totalVotes
    ? ((leftWins / totalVotes) * 100).toFixed(2)
    : "0.00";
  const rightPercentage = totalVotes
    ? ((rightWins / totalVotes) * 100).toFixed(2)
    : "0.00";
  const tiePercentage = totalVotes
    ? ((ties / totalVotes) * 100).toFixed(2)
    : "0.00";

  const loadEvals = async () => {
    if (!folder1Path || !folder2Path) {
      alert("Please enter both folder paths");
      return;
    }

    setIsLoading(true);
    try {
      const queryParams = new URLSearchParams({
        folder1: `/Users/abi/Downloads/${folder1Path}`,
        folder2: `/Users/abi/Downloads/${folder2Path}`,
      });

      const response = await fetch(
        `${HTTP_BACKEND_URL}/pairwise-evals?${queryParams}`
      );
      const data: PairwiseEvalsResponse = await response.json();

      setEvals(data.evals);
      setOutcomes(new Array(data.evals.length).fill(null));
      setFolderNames({
        left: data.folder1_name,
        right: data.folder2_name,
      });
    } catch (error) {
      console.error("Error loading evals:", error);
      alert(
        "Error loading evals. Please check the folder paths and try again."
      );
    } finally {
      setIsLoading(false);
    }
  };

  const handleVote = (index: number, outcome: Outcome) => {
    const newOutcomes = [...outcomes];
    newOutcomes[index] = outcome;
    setOutcomes(newOutcomes);
  };

  return (
    <div className="mx-auto">
      <div className="flex flex-col items-center justify-center w-full py-4 bg-zinc-950 text-white">
        <div className="flex flex-col gap-4 mb-4 w-full max-w-2xl px-4">
          <input
            type="text"
            value={folder1Path}
            onChange={(e) => setFolder1Path(e.target.value)}
            placeholder="Enter folder name in Downloads"
            className="w-full px-4 py-2 rounded text-black"
          />
          <input
            type="text"
            value={folder2Path}
            onChange={(e) => setFolder2Path(e.target.value)}
            placeholder="Enter folder name in Downloads"
            className="w-full px-4 py-2 rounded text-black"
          />
          <button
            onClick={loadEvals}
            disabled={isLoading}
            className="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded disabled:bg-blue-300"
          >
            {isLoading ? "Loading..." : "Start Comparison"}
          </button>
        </div>

        {evals.length > 0 && (
          <>
            <span className="text-2xl font-semibold">
              Total votes: {totalVotes}
            </span>
            <div className="text-lg mt-2">
              <span>
                {folderNames.left}: {leftWins} ({leftPercentage}%) |{" "}
              </span>
              <span>
                {folderNames.right}: {rightWins} ({rightPercentage}%) |{" "}
              </span>
              <span>
                Ties: {ties} ({tiePercentage}%)
              </span>
            </div>
          </>
        )}
      </div>

      <div className="flex flex-col gap-y-8 mt-4 mx-auto justify-center">
        {evals.map((e, index) => (
          <div className="flex flex-col justify-center" key={index}>
            <h2 className="font-bold text-lg ml-4 mb-2">
              Comparison {index + 1}
            </h2>

            <div className="w-full flex justify-center mb-4">
              <div className="w-1/2 p-1 border">
                <img src={e.input} alt={`Input for comparison ${index}`} />
              </div>
            </div>

            <div className="flex gap-x-4 justify-center">
              {e.outputs.slice(0, 2).map((output, outputIndex) => (
                <div
                  className={`w-1/2 p-1 border ${
                    outcomes[index] === (outputIndex === 0 ? "left" : "right")
                      ? "border-green-500 border-4"
                      : ""
                  }`}
                  key={outputIndex}
                >
                  <div className="relative">
                    <iframe
                      srcDoc={output}
                      className="w-[1200px] h-[800px] transform scale-[0.55]"
                      style={{ transformOrigin: "top left" }}
                    ></iframe>
                    <Dialog>
                      <DialogTrigger asChild>
                        <button
                          className="absolute top-2 right-2 bg-blue-500 text-white px-2 py-1 rounded text-sm"
                          onClick={() => setSelectedHtml(output)}
                        >
                          Full Screen
                        </button>
                      </DialogTrigger>
                      <DialogContent className="w-[95vw] max-w-[95vw] h-[95vh] max-h-[95vh]">
                        <iframe
                          srcDoc={selectedHtml}
                          className="w-[1400px] h-[800px] transform scale-[0.90]"
                        ></iframe>
                      </DialogContent>
                    </Dialog>
                  </div>
                </div>
              ))}
            </div>

            <div className="flex justify-center gap-x-4 mt-4">
              <button
                className={`px-4 py-2 rounded ${
                  outcomes[index] === "left"
                    ? "bg-green-500 text-white"
                    : "bg-gray-200 hover:bg-gray-300"
                }`}
                onClick={() => handleVote(index, "left")}
              >
                Left Wins
              </button>
              <button
                className={`px-4 py-2 rounded ${
                  outcomes[index] === "tie"
                    ? "bg-green-500 text-white"
                    : "bg-gray-200 hover:bg-gray-300"
                }`}
                onClick={() => handleVote(index, "tie")}
              >
                Tie
              </button>
              <button
                className={`px-4 py-2 rounded ${
                  outcomes[index] === "right"
                    ? "bg-green-500 text-white"
                    : "bg-gray-200 hover:bg-gray-300"
                }`}
                onClick={() => handleVote(index, "right")}
              >
                Right Wins
              </button>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

export default PairwiseEvalsPage;

```

## File: frontend/src/components/evals/RatingPicker.tsx

- Extension: .tsx
- Language: typescript
- Size: 737 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
interface RatingPickerProps {
  onSelect: (rating: number) => void;
  maxRating?: number;
  value?: number;
}

function RatingPicker({
  onSelect,
  maxRating = 5,
  value = 0,
}: RatingPickerProps) {
  return (
    <div className="flex gap-x-2">
      {Array.from({ length: maxRating }, (_, i) => i + 1).map((rating) => (
        <button
          key={rating}
          onClick={() => onSelect(rating)}
          className={`w-8 h-8 rounded-full border border-gray-300 
            ${
              value === rating
                ? "bg-blue-500 text-white"
                : "hover:bg-blue-500 hover:text-white"
            }`}
        >
          {rating}
        </button>
      ))}
    </div>
  );
}

export default RatingPicker;

```

## File: frontend/src/components/select-and-edit/utils.ts

- Extension: .ts
- Language: typescript
- Size: 537 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export function removeHighlight(element: HTMLElement) {
  element.style.outline = "";
  element.style.backgroundColor = "";
  return element;
}

export function addHighlight(element: HTMLElement) {
  element.style.outline = "2px dashed #1846db";
  element.style.backgroundColor = "#bfcbf5";
  return element;
}

export function getAdjustedCoordinates(
  x: number,
  y: number,
  rect: DOMRect | undefined
) {
  const offsetX = rect ? rect.left : 0;
  const offsetY = rect ? rect.top : 0;

  return { x: x + offsetX, y: y + offsetY };
}

```

## File: frontend/src/components/select-and-edit/EditPopup.tsx

- Extension: .tsx
- Language: typescript
- Size: 4472 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React, { useEffect, useRef, useState } from "react";
import { Textarea } from "../ui/textarea";
import { Button } from "../ui/button";
import { addHighlight, getAdjustedCoordinates, removeHighlight } from "./utils";
import { useAppStore } from "../../store/app-store";
import KeyboardShortcutBadge from "../core/KeyboardShortcutBadge";

interface EditPopupProps {
  event: MouseEvent | null;
  iframeRef: React.RefObject<HTMLIFrameElement>;
  doUpdate: (updateInstruction: string, selectedElement?: HTMLElement) => void;
}

const EditPopup: React.FC<EditPopupProps> = ({
  event,
  iframeRef,
  doUpdate,
}) => {
  // App state
  const { inSelectAndEditMode } = useAppStore();

  // Create a wrapper ref to store inSelectAndEditMode so the value is not stale
  // in a event listener
  const inSelectAndEditModeRef = useRef(inSelectAndEditMode);

  // Update the ref whenever the state changes
  useEffect(() => {
    inSelectAndEditModeRef.current = inSelectAndEditMode;
  }, [inSelectAndEditMode]);

  // Popup state
  const [popupVisible, setPopupVisible] = useState(false);
  const [popupPosition, setPopupPosition] = useState({ x: 0, y: 0 });

  // Edit state
  const [selectedElement, setSelectedElement] = useState<
    HTMLElement | undefined
  >(undefined);
  const [updateText, setUpdateText] = useState("");

  // Textarea ref for focusing
  const textareaRef = useRef<HTMLTextAreaElement | null>(null);

  function onUpdate(updateText: string) {
    // Perform the update
    doUpdate(
      updateText,
      selectedElement ? removeHighlight(selectedElement) : selectedElement
    );

    // Unselect the element
    setSelectedElement(undefined);

    // Hide the popup
    setPopupVisible(false);
  }

  // Remove highlight and reset state when not in select and edit mode
  useEffect(() => {
    if (!inSelectAndEditMode) {
      if (selectedElement) removeHighlight(selectedElement);
      setSelectedElement(undefined);
      setPopupVisible(false);
    }
  }, [inSelectAndEditMode, selectedElement]);

  // Handle the click event
  useEffect(() => {
    // Return if not in select and edit mode
    if (!inSelectAndEditModeRef.current || !event) {
      return;
    }

    // Prevent default to avoid issues like label clicks triggering textareas, etc.
    event.preventDefault();

    const targetElement = event.target as HTMLElement;

    // Return if no target element
    if (!targetElement) return;

    // Highlight and set the selected element
    setSelectedElement((prev) => {
      // Remove style from previous element
      if (prev) {
        removeHighlight(prev);
      }
      return addHighlight(targetElement);
    });

    // Calculate adjusted coordinates
    const adjustedCoordinates = getAdjustedCoordinates(
      event.clientX,
      event.clientY,
      iframeRef.current?.getBoundingClientRect()
    );

    // Show the popup at the click position
    setPopupVisible(true);
    setPopupPosition({ x: adjustedCoordinates.x, y: adjustedCoordinates.y });

    // Reset the update text
    setUpdateText("");

    // Focus the textarea
    textareaRef.current?.focus();
  }, [event, iframeRef]);

  // Focus the textarea when the popup is visible (we can't do this only when handling the click event
  // because the textarea is not rendered yet)
  // We need to also do it in the click event because popupVisible doesn't change values in that event
  useEffect(() => {
    if (popupVisible) {
      textareaRef.current?.focus();
    }
  }, [popupVisible]);

  if (!popupVisible) return;

  return (
    <div
      className="absolute bg-white dark:bg-gray-800 p-4 border border-gray-300 dark:border-gray-600 rounded shadow-lg w-60"
      style={{ top: popupPosition.y, left: popupPosition.x }}
    >
      <Textarea
        ref={textareaRef}
        value={updateText}
        onChange={(e) => setUpdateText(e.target.value)}
        placeholder="Tell the AI what to change about this element..."
        className="dark:bg-gray-700 dark:text-white"
        onKeyDown={(e) => {
          if (e.key === "Enter") {
            e.preventDefault();
            onUpdate(updateText);
          }
        }}
      />
      <div className="flex justify-end mt-2">
        <Button
          className="dark:bg-gray-700 dark:text-white"
          onClick={() => onUpdate(updateText)}
        >
          Update <KeyboardShortcutBadge letter="enter" />
        </Button>
      </div>
    </div>
  );
};

export default EditPopup;

```

## File: frontend/src/components/select-and-edit/SelectAndEditModeToggleButton.tsx

- Extension: .tsx
- Language: typescript
- Size: 691 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { GiClick } from "react-icons/gi";
import { useAppStore } from "../../store/app-store";
import { Button } from "../ui/button";

function SelectAndEditModeToggleButton() {
  const { inSelectAndEditMode, toggleInSelectAndEditMode } = useAppStore();

  return (
    <Button
      onClick={toggleInSelectAndEditMode}
      className="flex items-center gap-x-2 dark:text-white dark:bg-gray-700 regenerate-btn"
      variant={inSelectAndEditMode ? "destructive" : "default"}
    >
      <GiClick className="text-lg" />
      <span>
        {inSelectAndEditMode ? "Exit selection mode" : "Select and update"}
      </span>
    </Button>
  );
}

export default SelectAndEditModeToggleButton;

```

## File: frontend/src/components/start-pane/StartPane.tsx

- Extension: .tsx
- Language: typescript
- Size: 871 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import ImageUpload from "../ImageUpload";
import { UrlInputSection } from "../UrlInputSection";
import ImportCodeSection from "../ImportCodeSection";
import { Settings } from "../../types";
import { Stack } from "../../lib/stacks";

interface Props {
  doCreate: (images: string[], inputMode: "image" | "video") => void;
  importFromCode: (code: string, stack: Stack) => void;
  settings: Settings;
}

const StartPane: React.FC<Props> = ({ doCreate, importFromCode, settings }) => {
  return (
    <div className="flex flex-col justify-center items-center gap-y-10">
      <ImageUpload setReferenceImages={doCreate} />
      <UrlInputSection
        doCreate={doCreate}
        screenshotOneApiKey={settings.screenshotOneApiKey}
      />
      <ImportCodeSection importFromCode={importFromCode} />
    </div>
  );
};

export default StartPane;

```

## File: frontend/src/components/variants/Variants.tsx

- Extension: .tsx
- Language: typescript
- Size: 1281 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useProjectStore } from "../../store/project-store";

function Variants() {
  const { inputMode, head, commits, updateSelectedVariantIndex } =
    useProjectStore();

  // If there is no head, don't show the variants
  if (head === null) {
    return null;
  }

  const commit = commits[head];
  const variants = commit.variants;
  const selectedVariantIndex = commit.selectedVariantIndex;

  // If there is only one variant or the commit is already committed, don't show the variants
  if (variants.length <= 1 || commit.isCommitted || inputMode === "video") {
    return <div className="mt-2"></div>;
  }

  return (
    <div className="mt-4 mb-4">
      <div className="grid grid-cols-2 gap-2">
        {variants.map((_, index) => (
          <div
            key={index}
            className={`p-2 border rounded-md cursor-pointer ${
              index === selectedVariantIndex
                ? "bg-blue-100 dark:bg-blue-900"
                : "bg-gray-50 dark:bg-gray-800 hover:bg-gray-100 dark:hover:bg-gray-700"
            }`}
            onClick={() => updateSelectedVariantIndex(head, index)}
          >
            <h3 className="font-medium mb-1">Option {index + 1}</h3>
          </div>
        ))}
      </div>
    </div>
  );
}

export default Variants;

```

## File: frontend/src/components/messages/PicoBadge.tsx

- Extension: .tsx
- Language: typescript
- Size: 677 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export function PicoBadge() {
  return (
    <>
      <a
        href="https://screenshot-to-code.canny.io/feature-requests"
        target="_blank"
      >
        <div
          className="fixed z-50 bottom-16 right-5 rounded-md shadow bg-black
         text-white px-4 text-xs py-3 cursor-pointer"
        >
          feature requests?
        </div>
      </a>
      <a href="https://picoapps.xyz?ref=screenshot-to-code" target="_blank">
        <div
          className="fixed z-50 bottom-5 right-5 rounded-md shadow text-black
         bg-white px-4 text-xs py-3 cursor-pointer"
        >
          an open source project by Pico
        </div>
      </a>
    </>
  );
}

```

## File: frontend/src/components/messages/OnboardingNote.tsx

- Extension: .tsx
- Language: typescript
- Size: 936 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export function OnboardingNote() {
  return (
    <div className="flex flex-col space-y-4 bg-green-700 p-2 rounded text-stone-200 text-sm">
      <span>
        To use Screenshot to Code,{" "}
        <a
          className="inline underline hover:opacity-70"
          href="https://buy.stripe.com/8wM6sre70gBW1nqaEE"
          target="_blank"
        >
          buy some credits (100 generations for $36)
        </a>{" "}
        or use your own OpenAI API key with GPT4 vision access.{" "}
        <a
          href="https://github.com/abi/screenshot-to-code/blob/main/Troubleshooting.md"
          className="inline underline hover:opacity-70"
          target="_blank"
        >
          Follow these instructions to get yourself a key.
        </a>{" "}
        and paste it in the Settings dialog (gear icon above). Your key is only
        stored in your browser. Never stored on our servers.
      </span>
    </div>
  );
}

```

## File: frontend/src/components/messages/DeprecationMessage.tsx

- Extension: .tsx
- Language: typescript
- Size: 452 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";

interface DeprecationMessageProps {}

const DeprecationMessage: React.FC<DeprecationMessageProps> = () => {
  return (
    <div className="rounded-lg p-2 bg-fuchsia-200">
      <p className="text-gray-800 text-sm">
        We no longer support this model. Instead, code generation will use
        GPT-4o or Claude Sonnet 3.5, the 2 state-of-the-art models.
      </p>
    </div>
  );
};

export default DeprecationMessage;

```

## File: frontend/src/components/messages/TipLink.tsx

- Extension: .tsx
- Language: typescript
- Size: 279 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { URLS } from "../../urls";

function TipLink() {
  return (
    <a
      className="text-xs underline text-gray-500 text-right"
      href={URLS.tips}
      target="_blank"
      rel="noopener"
    >
      Tips for better results
    </a>
  );
}

export default TipLink;

```

## File: frontend/src/components/core/StackLabel.tsx

- Extension: .tsx
- Language: typescript
- Size: 574 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import { Stack, STACK_DESCRIPTIONS } from "../../lib/stacks";

interface StackLabelProps {
  stack: Stack;
}

const StackLabel: React.FC<StackLabelProps> = ({ stack }) => {
  const stackComponents = STACK_DESCRIPTIONS[stack].components;

  return (
    <div>
      {stackComponents.map((component, index) => (
        <React.Fragment key={index}>
          <span className="font-semibold">{component}</span>
          {index < stackComponents.length - 1 && " + "}
        </React.Fragment>
      ))}
    </div>
  );
};

export default StackLabel;

```

## File: frontend/src/components/core/KeyboardShortcutBadge.tsx

- Extension: .tsx
- Language: typescript
- Size: 586 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";
import { BsArrowReturnLeft } from "react-icons/bs";

interface KeyboardShortcutBadgeProps {
  letter: string;
}

const KeyboardShortcutBadge: React.FC<KeyboardShortcutBadgeProps> = ({
  letter,
}) => {
  const icon =
    letter.toLowerCase() === "enter" || letter.toLowerCase() === "return" ? (
      <BsArrowReturnLeft />
    ) : (
      letter.toUpperCase()
    );

  return (
    <span className="font-mono text-xs ml-2 rounded bg-gray-700 dark:bg-gray-900 text-white py-[2px] px-2">
      {icon}
    </span>
  );
};

export default KeyboardShortcutBadge;

```

## File: frontend/src/components/core/Spinner.tsx

- Extension: .tsx
- Language: typescript
- Size: 1481 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
function Spinner() {
  return (
    <div role="status">
      <svg
        aria-hidden="true"
        className="w-6 h-6 text-gray-200 animate-spin dark:text-gray-600 fill-gray-800"
        viewBox="0 0 100 101"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z"
          fill="currentColor"
        />
        <path
          d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z"
          fill="currentFill"
        />
      </svg>
      <span className="sr-only">Loading...</span>
    </div>
  );
}

export default Spinner;

```

## File: frontend/src/components/recording/ScreenRecorder.tsx

- Extension: .tsx
- Language: typescript
- Size: 4428 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useState } from "react";
import { Button } from "../ui/button";
import { ScreenRecorderState } from "../../types";
import { blobToBase64DataUrl } from "./utils";
import fixWebmDuration from "webm-duration-fix";
import toast from "react-hot-toast";

interface Props {
  screenRecorderState: ScreenRecorderState;
  setScreenRecorderState: (state: ScreenRecorderState) => void;
  generateCode: (
    referenceImages: string[],
    inputMode: "image" | "video"
  ) => void;
}

function ScreenRecorder({
  screenRecorderState,
  setScreenRecorderState,
  generateCode,
}: Props) {
  const [mediaStream, setMediaStream] = useState<MediaStream | null>(null);
  const [mediaRecorder, setMediaRecorder] = useState<MediaRecorder | null>(
    null
  );
  const [screenRecordingDataUrl, setScreenRecordingDataUrl] = useState<
    string | null
  >(null);

  const startScreenRecording = async () => {
    try {
      // Get the screen recording stream
      const stream = await navigator.mediaDevices.getDisplayMedia({
        video: true,
        audio: { echoCancellation: true },
      });
      setMediaStream(stream);

      // TODO: Test across different browsers
      // Create the media recorder
      const options = { mimeType: "video/webm" };
      const mediaRecorder = new MediaRecorder(stream, options);
      setMediaRecorder(mediaRecorder);

      const chunks: BlobPart[] = [];

      // Accumalate chunks as data is available
      mediaRecorder.ondataavailable = (e: BlobEvent) => chunks.push(e.data);

      // When media recorder is stopped, create a data URL
      mediaRecorder.onstop = async () => {
        // TODO: Do I need to fix duration if it's not a webm?
        const completeBlob = await fixWebmDuration(
          new Blob(chunks, {
            type: options.mimeType,
          })
        );

        const dataUrl = await blobToBase64DataUrl(completeBlob);

        setScreenRecordingDataUrl(dataUrl);
        setScreenRecorderState(ScreenRecorderState.FINISHED);
      };

      // Start recording
      mediaRecorder.start();
      setScreenRecorderState(ScreenRecorderState.RECORDING);
    } catch (error) {
      toast.error("Could not start screen recording");
      throw error;
    }
  };

  const stopScreenRecording = () => {
    // Stop the recorder
    if (mediaRecorder) {
      mediaRecorder.stop();
      setMediaRecorder(null);
    }

    // Stop the screen sharing stream
    if (mediaStream) {
      mediaStream.getTracks().forEach((track) => {
        track.stop();
      });
    }
  };

  const kickoffGeneration = () => {
    if (screenRecordingDataUrl) {
      generateCode([screenRecordingDataUrl], "video");
    } else {
      toast.error("Screen recording does not exist. Please try again.");
      throw new Error("No screen recording data url");
    }
  };

  return (
    <div className="flex items-center justify-center my-3">
      {screenRecorderState === ScreenRecorderState.INITIAL && (
        <Button onClick={startScreenRecording}>Record Screen</Button>
      )}

      {screenRecorderState === ScreenRecorderState.RECORDING && (
        <div className="flex items-center flex-col gap-y-4">
          <div className="flex items-center mr-2 text-xl gap-x-1">
            <span className="block h-10 w-10 bg-red-600 rounded-full mr-1 animate-pulse"></span>
            <span>Recording...</span>
          </div>
          <Button onClick={stopScreenRecording}>Finish Recording</Button>
        </div>
      )}

      {screenRecorderState === ScreenRecorderState.FINISHED && (
        <div className="flex items-center flex-col gap-y-4">
          <div className="flex items-center mr-2 text-xl gap-x-1">
            <span>Screen Recording Captured.</span>
          </div>
          {screenRecordingDataUrl && (
            <video
              muted
              autoPlay
              loop
              className="w-[340px] border border-gray-200 rounded-md"
              src={screenRecordingDataUrl}
            />
          )}
          <div className="flex gap-x-2">
            <Button
              variant="secondary"
              onClick={() =>
                setScreenRecorderState(ScreenRecorderState.INITIAL)
              }
            >
              Re-record
            </Button>
            <Button onClick={kickoffGeneration}>Generate</Button>
          </div>
        </div>
      )}
    </div>
  );
}

export default ScreenRecorder;

```

## File: frontend/src/components/recording/utils.ts

- Extension: .ts
- Language: typescript
- Size: 895 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export function downloadBlob(blob: Blob) {
  // Create a URL for the blob object
  const videoURL = URL.createObjectURL(blob);

  // Create a temporary anchor element and trigger the download
  const a = document.createElement("a");
  a.href = videoURL;
  a.download = "recording.webm";
  document.body.appendChild(a);
  a.click();
  document.body.removeChild(a);

  // Clear object URL
  URL.revokeObjectURL(videoURL);
}

export function blobToBase64DataUrl(blob: Blob): Promise<string> {
  return new Promise((resolve, reject) => {
    const reader = new FileReader();
    reader.onloadend = () => {
      if (reader.result) {
        resolve(reader.result as string);
      } else {
        reject(new Error("FileReader did not return a result."));
      }
    };
    reader.onerror = () =>
      reject(new Error("FileReader encountered an error."));
    reader.readAsDataURL(blob);
  });
}

```

## File: frontend/src/components/history/utils.test.ts

- Extension: .ts
- Language: typescript
- Size: 6140 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { extractHistory, renderHistory } from "./utils";
import { Commit, CommitHash } from "../commits/types";

const basicLinearHistory: Record<CommitHash, Commit> = {
  "0": {
    hash: "0",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_create",
    parentHash: null,
    variants: [{ code: "<html>1. create</html>" }],
    selectedVariantIndex: 0,
    inputs: {
      image_url: "",
    },
  },
  "1": {
    hash: "1",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_edit",
    parentHash: "0",
    variants: [{ code: "<html>2. edit with better icons</html>" }],
    selectedVariantIndex: 0,
    inputs: {
      prompt: "use better icons",
    },
  },
  "2": {
    hash: "2",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_edit",
    parentHash: "1",
    variants: [{ code: "<html>3. edit with better icons and red text</html>" }],
    selectedVariantIndex: 0,
    inputs: {
      prompt: "make text red",
    },
  },
};

const basicLinearHistoryWithCode: Record<CommitHash, Commit> = {
  "0": {
    hash: "0",
    dateCreated: new Date(),
    isCommitted: false,
    type: "code_create",
    parentHash: null,
    variants: [{ code: "<html>1. create</html>" }],
    selectedVariantIndex: 0,
    inputs: null,
  },
  ...Object.fromEntries(Object.entries(basicLinearHistory).slice(1)),
};

const basicBranchingHistory: Record<CommitHash, Commit> = {
  ...basicLinearHistory,
  "3": {
    hash: "3",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_edit",
    parentHash: "1",
    variants: [
      { code: "<html>4. edit with better icons and green text</html>" },
    ],
    selectedVariantIndex: 0,
    inputs: {
      prompt: "make text green",
    },
  },
};

const longerBranchingHistory: Record<CommitHash, Commit> = {
  ...basicBranchingHistory,
  "4": {
    hash: "4",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_edit",
    parentHash: "3",
    variants: [
      { code: "<html>5. edit with better icons and green, bold text</html>" },
    ],
    selectedVariantIndex: 0,
    inputs: {
      prompt: "make text bold",
    },
  },
};

const basicBadHistory: Record<CommitHash, Commit> = {
  "0": {
    hash: "0",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_create",
    parentHash: null,
    variants: [{ code: "<html>1. create</html>" }],
    selectedVariantIndex: 0,
    inputs: {
      image_url: "",
    },
  },
  "1": {
    hash: "1",
    dateCreated: new Date(),
    isCommitted: false,
    type: "ai_edit",
    parentHash: "2", // <- Bad parent hash
    variants: [{ code: "<html>2. edit with better icons</html>" }],
    selectedVariantIndex: 0,
    inputs: {
      prompt: "use better icons",
    },
  },
};

describe("History Utils", () => {
  test("should correctly extract the history tree", () => {
    expect(extractHistory("2", basicLinearHistory)).toEqual([
      "<html>1. create</html>",
      "use better icons",
      "<html>2. edit with better icons</html>",
      "make text red",
      "<html>3. edit with better icons and red text</html>",
    ]);

    expect(extractHistory("0", basicLinearHistory)).toEqual([
      "<html>1. create</html>",
    ]);

    // Test branching
    expect(extractHistory("3", basicBranchingHistory)).toEqual([
      "<html>1. create</html>",
      "use better icons",
      "<html>2. edit with better icons</html>",
      "make text green",
      "<html>4. edit with better icons and green text</html>",
    ]);

    expect(extractHistory("4", longerBranchingHistory)).toEqual([
      "<html>1. create</html>",
      "use better icons",
      "<html>2. edit with better icons</html>",
      "make text green",
      "<html>4. edit with better icons and green text</html>",
      "make text bold",
      "<html>5. edit with better icons and green, bold text</html>",
    ]);

    expect(extractHistory("2", longerBranchingHistory)).toEqual([
      "<html>1. create</html>",
      "use better icons",
      "<html>2. edit with better icons</html>",
      "make text red",
      "<html>3. edit with better icons and red text</html>",
    ]);

    // Errors

    // Bad hash
    expect(() => extractHistory("100", basicLinearHistory)).toThrow();

    // Bad tree
    expect(() => extractHistory("1", basicBadHistory)).toThrow();
  });

  test("should correctly render the history tree", () => {
    expect(renderHistory(Object.values(basicLinearHistory))).toEqual([
      {
        ...basicLinearHistory["0"],
        type: "Create",
        summary: "Create",
        parentVersion: null,
      },
      {
        ...basicLinearHistory["1"],
        type: "Edit",
        summary: "use better icons",
        parentVersion: null,
      },
      {
        ...basicLinearHistory["2"],
        type: "Edit",
        summary: "make text red",
        parentVersion: null,
      },
    ]);

    // Render a history with code
    expect(renderHistory(Object.values(basicLinearHistoryWithCode))).toEqual([
      {
        ...basicLinearHistoryWithCode["0"],
        type: "Imported from code",
        summary: "Imported from code",
        parentVersion: null,
      },
      {
        ...basicLinearHistoryWithCode["1"],
        type: "Edit",
        summary: "use better icons",
        parentVersion: null,
      },
      {
        ...basicLinearHistoryWithCode["2"],
        type: "Edit",
        summary: "make text red",
        parentVersion: null,
      },
    ]);

    // Render a non-linear history
    expect(renderHistory(Object.values(basicBranchingHistory))).toEqual([
      {
        ...basicBranchingHistory["0"],
        type: "Create",
        summary: "Create",
        parentVersion: null,
      },
      {
        ...basicBranchingHistory["1"],
        type: "Edit",
        summary: "use better icons",
        parentVersion: null,
      },
      {
        ...basicBranchingHistory["2"],
        type: "Edit",
        summary: "make text red",
        parentVersion: null,
      },
      {
        ...basicBranchingHistory["3"],
        type: "Edit",
        summary: "make text green",
        parentVersion: 2,
      },
    ]);
  });
});

```

## File: frontend/src/components/history/utils.ts

- Extension: .ts
- Language: typescript
- Size: 2500 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { Commit, CommitHash, CommitType } from "../commits/types";

export function extractHistory(
  hash: CommitHash,
  commits: Record<CommitHash, Commit>
): string[] {
  const flatHistory: string[] = [];

  let currentCommitHash: CommitHash | null = hash;
  while (currentCommitHash !== null) {
    const commit: Commit | null = commits[currentCommitHash];

    if (commit) {
      flatHistory.unshift(commit.variants[commit.selectedVariantIndex].code);

      // For edits, add the prompt to the history
      if (commit.type === "ai_edit") {
        flatHistory.unshift(commit.inputs.prompt);
      }

      // Move to the parent of the current item
      currentCommitHash = commit.parentHash;
    } else {
      throw new Error("Malformed history: missing parent index");
    }
  }

  return flatHistory;
}

function displayHistoryItemType(itemType: CommitType) {
  switch (itemType) {
    case "ai_create":
      return "Create";
    case "ai_edit":
      return "Edit";
    case "code_create":
      return "Imported from code";
    default: {
      const exhaustiveCheck: never = itemType;
      throw new Error(`Unhandled case: ${exhaustiveCheck}`);
    }
  }
}

const setParentVersion = (commit: Commit, history: Commit[]) => {
  // If the commit has no parent, return null
  if (!commit.parentHash) return null;

  const parentIndex = history.findIndex(
    (item) => item.hash === commit.parentHash
  );
  const currentIndex = history.findIndex((item) => item.hash === commit.hash);

  // Only set parent version if the parent is not the previous commit
  // and parent exists
  return parentIndex !== -1 && parentIndex != currentIndex - 1
    ? parentIndex + 1
    : null;
};

export function summarizeHistoryItem(commit: Commit) {
  const commitType = commit.type;
  switch (commitType) {
    case "ai_create":
      return "Create";
    case "ai_edit":
      return commit.inputs.prompt;
    case "code_create":
      return "Imported from code";
    default: {
      const exhaustiveCheck: never = commitType;
      throw new Error(`Unhandled case: ${exhaustiveCheck}`);
    }
  }
}

export const renderHistory = (history: Commit[]) => {
  const renderedHistory = [];

  for (let i = 0; i < history.length; i++) {
    const commit = history[i];
    renderedHistory.push({
      ...commit,
      type: displayHistoryItemType(commit.type),
      summary: summarizeHistoryItem(commit),
      parentVersion: setParentVersion(commit, history),
    });
  }

  return renderedHistory;
};

```

## File: frontend/src/components/history/HistoryDisplay.tsx

- Extension: .tsx
- Language: typescript
- Size: 3178 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import toast from "react-hot-toast";
import classNames from "classnames";

import { Badge } from "../ui/badge";
import { renderHistory } from "./utils";
import {
  Collapsible,
  CollapsibleContent,
  CollapsibleTrigger,
} from "../ui/collapsible";
import { Button } from "../ui/button";
import { CaretSortIcon } from "@radix-ui/react-icons";
import { useProjectStore } from "../../store/project-store";

interface Props {
  shouldDisableReverts: boolean;
}

export default function HistoryDisplay({ shouldDisableReverts }: Props) {
  const { commits, head, setHead } = useProjectStore();

  // Put all commits into an array and sort by created date (oldest first)
  const flatHistory = Object.values(commits).sort(
    (a, b) =>
      new Date(a.dateCreated).getTime() - new Date(b.dateCreated).getTime()
  );

  // Annotate history items with a summary, parent version, etc.
  const renderedHistory = renderHistory(flatHistory);

  return renderedHistory.length === 0 ? null : (
    <div className="flex flex-col h-screen">
      <h1 className="font-bold mb-2">Versions</h1>
      <ul className="space-y-0 flex flex-col-reverse">
        {renderedHistory.map((item, index) => (
          <li key={index}>
            <Collapsible>
              <div
                className={classNames(
                  "flex items-center justify-between space-x-2 w-full pr-2",
                  "border-b cursor-pointer",
                  {
                    " hover:bg-black hover:text-white": item.hash === head,
                    "bg-slate-500 text-white": item.hash === head,
                  }
                )}
              >
                <div
                  className="flex justify-between truncate flex-1 p-2"
                  onClick={() =>
                    shouldDisableReverts
                      ? toast.error(
                          "Please wait for code generation to complete before viewing an older version."
                        )
                      : setHead(item.hash)
                  }
                >
                  <div className="flex gap-x-1 truncate">
                    <h2 className="text-sm truncate">{item.summary}</h2>
                    {item.parentVersion !== null && (
                      <h2 className="text-sm">
                        (parent: v{item.parentVersion})
                      </h2>
                    )}
                  </div>
                  <h2 className="text-sm">v{index + 1}</h2>
                </div>
                <CollapsibleTrigger asChild>
                  <Button variant="ghost" size="sm" className="h-6">
                    <CaretSortIcon className="h-4 w-4" />
                    <span className="sr-only">Toggle</span>
                  </Button>
                </CollapsibleTrigger>
              </div>
              <CollapsibleContent className="w-full bg-slate-300 p-2">
                <div>Full prompt: {item.summary}</div>
                <div className="flex justify-end">
                  <Badge>{item.type}</Badge>
                </div>
              </CollapsibleContent>
            </Collapsible>
          </li>
        ))}
      </ul>
    </div>
  );
}

```

## File: frontend/src/components/preview/CodeMirror.tsx

- Extension: .tsx
- Language: typescript
- Size: 2193 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useRef, useEffect, useMemo } from "react";
import { EditorState } from "@codemirror/state";
import { EditorView, keymap, lineNumbers, ViewUpdate } from "@codemirror/view";
import { espresso, cobalt } from "thememirror";
import {
  defaultKeymap,
  history,
  indentWithTab,
  redo,
  undo,
} from "@codemirror/commands";
import { bracketMatching } from "@codemirror/language";
import { html } from "@codemirror/lang-html";
import { EditorTheme } from "@/types";

interface Props {
  code: string;
  editorTheme: EditorTheme;
  onCodeChange: (code: string) => void;
}

function CodeMirror({ code, editorTheme, onCodeChange }: Props) {
  const ref = useRef<HTMLDivElement>(null);
  const view = useRef<EditorView | null>(null);
  const editorState = useMemo(
    () =>
      EditorState.create({
        extensions: [
          history(),
          keymap.of([
            ...defaultKeymap,
            indentWithTab,
            { key: "Mod-z", run: undo, preventDefault: true },
            { key: "Mod-Shift-z", run: redo, preventDefault: true },
          ]),
          lineNumbers(),
          bracketMatching(),
          html(),
          editorTheme === EditorTheme.ESPRESSO ? espresso : cobalt,
          EditorView.lineWrapping,
          EditorView.updateListener.of((update: ViewUpdate) => {
            if (update.docChanged) {
              const updatedCode = update.state.doc.toString();
              onCodeChange(updatedCode);
            }
          }),
        ],
      }),
    [editorTheme]
  );
  useEffect(() => {
    view.current = new EditorView({
      state: editorState,
      parent: ref.current as Element,
    });

    return () => {
      if (view.current) {
        view.current.destroy();
        view.current = null;
      }
    };
  }, []);

  useEffect(() => {
    if (view.current && view.current.state.doc.toString() !== code) {
      view.current.dispatch({
        changes: { from: 0, to: view.current.state.doc.length, insert: code },
      });
    }
  }, [code]);

  return (
    <div
      className="overflow-x-scroll overflow-y-scroll mx-2 border-[4px] border-black rounded-[20px]"
      ref={ref}
    />
  );
}

export default CodeMirror;

```

## File: frontend/src/components/preview/CodePreview.tsx

- Extension: .tsx
- Language: typescript
- Size: 545 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useRef, useEffect } from "react";

interface Props {
  code: string;
}

function CodePreview({ code }: Props) {
  const scrollRef = useRef<HTMLDivElement>(null);

  useEffect(() => {
    if (scrollRef.current) {
      scrollRef.current.scrollLeft = scrollRef.current.scrollWidth;
    }
  }, [code]);

  return (
    <div
      ref={scrollRef}
      className="w-full px-2 bg-black text-green-400 whitespace-nowrap flex 
      overflow-x-auto font-mono text-[10px] my-4"
    >
      {code}
    </div>
  );
}

export default CodePreview;

```

## File: frontend/src/components/preview/PreviewPane.tsx

- Extension: .tsx
- Language: typescript
- Size: 3114 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { Tabs, TabsList, TabsTrigger, TabsContent } from "../ui/tabs";
import {
  FaUndo,
  FaDownload,
  FaDesktop,
  FaMobile,
  FaCode,
} from "react-icons/fa";
import { AppState, Settings } from "../../types";
import CodeTab from "./CodeTab";
import { Button } from "../ui/button";
import { useAppStore } from "../../store/app-store";
import { useProjectStore } from "../../store/project-store";
import { extractHtml } from "./extractHtml";
import PreviewComponent from "./PreviewComponent";
import { downloadCode } from "./download";

interface Props {
  doUpdate: (instruction: string) => void;
  reset: () => void;
  settings: Settings;
}

function PreviewPane({ doUpdate, reset, settings }: Props) {
  const { appState } = useAppStore();
  const { inputMode, head, commits } = useProjectStore();

  const currentCommit = head && commits[head] ? commits[head] : "";
  const currentCode = currentCommit
    ? currentCommit.variants[currentCommit.selectedVariantIndex].code
    : "";

  const previewCode =
    inputMode === "video" && appState === AppState.CODING
      ? extractHtml(currentCode)
      : currentCode;

  return (
    <div className="ml-4">
      <Tabs defaultValue="desktop">
        <div className="flex justify-between mr-8 mb-4">
          <div className="flex items-center gap-x-2">
            {appState === AppState.CODE_READY && (
              <>
                <Button
                  onClick={reset}
                  className="flex items-center ml-4 gap-x-2 dark:text-white dark:bg-gray-700"
                >
                  <FaUndo />
                  Reset
                </Button>
                <Button
                  onClick={() => downloadCode(previewCode)}
                  variant="secondary"
                  className="flex items-center gap-x-2 mr-4 dark:text-white dark:bg-gray-700 download-btn"
                >
                  <FaDownload /> Download
                </Button>
              </>
            )}
          </div>
          <div className="flex items-center">
            <TabsList>
              <TabsTrigger value="desktop" className="flex gap-x-2">
                <FaDesktop /> Desktop
              </TabsTrigger>
              <TabsTrigger value="mobile" className="flex gap-x-2">
                <FaMobile /> Mobile
              </TabsTrigger>
              <TabsTrigger value="code" className="flex gap-x-2">
                <FaCode />
                Code
              </TabsTrigger>
            </TabsList>
          </div>
        </div>
        <TabsContent value="desktop">
          <PreviewComponent
            code={previewCode}
            device="desktop"
            doUpdate={doUpdate}
          />
        </TabsContent>
        <TabsContent value="mobile">
          <PreviewComponent
            code={previewCode}
            device="mobile"
            doUpdate={doUpdate}
          />
        </TabsContent>
        <TabsContent value="code">
          <CodeTab code={previewCode} setCode={() => {}} settings={settings} />
        </TabsContent>
      </Tabs>
    </div>
  );
}

export default PreviewPane;

```

## File: frontend/src/components/preview/PreviewComponent.tsx

- Extension: .tsx
- Language: typescript
- Size: 2652 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useEffect, useRef, useState } from "react";
import classNames from "classnames";
import useThrottle from "../../hooks/useThrottle";
import EditPopup from "../select-and-edit/EditPopup";

interface Props {
  code: string;
  device: "mobile" | "desktop";
  doUpdate: (updateInstruction: string, selectedElement?: HTMLElement) => void;
}

function PreviewComponent({ code, device, doUpdate }: Props) {
  const iframeRef = useRef<HTMLIFrameElement | null>(null);
  const wrapperRef = useRef<HTMLDivElement | null>(null);

  // Don't update code more often than every 200ms.
  const throttledCode = useThrottle(code, 200);

  // Select and edit functionality
  const [clickEvent, setClickEvent] = useState<MouseEvent | null>(null);

  // Add scaling logic
  useEffect(() => {
    const updateScale = () => {
      const wrapper = wrapperRef.current;
      const iframe = iframeRef.current;
      if (!wrapper || !iframe) return;

      const viewportWidth = wrapper.clientWidth;
      const baseWidth = device === "desktop" ? 1440 : 375;
      const scale = Math.min(1, viewportWidth / baseWidth);

      iframe.style.transform = `scale(${scale})`;
      iframe.style.transformOrigin = "top left";
      // Adjust wrapper height to account for scaling
      wrapper.style.height = `${iframe.offsetHeight * scale}px`;
    };

    updateScale();

    // Add event listener for window resize
    window.addEventListener("resize", updateScale);
    return () => window.removeEventListener("resize", updateScale);
  }, [device]);

  useEffect(() => {
    const iframe = iframeRef.current;
    if (iframe) {
      iframe.srcdoc = throttledCode;

      // Set up click handler for select and edit funtionality
      iframe.addEventListener("load", function () {
        iframe.contentWindow?.document.body.addEventListener(
          "click",
          setClickEvent
        );
      });
    }
  }, [throttledCode]);

  return (
    <div className="flex justify-center mr-4">
      <div
        ref={wrapperRef}
        className="overflow-y-auto overflow-x-hidden w-full"
      >
        <iframe
          id={`preview-${device}`}
          ref={iframeRef}
          title="Preview"
          className={classNames(
            "border-[4px] border-black rounded-[20px] shadow-lg mx-auto",
            {
              "w-[1440px] h-[900px]": device === "desktop",
              "w-[375px] h-[812px]": device === "mobile",
            }
          )}
        ></iframe>
        <EditPopup
          event={clickEvent}
          iframeRef={iframeRef}
          doUpdate={doUpdate}
        />
      </div>
    </div>
  );
}

export default PreviewComponent;

```

## File: frontend/src/components/preview/simpleHash.ts

- Extension: .ts
- Language: typescript
- Size: 251 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript

export function simpleHash(str: string, seed = 0) {
  let hash = seed;
  for (let i = 0; i < str.length; i++) {
    const char = str.charCodeAt(i);
    hash = (hash << 5) - hash + char;
    hash |= 0; // Convert to 32bit integer
  }
  return hash;
}

```

## File: frontend/src/components/preview/download.ts

- Extension: .ts
- Language: typescript
- Size: 626 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
export const downloadCode = (code: string) => {
  // Create a blob from the generated code
  const blob = new Blob([code], { type: "text/html" });
  const url = URL.createObjectURL(blob);

  // Create an anchor element and set properties for download
  const a = document.createElement("a");
  a.href = url;
  a.download = "index.html"; // Set the file name for download
  document.body.appendChild(a); // Append to the document
  a.click(); // Programmatically click the anchor to trigger download

  // Clean up by removing the anchor and revoking the Blob URL
  document.body.removeChild(a);
  URL.revokeObjectURL(url);
};

```

## File: frontend/src/components/preview/extractHtml.ts

- Extension: .ts
- Language: typescript
- Size: 646 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
// Not robust enough to support <html lang='en'> for instance
export function extractHtml(code: string): string {
  const lastHtmlStartIndex = code.lastIndexOf("<html>");
  let htmlEndIndex = code.indexOf("</html>", lastHtmlStartIndex);

  if (lastHtmlStartIndex !== -1) {
    // If "</html>" is found, adjust htmlEndIndex to include the "</html>" tag
    if (htmlEndIndex !== -1) {
      htmlEndIndex += "</html>".length;
      return code.slice(lastHtmlStartIndex, htmlEndIndex);
    }
    // If "</html>" is not found, return the rest of the string starting from the last "<html>"
    return code.slice(lastHtmlStartIndex);
  }
  return "";
}

```

## File: frontend/src/components/preview/CodeTab.tsx

- Extension: .tsx
- Language: typescript
- Size: 2916 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { FaCopy } from "react-icons/fa";
import CodeMirror from "./CodeMirror";
import { Button } from "../ui/button";
import { Settings } from "../../types";
import copy from "copy-to-clipboard";
import { useCallback } from "react";
import toast from "react-hot-toast";

interface Props {
  code: string;
  setCode: React.Dispatch<React.SetStateAction<string>>;
  settings: Settings;
}

function CodeTab({ code, setCode, settings }: Props) {
  const copyCode = useCallback(() => {
    copy(code);
    toast.success("Copied to clipboard");
  }, [code]);

  const doOpenInCodepenio = useCallback(async () => {
    // TODO: Update CSS and JS external links depending on the framework being used
    const data = {
      html: code,
      editors: "100", // 1: Open HTML, 0: Close CSS, 0: Close JS
      layout: "left",
      css_external:
        "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" +
        (code.includes("<ion-")
          ? ",https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css"
          : ""),
      js_external:
        "https://cdn.tailwindcss.com " +
        (code.includes("<ion-")
          ? ",https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js,https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"
          : ""),
    };

    // Create a hidden form and submit it to open the code in CodePen
    // Can't use fetch API directly because we want to open the URL in a new tab
    const input = document.createElement("input");
    input.setAttribute("type", "hidden");
    input.setAttribute("name", "data");
    input.setAttribute("value", JSON.stringify(data));

    const form = document.createElement("form");
    form.setAttribute("method", "POST");
    form.setAttribute("action", "https://codepen.io/pen/define");
    form.setAttribute("target", "_blank");
    form.appendChild(input);

    document.body.appendChild(form);
    form.submit();
  }, [code]);

  return (
    <div className="relative">
      <div className="flex justify-start items-center px-4 mb-2">
        <span
          title="Copy Code"
          className="bg-black text-white flex items-center justify-center hover:text-black hover:bg-gray-100 cursor-pointer rounded-lg text-sm p-2.5"
          onClick={copyCode}
        >
          Copy Code <FaCopy className="ml-2" />
        </span>
        <Button
          onClick={doOpenInCodepenio}
          className="bg-gray-100 text-black ml-2 py-2 px-4 border border-black rounded-md hover:bg-gray-400 focus:outline-none"
        >
          Open in{" "}
          <img
            src="https://assets.codepen.io/t-1/codepen-logo.svg"
            alt="codepen.io"
            className="h-4 ml-1"
          />
        </Button>
      </div>
      <CodeMirror
        code={code}
        editorTheme={settings.editorTheme}
        onCodeChange={setCode}
      />
    </div>
  );
}

export default CodeTab;

```

## File: frontend/src/hooks/useBrowserTabIndicator.ts

- Extension: .ts
- Language: typescript
- Size: 667 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { useEffect } from "react";

const CODING_SETTINGS = {
  title: "Coding...",
  favicon: "/favicon/coding.png",
};
const DEFAULT_SETTINGS = {
  title: "Screenshot to Code",
  favicon: "/favicon/main.png",
};

const useBrowserTabIndicator = (isCoding: boolean) => {
  useEffect(() => {
    const settings = isCoding ? CODING_SETTINGS : DEFAULT_SETTINGS;

    // Set favicon
    const faviconEl = document.querySelector(
      "link[rel='icon']"
    ) as HTMLLinkElement | null;
    if (faviconEl) {
      faviconEl.href = settings.favicon;
    }

    // Set title
    document.title = settings.title;
  }, [isCoding]);
};

export default useBrowserTabIndicator;

```

## File: frontend/src/hooks/useThrottle.ts

- Extension: .ts
- Language: typescript
- Size: 939 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import React from "react";

// Updates take effect immediately if the last update was more than {interval} ago.
// Otherwise, updates are throttled to {interval}. The latest value is always sent.
// The last update always gets executed, with potentially a {interval} delay.
export function useThrottle(value: string, interval = 500) {
  const [throttledValue, setThrottledValue] = React.useState(value);
  const lastUpdated = React.useRef<number | null>(null);

  React.useEffect(() => {
    const now = performance.now();

    if (!lastUpdated.current || now >= lastUpdated.current + interval) {
      lastUpdated.current = now;
      setThrottledValue(value);
    } else {
      const id = window.setTimeout(() => {
        lastUpdated.current = now;
        setThrottledValue(value);
      }, interval);

      return () => window.clearTimeout(id);
    }
  }, [value, interval]);

  return throttledValue;
}
export default useThrottle;

```

## File: frontend/src/hooks/usePersistedState.ts

- Extension: .ts
- Language: typescript
- Size: 544 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { Dispatch, SetStateAction, useEffect, useState } from 'react';

type PersistedState<T> = [T, Dispatch<SetStateAction<T>>];

function usePersistedState<T>(defaultValue: T, key: string): PersistedState<T> {
  const [value, setValue] = useState<T>(() => {
    const value = window.localStorage.getItem(key);

    return value ? (JSON.parse(value) as T) : defaultValue;
  });

  useEffect(() => {
    window.localStorage.setItem(key, JSON.stringify(value));
  }, [key, value]);

  return [value, setValue];
}

export { usePersistedState };

```

## File: frontend/src/lib/stacks.ts

- Extension: .ts
- Language: typescript
- Size: 873 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
// Keep in sync with backend (prompts/types.py)
// Order here determines order in dropdown
export enum Stack {
  HTML_TAILWIND = "html_tailwind",
  HTML_CSS = "html_css",
  REACT_TAILWIND = "react_tailwind",
  BOOTSTRAP = "bootstrap",
  VUE_TAILWIND = "vue_tailwind",
  IONIC_TAILWIND = "ionic_tailwind",
  SVG = "svg",
}

export const STACK_DESCRIPTIONS: {
  [key in Stack]: { components: string[]; inBeta: boolean };
} = {
  html_css: { components: ["HTML", "CSS"], inBeta: false },
  html_tailwind: { components: ["HTML", "Tailwind"], inBeta: false },
  react_tailwind: { components: ["React", "Tailwind"], inBeta: false },
  bootstrap: { components: ["Bootstrap"], inBeta: false },
  vue_tailwind: { components: ["Vue", "Tailwind"], inBeta: true },
  ionic_tailwind: { components: ["Ionic", "Tailwind"], inBeta: true },
  svg: { components: ["SVG"], inBeta: true },
};

```

## File: frontend/src/lib/utils.ts

- Extension: .ts
- Language: typescript
- Size: 267 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { type ClassValue, clsx } from "clsx";
import { twMerge } from "tailwind-merge";

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}

export function capitalize(str: string) {
  return str.charAt(0).toUpperCase() + str.slice(1);
}

```

## File: frontend/src/lib/takeScreenshot.ts

- Extension: .ts
- Language: typescript
- Size: 413 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import html2canvas from "html2canvas";

export const takeScreenshot = async (): Promise<string> => {
  const iframeElement = document.querySelector(
    "#preview-desktop"
  ) as HTMLIFrameElement;
  if (!iframeElement?.contentWindow?.document.body) {
    return "";
  }

  const canvas = await html2canvas(iframeElement.contentWindow.document.body);
  const png = canvas.toDataURL("image/png");
  return png;
};

```

## File: frontend/src/lib/models.ts

- Extension: .ts
- Language: typescript
- Size: 914 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
// Keep in sync with backend (llm.py)
// Order here matches dropdown order
export enum CodeGenerationModel {
  CLAUDE_3_5_SONNET_2024_06_20 = "claude-3-5-sonnet-20240620",
  GPT_4O_2024_05_13 = "gpt-4o-2024-05-13",
  GPT_4_TURBO_2024_04_09 = "gpt-4-turbo-2024-04-09",
  GPT_4_VISION = "gpt_4_vision",
  CLAUDE_3_SONNET = "claude_3_sonnet",
}

// Will generate a static error if a model in the enum above is not in the descriptions
export const CODE_GENERATION_MODEL_DESCRIPTIONS: {
  [key in CodeGenerationModel]: { name: string; inBeta: boolean };
} = {
  "gpt-4o-2024-05-13": { name: "GPT-4o", inBeta: false },
  "claude-3-5-sonnet-20240620": { name: "Claude 3.5 Sonnet", inBeta: false },
  "gpt-4-turbo-2024-04-09": { name: "GPT-4 Turbo (deprecated)", inBeta: false },
  gpt_4_vision: { name: "GPT-4 Vision (deprecated)", inBeta: false },
  claude_3_sonnet: { name: "Claude 3 (deprecated)", inBeta: false },
};

```

## File: frontend/src/store/app-store.ts

- Extension: .ts
- Language: typescript
- Size: 904 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { create } from "zustand";
import { AppState } from "../types";

// Store for app-wide state
interface AppStore {
  appState: AppState;
  setAppState: (state: AppState) => void;

  // UI state
  updateInstruction: string;
  setUpdateInstruction: (instruction: string) => void;

  inSelectAndEditMode: boolean;
  toggleInSelectAndEditMode: () => void;
  disableInSelectAndEditMode: () => void;
}

export const useAppStore = create<AppStore>((set) => ({
  appState: AppState.INITIAL,
  setAppState: (state: AppState) => set({ appState: state }),

  // UI state
  updateInstruction: "",
  setUpdateInstruction: (instruction: string) =>
    set({ updateInstruction: instruction }),

  inSelectAndEditMode: false,
  toggleInSelectAndEditMode: () =>
    set((state) => ({ inSelectAndEditMode: !state.inSelectAndEditMode })),
  disableInSelectAndEditMode: () => set({ inSelectAndEditMode: false }),
}));

```

## File: frontend/src/store/project-store.ts

- Extension: .ts
- Language: typescript
- Size: 4393 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```typescript
import { create } from "zustand";
import { Commit, CommitHash } from "../components/commits/types";

// Store for app-wide state
interface ProjectStore {
  // Inputs
  inputMode: "image" | "video";
  setInputMode: (mode: "image" | "video") => void;
  isImportedFromCode: boolean;
  setIsImportedFromCode: (imported: boolean) => void;
  referenceImages: string[];
  setReferenceImages: (images: string[]) => void;

  // Outputs
  commits: Record<string, Commit>;
  head: CommitHash | null;

  addCommit: (commit: Commit) => void;
  removeCommit: (hash: CommitHash) => void;
  resetCommits: () => void;

  appendCommitCode: (
    hash: CommitHash,
    numVariant: number,
    code: string
  ) => void;
  setCommitCode: (hash: CommitHash, numVariant: number, code: string) => void;
  updateSelectedVariantIndex: (hash: CommitHash, index: number) => void;

  setHead: (hash: CommitHash) => void;
  resetHead: () => void;

  executionConsoles: { [key: number]: string[] };
  appendExecutionConsole: (variantIndex: number, line: string) => void;
  resetExecutionConsoles: () => void;
}

export const useProjectStore = create<ProjectStore>((set) => ({
  // Inputs and their setters
  inputMode: "image",
  setInputMode: (mode) => set({ inputMode: mode }),
  isImportedFromCode: false,
  setIsImportedFromCode: (imported) => set({ isImportedFromCode: imported }),
  referenceImages: [],
  setReferenceImages: (images) => set({ referenceImages: images }),

  // Outputs
  commits: {},
  head: null,

  addCommit: (commit: Commit) => {
    // When adding a new commit, make sure all existing commits are marked as committed
    set((state) => ({
      commits: {
        ...Object.fromEntries(
          Object.entries(state.commits).map(([hash, existingCommit]) => [
            hash,
            { ...existingCommit, isCommitted: true },
          ])
        ),
        [commit.hash]: commit,
      },
    }));
  },
  removeCommit: (hash: CommitHash) => {
    set((state) => {
      const newCommits = { ...state.commits };
      delete newCommits[hash];
      return { commits: newCommits };
    });
  },
  resetCommits: () => set({ commits: {} }),

  appendCommitCode: (hash: CommitHash, numVariant: number, code: string) =>
    set((state) => {
      const commit = state.commits[hash];
      // Don't update if the commit is already committed
      if (commit.isCommitted) {
        throw new Error("Attempted to append code to a committed commit");
      }
      return {
        commits: {
          ...state.commits,
          [hash]: {
            ...commit,
            variants: commit.variants.map((variant, index) =>
              index === numVariant
                ? { ...variant, code: variant.code + code }
                : variant
            ),
          },
        },
      };
    }),
  setCommitCode: (hash: CommitHash, numVariant: number, code: string) =>
    set((state) => {
      const commit = state.commits[hash];
      // Don't update if the commit is already committed
      if (commit.isCommitted) {
        throw new Error("Attempted to set code of a committed commit");
      }
      return {
        commits: {
          ...state.commits,
          [hash]: {
            ...commit,
            variants: commit.variants.map((variant, index) =>
              index === numVariant ? { ...variant, code } : variant
            ),
          },
        },
      };
    }),
  updateSelectedVariantIndex: (hash: CommitHash, index: number) =>
    set((state) => {
      const commit = state.commits[hash];
      // Don't update if the commit is already committed
      if (commit.isCommitted) {
        throw new Error(
          "Attempted to update selected variant index of a committed commit"
        );
      }
      return {
        commits: {
          ...state.commits,
          [hash]: {
            ...commit,
            selectedVariantIndex: index,
          },
        },
      };
    }),

  setHead: (hash: CommitHash) => set({ head: hash }),
  resetHead: () => set({ head: null }),

  executionConsoles: {},
  appendExecutionConsole: (variantIndex: number, line: string) =>
    set((state) => ({
      executionConsoles: {
        ...state.executionConsoles,
        [variantIndex]: [
          ...(state.executionConsoles[variantIndex] || []),
          line,
        ],
      },
    })),
  resetExecutionConsoles: () => set({ executionConsoles: {} }),
}));

```

## File: backend/config.py

- Extension: .py
- Language: python
- Size: 983 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Useful for debugging purposes when you don't want to waste GPT4-Vision credits
# Setting to True will stream a mock response instead of calling the OpenAI API
# TODO: Should only be set to true when value is 'True', not any abitrary truthy value
import os

NUM_VARIANTS = 2

# LLM-related
OPENAI_API_KEY = os.environ.get("OPENAI_API_KEY", None)
ANTHROPIC_API_KEY = os.environ.get("ANTHROPIC_API_KEY", None)
GEMINI_API_KEY = os.environ.get("GEMINI_API_KEY", None)
OPENAI_BASE_URL = os.environ.get("OPENAI_BASE_URL", None)

# Image generation (optional)
REPLICATE_API_KEY = os.environ.get("REPLICATE_API_KEY", None)

# Debugging-related

SHOULD_MOCK_AI_RESPONSE = bool(os.environ.get("MOCK", False))
IS_DEBUG_ENABLED = bool(os.environ.get("IS_DEBUG_ENABLED", False))
DEBUG_DIR = os.environ.get("DEBUG_DIR", "")

# Set to True when running in production (on the hosted version)
# Used as a feature flag to enable or disable certain features
IS_PROD = os.environ.get("IS_PROD", False)

```

## File: backend/pyrightconfig.json

- Extension: .json
- Language: json
- Size: 41 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "exclude": ["image_generation.py"]
}

```

## File: backend/.pre-commit-config.yaml

- Extension: .yaml
- Language: yaml
- Size: 803 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```yaml
# See https://pre-commit.com for more information
# See https://pre-commit.com/hooks.html for more hooks
repos:
  - repo: https://github.com/pre-commit/pre-commit-hooks
    rev: v3.2.0
    hooks:
      - id: end-of-file-fixer
      - id: check-yaml
      - id: check-added-large-files
  # - repo: local
  #   hooks:
  #     - id: poetry-pytest
  #       name: Run pytest with Poetry
  #       entry: poetry run --directory backend pytest
  #       language: system
  #       pass_filenames: false
  #       always_run: true
  #       files: ^backend/
  #     # - id: poetry-pyright
  #     #   name: Run pyright with Poetry
  #     #   entry: poetry run --directory backend pyright
  #     #   language: system
  #     #   pass_filenames: false
  #     #   always_run: true
  #     #   files: ^backend/

```

## File: backend/Dockerfile

- Extension: 
- Language: unknown
- Size: 475 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
FROM python:3.12.3-slim-bullseye

ENV POETRY_VERSION 1.7.1

# Install system dependencies
RUN pip install "poetry==$POETRY_VERSION"

# Set work directory
WORKDIR /app

# Copy only requirements to cache them in docker layer
COPY poetry.lock pyproject.toml /app/

# Disable the creation of virtual environments
RUN poetry config virtualenvs.create false

# Install dependencies
RUN poetry install

# Copy the current directory contents into the container at /app
COPY ./ /app/

```

## File: backend/mock_llm.py

- Extension: .py
- Language: python
- Size: 62679 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import asyncio
from typing import Awaitable, Callable

from custom_types import InputMode
from llm import Completion


STREAM_CHUNK_SIZE = 20


async def mock_completion(
    process_chunk: Callable[[str, int], Awaitable[None]], input_mode: InputMode
) -> Completion:
    code_to_return = (
        TALLY_FORM_VIDEO_PROMPT_MOCK
        if input_mode == "video"
        else NO_IMAGES_NYTIMES_MOCK_CODE
    )

    for i in range(0, len(code_to_return), STREAM_CHUNK_SIZE):
        await process_chunk(code_to_return[i : i + STREAM_CHUNK_SIZE], i)
        await asyncio.sleep(0.01)

    if input_mode == "video":
        # Extract the last <html></html> block from code_to_return
        # because we can have multiple passes
        start = code_to_return.rfind("<html")
        end = code_to_return.rfind("</html>") + len("</html>")
        if start != -1 and end != -1:
            code_to_return = code_to_return[start:end]
        else:
            code_to_return = "Error: HTML block not found."

    return {"duration": 0.1, "code": code_to_return}


APPLE_MOCK_CODE = """<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Showcase</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body class="bg-black text-white">
    <nav class="py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center">
            <div class="flex items-center">
                <img src="https://placehold.co/24x24" alt="Company Logo" class="mr-8">
                <a href="#" class="text-white text-sm font-medium mr-4">Store</a>
                <a href="#" class="text-white text-sm font-medium mr-4">Mac</a>
                <a href="#" class="text-white text-sm font-medium mr-4">iPad</a>
                <a href="#" class="text-white text-sm font-medium mr-4">iPhone</a>
                <a href="#" class="text-white text-sm font-medium mr-4">Watch</a>
                <a href="#" class="text-white text-sm font-medium mr-4">Vision</a>
                <a href="#" class="text-white text-sm font-medium mr-4">AirPods</a>
                <a href="#" class="text-white text-sm font-medium mr-4">TV & Home</a>
                <a href="#" class="text-white text-sm font-medium mr-4">Entertainment</a>
                <a href="#" class="text-white text-sm font-medium mr-4">Accessories</a>
                <a href="#" class="text-white text-sm font-medium">Support</a>
            </div>
            <div class="flex items-center">
                <a href="#" class="text-white text-sm font-medium mr-4"><i class="fas fa-search"></i></a>
                <a href="#" class="text-white text-sm font-medium"><i class="fas fa-shopping-bag"></i></a>
            </div>
        </div>
    </nav>

    <main class="mt-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <img src="https://placehold.co/100x100" alt="Brand Logo" class="mx-auto mb-4">
                <h1 class="text-5xl font-bold mb-4">WATCH SERIES 9</h1>
                <p class="text-2xl font-medium mb-8">Smarter. Brighter. Mightier.</p>
                <div class="flex justify-center space-x-4">
                    <a href="#" class="text-blue-600 text-sm font-medium">Learn more ></a>
                    <a href="#" class="text-blue-600 text-sm font-medium">Buy ></a>
                </div>
            </div>
            <div class="flex justify-center mt-12">
                <img src="https://placehold.co/500x300" alt="Product image of a smartwatch with a pink band and a circular interface displaying various health metrics." class="mr-8">
                <img src="https://placehold.co/500x300" alt="Product image of a smartwatch with a blue band and a square interface showing a classic analog clock face." class="ml-8">
            </div>
        </div>
    </main>
</body>
</html>"""

NYTIMES_MOCK_CODE = """
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The New York Times - News</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Libre+Franklin:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: 'Libre Franklin', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <div class="container mx-auto px-4">
        <header class="border-b border-gray-300 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <button class="text-gray-700"><i class="fas fa-bars"></i></button>
                    <button class="text-gray-700"><i class="fas fa-search"></i></button>
                    <div class="text-xs uppercase tracking-widest">Tuesday, November 14, 2023<br>Today's Paper</div>
                </div>
                <div>
                    <img src="https://placehold.co/200x50?text=The+New+York+Times+Logo" alt="The New York Times Logo" class="h-8">
                </div>
                <div class="flex items-center space-x-4">
                    <button class="bg-black text-white px-4 py-1 text-xs uppercase tracking-widest">Give the times</button>
                    <div class="text-xs">Account</div>
                </div>
            </div>
            <nav class="flex justify-between items-center py-4">
                <div class="flex space-x-4">
                    <a href="#" class="text-xs uppercase tracking-widest text-gray-700">U.S.</a>
                    <!-- Add other navigation links as needed -->
                </div>
                <div class="flex space-x-4">
                    <a href="#" class="text-xs uppercase tracking-widest text-gray-700">Cooking</a>
                    <!-- Add other navigation links as needed -->
                </div>
            </nav>
        </header>
        <main>
            <section class="py-6">
                <div class="grid grid-cols-3 gap-4">
                    <div class="col-span-2">
                        <article class="mb-4">
                            <h2 class="text-xl font-bold mb-2">Israeli Military Raids Gaza's Largest Hospital</h2>
                            <p class="text-gray-700 mb-2">Israeli troops have entered the Al-Shifa Hospital complex, where conditions have grown dire and Israel says Hamas fighters are embedded.</p>
                            <a href="#" class="text-blue-600 text-sm">See more updates <i class="fas fa-external-link-alt"></i></a>
                        </article>
                        <!-- Repeat for each news item -->
                    </div>
                    <div class="col-span-1">
                        <article class="mb-4">
                            <img src="https://placehold.co/300x200?text=News+Image" alt="Flares and plumes of smoke over the northern Gaza skyline on Tuesday." class="mb-2">
                            <h2 class="text-xl font-bold mb-2">From Elvis to Elopements, the Evolution of the Las Vegas Wedding</h2>
                            <p class="text-gray-700 mb-2">The glittering city that attracts thousands of couples seeking unconventional nuptials has grown beyond the drive-through wedding.</p>
                            <a href="#" class="text-blue-600 text-sm">8 MIN READ</a>
                        </article>
                        <!-- Repeat for each news item -->
                    </div>
                </div>
            </section>
        </main>
    </div>
</body>
</html>
"""

NO_IMAGES_NYTIMES_MOCK_CODE = """
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The New York Times - News</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Libre+Franklin:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: 'Libre Franklin', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <div class="container mx-auto px-4">
        <header class="border-b border-gray-300 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <button class="text-gray-700"><i class="fas fa-bars"></i></button>
                    <button class="text-gray-700"><i class="fas fa-search"></i></button>
                    <div class="text-xs uppercase tracking-widest">Tuesday, November 14, 2023<br>Today's Paper</div>
                </div>
                <div class="flex items-center space-x-4">
                    <button class="bg-black text-white px-4 py-1 text-xs uppercase tracking-widest">Give the times</button>
                    <div class="text-xs">Account</div>
                </div>
            </div>
            <nav class="flex justify-between items-center py-4">
                <div class="flex space-x-4">
                    <a href="#" class="text-xs uppercase tracking-widest text-gray-700">U.S.</a>
                    <!-- Add other navigation links as needed -->
                </div>
                <div class="flex space-x-4">
                    <a href="#" class="text-xs uppercase tracking-widest text-gray-700">Cooking</a>
                    <!-- Add other navigation links as needed -->
                </div>
            </nav>
        </header>
        <main>
            <section class="py-6">
                <div class="grid grid-cols-3 gap-4">
                    <div class="col-span-2">
                        <article class="mb-4">
                            <h2 class="text-xl font-bold mb-2">Israeli Military Raids Gaza's Largest Hospital</h2>
                            <p class="text-gray-700 mb-2">Israeli troops have entered the Al-Shifa Hospital complex, where conditions have grown dire and Israel says Hamas fighters are embedded.</p>
                            <a href="#" class="text-blue-600 text-sm">See more updates <i class="fas fa-external-link-alt"></i></a>
                        </article>
                        <!-- Repeat for each news item -->
                    </div>
                    <div class="col-span-1">
                        <article class="mb-4">
                            <h2 class="text-xl font-bold mb-2">From Elvis to Elopements, the Evolution of the Las Vegas Wedding</h2>
                            <p class="text-gray-700 mb-2">The glittering city that attracts thousands of couples seeking unconventional nuptials has grown beyond the drive-through wedding.</p>
                            <a href="#" class="text-blue-600 text-sm">8 MIN READ</a>
                        </article>
                        <!-- Repeat for each news item -->
                    </div>
                </div>
            </section>
        </main>
    </div>
</body>
</html>
"""

MORTGAGE_CALCULATOR_VIDEO_PROMPT_MOCK = """
<thinking>
The user flow in the video seems to be:
1. The calculator starts with some default values for loan amount, loan term, interest rate, etc. 
2. The user toggles the "Include taxes & fees" checkbox which shows an explanation tooltip.
3. The user selects different loan terms from the dropdown, which updates the monthly payment amount.
4. The user enters a custom loan amount.
5. The user selects a different loan term (30-yr fixed FHA).
6. The user enters additional details like home price, down payment, state, credit score, property tax, home insurance, and HOA fees.
7. The calculator updates the total monthly payment breakdown.

To build this:
- Use a container div for the whole calculator
- Have sections for Monthly Payment, Purchase Budget, loan details, additional costs
- Use input fields, dropdowns, and checkboxes for user input
- Update values dynamically using JavaScript when inputs change
- Show/hide explanation tooltip when checkbox is toggled
- Update monthly payment whenever loan amount, interest rate or term is changed
- Allow selecting loan term from a dropdown 
- Update total monthly payment breakdown as additional costs are entered
- Style everything to match the screenshots using Tailwind utility classes
</thinking>

<html>
<head>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
<div class="max-w-lg mx-auto bg-white shadow-lg rounded-lg p-6 font-sans">
  <div class="text-2xl font-semibold mb-6">Mortgage Calculator</div>
  
  <div class="flex justify-between text-sm uppercase font-semibold text-gray-500 border-b mb-4">
    <div class="pb-2 border-b-2 border-blue-500">Monthly payment</div>
    <div class="pb-2">Purchase budget</div>
  </div>

  <div class="flex items-center mb-4">
    <input type="checkbox" class="mr-2 taxes-toggle" id="taxesToggle">
    <label for="taxesToggle" class="text-sm">Include taxes & fees</label>
    <i class="fas fa-info-circle ml-1 text-gray-400 cursor-pointer" id="taxesInfo"></i>
    <div class="hidden bg-gray-100 text-xs p-2 ml-2 rounded" id="taxesTooltip">Your total monthly payment is more than just your mortgage. It can include property taxes, homeowners insurance, and HOA fees, among other things.</div>
  </div>

  <div class="text-3xl font-semibold mb-4">$<span id="monthlyPayment">1,696</span></div>

  <div class="mb-4">
    <div class="text-sm font-semibold mb-2">Loan amount</div>
    <input type="text" value="240,000" class="w-full border rounded px-2 py-1 text-lg" id="loanAmount">
  </div>

  <div class="mb-4">
    <div class="text-sm font-semibold mb-2">Loan term</div>
    <select class="w-full border rounded px-2 py-1 text-lg" id="loanTerm">
      <option>30-yr fixed</option>
      <option>30-yr fixed FHA</option>
      <option>30-yr fixed VA</option>
      <option>30-yr fixed USDA</option>
      <option>20-yr fixed</option>
      <option>15-yr fixed</option>
      <option>10 / 6 ARM</option>
      <option>7 / 6 ARM</option>
      <option>5 / 6 ARM</option>
      <option>3 / 6 ARM</option>
    </select>
  </div>

  <div class="flex justify-between mb-4">
    <div>
      <div class="text-sm font-semibold mb-2">Interest</div>
      <div class="text-lg">7.61 %</div>
    </div>
    <i class="fas fa-info-circle text-gray-400 cursor-pointer self-center"></i>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Home price</div>
      <input type="text" value="300,000" class="w-full border rounded px-2 py-1 text-lg" id="homePrice">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Down payment</div>
      <div class="flex">
        <input type="text" value="60,000" class="w-full border rounded-l px-2 py-1 text-lg" id="downPayment">
        <div class="bg-gray-200 rounded-r px-4 py-1 text-lg flex items-center">20 %</div>
      </div>
    </div>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">State</div>
      <select class="w-full border rounded px-2 py-1 text-lg" id="state">
        <option>New York</option>
      </select>
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Credit score</div>
      <select class="w-full border rounded px-2 py-1 text-lg" id="creditScore">
        <option>700 - 719</option>
      </select>
    </div>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Property tax (yearly)</div>
      <input type="text" value="3,750" class="w-full border rounded px-2 py-1 text-lg" id="propertyTax">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Home insurance (yearly)</div>
      <input type="text" value="1,050" class="w-full border rounded px-2 py-1 text-lg" id="homeInsurance">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Private mortgage insurance (monthly)</div>
      <input type="text" value="0" class="w-full border rounded px-2 py-1 text-lg" id="mortgageInsurance">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Homeowners association (monthly)</div>
      <input type="text" value="0" class="w-full border rounded px-2 py-1 text-lg" id="hoaFees">
    </div>
  </div>

  <div class="flex justify-between pt-4">
    <div class="text-sm">
      <div class="font-semibold">Total monthly payment</div>
      <div class="text-3xl font-semibold">$<span id="totalPayment">2,036</span></div>
    </div>
    <div class="text-right">
      <div class="text-sm">Loan</div>
      <div class="text-lg">$<span id="loanPayment">1,635</span></div>
      <div class="text-sm">Taxes & fees</div>
      <div>$<span id="taxesPayment">401</span></div>
    </div>
  </div>

  <div class="text-xs text-gray-500 mt-4">
    <div>Disclaimer • Feedback</div>
  </div>
</div>

<script>
$(document).ready(function() {
  var loanAmount = 240000;
  var interestRate = 7.61;
  var loanTerm = 30;
  var homePrice = 300000;
  var downPayment = 60000;
  var propertyTax = 3750;
  var homeInsurance = 1050;
  var mortgageInsurance = 0;
  var hoaFees = 0;

  function updateCalculations() {
    var principal = loanAmount;
    var monthlyInterest = interestRate / 100 / 12;
    var numPayments = loanTerm * 12;
    var monthlyPayment = principal * monthlyInterest / (1 - (Math.pow(1/(1 + monthlyInterest), numPayments)));
    var totalPayment = monthlyPayment;
    var taxesPayment = (propertyTax + homeInsurance) / 12;

    if ($('#taxesToggle').is(':checked')) {
      totalPayment += taxesPayment + mortgageInsurance + hoaFees;
    }

    $('#monthlyPayment').text(Math.round(monthlyPayment).toLocaleString());
    $('#loanPayment').text(Math.round(monthlyPayment).toLocaleString());
    $('#taxesPayment').text(Math.round(taxesPayment + mortgageInsurance + hoaFees).toLocaleString());
    $('#totalPayment').text(Math.round(totalPayment).toLocaleString());
  }

  $('#taxesInfo').hover(function() {
    $('#taxesTooltip').removeClass('hidden');
  }, function() {
    $('#taxesTooltip').addClass('hidden');
  });

  $('#loanTerm').change(function() {
    loanTerm = parseInt($(this).val().split('-')[0]);
    updateCalculations();
  });

  $('#loanAmount').change(function() {
    loanAmount = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#homePrice').change(function() {
    homePrice = parseInt($(this).val().replace(/,/g, ''));
    loanAmount = homePrice - downPayment;
    $('#loanAmount').val(loanAmount.toLocaleString());
    updateCalculations();
  });

  $('#downPayment').change(function() {
    downPayment = parseInt($(this).val().replace(/,/g, ''));
    loanAmount = homePrice - downPayment;
    $('#loanAmount').val(loanAmount.toLocaleString());
    updateCalculations();
  });

  $('#propertyTax').change(function() {
    propertyTax = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#homeInsurance').change(function() {
    homeInsurance = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#mortgageInsurance').change(function() {
    mortgageInsurance = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#hoaFees').change(function() {
    hoaFees = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  updateCalculations();
});
</script>
</body>
</html>

<thinking>
More things to consider:
- Add validation to input fields to prevent non-numeric values
- Add a reset button to clear all inputs and reset to default values
</thinking>

<html>
<head>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
<div class="max-w-lg mx-auto bg-black text-white shadow-lg rounded-lg p-6 font-sans">
  <div class="text-2xl font-semibold mb-6">Mortgage Calculator</div>
  
  <div class="flex justify-between text-sm uppercase font-semibold text-gray-500 border-b mb-4">
    <div class="pb-2 border-b-2 border-blue-500">Monthly payment</div>
    <div class="pb-2">Purchase budget</div>
  </div>

  <div class="flex items-center mb-4">
    <input type="checkbox" class="mr-2 taxes-toggle" id="taxesToggle">
    <label for="taxesToggle" class="text-sm">Include taxes & fees</label>
    <i class="fas fa-info-circle ml-1 text-gray-400 cursor-pointer" id="taxesInfo"></i>
    <div class="hidden bg-gray-100 text-xs p-2 ml-2 rounded" id="taxesTooltip">Your total monthly payment is more than just your mortgage. It can include property taxes, homeowners insurance, and HOA fees, among other things.</div>
  </div>

  <div class="text-3xl font-semibold mb-4">$<span id="monthlyPayment">1,696</span></div>

  <div class="mb-4">
    <div class="text-sm font-semibold mb-2">Loan amount</div>
    <input type="text" value="240,000" class="w-full border rounded px-2 py-1 text-lg" id="loanAmount">
  </div>

  <div class="mb-4">
    <div class="text-sm font-semibold mb-2">Loan term</div>
    <select class="w-full border rounded px-2 py-1 text-lg" id="loanTerm">
      <option>30-yr fixed</option>
      <option>30-yr fixed FHA</option>
      <option>30-yr fixed VA</option>
      <option>30-yr fixed USDA</option>
      <option>20-yr fixed</option>
      <option>15-yr fixed</option>
      <option>10 / 6 ARM</option>
      <option>7 / 6 ARM</option>
      <option>5 / 6 ARM</option>
      <option>3 / 6 ARM</option>
    </select>
  </div>

  <div class="flex justify-between mb-4">
    <div>
      <div class="text-sm font-semibold mb-2">Interest</div>
      <div class="text-lg">7.61 %</div>
    </div>
    <i class="fas fa-info-circle text-gray-400 cursor-pointer self-center"></i>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Home price</div>
      <input type="text" value="300,000" class="w-full border rounded px-2 py-1 text-lg" id="homePrice">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Down payment</div>
      <div class="flex">
        <input type="text" value="60,000" class="w-full border rounded-l px-2 py-1 text-lg" id="downPayment">
        <div class="bg-gray-200 rounded-r px-4 py-1 text-lg flex items-center">20 %</div>
      </div>
    </div>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">State</div>
      <select class="w-full border rounded px-2 py-1 text-lg" id="state">
        <option>New York</option>
      </select>
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Credit score</div>
      <select class="w-full border rounded px-2 py-1 text-lg" id="creditScore">
        <option>700 - 719</option>
      </select>
    </div>
  </div>

  <div class="border-t pt-4">
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Property tax (yearly)</div>
      <input type="text" value="3,750" class="w-full border rounded px-2 py-1 text-lg" id="propertyTax">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Home insurance (yearly)</div>
      <input type="text" value="1,050" class="w-full border rounded px-2 py-1 text-lg" id="homeInsurance">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Private mortgage insurance (monthly)</div>
      <input type="text" value="0" class="w-full border rounded px-2 py-1 text-lg" id="mortgageInsurance">
    </div>
    <div class="mb-4">
      <div class="text-sm font-semibold mb-2">Homeowners association (monthly)</div>
      <input type="text" value="0" class="w-full border rounded px-2 py-1 text-lg" id="hoaFees">
    </div>
  </div>

  <div class="flex justify-between pt-4">
    <div class="text-sm">
      <div class="font-semibold">Total monthly payment</div>
      <div class="text-3xl font-semibold">$<span id="totalPayment">2,036</span></div>
    </div>
    <div class="text-right">
      <div class="text-sm">Loan</div>
      <div class="text-lg">$<span id="loanPayment">1,635</span></div>
      <div class="text-sm">Taxes & fees</div>
      <div>$<span id="taxesPayment">401</span></div>
    </div>
  </div>

  <div class="text-xs text-gray-500 mt-4">
    <div>Disclaimer • Feedback</div>
  </div>
</div>

<script>
$(document).ready(function() {
  var loanAmount = 240000;
  var interestRate = 7.61;
  var loanTerm = 30;
  var homePrice = 300000;
  var downPayment = 60000;
  var propertyTax = 3750;
  var homeInsurance = 1050;
  var mortgageInsurance = 0;
  var hoaFees = 0;

  function updateCalculations() {
    var principal = loanAmount;
    var monthlyInterest = interestRate / 100 / 12;
    var numPayments = loanTerm * 12;
    var monthlyPayment = principal * monthlyInterest / (1 - (Math.pow(1/(1 + monthlyInterest), numPayments)));
    var totalPayment = monthlyPayment;
    var taxesPayment = (propertyTax + homeInsurance) / 12;

    if ($('#taxesToggle').is(':checked')) {
      totalPayment += taxesPayment + mortgageInsurance + hoaFees;
    }

    $('#monthlyPayment').text(Math.round(monthlyPayment).toLocaleString());
    $('#loanPayment').text(Math.round(monthlyPayment).toLocaleString());
    $('#taxesPayment').text(Math.round(taxesPayment + mortgageInsurance + hoaFees).toLocaleString());
    $('#totalPayment').text(Math.round(totalPayment).toLocaleString());
  }

  $('#taxesInfo').hover(function() {
    $('#taxesTooltip').removeClass('hidden');
  }, function() {
    $('#taxesTooltip').addClass('hidden');
  });

  $('#loanTerm').change(function() {
    loanTerm = parseInt($(this).val().split('-')[0]);
    updateCalculations();
  });

  $('#loanAmount').change(function() {
    loanAmount = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#homePrice').change(function() {
    homePrice = parseInt($(this).val().replace(/,/g, ''));
    loanAmount = homePrice - downPayment;
    $('#loanAmount').val(loanAmount.toLocaleString());
    updateCalculations();
  });

  $('#downPayment').change(function() {
    downPayment = parseInt($(this).val().replace(/,/g, ''));
    loanAmount = homePrice - downPayment;
    $('#loanAmount').val(loanAmount.toLocaleString());
    updateCalculations();
  });

  $('#propertyTax').change(function() {
    propertyTax = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#homeInsurance').change(function() {
    homeInsurance = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#mortgageInsurance').change(function() {
    mortgageInsurance = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  $('#hoaFees').change(function() {
    hoaFees = parseInt($(this).val().replace(/,/g, ''));
    updateCalculations();
  });

  updateCalculations();
});
</script>
</body>
</html>

"""

GOOGLE_FORM_VIDEO_PROMPT_MOCK = """

<thinking>User flow:
1. User starts on the Google search page and types in "times" in the search bar
2. As the user types, Google provides autocomplete suggestions related to "times"
3. User selects the "times" suggestion from the autocomplete dropdown
4. The search results page for "times" loads, showing various results related to The New York Times newspaper
5. User clicks the "Generate" button under "Get an AI-powered overview for this search?"
6. An AI-generated overview about The New York Times loads on the right side of the search results

Code structure:
- HTML structure with header, search bar, autocomplete dropdown, search button
- Search results area to display search results
- Sidebar area to display the AI-generated overview
- Use Tailwind CSS utility classes for styling
- Use jQuery to handle user interactions:
  - Typing in search bar to show/filter autocomplete suggestions
  - Selecting autocomplete suggestion to populate search bar
  - Clicking search button to display search results
  - Clicking "Generate" button to display AI overview
- Hardcode search results and AI overview content for demo purposes
</thinking>

<html>
<head>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
</head>
<body>

<div class="flex flex-col h-screen">
  <div class="flex items-center gap-4 px-5 py-3">
    <img class="w-24" src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png" alt="Google logo">
    <div class="flex-grow relative">
      <input type="text" id="search" class="w-full px-4 py-2 text-lg border border-gray-200 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="Search Google or type a URL">
      <div id="autocomplete" class="absolute w-full bg-white border border-gray-100 rounded-md shadow-lg z-10 hidden">
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">times</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">ts-ebml</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">tiktok ceo</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">two videos</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Taskrabbit</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">translate</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Target</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Taylor Swift</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Travis Kelce</div>
        <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Temu</div>
      </div>
    </div>
    <button id="search-btn" class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded-md ml-2">
      <i class="fas fa-search"></i>
    </button>
    <img class="w-8 h-8 rounded-full ml-4" src="https://via.placeholder.com/150" alt="Profile picture of the user">
  </div>
  
  <div class="flex-grow overflow-y-auto">
    <div id="search-results" class="p-8 hidden">
      <div class="text-sm text-gray-600 mb-4">Results for New York, NY 10022 - Choose area</div>
      
      <div class="bg-blue-50 p-4 mb-4">
        <button id="overview-btn" class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded-md">Get an AI-powered overview for this search?</button>
      </div>
      
      <div class="mb-4">
        <div class="text-xl text-blue-800 mb-1">
          <a href="https://www.nytimes.com">The New York Times</a>
        </div>
        <div class="text-sm text-gray-800 mb-1">https://www.nytimes.com</div>
        <div class="text-sm text-gray-600">
          The New York Times - Breaking News, US News, World News ...
        </div>
        <div class="text-sm text-gray-600">  
          Live news, investigations, opinion, photos and video by the journalists of The New York Times from more than 150 countries around the world.
        </div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Opinion | The House Vote to Force TikTok's Sale Is a Mistake - The ...</div>
        <div class="text-sm text-gray-600">Why Are Lawmakers Trying to Ban TikTok Instead of Doing What ...</div>
      </div>

      <div class="mb-4">  
        <div class="text-sm text-gray-600 mb-1">The Crossword</div>
        <div class="text-sm text-gray-600">Play the Daily New York Times Crossword puzzle edited by Will ...</div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Today's Paper</div>
        <div class="text-sm text-gray-600">Today's Paper · The Front Page · Highlights · Lawyer, Author ...</div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Word game Wordle</div>
        <div class="text-sm text-gray-600">Get 6 chances to guess a 5-letter word.Get 6 chances to guess a ...</div>
      </div>

      <div>
        <div class="text-sm text-gray-600">Connections</div>
        <div class="text-sm text-gray-600">A look at the links between The Times and the world it covers.</div>
      </div>
    </div>
    
    <div id="overview" class="p-8 hidden">
      <h2 class="text-2xl font-bold mb-4">The New York Times</h2>
      <div class="mb-4">
        <div class="font-bold">Newspaper</div>
      </div>
      <div class="mb-4">  
        <div class="font-bold">Owner:</div>
        <div>The New York Times Company</div>
      </div>
      <div class="mb-4">
        <div class="font-bold">Publisher:</div>  
        <div>The New York Times Company</div>
      </div>
      <div class="mb-4">
        <div class="font-bold">Founders:</div>
        <div>George Jones, Henry Jarvis Raymond</div>  
      </div>
      <div class="mb-4">
        <div class="font-bold">Circulation:</div>
        <div>10,360,000 news subscribers (as of February 2024)</div>
      </div>
      <div class="mb-4">  
        <div class="font-bold">Editor-in-chief:</div>
        <div>Joseph Kahn</div>
      </div>
      <div class="mb-4">
        <div class="font-bold">Format:</div>
        <div>Broadsheet</div>
      </div>
      <div>  
        <div class="font-bold">Founded:</div> 
        <div>September 18, 1851; 172 years ago</div>
      </div>
    </div>
  </div>
</div>

<script>
$(document).ready(function() {
  let selectedText = "";
  
  $("#search").on("input", function() {
    const searchText = $(this).val().trim();
    
    if (searchText !== "") {
      $("#autocomplete").removeClass("hidden");
      $("#autocomplete div").each(function() {
        if ($(this).text().toLowerCase().startsWith(searchText.toLowerCase())) {
          $(this).removeClass("hidden");
        } else {
          $(this).addClass("hidden");
        }
      });
    } else {
      $("#autocomplete").addClass("hidden");
    }
  });
  
  $("#autocomplete div").click(function() {
    selectedText = $(this).text();
    $("#search").val(selectedText);
    $("#autocomplete").addClass("hidden");
  });
  
  $("#search-btn").click(function() {
    if (selectedText !== "") {
      $("#search-results").removeClass("hidden");
      $("#overview").addClass("hidden");
    }
  });
  
  $("#overview-btn").click(function() {
    $("#overview").removeClass("hidden");
  });
});
</script>

</body>
</html>

<thinking>
To improve the app further and make it fully functional like the original video:

1. Add more visual styling to match the original, including:
   - Google logo and favicon
   - User profile icon
   - Search bar styling and hover effects
   - Search button icon and styling
   - Fonts and text sizes
   - Spacing and layout adjustments

2. Implement the search functionality:
   - Perform a search when the user presses Enter or clicks the search button
   - Show a loading state while searching
   - Display the search results dynamically based on the query
   - Handle cases when no results are found

3. Enhance the autocomplete functionality:
   - Fetch autocomplete suggestions from a data source based on the user's input
   - Highlight the text match in the suggestions
   - Allow navigating the suggestions with arrow keys
   - Update the search input when a suggestion is selected

4. Improve the AI-powered overview:
   - Fetch the overview content dynamically based on the search query
   - Display a loading state while generating the overview
   - Enhance the styling of the overview to match the original

5. Add additional UI elements:
   - Header navigation tabs (About, Store, Gmail, Images)
   - Footer links (Advertising, Business, How Search works, Privacy, Terms)
   - Pagination for search results
   - Feedback link

6. Optimize performance:
   - Lazy-load images and content
   - Implement caching mechanisms
   - Minify and compress assets

7. Ensure responsiveness:
   - Make the layout responsive and mobile-friendly
   - Adjust font sizes, padding, and margins for different screen sizes
   - Hide/collapse certain elements on smaller screens

8. Enhance accessibility:
   - Add appropriate ARIA attributes
   - Ensure keyboard navigation works properly
   - Provide alternative text for images

9. Implement error handling:
   - Handle network errors gracefully
   - Display user-friendly error messages
   - Provide options to retry or refresh

10. Add smooth animations and transitions:
    - Fade in/out effects for loading states
    - Smooth sliding animations for autocomplete suggestions
    - Subtle hover and click animations for interactive elements
</thinking>

<html>
<head>
  <title>Google Search</title>
  <link rel="icon" href="https://www.google.com/favicon.ico" type="image/x-icon">
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
</head>
<body class="font-roboto">

<div class="flex flex-col min-h-screen">
  <header class="flex items-center justify-end space-x-4 px-5 py-2 text-sm text-gray-700">
    <a href="#" class="hover:underline">About</a>
    <a href="#" class="hover:underline">Store</a>
    <a href="#" class="hover:underline">Gmail</a>
    <a href="#" class="hover:underline">Images</a>
    <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/150" alt="Profile picture of the user">
  </header>
  
  <div class="flex items-center justify-center flex-grow">
    <div class="flex flex-col items-center w-full max-w-[584px]">
      <img class="w-[272px] mb-8" src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" alt="Google logo">
      <div class="relative w-full mb-3">
        <input type="text" id="search" class="w-full px-5 py-3 text-lg border border-gray-200 rounded-full hover:shadow-md focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="Search Google or type a URL" autocomplete="off">
        <div id="autocomplete" class="absolute w-full bg-white border border-gray-100 rounded-md shadow-lg z-10 hidden">
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">times</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">ts-ebml</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">tiktok ceo</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">two videos</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Taskrabbit</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">translate</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Target</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Taylor Swift</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Travis Kelce</div>
          <div class="px-4 py-2 hover:bg-gray-100 cursor-pointer">Temu</div>
        </div>
      </div>
      <div class="flex space-x-2">
        <button id="search-btn" class="bg-gray-100 hover:bg-gray-200 text-gray-800 px-4 py-2 rounded">Google Search</button>
        <button class="bg-gray-100 hover:bg-gray-200 text-gray-800 px-4 py-2 rounded">I'm Feeling Lucky</button>
      </div>
    </div>
  </div>
  
  <div id="search-results" class="flex-grow p-8 overflow-y-auto hidden">
    <div class="text-sm text-gray-600 mb-4">Results for New York, NY 10022 - Choose area</div>
    
    <div class="bg-blue-50 p-4 mb-4">
      <button id="overview-btn" class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded">Get an AI-powered overview for this search</button>
    </div>
    
    <div id="results-list">
      <div class="mb-4">
        <div class="text-xl text-blue-800 mb-1">
          <a href="https://www.nytimes.com">The New York Times</a>
        </div>
        <div class="text-sm text-gray-800 mb-1">https://www.nytimes.com</div>
        <div class="text-sm text-gray-600">
          The New York Times - Breaking News, US News, World News ...
        </div>
        <div class="text-sm text-gray-600">  
          Live news, investigations, opinion, photos and video by the journalists of The New York Times from more than 150 countries around the world.
        </div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Opinion | The House Vote to Force TikTok's Sale Is a Mistake - The ...</div>
        <div class="text-sm text-gray-600">Why Are Lawmakers Trying to Ban TikTok Instead of Doing What ...</div>
      </div>

      <div class="mb-4">  
        <div class="text-sm text-gray-600 mb-1">The Crossword</div>
        <div class="text-sm text-gray-600">Play the Daily New York Times Crossword puzzle edited by Will ...</div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Today's Paper</div>
        <div class="text-sm text-gray-600">Today's Paper · The Front Page · Highlights · Lawyer, Author ...</div>
      </div>

      <div class="mb-4">
        <div class="text-sm text-gray-600 mb-1">Word game Wordle</div>
        <div class="text-sm text-gray-600">Get 6 chances to guess a 5-letter word.Get 6 chances to guess a ...</div>
      </div>

      <div>
        <div class="text-sm text-gray-600">Connections</div>
        <div class="text-sm text-gray-600">A look at the links between The Times and the world it covers.</div>
      </div>
    </div>
    
    <div id="pagination" class="flex justify-center mt-8">
      <button class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded mr-2">Previous</button>
      <button class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded">Next</button>
    </div>
  </div>
  
  <div id="overview" class="flex-grow p-8 overflow-y-auto hidden">
    <h2 class="text-2xl font-medium mb-4">The New York Times</h2>
    <div class="mb-4">
      <div class="font-medium">Newspaper</div>
    </div>
    <div class="mb-4">  
      <div class="font-medium">Owner:</div>
      <div>The New York Times Company</div>
    </div>
    <div class="mb-4">
      <div class="font-medium">Publisher:</div>  
      <div>The New York Times Company</div>
    </div>
    <div class="mb-4">
      <div class="font-medium">Founders:</div>
      <div>George Jones, Henry Jarvis Raymond</div>  
    </div>
    <div class="mb-4">
      <div class="font-medium">Circulation:</div>
      <div>10,360,000 news subscribers (as of February 2024)</div>
    </div>
    <div class="mb-4">  
      <div class="font-medium">Editor-in-chief:</div>
      <div>Joseph Kahn</div>
    </div>
    <div class="mb-4">
      <div class="font-medium">Format:</div>
      <div>Broadsheet</div>
    </div>
    <div>  
      <div class="font-medium">Founded:</div> 
      <div>September 18, 1851; 172 years ago</div>
    </div>
  </div>
  
  <footer class="bg-gray-100 text-sm text-gray-600 px-8 py-3">
    <div class="flex justify-between">
      <div class="flex space-x-6">
        <a href="#" class="hover:underline">Advertising</a>
        <a href="#" class="hover:underline">Business</a>
        <a href="#" class="hover:underline">How Search works</a>
      </div>
      <div class="flex space-x-6">
        <a href="#" class="hover:underline">Privacy</a>
        <a href="#" class="hover:underline">Terms</a>
        <a href="#" class="hover:underline">Settings</a>
      </div>
    </div>
  </footer>
</div>

<script>
$(document).ready(function() {
  let selectedText = "";
  
  $("#search").on("input", function() {
    const searchText = $(this).val().trim();
    
    if (searchText !== "") {
      $("#autocomplete").removeClass("hidden");
      $("#autocomplete div").each(function() {
        if ($(this).text().toLowerCase().includes(searchText.toLowerCase())) {
          $(this).removeClass("hidden");
          $(this).html($(this).text().replace(new RegExp(searchText, "gi"), "<strong>$&</strong>"));
        } else {
          $(this).addClass("hidden");
        }
      });
    } else {
      $("#autocomplete").addClass("hidden");
    }
  });
  
  $("#autocomplete div").click(function() {
    selectedText = $(this).text();
    $("#search").val(selectedText);
    $("#autocomplete").addClass("hidden");
  });
  
  $("#search").keydown(function(e) {
    if (e.which === 13) {
      performSearch();
    }
  });
  
  $("#search-btn").click(performSearch);
  
  $("#overview-btn").click(function() {
    $("#overview").removeClass("hidden");
    $("#search-results").addClass("hidden");
  });
  
  function performSearch() {
    const query = $("#search").val().trim();
    if (query !== "") {
      $("#search-results").removeClass("hidden");
      $("#overview").addClass("hidden");
      
      // Simulating search results for demo purposes
      $("#results-list").empty();
      for (let i = 0; i < 6; i++) {
        $("#results-list").append(`
          <div class="mb-4">
            <div class="text-xl text-blue-800 mb-1">
              <a href="#">Search Result ${i + 1}</a>
            </div>
            <div class="text-sm text-gray-800 mb-1">https://example.com/result${i + 1}</div>
            <div class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nulla sit amet aliquam lacinia, nisl nisl aliquam nisl, nec aliquam nisl nisl sit amet nisl.
            </div>
          </div>
        `);
      }
    }
  }
});
</script>

</body>
</html>
"""

TALLY_FORM_VIDEO_PROMPT_MOCK = """
<thinking>
The user flow in the video seems to be:
1. The quiz starts by asking "What is the capital of Bulgaria?" with three multiple choice options. The user selects "Sofia".
2. The next question asks "What is the most famous dish in Belgium?" with two image-based options. The user selects "Steak with fries".
3. The next question asks "What is the name of this actor?" with an image of an older man with gray hair and beard. The user types in "Clooney" and submits the answer.
4. The quiz ends showing the user's score of 10/30 and a "Bummer, try again!" message with an arrow to restart.

To build this as a functional web app:
1. Create the overall page structure with a title, question area, answer options area, and next/submit buttons.
2. Use jQuery to show/hide different questions and update the answer options based on the current question. 
3. Store the questions, answer options, and correct answers in a Javascript array.
4. Keep track of the user's selections and compare them to the correct answers to calculate the score.
5. After the last question, show the final score and restart option.
6. Style everything to match the screenshots using Tailwind utility classes.
</thinking>

<html>
<!DOCTYPE html>
<html>
<head>
  <title>Online Trivia Quiz</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
</head>
<body class="bg-white text-gray-800 p-6">
  <h1 class="text-2xl font-bold mb-4">Online Trivia Quiz</h1>
  
  <div id="question-container" class="mb-6">
    <h2 id="question" class="text-xl mb-4"></h2>
    <div id="options" class="space-y-4"></div>
  </div>
  
  <div id="actor-container" class="mb-6 hidden">
    <img id="actor-image" src="" alt="" class="mb-4 w-2/3 mx-auto rounded-lg">
    <input type="text" id="actor-answer" class="border rounded w-full py-2 px-3 text-gray-700 mb-3">
  </div>

  <div id="result-container" class="text-center hidden">
    <h2 class="text-xl mb-2">Bummer, try again!</h2>
    <p id="score" class="text-lg mb-4"></p>
    <button id="restart-btn" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
      <i class="fas fa-redo mr-2"></i> Restart
    </button>
  </div>

  <button id="next-btn" class="bg-black hover:bg-gray-800 text-white font-bold py-2 px-4 rounded">
    Next <i class="fas fa-arrow-right ml-2"></i>
  </button>
  
  <button id="submit-btn" class="bg-black hover:bg-gray-800 text-white font-bold py-2 px-4 rounded hidden">
    Submit <i class="fas fa-arrow-right ml-2"></i>
  </button>

  <script>
    const quizData = [
      {
        question: "What is the capital of Bulgaria?",
        options: ["Sofia", "Plovdiv", "Varna"],
        answer: "Sofia"
      },
      {
        question: "What is the most famous dish in Belgium?", 
        options: [
          {
            image: "https://via.placeholder.com/300x200?text=Spaghetti",
            alt: "A bowl of spaghetti pasta with tomato sauce and parmesan cheese on top",
            text: "Spaghetti"
          },
          {
            image: "https://via.placeholder.com/300x200?text=Steak+with+fries",
            alt: "A plate with grilled steak, french fries, and greens",
            text: "Steak with fries"
          }
        ],
        answer: "Steak with fries"
      },
      {
        question: "What is the name of this actor?",
        image: "https://via.placeholder.com/400x300?text=Older+man+with+gray+hair+and+beard",
        alt: "Headshot of an older man with gray hair and a gray beard wearing a black suit and bowtie",
        answer: "Clooney"
      }
    ];

    let currentQuestion = 0;
    let score = 0;

    function startQuiz() {
      currentQuestion = 0;
      score = 0;
      $("#question-container").show();
      $("#actor-container").hide();
      $("#result-container").hide();
      $("#next-btn").show();
      $("#submit-btn").hide();
      showQuestion();
    }

    function showQuestion() {
      const questionData = quizData[currentQuestion];
      $("#question").text(questionData.question);
      
      if (questionData.options) {
        let optionsHtml = "";
        for (let option of questionData.options) {
          if (typeof option === "string") {
            optionsHtml += `
              <div>
                <label>
                  <input type="radio" name="answer" value="${option}">
                  ${option}
                </label>
              </div>
            `;
          } else {
            optionsHtml += `
              <div>
                <label>
                  <input type="radio" name="answer" value="${option.text}">
                  <img src="${option.image}" alt="${option.alt}" class="w-full mb-2">
                  ${option.text}
                </label>
              </div>
            `;
          }
        }
        $("#options").html(optionsHtml);
        $("#actor-container").hide();
      } else {
        $("#options").empty();
        $("#actor-image").attr("src", questionData.image).attr("alt", questionData.alt);
        $("#actor-answer").val("");
        $("#actor-container").show();
        $("#next-btn").hide();
        $("#submit-btn").show();
      }
    }

    function checkAnswer() {
      const questionData = quizData[currentQuestion];
      
      let userAnswer;
      if (questionData.options) {
        userAnswer = $("input[name='answer']:checked").val();
      } else {
        userAnswer = $("#actor-answer").val().trim();
      }

      if (userAnswer === questionData.answer) {
        score++;
      }

      currentQuestion++;
      
      if (currentQuestion < quizData.length) {
        showQuestion();
      } else {
        showResult();
      }
    }

    function showResult() {
      $("#question-container").hide();
      $("#actor-container").hide();
      $("#score").text(`Your score is: ${score} / ${quizData.length}`);
      $("#result-container").show();
    }

    $("#next-btn").click(checkAnswer);
    $("#submit-btn").click(checkAnswer);
    $("#restart-btn").click(startQuiz);

    startQuiz();
  </script>
</body>
</html>
</html>

This implements the online trivia quiz app as shown in the video. It uses jQuery to handle the interactions and Tailwind CSS for styling. The questions, options, and answers are defined in the quizData array. The app keeps track of the user's current question and score, allows selecting or entering answers, and displays the final score at the end with the option to restart.

<thinking>
To further improve the app to match the original video:

1. Adjust the styling to more closely match the font, colors, spacing, and layout in the screenshots. 
2. Add a cursor pointer when hovering over answer options.
3. Improve the styling of the selected answer option.
4. Make the "Next" button change to an arrow icon on hover.
5. Add a "Back" button to go to the previous question.
6. Show the current question number and total (e.g. "Question 1 of 3").
7. Animate the transitions between questions.
8. Improve the responsive layout for different screen sizes.
9. Preload the images to avoid flickering.
10. Refactor the code to be more modular and maintainable.
</thinking>

<html>
<!DOCTYPE html>
<html>
<head>
  <title>Online Trivia Quiz</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');
    body {
      font-family: 'Roboto', sans-serif;
    }
    .option {
      cursor: pointer;
    }
    .option.selected {
      background-color: #EFF6FF;
      border-color: #2563EB;
    }
    #next-btn:hover i {
      transform: translateX(5px);
    }
  </style>
</head>
<body class="bg-white text-gray-800 p-6">
  <h1 class="text-3xl font-bold mb-8 text-center">Online Trivia Quiz</h1>
  
  <div class="max-w-xl mx-auto">
    <div id="question-container" class="mb-8">
      <div class="flex justify-between mb-4">
        <button id="back-btn" class="text-blue-600 hover:text-blue-800 font-medium py-2 px-4 rounded">
          <i class="fas fa-arrow-left mr-2"></i> Back
        </button>
        <span id="question-number" class="text-lg font-medium"></span>
      </div>
      <h2 id="question" class="text-2xl font-medium mb-6"></h2>
      <div id="options" class="space-y-4"></div>
    </div>
    
    <div id="actor-container" class="mb-8 hidden">
      <img id="actor-image" src="" alt="" class="mb-6 mx-auto rounded-lg">
      <input type="text" id="actor-answer" class="border border-gray-400 rounded w-full py-2 px-4 text-lg mb-4 focus:outline-none focus:ring-2 focus:ring-blue-600">
    </div>

    <div id="result-container" class="text-center hidden">
      <h2 class="text-2xl font-medium mb-2">Bummer, try again!</h2>
      <p id="score" class="text-xl mb-6"></p>
      <button id="restart-btn" class="bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-4 rounded">
        <i class="fas fa-redo mr-2"></i> Restart
      </button>
    </div>

    <button id="next-btn" class="bg-black hover:bg-gray-800 text-white font-medium py-2 px-4 rounded flex items-center ml-auto">
      Next <i class="fas fa-arrow-right ml-2"></i>
    </button>
    
    <button id="submit-btn" class="bg-black hover:bg-gray-800 text-white font-medium py-2 px-4 rounded flex items-center ml-auto hidden">
      Submit <i class="fas fa-arrow-right ml-2"></i>
    </button>
  </div>

  <script>
    const quizData = [
      {
        question: "What is the capital of Bulgaria?",
        options: ["Sofia", "Plovdiv", "Varna"],
        answer: "Sofia"
      },
      {
        question: "What is the most famous dish in Belgium?", 
        options: [
          {
            image: "https://sdxl-trainings.s3.amazonaws.com/DALL%C2%B7E+2024-03-08+12.29.30+-+A+bowl+of+spaghetti+pasta+with+tomato+sauce+and+parmesan+cheese+on+top%2C+set+on+a+rustic+wooden+table.+The+light+is+soft+and+warm%2C+enhancing+the+vibran.webp",
            alt: "A bowl of spaghetti pasta with tomato sauce and parmesan cheese on top",
            text: "Spaghetti"
          },
          {
            image: "https://sdxl-trainings.s3.amazonaws.com/DALL%C2%B7E+2024-03-08+12.33.19+-+A+plate+with+grilled+steak%2C+french+fries%2C+and+greens%2C+presented+elegantly.+The+steak+is+perfectly+cooked+to+medium+rare%2C+showing+a+rich%2C+pink+center+a.webp",
            alt: "A plate with grilled steak, french fries, and greens",
            text: "Steak with fries"
          }
        ],
        answer: "Steak with fries"
      },
      {
        question: "What is the name of this actor?",
        image: "https://sdxl-trainings.s3.amazonaws.com/DALL%C2%B7E+2024-03-08+12.34.00+-+Headshot+of+an+older+man+with+distinguished+gray+hair+and+a+neatly+trimmed+gray+beard%2C+conveying+a+sense+of+wisdom+and+experience.+He+is+wearing+a+cri.webp",
        alt: "Headshot of an older man with gray hair and a gray beard wearing a black suit and bowtie",
        answer: "Clooney"
      }
    ];

    let currentQuestion = 0;
    let score = 0;

    function startQuiz() {
      currentQuestion = 0;
      score = 0;
      $("#question-container").show();
      $("#actor-container").hide();
      $("#result-container").hide();
      $("#next-btn").show();
      $("#submit-btn").hide();
      showQuestion();
    }

    function showQuestion() {
      const questionData = quizData[currentQuestion];
      $("#question").text(questionData.question);
      $("#question-number").text(`Question ${currentQuestion + 1} of ${quizData.length}`);
      
      if (questionData.options) {
        let optionsHtml = "";
        for (let option of questionData.options) {
          if (typeof option === "string") {
            optionsHtml += `
              <div class="option p-4 border border-gray-300 rounded flex items-center">
                <input type="radio" name="answer" id="${option}" value="${option}" class="mr-4">
                <label for="${option}" class="text-lg font-medium flex-grow cursor-pointer">${option}</label>
              </div>
            `;
          } else {
            optionsHtml += `
              <div class="option p-4 border border-gray-300 rounded flex items-center">
                <input type="radio" name="answer" id="${option.text}" value="${option.text}" class="mr-4">
                <label for="${option.text}" class="flex-grow cursor-pointer">
                  <img src="${option.image}" alt="${option.alt}" class="w-full mb-2 rounded">
                  <span class="text-lg font-medium">${option.text}</span>
                </label>
              </div>
            `;
          }
        }
        $("#options").html(optionsHtml);
        $("#actor-container").hide();
      } else {
        $("#options").empty();
        $("#actor-image").attr("src", questionData.image).attr("alt", questionData.alt);
        $("#actor-answer").val("");
        $("#actor-container").show();
        $("#next-btn").hide();
        $("#submit-btn").show();
      }
      
      $("#back-btn").toggle(currentQuestion > 0);
    }

    function checkAnswer() {
      const questionData = quizData[currentQuestion];
      
      let userAnswer;
      if (questionData.options) {
        userAnswer = $("input[name='answer']:checked").val();
      } else {
        userAnswer = $("#actor-answer").val().trim();
      }

      if (userAnswer === questionData.answer) {
        score++;
      }

      currentQuestion++;
      
      if (currentQuestion < quizData.length) {
        $("#question-container").fadeOut(200, function() {
          showQuestion();
          $(this).fadeIn(200);
        });
      } else {
        $("#question-container").fadeOut(200, function() {
          showResult();
          $("#result-container").fadeIn(200);
        });
      }
    }

    function previousQuestion() {
      if (currentQuestion > 0) {
        currentQuestion--;
        $("#question-container").fadeOut(200, function() {
          showQuestion();
          $(this).fadeIn(200);
        });
      }
    }

    function showResult() {
      $("#score").text(`Your score is: ${score} / ${quizData.length}`);
    }

    $("#next-btn").click(checkAnswer);
    $("#submit-btn").click(checkAnswer);
    $("#back-btn").click(previousQuestion);
    $("#restart-btn").click(function() {
      $("#result-container").fadeOut(200, function() {
        startQuiz();
        $("#question-container").fadeIn(200);
      });
    });

    $("body").on("change", "input[name='answer']", function() {
      $(".option").removeClass("selected");
      $(this).closest(".option").addClass("selected");
    });

    $(document).ready(function() {
      // Preload images
      let images = [];
      for (let question of quizData) {
        if (question.image) {
          images.push(question.image);
        } else if (question.options) {
          for (let option of question.options) {
            if (option.image) {
              images.push(option.image);
            }
          }
        }
      }
      preloadImages(images, startQuiz);
    });

    function preloadImages(urls, callback) {
      let count = 0;
      for (let url of urls) {
        $("<img>").attr("src", url).on("load", function() {
          count++;
          if (count === urls.length) {
            callback();
          }
        });
      }
    }
  </script>
</body>
</html>
</html>

This updated version makes several improvements to match the original app more closely:

1. Styling is refined to better match the font, colors, spacing, and layout of the screenshots.
2. Cursor changes to a pointer when hovering over answer options.
3. Selected answer option is highlighted.
4. "Next" button shows an animated arrow on hover.
5. "Back" button added to go to the previous question.
6. Current question number and total are displayed.
7. Fade transitions are added between questions.
8. Layout is made responsive for different screen sizes.
9. Images are preloaded to avoid flickering.
10. Code is refactored to be more modular and maintainable.

The app should now be fully functional and closely resemble the look and behavior of the original video. Let me know if you would like any further adjustments!
"""

```

## File: backend/pyproject.toml

- Extension: .toml
- Language: toml
- Size: 665 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```toml
[tool.poetry]
name = "backend"
version = "0.1.0"
description = ""
authors = ["Abi Raja <abimanyuraja@gmail.com>"]
license = "MIT"

[tool.poetry.dependencies]
python = "^3.10"
fastapi = "^0.115.6"
uvicorn = "^0.25.0"
websockets = "^14.1"
openai = "^1.2.4"
python-dotenv = "^1.0.0"
beautifulsoup4 = "^4.12.2"
httpx = "^0.25.1"
pre-commit = "^3.6.2"
anthropic = "^0.37.1"
moviepy = "^1.0.3"
pillow = "^10.3.0"
types-pillow = "^10.2.0.20240520"
aiohttp = "^3.9.5"
pydantic = "^2.10"
google-genai = "^0.3.0"

[tool.poetry.group.dev.dependencies]
pytest = "^7.4.3"
pyright = "^1.1.352"

[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"

```

## File: backend/llm.py

- Extension: .py
- Language: python
- Size: 10365 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import copy
from enum import Enum
import base64
import time
from typing import Any, Awaitable, Callable, List, cast, TypedDict
from anthropic import AsyncAnthropic
from openai import AsyncOpenAI
from openai.types.chat import ChatCompletionMessageParam, ChatCompletionChunk
from config import IS_DEBUG_ENABLED
from debug.DebugFileWriter import DebugFileWriter
from image_processing.utils import process_image
from google import genai
from google.genai import types

from utils import pprint_prompt


# Actual model versions that are passed to the LLMs and stored in our logs
class Llm(Enum):
    GPT_4_VISION = "gpt-4-vision-preview"
    GPT_4_TURBO_2024_04_09 = "gpt-4-turbo-2024-04-09"
    GPT_4O_2024_05_13 = "gpt-4o-2024-05-13"
    GPT_4O_2024_08_06 = "gpt-4o-2024-08-06"
    GPT_4O_2024_11_20 = "gpt-4o-2024-11-20"
    CLAUDE_3_SONNET = "claude-3-sonnet-20240229"
    CLAUDE_3_OPUS = "claude-3-opus-20240229"
    CLAUDE_3_HAIKU = "claude-3-haiku-20240307"
    CLAUDE_3_5_SONNET_2024_06_20 = "claude-3-5-sonnet-20240620"
    CLAUDE_3_5_SONNET_2024_10_22 = "claude-3-5-sonnet-20241022"
    GEMINI_2_0_FLASH_EXP = "gemini-2.0-flash-exp"
    O1_2024_12_17 = "o1-2024-12-17"


class Completion(TypedDict):
    duration: float
    code: str


async def stream_openai_response(
    messages: List[ChatCompletionMessageParam],
    api_key: str,
    base_url: str | None,
    callback: Callable[[str], Awaitable[None]],
    model: Llm,
) -> Completion:
    start_time = time.time()
    client = AsyncOpenAI(api_key=api_key, base_url=base_url)

    # Base parameters
    params = {
        "model": model.value,
        "messages": messages,
        "timeout": 600,
    }

    # O1 doesn't support streaming or temperature
    if model != Llm.O1_2024_12_17:
        params["temperature"] = 0
        params["stream"] = True

    # Add 'max_tokens' corresponding to the model
    if model == Llm.GPT_4O_2024_05_13:
        params["max_tokens"] = 4096

    if model == Llm.GPT_4O_2024_11_20:
        params["max_tokens"] = 16384

    if model == Llm.O1_2024_12_17:
        params["max_completion_tokens"] = 20000

    # O1 doesn't support streaming
    if model == Llm.O1_2024_12_17:
        response = await client.chat.completions.create(**params)  # type: ignore
        full_response = response.choices[0].message.content  # type: ignore
    else:
        stream = await client.chat.completions.create(**params)  # type: ignore
        full_response = ""
        async for chunk in stream:  # type: ignore
            assert isinstance(chunk, ChatCompletionChunk)
            if (
                chunk.choices
                and len(chunk.choices) > 0
                and chunk.choices[0].delta
                and chunk.choices[0].delta.content
            ):
                content = chunk.choices[0].delta.content or ""
                full_response += content
                await callback(content)

    await client.close()

    completion_time = time.time() - start_time
    return {"duration": completion_time, "code": full_response}


# TODO: Have a seperate function that translates OpenAI messages to Claude messages
async def stream_claude_response(
    messages: List[ChatCompletionMessageParam],
    api_key: str,
    callback: Callable[[str], Awaitable[None]],
    model: Llm,
) -> Completion:
    start_time = time.time()
    client = AsyncAnthropic(api_key=api_key)

    # Base parameters
    max_tokens = 8192
    temperature = 0.0

    # Translate OpenAI messages to Claude messages

    # Deep copy messages to avoid modifying the original list
    cloned_messages = copy.deepcopy(messages)

    system_prompt = cast(str, cloned_messages[0].get("content"))
    claude_messages = [dict(message) for message in cloned_messages[1:]]
    for message in claude_messages:
        if not isinstance(message["content"], list):
            continue

        for content in message["content"]:  # type: ignore
            if content["type"] == "image_url":
                content["type"] = "image"

                # Extract base64 data and media type from data URL
                # Example base64 data URL: data:image/png;base64,iVBOR...
                image_data_url = cast(str, content["image_url"]["url"])

                # Process image and split media type and data
                # so it works with Claude (under 5mb in base64 encoding)
                (media_type, base64_data) = process_image(image_data_url)

                # Remove OpenAI parameter
                del content["image_url"]

                content["source"] = {
                    "type": "base64",
                    "media_type": media_type,
                    "data": base64_data,
                }

    # Stream Claude response
    async with client.messages.stream(
        model=model.value,
        max_tokens=max_tokens,
        temperature=temperature,
        system=system_prompt,
        messages=claude_messages,  # type: ignore
        extra_headers={"anthropic-beta": "max-tokens-3-5-sonnet-2024-07-15"},
    ) as stream:
        async for text in stream.text_stream:
            await callback(text)

    # Return final message
    response = await stream.get_final_message()

    # Close the Anthropic client
    await client.close()

    completion_time = time.time() - start_time
    return {"duration": completion_time, "code": response.content[0].text}


async def stream_claude_response_native(
    system_prompt: str,
    messages: list[Any],
    api_key: str,
    callback: Callable[[str], Awaitable[None]],
    include_thinking: bool = False,
    model: Llm = Llm.CLAUDE_3_OPUS,
) -> Completion:
    start_time = time.time()
    client = AsyncAnthropic(api_key=api_key)

    # Base model parameters
    max_tokens = 4096
    temperature = 0.0

    # Multi-pass flow
    current_pass_num = 1
    max_passes = 2

    prefix = "<thinking>"
    response = None

    # For debugging
    full_stream = ""
    debug_file_writer = DebugFileWriter()

    while current_pass_num <= max_passes:
        current_pass_num += 1

        # Set up message depending on whether we have a <thinking> prefix
        messages_to_send = (
            messages + [{"role": "assistant", "content": prefix}]
            if include_thinking
            else messages
        )

        pprint_prompt(messages_to_send)

        async with client.messages.stream(
            model=model.value,
            max_tokens=max_tokens,
            temperature=temperature,
            system=system_prompt,
            messages=messages_to_send,  # type: ignore
        ) as stream:
            async for text in stream.text_stream:
                print(text, end="", flush=True)
                full_stream += text
                await callback(text)

        response = await stream.get_final_message()
        response_text = response.content[0].text

        # Write each pass's code to .html file and thinking to .txt file
        if IS_DEBUG_ENABLED:
            debug_file_writer.write_to_file(
                f"pass_{current_pass_num - 1}.html",
                debug_file_writer.extract_html_content(response_text),
            )
            debug_file_writer.write_to_file(
                f"thinking_pass_{current_pass_num - 1}.txt",
                response_text.split("</thinking>")[0],
            )

        # Set up messages array for next pass
        messages += [
            {"role": "assistant", "content": str(prefix) + response.content[0].text},
            {
                "role": "user",
                "content": "You've done a good job with a first draft. Improve this further based on the original instructions so that the app is fully functional and looks like the original video of the app we're trying to replicate.",
            },
        ]

        print(
            f"Token usage: Input Tokens: {response.usage.input_tokens}, Output Tokens: {response.usage.output_tokens}"
        )

    # Close the Anthropic client
    await client.close()

    completion_time = time.time() - start_time

    if IS_DEBUG_ENABLED:
        debug_file_writer.write_to_file("full_stream.txt", full_stream)

    if not response:
        raise Exception("No HTML response found in AI response")
    else:
        return {
            "duration": completion_time,
            "code": response.content[0].text,  # type: ignore
        }


async def stream_gemini_response(
    messages: List[ChatCompletionMessageParam],
    api_key: str,
    callback: Callable[[str], Awaitable[None]],
    model: Llm,
) -> Completion:
    start_time = time.time()

    # Extract image URLs from messages
    image_urls = []
    for content_part in messages[-1]["content"]:  # type: ignore
        if content_part["type"] == "image_url":  # type: ignore
            image_url = content_part["image_url"]["url"]  # type: ignore
            if image_url.startswith("data:"):  # type: ignore
                # Extract base64 data and mime type for data URLs
                mime_type = image_url.split(";")[0].split(":")[1]  # type: ignore
                base64_data = image_url.split(",")[1]  # type: ignore
                image_urls = [{"mime_type": mime_type, "data": base64_data}]  # type: ignore
            else:
                # Store regular URLs
                image_urls = [{"uri": image_url}]  # type: ignore
            break  # Exit after first image URL

    client = genai.Client(api_key=api_key)  # type: ignore
    full_response = ""
    async for response in client.aio.models.generate_content_stream(  # type: ignore
        model=model.value,
        contents={
            "parts": [
                {"text": messages[0]["content"]},  # type: ignore
                types.Part.from_bytes(  # type: ignore
                    data=base64.b64decode(image_urls[0]["data"]),  # type: ignore
                    mime_type=image_urls[0]["mime_type"],  # type: ignore
                ),
            ]  # type: ignore
        },  # type: ignore
        config=types.GenerateContentConfig(  # type: ignore
            temperature=0, max_output_tokens=8192
        ),
    ):  # type: ignore
        if response.text:  # type: ignore
            full_response += response.text  # type: ignore
            await callback(response.text)  # type: ignore
    completion_time = time.time() - start_time
    return {"duration": completion_time, "code": full_response}

```

## File: backend/start.py

- Extension: .py
- Language: python
- Size: 95 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import uvicorn

if __name__ == "__main__":
    uvicorn.run("main:app", port=7001, reload=True)

```

## File: backend/README.md

- Extension: .md
- Language: markdown
- Size: 75 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
# Run the type checker

poetry run pyright

# Run tests

poetry run pytest

```

## File: backend/run_evals.py

- Extension: .py
- Language: python
- Size: 1754 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Load environment variables first
from dotenv import load_dotenv

load_dotenv()

import asyncio
from evals.runner import run_image_evals


async def main():
    await run_image_evals()


# async def text_main():
#     OUTPUT_DIR = EVALS_DIR + "/outputs"

#     GENERAL_TEXT_V1 = [
#         "Login form",
#         "Simple notification",
#         "button",
#         "saas dashboard",
#         "landing page for barber shop",
#     ]

#     tasks: list[Coroutine[Any, Any, str]] = []
#     for prompt in GENERAL_TEXT_V1:
#         for n in range(N):  # Generate N tasks for each input
#             if n == 0:
#                 task = generate_code_for_text(
#                     text=prompt,
#                     stack=STACK,
#                     model=Llm.CLAUDE_3_5_SONNET_2024_06_20,
#                 )
#             else:
#                 task = generate_code_for_text(
#                     text=prompt, stack=STACK, model=Llm.GPT_4O_2024_05_13
#                 )
#             tasks.append(task)

#     print(f"Generating {len(tasks)} codes")

#     results = await asyncio.gather(*tasks)

#     os.makedirs(OUTPUT_DIR, exist_ok=True)

#     for i, content in enumerate(results):
#         # Calculate index for filename and output number
#         eval_index = i // N
#         output_number = i % N
#         filename = GENERAL_TEXT_V1[eval_index]
#         # File name is derived from the original filename in evals with an added output number
#         output_filename = f"{os.path.splitext(filename)[0]}_{output_number}.html"
#         output_filepath = os.path.join(OUTPUT_DIR, output_filename)
#         with open(output_filepath, "w") as file:
#             file.write(content)

if __name__ == "__main__":
    asyncio.run(main())

```

## File: backend/.gitignore

- Extension: 
- Language: unknown
- Size: 2860 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# C extensions
*.so

# Distribution / packaging
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
share/python-wheels/
*.egg-info/
.installed.cfg
*.egg
MANIFEST

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.nox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
*.py,cover
.hypothesis/
.pytest_cache/
cover/

# Translations
*.mo
*.pot

# Django stuff:
*.log
local_settings.py
db.sqlite3
db.sqlite3-journal

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/

# PyBuilder
.pybuilder/
target/

# Jupyter Notebook
.ipynb_checkpoints

# IPython
profile_default/
ipython_config.py

# pyenv
#   For a library or package, you might want to ignore these files since the code is
#   intended to run in multiple environments; otherwise, check them in:
# .python-version

# pipenv
#   According to pypa/pipenv#598, it is recommended to include Pipfile.lock in version control.
#   However, in case of collaboration, if having platform-specific dependencies or dependencies
#   having no cross-platform support, pipenv may install dependencies that don't work, or not
#   install all needed dependencies.
#Pipfile.lock

# poetry
#   Similar to Pipfile.lock, it is generally recommended to include poetry.lock in version control.
#   This is especially recommended for binary packages to ensure reproducibility, and is more
#   commonly ignored for libraries.
#   https://python-poetry.org/docs/basic-usage/#commit-your-poetrylock-file-to-version-control
#poetry.lock

# PEP 582; used by e.g. github.com/David-OConnor/pyflow
__pypackages__/

# Celery stuff
celerybeat-schedule
celerybeat.pid

# SageMath parsed files
*.sage.py

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# Spyder project settings
.spyderproject
.spyproject

# Rope project settings
.ropeproject

# mkdocs documentation
/site

# mypy
.mypy_cache/
.dmypy.json
dmypy.json

# Pyre type checker
.pyre/

# pytype static type analyzer
.pytype/

# Cython debug symbols
cython_debug/

# PyCharm
#  JetBrains specific template is maintainted in a separate JetBrains.gitignore that can
#  be found at https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore
#  and can be added to the global gitignore or merged into this file.  For a more nuclear
#  option (not recommended) you can uncomment the following to ignore the entire idea folder.
#.idea/


# Temporary eval output
evals_data


# Temporary video evals (Remove before merge)
video_evals

```

## File: backend/utils.py

- Extension: .py
- Language: python
- Size: 1285 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import copy
import json
from typing import List
from openai.types.chat import ChatCompletionMessageParam


def pprint_prompt(prompt_messages: List[ChatCompletionMessageParam]):
    print(json.dumps(truncate_data_strings(prompt_messages), indent=4))


def truncate_data_strings(data: List[ChatCompletionMessageParam]):  # type: ignore
    # Deep clone the data to avoid modifying the original object
    cloned_data = copy.deepcopy(data)

    if isinstance(cloned_data, dict):
        for key, value in cloned_data.items():  # type: ignore
            # Recursively call the function if the value is a dictionary or a list
            if isinstance(value, (dict, list)):
                cloned_data[key] = truncate_data_strings(value)  # type: ignore
            # Truncate the string if it it's long and add ellipsis and length
            elif isinstance(value, str):
                cloned_data[key] = value[:40]  # type: ignore
                if len(value) > 40:
                    cloned_data[key] += "..." + f" ({len(value)} chars)"  # type: ignore

    elif isinstance(cloned_data, list):  # type: ignore
        # Process each item in the list
        cloned_data = [truncate_data_strings(item) for item in cloned_data]  # type: ignore

    return cloned_data  # type: ignore

```

## File: backend/custom_types.py

- Extension: .py
- Language: python
- Size: 78 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from typing import Literal


InputMode = Literal[
    "image",
    "video",
]

```

## File: backend/poetry.lock

- Extension: .lock
- Language: unknown
- Size: 201698 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```unknown
# This file is automatically @generated by Poetry 1.7.1 and should not be changed by hand.

[[package]]
name = "aiohappyeyeballs"
version = "2.4.4"
description = "Happy Eyeballs for asyncio"
optional = false
python-versions = ">=3.8"
files = [
    {file = "aiohappyeyeballs-2.4.4-py3-none-any.whl", hash = "sha256:a980909d50efcd44795c4afeca523296716d50cd756ddca6af8c65b996e27de8"},
    {file = "aiohappyeyeballs-2.4.4.tar.gz", hash = "sha256:5fdd7d87889c63183afc18ce9271f9b0a7d32c2303e394468dd45d514a757745"},
]

[[package]]
name = "aiohttp"
version = "3.11.11"
description = "Async http client/server framework (asyncio)"
optional = false
python-versions = ">=3.9"
files = [
    {file = "aiohttp-3.11.11-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:a60804bff28662cbcf340a4d61598891f12eea3a66af48ecfdc975ceec21e3c8"},
    {file = "aiohttp-3.11.11-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:4b4fa1cb5f270fb3eab079536b764ad740bb749ce69a94d4ec30ceee1b5940d5"},
    {file = "aiohttp-3.11.11-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:731468f555656767cda219ab42e033355fe48c85fbe3ba83a349631541715ba2"},
    {file = "aiohttp-3.11.11-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:cb23d8bb86282b342481cad4370ea0853a39e4a32a0042bb52ca6bdde132df43"},
    {file = "aiohttp-3.11.11-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f047569d655f81cb70ea5be942ee5d4421b6219c3f05d131f64088c73bb0917f"},
    {file = "aiohttp-3.11.11-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:dd7659baae9ccf94ae5fe8bfaa2c7bc2e94d24611528395ce88d009107e00c6d"},
    {file = "aiohttp-3.11.11-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:af01e42ad87ae24932138f154105e88da13ce7d202a6de93fafdafb2883a00ef"},
    {file = "aiohttp-3.11.11-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:5854be2f3e5a729800bac57a8d76af464e160f19676ab6aea74bde18ad19d438"},
    {file = "aiohttp-3.11.11-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:6526e5fb4e14f4bbf30411216780c9967c20c5a55f2f51d3abd6de68320cc2f3"},
    {file = "aiohttp-3.11.11-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:85992ee30a31835fc482468637b3e5bd085fa8fe9392ba0bdcbdc1ef5e9e3c55"},
    {file = "aiohttp-3.11.11-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:88a12ad8ccf325a8a5ed80e6d7c3bdc247d66175afedbe104ee2aaca72960d8e"},
    {file = "aiohttp-3.11.11-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:0a6d3fbf2232e3a08c41eca81ae4f1dff3d8f1a30bae415ebe0af2d2458b8a33"},
    {file = "aiohttp-3.11.11-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:84a585799c58b795573c7fa9b84c455adf3e1d72f19a2bf498b54a95ae0d194c"},
    {file = "aiohttp-3.11.11-cp310-cp310-win32.whl", hash = "sha256:bfde76a8f430cf5c5584553adf9926534352251d379dcb266ad2b93c54a29745"},
    {file = "aiohttp-3.11.11-cp310-cp310-win_amd64.whl", hash = "sha256:0fd82b8e9c383af11d2b26f27a478640b6b83d669440c0a71481f7c865a51da9"},
    {file = "aiohttp-3.11.11-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:ba74ec819177af1ef7f59063c6d35a214a8fde6f987f7661f4f0eecc468a8f76"},
    {file = "aiohttp-3.11.11-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:4af57160800b7a815f3fe0eba9b46bf28aafc195555f1824555fa2cfab6c1538"},
    {file = "aiohttp-3.11.11-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:ffa336210cf9cd8ed117011085817d00abe4c08f99968deef0013ea283547204"},
    {file = "aiohttp-3.11.11-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:81b8fe282183e4a3c7a1b72f5ade1094ed1c6345a8f153506d114af5bf8accd9"},
    {file = "aiohttp-3.11.11-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:3af41686ccec6a0f2bdc66686dc0f403c41ac2089f80e2214a0f82d001052c03"},
    {file = "aiohttp-3.11.11-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:70d1f9dde0e5dd9e292a6d4d00058737052b01f3532f69c0c65818dac26dc287"},
    {file = "aiohttp-3.11.11-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:249cc6912405917344192b9f9ea5cd5b139d49e0d2f5c7f70bdfaf6b4dbf3a2e"},
    {file = "aiohttp-3.11.11-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:0eb98d90b6690827dcc84c246811feeb4e1eea683c0eac6caed7549be9c84665"},
    {file = "aiohttp-3.11.11-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:ec82bf1fda6cecce7f7b915f9196601a1bd1a3079796b76d16ae4cce6d0ef89b"},
    {file = "aiohttp-3.11.11-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:9fd46ce0845cfe28f108888b3ab17abff84ff695e01e73657eec3f96d72eef34"},
    {file = "aiohttp-3.11.11-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:bd176afcf8f5d2aed50c3647d4925d0db0579d96f75a31e77cbaf67d8a87742d"},
    {file = "aiohttp-3.11.11-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:ec2aa89305006fba9ffb98970db6c8221541be7bee4c1d027421d6f6df7d1ce2"},
    {file = "aiohttp-3.11.11-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:92cde43018a2e17d48bb09c79e4d4cb0e236de5063ce897a5e40ac7cb4878773"},
    {file = "aiohttp-3.11.11-cp311-cp311-win32.whl", hash = "sha256:aba807f9569455cba566882c8938f1a549f205ee43c27b126e5450dc9f83cc62"},
    {file = "aiohttp-3.11.11-cp311-cp311-win_amd64.whl", hash = "sha256:ae545f31489548c87b0cced5755cfe5a5308d00407000e72c4fa30b19c3220ac"},
    {file = "aiohttp-3.11.11-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:e595c591a48bbc295ebf47cb91aebf9bd32f3ff76749ecf282ea7f9f6bb73886"},
    {file = "aiohttp-3.11.11-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:3ea1b59dc06396b0b424740a10a0a63974c725b1c64736ff788a3689d36c02d2"},
    {file = "aiohttp-3.11.11-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:8811f3f098a78ffa16e0ea36dffd577eb031aea797cbdba81be039a4169e242c"},
    {file = "aiohttp-3.11.11-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:bd7227b87a355ce1f4bf83bfae4399b1f5bb42e0259cb9405824bd03d2f4336a"},
    {file = "aiohttp-3.11.11-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d40f9da8cabbf295d3a9dae1295c69975b86d941bc20f0a087f0477fa0a66231"},
    {file = "aiohttp-3.11.11-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:ffb3dc385f6bb1568aa974fe65da84723210e5d9707e360e9ecb51f59406cd2e"},
    {file = "aiohttp-3.11.11-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a8f5f7515f3552d899c61202d99dcb17d6e3b0de777900405611cd747cecd1b8"},
    {file = "aiohttp-3.11.11-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:3499c7ffbfd9c6a3d8d6a2b01c26639da7e43d47c7b4f788016226b1e711caa8"},
    {file = "aiohttp-3.11.11-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:8e2bf8029dbf0810c7bfbc3e594b51c4cc9101fbffb583a3923aea184724203c"},
    {file = "aiohttp-3.11.11-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:b6212a60e5c482ef90f2d788835387070a88d52cf6241d3916733c9176d39eab"},
    {file = "aiohttp-3.11.11-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:d119fafe7b634dbfa25a8c597718e69a930e4847f0b88e172744be24515140da"},
    {file = "aiohttp-3.11.11-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:6fba278063559acc730abf49845d0e9a9e1ba74f85f0ee6efd5803f08b285853"},
    {file = "aiohttp-3.11.11-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:92fc484e34b733704ad77210c7957679c5c3877bd1e6b6d74b185e9320cc716e"},
    {file = "aiohttp-3.11.11-cp312-cp312-win32.whl", hash = "sha256:9f5b3c1ed63c8fa937a920b6c1bec78b74ee09593b3f5b979ab2ae5ef60d7600"},
    {file = "aiohttp-3.11.11-cp312-cp312-win_amd64.whl", hash = "sha256:1e69966ea6ef0c14ee53ef7a3d68b564cc408121ea56c0caa2dc918c1b2f553d"},
    {file = "aiohttp-3.11.11-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:541d823548ab69d13d23730a06f97460f4238ad2e5ed966aaf850d7c369782d9"},
    {file = "aiohttp-3.11.11-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:929f3ed33743a49ab127c58c3e0a827de0664bfcda566108989a14068f820194"},
    {file = "aiohttp-3.11.11-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:0882c2820fd0132240edbb4a51eb8ceb6eef8181db9ad5291ab3332e0d71df5f"},
    {file = "aiohttp-3.11.11-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b63de12e44935d5aca7ed7ed98a255a11e5cb47f83a9fded7a5e41c40277d104"},
    {file = "aiohttp-3.11.11-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:aa54f8ef31d23c506910c21163f22b124facb573bff73930735cf9fe38bf7dff"},
    {file = "aiohttp-3.11.11-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a344d5dc18074e3872777b62f5f7d584ae4344cd6006c17ba12103759d407af3"},
    {file = "aiohttp-3.11.11-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:0b7fb429ab1aafa1f48578eb315ca45bd46e9c37de11fe45c7f5f4138091e2f1"},
    {file = "aiohttp-3.11.11-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:c341c7d868750e31961d6d8e60ff040fb9d3d3a46d77fd85e1ab8e76c3e9a5c4"},
    {file = "aiohttp-3.11.11-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:ed9ee95614a71e87f1a70bc81603f6c6760128b140bc4030abe6abaa988f1c3d"},
    {file = "aiohttp-3.11.11-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:de8d38f1c2810fa2a4f1d995a2e9c70bb8737b18da04ac2afbf3971f65781d87"},
    {file = "aiohttp-3.11.11-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:a9b7371665d4f00deb8f32208c7c5e652059b0fda41cf6dbcac6114a041f1cc2"},
    {file = "aiohttp-3.11.11-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:620598717fce1b3bd14dd09947ea53e1ad510317c85dda2c9c65b622edc96b12"},
    {file = "aiohttp-3.11.11-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:bf8d9bfee991d8acc72d060d53860f356e07a50f0e0d09a8dfedea1c554dd0d5"},
    {file = "aiohttp-3.11.11-cp313-cp313-win32.whl", hash = "sha256:9d73ee3725b7a737ad86c2eac5c57a4a97793d9f442599bea5ec67ac9f4bdc3d"},
    {file = "aiohttp-3.11.11-cp313-cp313-win_amd64.whl", hash = "sha256:c7a06301c2fb096bdb0bd25fe2011531c1453b9f2c163c8031600ec73af1cc99"},
    {file = "aiohttp-3.11.11-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:3e23419d832d969f659c208557de4a123e30a10d26e1e14b73431d3c13444c2e"},
    {file = "aiohttp-3.11.11-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:21fef42317cf02e05d3b09c028712e1d73a9606f02467fd803f7c1f39cc59add"},
    {file = "aiohttp-3.11.11-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:1f21bb8d0235fc10c09ce1d11ffbd40fc50d3f08a89e4cf3a0c503dc2562247a"},
    {file = "aiohttp-3.11.11-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:1642eceeaa5ab6c9b6dfeaaa626ae314d808188ab23ae196a34c9d97efb68350"},
    {file = "aiohttp-3.11.11-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:2170816e34e10f2fd120f603e951630f8a112e1be3b60963a1f159f5699059a6"},
    {file = "aiohttp-3.11.11-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:8be8508d110d93061197fd2d6a74f7401f73b6d12f8822bbcd6d74f2b55d71b1"},
    {file = "aiohttp-3.11.11-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4eed954b161e6b9b65f6be446ed448ed3921763cc432053ceb606f89d793927e"},
    {file = "aiohttp-3.11.11-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:d6c9af134da4bc9b3bd3e6a70072509f295d10ee60c697826225b60b9959acdd"},
    {file = "aiohttp-3.11.11-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:44167fc6a763d534a6908bdb2592269b4bf30a03239bcb1654781adf5e49caf1"},
    {file = "aiohttp-3.11.11-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:479b8c6ebd12aedfe64563b85920525d05d394b85f166b7873c8bde6da612f9c"},
    {file = "aiohttp-3.11.11-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:10b4ff0ad793d98605958089fabfa350e8e62bd5d40aa65cdc69d6785859f94e"},
    {file = "aiohttp-3.11.11-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:b540bd67cfb54e6f0865ceccd9979687210d7ed1a1cc8c01f8e67e2f1e883d28"},
    {file = "aiohttp-3.11.11-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:1dac54e8ce2ed83b1f6b1a54005c87dfed139cf3f777fdc8afc76e7841101226"},
    {file = "aiohttp-3.11.11-cp39-cp39-win32.whl", hash = "sha256:568c1236b2fde93b7720f95a890741854c1200fba4a3471ff48b2934d2d93fd3"},
    {file = "aiohttp-3.11.11-cp39-cp39-win_amd64.whl", hash = "sha256:943a8b052e54dfd6439fd7989f67fc6a7f2138d0a2cf0a7de5f18aa4fe7eb3b1"},
    {file = "aiohttp-3.11.11.tar.gz", hash = "sha256:bb49c7f1e6ebf3821a42d81d494f538107610c3a705987f53068546b0e90303e"},
]

[package.dependencies]
aiohappyeyeballs = ">=2.3.0"
aiosignal = ">=1.1.2"
async-timeout = {version = ">=4.0,<6.0", markers = "python_version < \"3.11\""}
attrs = ">=17.3.0"
frozenlist = ">=1.1.1"
multidict = ">=4.5,<7.0"
propcache = ">=0.2.0"
yarl = ">=1.17.0,<2.0"

[package.extras]
speedups = ["Brotli", "aiodns (>=3.2.0)", "brotlicffi"]

[[package]]
name = "aiosignal"
version = "1.3.2"
description = "aiosignal: a list of registered asynchronous callbacks"
optional = false
python-versions = ">=3.9"
files = [
    {file = "aiosignal-1.3.2-py2.py3-none-any.whl", hash = "sha256:45cde58e409a301715980c2b01d0c28bdde3770d8290b5eb2173759d9acb31a5"},
    {file = "aiosignal-1.3.2.tar.gz", hash = "sha256:a8c255c66fafb1e499c9351d0bf32ff2d8a0321595ebac3b93713656d2436f54"},
]

[package.dependencies]
frozenlist = ">=1.1.0"

[[package]]
name = "annotated-types"
version = "0.7.0"
description = "Reusable constraint types to use with typing.Annotated"
optional = false
python-versions = ">=3.8"
files = [
    {file = "annotated_types-0.7.0-py3-none-any.whl", hash = "sha256:1f02e8b43a8fbbc3f3e0d4f0f4bfc8131bcb4eebe8849b8e5c773f3a1c582a53"},
    {file = "annotated_types-0.7.0.tar.gz", hash = "sha256:aff07c09a53a08bc8cfccb9c85b05f1aa9a2a6f23728d790723543408344ce89"},
]

[[package]]
name = "anthropic"
version = "0.37.1"
description = "The official Python library for the anthropic API"
optional = false
python-versions = ">=3.7"
files = [
    {file = "anthropic-0.37.1-py3-none-any.whl", hash = "sha256:8f550f88906823752e2abf99fbe491fbc8d40bce4cb26b9663abdf7be990d721"},
    {file = "anthropic-0.37.1.tar.gz", hash = "sha256:99f688265795daa7ba9256ee68eaf2f05d53cd99d7417f4a0c2dc292c106d00a"},
]

[package.dependencies]
anyio = ">=3.5.0,<5"
distro = ">=1.7.0,<2"
httpx = ">=0.23.0,<1"
jiter = ">=0.4.0,<1"
pydantic = ">=1.9.0,<3"
sniffio = "*"
tokenizers = ">=0.13.0"
typing-extensions = ">=4.7,<5"

[package.extras]
bedrock = ["boto3 (>=1.28.57)", "botocore (>=1.31.57)"]
vertex = ["google-auth (>=2,<3)"]

[[package]]
name = "anyio"
version = "4.7.0"
description = "High level compatibility layer for multiple asynchronous event loop implementations"
optional = false
python-versions = ">=3.9"
files = [
    {file = "anyio-4.7.0-py3-none-any.whl", hash = "sha256:ea60c3723ab42ba6fff7e8ccb0488c898ec538ff4df1f1d5e642c3601d07e352"},
    {file = "anyio-4.7.0.tar.gz", hash = "sha256:2f834749c602966b7d456a7567cafcb309f96482b5081d14ac93ccd457f9dd48"},
]

[package.dependencies]
exceptiongroup = {version = ">=1.0.2", markers = "python_version < \"3.11\""}
idna = ">=2.8"
sniffio = ">=1.1"
typing_extensions = {version = ">=4.5", markers = "python_version < \"3.13\""}

[package.extras]
doc = ["Sphinx (>=7.4,<8.0)", "packaging", "sphinx-autodoc-typehints (>=1.2.0)", "sphinx_rtd_theme"]
test = ["anyio[trio]", "coverage[toml] (>=7)", "exceptiongroup (>=1.2.0)", "hypothesis (>=4.0)", "psutil (>=5.9)", "pytest (>=7.0)", "pytest-mock (>=3.6.1)", "trustme", "truststore (>=0.9.1)", "uvloop (>=0.21)"]
trio = ["trio (>=0.26.1)"]

[[package]]
name = "async-timeout"
version = "5.0.1"
description = "Timeout context manager for asyncio programs"
optional = false
python-versions = ">=3.8"
files = [
    {file = "async_timeout-5.0.1-py3-none-any.whl", hash = "sha256:39e3809566ff85354557ec2398b55e096c8364bacac9405a7a1fa429e77fe76c"},
    {file = "async_timeout-5.0.1.tar.gz", hash = "sha256:d9321a7a3d5a6a5e187e824d2fa0793ce379a202935782d555d6e9d2735677d3"},
]

[[package]]
name = "attrs"
version = "24.3.0"
description = "Classes Without Boilerplate"
optional = false
python-versions = ">=3.8"
files = [
    {file = "attrs-24.3.0-py3-none-any.whl", hash = "sha256:ac96cd038792094f438ad1f6ff80837353805ac950cd2aa0e0625ef19850c308"},
    {file = "attrs-24.3.0.tar.gz", hash = "sha256:8f5c07333d543103541ba7be0e2ce16eeee8130cb0b3f9238ab904ce1e85baff"},
]

[package.extras]
benchmark = ["cloudpickle", "hypothesis", "mypy (>=1.11.1)", "pympler", "pytest (>=4.3.0)", "pytest-codspeed", "pytest-mypy-plugins", "pytest-xdist[psutil]"]
cov = ["cloudpickle", "coverage[toml] (>=5.3)", "hypothesis", "mypy (>=1.11.1)", "pympler", "pytest (>=4.3.0)", "pytest-mypy-plugins", "pytest-xdist[psutil]"]
dev = ["cloudpickle", "hypothesis", "mypy (>=1.11.1)", "pre-commit-uv", "pympler", "pytest (>=4.3.0)", "pytest-mypy-plugins", "pytest-xdist[psutil]"]
docs = ["cogapp", "furo", "myst-parser", "sphinx", "sphinx-notfound-page", "sphinxcontrib-towncrier", "towncrier (<24.7)"]
tests = ["cloudpickle", "hypothesis", "mypy (>=1.11.1)", "pympler", "pytest (>=4.3.0)", "pytest-mypy-plugins", "pytest-xdist[psutil]"]
tests-mypy = ["mypy (>=1.11.1)", "pytest-mypy-plugins"]

[[package]]
name = "beautifulsoup4"
version = "4.12.3"
description = "Screen-scraping library"
optional = false
python-versions = ">=3.6.0"
files = [
    {file = "beautifulsoup4-4.12.3-py3-none-any.whl", hash = "sha256:b80878c9f40111313e55da8ba20bdba06d8fa3969fc68304167741bbf9e082ed"},
    {file = "beautifulsoup4-4.12.3.tar.gz", hash = "sha256:74e3d1928edc070d21748185c46e3fb33490f22f52a3addee9aee0f4f7781051"},
]

[package.dependencies]
soupsieve = ">1.2"

[package.extras]
cchardet = ["cchardet"]
chardet = ["chardet"]
charset-normalizer = ["charset-normalizer"]
html5lib = ["html5lib"]
lxml = ["lxml"]

[[package]]
name = "cachetools"
version = "5.5.0"
description = "Extensible memoizing collections and decorators"
optional = false
python-versions = ">=3.7"
files = [
    {file = "cachetools-5.5.0-py3-none-any.whl", hash = "sha256:02134e8439cdc2ffb62023ce1debca2944c3f289d66bb17ead3ab3dede74b292"},
    {file = "cachetools-5.5.0.tar.gz", hash = "sha256:2cc24fb4cbe39633fb7badd9db9ca6295d766d9c2995f245725a46715d050f2a"},
]

[[package]]
name = "certifi"
version = "2024.12.14"
description = "Python package for providing Mozilla's CA Bundle."
optional = false
python-versions = ">=3.6"
files = [
    {file = "certifi-2024.12.14-py3-none-any.whl", hash = "sha256:1275f7a45be9464efc1173084eaa30f866fe2e47d389406136d332ed4967ec56"},
    {file = "certifi-2024.12.14.tar.gz", hash = "sha256:b650d30f370c2b724812bee08008be0c4163b163ddaec3f2546c1caf65f191db"},
]

[[package]]
name = "cfgv"
version = "3.4.0"
description = "Validate configuration and produce human readable error messages."
optional = false
python-versions = ">=3.8"
files = [
    {file = "cfgv-3.4.0-py2.py3-none-any.whl", hash = "sha256:b7265b1f29fd3316bfcd2b330d63d024f2bfd8bcb8b0272f8e19a504856c48f9"},
    {file = "cfgv-3.4.0.tar.gz", hash = "sha256:e52591d4c5f5dead8e0f673fb16db7949d2cfb3f7da4582893288f0ded8fe560"},
]

[[package]]
name = "charset-normalizer"
version = "3.4.0"
description = "The Real First Universal Charset Detector. Open, modern and actively maintained alternative to Chardet."
optional = false
python-versions = ">=3.7.0"
files = [
    {file = "charset_normalizer-3.4.0-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:4f9fc98dad6c2eaa32fc3af1417d95b5e3d08aff968df0cd320066def971f9a6"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:0de7b687289d3c1b3e8660d0741874abe7888100efe14bd0f9fd7141bcbda92b"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:5ed2e36c3e9b4f21dd9422f6893dec0abf2cca553af509b10cd630f878d3eb99"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:40d3ff7fc90b98c637bda91c89d51264a3dcf210cade3a2c6f838c7268d7a4ca"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:1110e22af8ca26b90bd6364fe4c763329b0ebf1ee213ba32b68c73de5752323d"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:86f4e8cca779080f66ff4f191a685ced73d2f72d50216f7112185dc02b90b9b7"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7f683ddc7eedd742e2889d2bfb96d69573fde1d92fcb811979cdb7165bb9c7d3"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:27623ba66c183eca01bf9ff833875b459cad267aeeb044477fedac35e19ba907"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:f606a1881d2663630ea5b8ce2efe2111740df4b687bd78b34a8131baa007f79b"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:0b309d1747110feb25d7ed6b01afdec269c647d382c857ef4663bbe6ad95a912"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:136815f06a3ae311fae551c3df1f998a1ebd01ddd424aa5603a4336997629e95"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:14215b71a762336254351b00ec720a8e85cada43b987da5a042e4ce3e82bd68e"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:79983512b108e4a164b9c8d34de3992f76d48cadc9554c9e60b43f308988aabe"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-win32.whl", hash = "sha256:c94057af19bc953643a33581844649a7fdab902624d2eb739738a30e2b3e60fc"},
    {file = "charset_normalizer-3.4.0-cp310-cp310-win_amd64.whl", hash = "sha256:55f56e2ebd4e3bc50442fbc0888c9d8c94e4e06a933804e2af3e89e2f9c1c749"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:0d99dd8ff461990f12d6e42c7347fd9ab2532fb70e9621ba520f9e8637161d7c"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:c57516e58fd17d03ebe67e181a4e4e2ccab1168f8c2976c6a334d4f819fe5944"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:6dba5d19c4dfab08e58d5b36304b3f92f3bd5d42c1a3fa37b5ba5cdf6dfcbcee"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:bf4475b82be41b07cc5e5ff94810e6a01f276e37c2d55571e3fe175e467a1a1c"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:ce031db0408e487fd2775d745ce30a7cd2923667cf3b69d48d219f1d8f5ddeb6"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:8ff4e7cdfdb1ab5698e675ca622e72d58a6fa2a8aa58195de0c0061288e6e3ea"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3710a9751938947e6327ea9f3ea6332a09bf0ba0c09cae9cb1f250bd1f1549bc"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:82357d85de703176b5587dbe6ade8ff67f9f69a41c0733cf2425378b49954de5"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:47334db71978b23ebcf3c0f9f5ee98b8d65992b65c9c4f2d34c2eaf5bcaf0594"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:8ce7fd6767a1cc5a92a639b391891bf1c268b03ec7e021c7d6d902285259685c"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:f1a2f519ae173b5b6a2c9d5fa3116ce16e48b3462c8b96dfdded11055e3d6365"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:63bc5c4ae26e4bc6be6469943b8253c0fd4e4186c43ad46e713ea61a0ba49129"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:bcb4f8ea87d03bc51ad04add8ceaf9b0f085ac045ab4d74e73bbc2dc033f0236"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-win32.whl", hash = "sha256:9ae4ef0b3f6b41bad6366fb0ea4fc1d7ed051528e113a60fa2a65a9abb5b1d99"},
    {file = "charset_normalizer-3.4.0-cp311-cp311-win_amd64.whl", hash = "sha256:cee4373f4d3ad28f1ab6290684d8e2ebdb9e7a1b74fdc39e4c211995f77bec27"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:0713f3adb9d03d49d365b70b84775d0a0d18e4ab08d12bc46baa6132ba78aaf6"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:de7376c29d95d6719048c194a9cf1a1b0393fbe8488a22008610b0361d834ecf"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:4a51b48f42d9358460b78725283f04bddaf44a9358197b889657deba38f329db"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b295729485b06c1a0683af02a9e42d2caa9db04a373dc38a6a58cdd1e8abddf1"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:ee803480535c44e7f5ad00788526da7d85525cfefaf8acf8ab9a310000be4b03"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:3d59d125ffbd6d552765510e3f31ed75ebac2c7470c7274195b9161a32350284"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:8cda06946eac330cbe6598f77bb54e690b4ca93f593dee1568ad22b04f347c15"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:07afec21bbbbf8a5cc3651aa96b980afe2526e7f048fdfb7f1014d84acc8b6d8"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:6b40e8d38afe634559e398cc32b1472f376a4099c75fe6299ae607e404c033b2"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:b8dcd239c743aa2f9c22ce674a145e0a25cb1566c495928440a181ca1ccf6719"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:84450ba661fb96e9fd67629b93d2941c871ca86fc38d835d19d4225ff946a631"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:44aeb140295a2f0659e113b31cfe92c9061622cadbc9e2a2f7b8ef6b1e29ef4b"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:1db4e7fefefd0f548d73e2e2e041f9df5c59e178b4c72fbac4cc6f535cfb1565"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-win32.whl", hash = "sha256:5726cf76c982532c1863fb64d8c6dd0e4c90b6ece9feb06c9f202417a31f7dd7"},
    {file = "charset_normalizer-3.4.0-cp312-cp312-win_amd64.whl", hash = "sha256:b197e7094f232959f8f20541ead1d9862ac5ebea1d58e9849c1bf979255dfac9"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:dd4eda173a9fcccb5f2e2bd2a9f423d180194b1bf17cf59e3269899235b2a114"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:e9e3c4c9e1ed40ea53acf11e2a386383c3304212c965773704e4603d589343ed"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:92a7e36b000bf022ef3dbb9c46bfe2d52c047d5e3f3343f43204263c5addc250"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:54b6a92d009cbe2fb11054ba694bc9e284dad30a26757b1e372a1fdddaf21920"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:1ffd9493de4c922f2a38c2bf62b831dcec90ac673ed1ca182fe11b4d8e9f2a64"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:35c404d74c2926d0287fbd63ed5d27eb911eb9e4a3bb2c6d294f3cfd4a9e0c23"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4796efc4faf6b53a18e3d46343535caed491776a22af773f366534056c4e1fbc"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e7fdd52961feb4c96507aa649550ec2a0d527c086d284749b2f582f2d40a2e0d"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:92db3c28b5b2a273346bebb24857fda45601aef6ae1c011c0a997106581e8a88"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:ab973df98fc99ab39080bfb0eb3a925181454d7c3ac8a1e695fddfae696d9e90"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:4b67fdab07fdd3c10bb21edab3cbfe8cf5696f453afce75d815d9d7223fbe88b"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:aa41e526a5d4a9dfcfbab0716c7e8a1b215abd3f3df5a45cf18a12721d31cb5d"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:ffc519621dce0c767e96b9c53f09c5d215578e10b02c285809f76509a3931482"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-win32.whl", hash = "sha256:f19c1585933c82098c2a520f8ec1227f20e339e33aca8fa6f956f6691b784e67"},
    {file = "charset_normalizer-3.4.0-cp313-cp313-win_amd64.whl", hash = "sha256:707b82d19e65c9bd28b81dde95249b07bf9f5b90ebe1ef17d9b57473f8a64b7b"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:dbe03226baf438ac4fda9e2d0715022fd579cb641c4cf639fa40d53b2fe6f3e2"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:dd9a8bd8900e65504a305bf8ae6fa9fbc66de94178c420791d0293702fce2df7"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b8831399554b92b72af5932cdbbd4ddc55c55f631bb13ff8fe4e6536a06c5c51"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a14969b8691f7998e74663b77b4c36c0337cb1df552da83d5c9004a93afdb574"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:dcaf7c1524c0542ee2fc82cc8ec337f7a9f7edee2532421ab200d2b920fc97cf"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:425c5f215d0eecee9a56cdb703203dda90423247421bf0d67125add85d0c4455"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-musllinux_1_2_aarch64.whl", hash = "sha256:d5b054862739d276e09928de37c79ddeec42a6e1bfc55863be96a36ba22926f6"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-musllinux_1_2_i686.whl", hash = "sha256:f3e73a4255342d4eb26ef6df01e3962e73aa29baa3124a8e824c5d3364a65748"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-musllinux_1_2_ppc64le.whl", hash = "sha256:2f6c34da58ea9c1a9515621f4d9ac379871a8f21168ba1b5e09d74250de5ad62"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-musllinux_1_2_s390x.whl", hash = "sha256:f09cb5a7bbe1ecae6e87901a2eb23e0256bb524a79ccc53eb0b7629fbe7677c4"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-musllinux_1_2_x86_64.whl", hash = "sha256:0099d79bdfcf5c1f0c2c72f91516702ebf8b0b8ddd8905f97a8aecf49712c621"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-win32.whl", hash = "sha256:9c98230f5042f4945f957d006edccc2af1e03ed5e37ce7c373f00a5a4daa6149"},
    {file = "charset_normalizer-3.4.0-cp37-cp37m-win_amd64.whl", hash = "sha256:62f60aebecfc7f4b82e3f639a7d1433a20ec32824db2199a11ad4f5e146ef5ee"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-macosx_10_9_universal2.whl", hash = "sha256:af73657b7a68211996527dbfeffbb0864e043d270580c5aef06dc4b659a4b578"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:cab5d0b79d987c67f3b9e9c53f54a61360422a5a0bc075f43cab5621d530c3b6"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:9289fd5dddcf57bab41d044f1756550f9e7cf0c8e373b8cdf0ce8773dc4bd417"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:6b493a043635eb376e50eedf7818f2f322eabbaa974e948bd8bdd29eb7ef2a51"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:9fa2566ca27d67c86569e8c85297aaf413ffab85a8960500f12ea34ff98e4c41"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a8e538f46104c815be19c975572d74afb53f29650ea2025bbfaef359d2de2f7f"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6fd30dc99682dc2c603c2b315bded2799019cea829f8bf57dc6b61efde6611c8"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:2006769bd1640bdf4d5641c69a3d63b71b81445473cac5ded39740a226fa88ab"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-musllinux_1_2_aarch64.whl", hash = "sha256:dc15e99b2d8a656f8e666854404f1ba54765871104e50c8e9813af8a7db07f12"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-musllinux_1_2_i686.whl", hash = "sha256:ab2e5bef076f5a235c3774b4f4028a680432cded7cad37bba0fd90d64b187d19"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-musllinux_1_2_ppc64le.whl", hash = "sha256:4ec9dd88a5b71abfc74e9df5ebe7921c35cbb3b641181a531ca65cdb5e8e4dea"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-musllinux_1_2_s390x.whl", hash = "sha256:43193c5cda5d612f247172016c4bb71251c784d7a4d9314677186a838ad34858"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-musllinux_1_2_x86_64.whl", hash = "sha256:aa693779a8b50cd97570e5a0f343538a8dbd3e496fa5dcb87e29406ad0299654"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-win32.whl", hash = "sha256:7706f5850360ac01d80c89bcef1640683cc12ed87f42579dab6c5d3ed6888613"},
    {file = "charset_normalizer-3.4.0-cp38-cp38-win_amd64.whl", hash = "sha256:c3e446d253bd88f6377260d07c895816ebf33ffffd56c1c792b13bff9c3e1ade"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:980b4f289d1d90ca5efcf07958d3eb38ed9c0b7676bf2831a54d4f66f9c27dfa"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:f28f891ccd15c514a0981f3b9db9aa23d62fe1a99997512b0491d2ed323d229a"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:a8aacce6e2e1edcb6ac625fb0f8c3a9570ccc7bfba1f63419b3769ccf6a00ed0"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:bd7af3717683bea4c87acd8c0d3d5b44d56120b26fd3f8a692bdd2d5260c620a"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:5ff2ed8194587faf56555927b3aa10e6fb69d931e33953943bc4f837dfee2242"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:e91f541a85298cf35433bf66f3fab2a4a2cff05c127eeca4af174f6d497f0d4b"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:309a7de0a0ff3040acaebb35ec45d18db4b28232f21998851cfa709eeff49d62"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:285e96d9d53422efc0d7a17c60e59f37fbf3dfa942073f666db4ac71e8d726d0"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:5d447056e2ca60382d460a604b6302d8db69476fd2015c81e7c35417cfabe4cd"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:20587d20f557fe189b7947d8e7ec5afa110ccf72a3128d61a2a387c3313f46be"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:130272c698667a982a5d0e626851ceff662565379baf0ff2cc58067b81d4f11d"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:ab22fbd9765e6954bc0bcff24c25ff71dcbfdb185fcdaca49e81bac68fe724d3"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:7782afc9b6b42200f7362858f9e73b1f8316afb276d316336c0ec3bd73312742"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-win32.whl", hash = "sha256:2de62e8801ddfff069cd5c504ce3bc9672b23266597d4e4f50eda28846c322f2"},
    {file = "charset_normalizer-3.4.0-cp39-cp39-win_amd64.whl", hash = "sha256:95c3c157765b031331dd4db3c775e58deaee050a3042fcad72cbc4189d7c8dca"},
    {file = "charset_normalizer-3.4.0-py3-none-any.whl", hash = "sha256:fe9f97feb71aa9896b81973a7bbada8c49501dc73e58a10fcef6663af95e5079"},
    {file = "charset_normalizer-3.4.0.tar.gz", hash = "sha256:223217c3d4f82c3ac5e29032b3f1c2eb0fb591b72161f86d93f5719079dae93e"},
]

[[package]]
name = "click"
version = "8.1.7"
description = "Composable command line interface toolkit"
optional = false
python-versions = ">=3.7"
files = [
    {file = "click-8.1.7-py3-none-any.whl", hash = "sha256:ae74fb96c20a0277a1d615f1e4d73c8414f5a98db8b799a7931d1582f3390c28"},
    {file = "click-8.1.7.tar.gz", hash = "sha256:ca9853ad459e787e2192211578cc907e7594e294c7ccc834310722b41b9ca6de"},
]

[package.dependencies]
colorama = {version = "*", markers = "platform_system == \"Windows\""}

[[package]]
name = "colorama"
version = "0.4.6"
description = "Cross-platform colored terminal text."
optional = false
python-versions = "!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,!=3.4.*,!=3.5.*,!=3.6.*,>=2.7"
files = [
    {file = "colorama-0.4.6-py2.py3-none-any.whl", hash = "sha256:4f1d9991f5acc0ca119f9d443620b77f9d6b33703e51011c16baf57afb285fc6"},
    {file = "colorama-0.4.6.tar.gz", hash = "sha256:08695f5cb7ed6e0531a20572697297273c47b8cae5a63ffc6d6ed5c201be6e44"},
]

[[package]]
name = "decorator"
version = "4.4.2"
description = "Decorators for Humans"
optional = false
python-versions = ">=2.6, !=3.0.*, !=3.1.*"
files = [
    {file = "decorator-4.4.2-py2.py3-none-any.whl", hash = "sha256:41fa54c2a0cc4ba648be4fd43cff00aedf5b9465c9bf18d64325bc225f08f760"},
    {file = "decorator-4.4.2.tar.gz", hash = "sha256:e3a62f0520172440ca0dcc823749319382e377f37f140a0b99ef45fecb84bfe7"},
]

[[package]]
name = "distlib"
version = "0.3.9"
description = "Distribution utilities"
optional = false
python-versions = "*"
files = [
    {file = "distlib-0.3.9-py2.py3-none-any.whl", hash = "sha256:47f8c22fd27c27e25a65601af709b38e4f0a45ea4fc2e710f65755fa8caaaf87"},
    {file = "distlib-0.3.9.tar.gz", hash = "sha256:a60f20dea646b8a33f3e7772f74dc0b2d0772d2837ee1342a00645c81edf9403"},
]

[[package]]
name = "distro"
version = "1.9.0"
description = "Distro - an OS platform information API"
optional = false
python-versions = ">=3.6"
files = [
    {file = "distro-1.9.0-py3-none-any.whl", hash = "sha256:7bffd925d65168f85027d8da9af6bddab658135b840670a223589bc0c8ef02b2"},
    {file = "distro-1.9.0.tar.gz", hash = "sha256:2fa77c6fd8940f116ee1d6b94a2f90b13b5ea8d019b98bc8bafdcabcdd9bdbed"},
]

[[package]]
name = "exceptiongroup"
version = "1.2.2"
description = "Backport of PEP 654 (exception groups)"
optional = false
python-versions = ">=3.7"
files = [
    {file = "exceptiongroup-1.2.2-py3-none-any.whl", hash = "sha256:3111b9d131c238bec2f8f516e123e14ba243563fb135d3fe885990585aa7795b"},
    {file = "exceptiongroup-1.2.2.tar.gz", hash = "sha256:47c2edf7c6738fafb49fd34290706d1a1a2f4d1c6df275526b62cbb4aa5393cc"},
]

[package.extras]
test = ["pytest (>=6)"]

[[package]]
name = "fastapi"
version = "0.115.6"
description = "FastAPI framework, high performance, easy to learn, fast to code, ready for production"
optional = false
python-versions = ">=3.8"
files = [
    {file = "fastapi-0.115.6-py3-none-any.whl", hash = "sha256:e9240b29e36fa8f4bb7290316988e90c381e5092e0cbe84e7818cc3713bcf305"},
    {file = "fastapi-0.115.6.tar.gz", hash = "sha256:9ec46f7addc14ea472958a96aae5b5de65f39721a46aaf5705c480d9a8b76654"},
]

[package.dependencies]
pydantic = ">=1.7.4,<1.8 || >1.8,<1.8.1 || >1.8.1,<2.0.0 || >2.0.0,<2.0.1 || >2.0.1,<2.1.0 || >2.1.0,<3.0.0"
starlette = ">=0.40.0,<0.42.0"
typing-extensions = ">=4.8.0"

[package.extras]
all = ["email-validator (>=2.0.0)", "fastapi-cli[standard] (>=0.0.5)", "httpx (>=0.23.0)", "itsdangerous (>=1.1.0)", "jinja2 (>=2.11.2)", "orjson (>=3.2.1)", "pydantic-extra-types (>=2.0.0)", "pydantic-settings (>=2.0.0)", "python-multipart (>=0.0.7)", "pyyaml (>=5.3.1)", "ujson (>=4.0.1,!=4.0.2,!=4.1.0,!=4.2.0,!=4.3.0,!=5.0.0,!=5.1.0)", "uvicorn[standard] (>=0.12.0)"]
standard = ["email-validator (>=2.0.0)", "fastapi-cli[standard] (>=0.0.5)", "httpx (>=0.23.0)", "jinja2 (>=2.11.2)", "python-multipart (>=0.0.7)", "uvicorn[standard] (>=0.12.0)"]

[[package]]
name = "filelock"
version = "3.16.1"
description = "A platform independent file lock."
optional = false
python-versions = ">=3.8"
files = [
    {file = "filelock-3.16.1-py3-none-any.whl", hash = "sha256:2082e5703d51fbf98ea75855d9d5527e33d8ff23099bec374a134febee6946b0"},
    {file = "filelock-3.16.1.tar.gz", hash = "sha256:c249fbfcd5db47e5e2d6d62198e565475ee65e4831e2561c8e313fa7eb961435"},
]

[package.extras]
docs = ["furo (>=2024.8.6)", "sphinx (>=8.0.2)", "sphinx-autodoc-typehints (>=2.4.1)"]
testing = ["covdefaults (>=2.3)", "coverage (>=7.6.1)", "diff-cover (>=9.2)", "pytest (>=8.3.3)", "pytest-asyncio (>=0.24)", "pytest-cov (>=5)", "pytest-mock (>=3.14)", "pytest-timeout (>=2.3.1)", "virtualenv (>=20.26.4)"]
typing = ["typing-extensions (>=4.12.2)"]

[[package]]
name = "frozenlist"
version = "1.5.0"
description = "A list-like structure which implements collections.abc.MutableSequence"
optional = false
python-versions = ">=3.8"
files = [
    {file = "frozenlist-1.5.0-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:5b6a66c18b5b9dd261ca98dffcb826a525334b2f29e7caa54e182255c5f6a65a"},
    {file = "frozenlist-1.5.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:d1b3eb7b05ea246510b43a7e53ed1653e55c2121019a97e60cad7efb881a97bb"},
    {file = "frozenlist-1.5.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:15538c0cbf0e4fa11d1e3a71f823524b0c46299aed6e10ebb4c2089abd8c3bec"},
    {file = "frozenlist-1.5.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:e79225373c317ff1e35f210dd5f1344ff31066ba8067c307ab60254cd3a78ad5"},
    {file = "frozenlist-1.5.0-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:9272fa73ca71266702c4c3e2d4a28553ea03418e591e377a03b8e3659d94fa76"},
    {file = "frozenlist-1.5.0-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:498524025a5b8ba81695761d78c8dd7382ac0b052f34e66939c42df860b8ff17"},
    {file = "frozenlist-1.5.0-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:92b5278ed9d50fe610185ecd23c55d8b307d75ca18e94c0e7de328089ac5dcba"},
    {file = "frozenlist-1.5.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7f3c8c1dacd037df16e85227bac13cca58c30da836c6f936ba1df0c05d046d8d"},
    {file = "frozenlist-1.5.0-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:f2ac49a9bedb996086057b75bf93538240538c6d9b38e57c82d51f75a73409d2"},
    {file = "frozenlist-1.5.0-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:e66cc454f97053b79c2ab09c17fbe3c825ea6b4de20baf1be28919460dd7877f"},
    {file = "frozenlist-1.5.0-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:5a3ba5f9a0dfed20337d3e966dc359784c9f96503674c2faf015f7fe8e96798c"},
    {file = "frozenlist-1.5.0-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:6321899477db90bdeb9299ac3627a6a53c7399c8cd58d25da094007402b039ab"},
    {file = "frozenlist-1.5.0-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:76e4753701248476e6286f2ef492af900ea67d9706a0155335a40ea21bf3b2f5"},
    {file = "frozenlist-1.5.0-cp310-cp310-win32.whl", hash = "sha256:977701c081c0241d0955c9586ffdd9ce44f7a7795df39b9151cd9a6fd0ce4cfb"},
    {file = "frozenlist-1.5.0-cp310-cp310-win_amd64.whl", hash = "sha256:189f03b53e64144f90990d29a27ec4f7997d91ed3d01b51fa39d2dbe77540fd4"},
    {file = "frozenlist-1.5.0-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:fd74520371c3c4175142d02a976aee0b4cb4a7cc912a60586ffd8d5929979b30"},
    {file = "frozenlist-1.5.0-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:2f3f7a0fbc219fb4455264cae4d9f01ad41ae6ee8524500f381de64ffaa077d5"},
    {file = "frozenlist-1.5.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:f47c9c9028f55a04ac254346e92977bf0f166c483c74b4232bee19a6697e4778"},
    {file = "frozenlist-1.5.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0996c66760924da6e88922756d99b47512a71cfd45215f3570bf1e0b694c206a"},
    {file = "frozenlist-1.5.0-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:a2fe128eb4edeabe11896cb6af88fca5346059f6c8d807e3b910069f39157869"},
    {file = "frozenlist-1.5.0-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:1a8ea951bbb6cacd492e3948b8da8c502a3f814f5d20935aae74b5df2b19cf3d"},
    {file = "frozenlist-1.5.0-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:de537c11e4aa01d37db0d403b57bd6f0546e71a82347a97c6a9f0dcc532b3a45"},
    {file = "frozenlist-1.5.0-cp311-cp311-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9c2623347b933fcb9095841f1cc5d4ff0b278addd743e0e966cb3d460278840d"},
    {file = "frozenlist-1.5.0-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:cee6798eaf8b1416ef6909b06f7dc04b60755206bddc599f52232606e18179d3"},
    {file = "frozenlist-1.5.0-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:f5f9da7f5dbc00a604fe74aa02ae7c98bcede8a3b8b9666f9f86fc13993bc71a"},
    {file = "frozenlist-1.5.0-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:90646abbc7a5d5c7c19461d2e3eeb76eb0b204919e6ece342feb6032c9325ae9"},
    {file = "frozenlist-1.5.0-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:bdac3c7d9b705d253b2ce370fde941836a5f8b3c5c2b8fd70940a3ea3af7f4f2"},
    {file = "frozenlist-1.5.0-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:03d33c2ddbc1816237a67f66336616416e2bbb6beb306e5f890f2eb22b959cdf"},
    {file = "frozenlist-1.5.0-cp311-cp311-win32.whl", hash = "sha256:237f6b23ee0f44066219dae14c70ae38a63f0440ce6750f868ee08775073f942"},
    {file = "frozenlist-1.5.0-cp311-cp311-win_amd64.whl", hash = "sha256:0cc974cc93d32c42e7b0f6cf242a6bd941c57c61b618e78b6c0a96cb72788c1d"},
    {file = "frozenlist-1.5.0-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:31115ba75889723431aa9a4e77d5f398f5cf976eea3bdf61749731f62d4a4a21"},
    {file = "frozenlist-1.5.0-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:7437601c4d89d070eac8323f121fcf25f88674627505334654fd027b091db09d"},
    {file = "frozenlist-1.5.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:7948140d9f8ece1745be806f2bfdf390127cf1a763b925c4a805c603df5e697e"},
    {file = "frozenlist-1.5.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:feeb64bc9bcc6b45c6311c9e9b99406660a9c05ca8a5b30d14a78555088b0b3a"},
    {file = "frozenlist-1.5.0-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:683173d371daad49cffb8309779e886e59c2f369430ad28fe715f66d08d4ab1a"},
    {file = "frozenlist-1.5.0-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:7d57d8f702221405a9d9b40f9da8ac2e4a1a8b5285aac6100f3393675f0a85ee"},
    {file = "frozenlist-1.5.0-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:30c72000fbcc35b129cb09956836c7d7abf78ab5416595e4857d1cae8d6251a6"},
    {file = "frozenlist-1.5.0-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:000a77d6034fbad9b6bb880f7ec073027908f1b40254b5d6f26210d2dab1240e"},
    {file = "frozenlist-1.5.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:5d7f5a50342475962eb18b740f3beecc685a15b52c91f7d975257e13e029eca9"},
    {file = "frozenlist-1.5.0-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:87f724d055eb4785d9be84e9ebf0f24e392ddfad00b3fe036e43f489fafc9039"},
    {file = "frozenlist-1.5.0-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:6e9080bb2fb195a046e5177f10d9d82b8a204c0736a97a153c2466127de87784"},
    {file = "frozenlist-1.5.0-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:9b93d7aaa36c966fa42efcaf716e6b3900438632a626fb09c049f6a2f09fc631"},
    {file = "frozenlist-1.5.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:52ef692a4bc60a6dd57f507429636c2af8b6046db8b31b18dac02cbc8f507f7f"},
    {file = "frozenlist-1.5.0-cp312-cp312-win32.whl", hash = "sha256:29d94c256679247b33a3dc96cce0f93cbc69c23bf75ff715919332fdbb6a32b8"},
    {file = "frozenlist-1.5.0-cp312-cp312-win_amd64.whl", hash = "sha256:8969190d709e7c48ea386db202d708eb94bdb29207a1f269bab1196ce0dcca1f"},
    {file = "frozenlist-1.5.0-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:7a1a048f9215c90973402e26c01d1cff8a209e1f1b53f72b95c13db61b00f953"},
    {file = "frozenlist-1.5.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:dd47a5181ce5fcb463b5d9e17ecfdb02b678cca31280639255ce9d0e5aa67af0"},
    {file = "frozenlist-1.5.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:1431d60b36d15cda188ea222033eec8e0eab488f39a272461f2e6d9e1a8e63c2"},
    {file = "frozenlist-1.5.0-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:6482a5851f5d72767fbd0e507e80737f9c8646ae7fd303def99bfe813f76cf7f"},
    {file = "frozenlist-1.5.0-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:44c49271a937625619e862baacbd037a7ef86dd1ee215afc298a417ff3270608"},
    {file = "frozenlist-1.5.0-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:12f78f98c2f1c2429d42e6a485f433722b0061d5c0b0139efa64f396efb5886b"},
    {file = "frozenlist-1.5.0-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:ce3aa154c452d2467487765e3adc730a8c153af77ad84096bc19ce19a2400840"},
    {file = "frozenlist-1.5.0-cp313-cp313-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9b7dc0c4338e6b8b091e8faf0db3168a37101943e687f373dce00959583f7439"},
    {file = "frozenlist-1.5.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:45e0896250900b5aa25180f9aec243e84e92ac84bd4a74d9ad4138ef3f5c97de"},
    {file = "frozenlist-1.5.0-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:561eb1c9579d495fddb6da8959fd2a1fca2c6d060d4113f5844b433fc02f2641"},
    {file = "frozenlist-1.5.0-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:df6e2f325bfee1f49f81aaac97d2aa757c7646534a06f8f577ce184afe2f0a9e"},
    {file = "frozenlist-1.5.0-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:140228863501b44b809fb39ec56b5d4071f4d0aa6d216c19cbb08b8c5a7eadb9"},
    {file = "frozenlist-1.5.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:7707a25d6a77f5d27ea7dc7d1fc608aa0a478193823f88511ef5e6b8a48f9d03"},
    {file = "frozenlist-1.5.0-cp313-cp313-win32.whl", hash = "sha256:31a9ac2b38ab9b5a8933b693db4939764ad3f299fcaa931a3e605bc3460e693c"},
    {file = "frozenlist-1.5.0-cp313-cp313-win_amd64.whl", hash = "sha256:11aabdd62b8b9c4b84081a3c246506d1cddd2dd93ff0ad53ede5defec7886b28"},
    {file = "frozenlist-1.5.0-cp38-cp38-macosx_10_9_universal2.whl", hash = "sha256:dd94994fc91a6177bfaafd7d9fd951bc8689b0a98168aa26b5f543868548d3ca"},
    {file = "frozenlist-1.5.0-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:2d0da8bbec082bf6bf18345b180958775363588678f64998c2b7609e34719b10"},
    {file = "frozenlist-1.5.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:73f2e31ea8dd7df61a359b731716018c2be196e5bb3b74ddba107f694fbd7604"},
    {file = "frozenlist-1.5.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:828afae9f17e6de596825cf4228ff28fbdf6065974e5ac1410cecc22f699d2b3"},
    {file = "frozenlist-1.5.0-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f1577515d35ed5649d52ab4319db757bb881ce3b2b796d7283e6634d99ace307"},
    {file = "frozenlist-1.5.0-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:2150cc6305a2c2ab33299453e2968611dacb970d2283a14955923062c8d00b10"},
    {file = "frozenlist-1.5.0-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:a72b7a6e3cd2725eff67cd64c8f13335ee18fc3c7befc05aed043d24c7b9ccb9"},
    {file = "frozenlist-1.5.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c16d2fa63e0800723139137d667e1056bee1a1cf7965153d2d104b62855e9b99"},
    {file = "frozenlist-1.5.0-cp38-cp38-musllinux_1_2_aarch64.whl", hash = "sha256:17dcc32fc7bda7ce5875435003220a457bcfa34ab7924a49a1c19f55b6ee185c"},
    {file = "frozenlist-1.5.0-cp38-cp38-musllinux_1_2_i686.whl", hash = "sha256:97160e245ea33d8609cd2b8fd997c850b56db147a304a262abc2b3be021a9171"},
    {file = "frozenlist-1.5.0-cp38-cp38-musllinux_1_2_ppc64le.whl", hash = "sha256:f1e6540b7fa044eee0bb5111ada694cf3dc15f2b0347ca125ee9ca984d5e9e6e"},
    {file = "frozenlist-1.5.0-cp38-cp38-musllinux_1_2_s390x.whl", hash = "sha256:91d6c171862df0a6c61479d9724f22efb6109111017c87567cfeb7b5d1449fdf"},
    {file = "frozenlist-1.5.0-cp38-cp38-musllinux_1_2_x86_64.whl", hash = "sha256:c1fac3e2ace2eb1052e9f7c7db480818371134410e1f5c55d65e8f3ac6d1407e"},
    {file = "frozenlist-1.5.0-cp38-cp38-win32.whl", hash = "sha256:b97f7b575ab4a8af9b7bc1d2ef7f29d3afee2226bd03ca3875c16451ad5a7723"},
    {file = "frozenlist-1.5.0-cp38-cp38-win_amd64.whl", hash = "sha256:374ca2dabdccad8e2a76d40b1d037f5bd16824933bf7bcea3e59c891fd4a0923"},
    {file = "frozenlist-1.5.0-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:9bbcdfaf4af7ce002694a4e10a0159d5a8d20056a12b05b45cea944a4953f972"},
    {file = "frozenlist-1.5.0-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:1893f948bf6681733aaccf36c5232c231e3b5166d607c5fa77773611df6dc336"},
    {file = "frozenlist-1.5.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:2b5e23253bb709ef57a8e95e6ae48daa9ac5f265637529e4ce6b003a37b2621f"},
    {file = "frozenlist-1.5.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0f253985bb515ecd89629db13cb58d702035ecd8cfbca7d7a7e29a0e6d39af5f"},
    {file = "frozenlist-1.5.0-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:04a5c6babd5e8fb7d3c871dc8b321166b80e41b637c31a995ed844a6139942b6"},
    {file = "frozenlist-1.5.0-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a9fe0f1c29ba24ba6ff6abf688cb0b7cf1efab6b6aa6adc55441773c252f7411"},
    {file = "frozenlist-1.5.0-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:226d72559fa19babe2ccd920273e767c96a49b9d3d38badd7c91a0fdeda8ea08"},
    {file = "frozenlist-1.5.0-cp39-cp39-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:15b731db116ab3aedec558573c1a5eec78822b32292fe4f2f0345b7f697745c2"},
    {file = "frozenlist-1.5.0-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:366d8f93e3edfe5a918c874702f78faac300209a4d5bf38352b2c1bdc07a766d"},
    {file = "frozenlist-1.5.0-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:1b96af8c582b94d381a1c1f51ffaedeb77c821c690ea5f01da3d70a487dd0a9b"},
    {file = "frozenlist-1.5.0-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:c03eff4a41bd4e38415cbed054bbaff4a075b093e2394b6915dca34a40d1e38b"},
    {file = "frozenlist-1.5.0-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:50cf5e7ee9b98f22bdecbabf3800ae78ddcc26e4a435515fc72d97903e8488e0"},
    {file = "frozenlist-1.5.0-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:1e76bfbc72353269c44e0bc2cfe171900fbf7f722ad74c9a7b638052afe6a00c"},
    {file = "frozenlist-1.5.0-cp39-cp39-win32.whl", hash = "sha256:666534d15ba8f0fda3f53969117383d5dc021266b3c1a42c9ec4855e4b58b9d3"},
    {file = "frozenlist-1.5.0-cp39-cp39-win_amd64.whl", hash = "sha256:5c28f4b5dbef8a0d8aad0d4de24d1e9e981728628afaf4ea0792f5d0939372f0"},
    {file = "frozenlist-1.5.0-py3-none-any.whl", hash = "sha256:d994863bba198a4a518b467bb971c56e1db3f180a25c6cf7bb1949c267f748c3"},
    {file = "frozenlist-1.5.0.tar.gz", hash = "sha256:81d5af29e61b9c8348e876d442253723928dce6433e0e76cd925cd83f1b4b817"},
]

[[package]]
name = "fsspec"
version = "2024.10.0"
description = "File-system specification"
optional = false
python-versions = ">=3.8"
files = [
    {file = "fsspec-2024.10.0-py3-none-any.whl", hash = "sha256:03b9a6785766a4de40368b88906366755e2819e758b83705c88cd7cb5fe81871"},
    {file = "fsspec-2024.10.0.tar.gz", hash = "sha256:eda2d8a4116d4f2429db8550f2457da57279247dd930bb12f821b58391359493"},
]

[package.extras]
abfs = ["adlfs"]
adl = ["adlfs"]
arrow = ["pyarrow (>=1)"]
dask = ["dask", "distributed"]
dev = ["pre-commit", "ruff"]
doc = ["numpydoc", "sphinx", "sphinx-design", "sphinx-rtd-theme", "yarl"]
dropbox = ["dropbox", "dropboxdrivefs", "requests"]
full = ["adlfs", "aiohttp (!=4.0.0a0,!=4.0.0a1)", "dask", "distributed", "dropbox", "dropboxdrivefs", "fusepy", "gcsfs", "libarchive-c", "ocifs", "panel", "paramiko", "pyarrow (>=1)", "pygit2", "requests", "s3fs", "smbprotocol", "tqdm"]
fuse = ["fusepy"]
gcs = ["gcsfs"]
git = ["pygit2"]
github = ["requests"]
gs = ["gcsfs"]
gui = ["panel"]
hdfs = ["pyarrow (>=1)"]
http = ["aiohttp (!=4.0.0a0,!=4.0.0a1)"]
libarchive = ["libarchive-c"]
oci = ["ocifs"]
s3 = ["s3fs"]
sftp = ["paramiko"]
smb = ["smbprotocol"]
ssh = ["paramiko"]
test = ["aiohttp (!=4.0.0a0,!=4.0.0a1)", "numpy", "pytest", "pytest-asyncio (!=0.22.0)", "pytest-benchmark", "pytest-cov", "pytest-mock", "pytest-recording", "pytest-rerunfailures", "requests"]
test-downstream = ["aiobotocore (>=2.5.4,<3.0.0)", "dask-expr", "dask[dataframe,test]", "moto[server] (>4,<5)", "pytest-timeout", "xarray"]
test-full = ["adlfs", "aiohttp (!=4.0.0a0,!=4.0.0a1)", "cloudpickle", "dask", "distributed", "dropbox", "dropboxdrivefs", "fastparquet", "fusepy", "gcsfs", "jinja2", "kerchunk", "libarchive-c", "lz4", "notebook", "numpy", "ocifs", "pandas", "panel", "paramiko", "pyarrow", "pyarrow (>=1)", "pyftpdlib", "pygit2", "pytest", "pytest-asyncio (!=0.22.0)", "pytest-benchmark", "pytest-cov", "pytest-mock", "pytest-recording", "pytest-rerunfailures", "python-snappy", "requests", "smbprotocol", "tqdm", "urllib3", "zarr", "zstandard"]
tqdm = ["tqdm"]

[[package]]
name = "google-auth"
version = "2.37.0"
description = "Google Authentication Library"
optional = false
python-versions = ">=3.7"
files = [
    {file = "google_auth-2.37.0-py2.py3-none-any.whl", hash = "sha256:42664f18290a6be591be5329a96fe30184be1a1badb7292a7f686a9659de9ca0"},
    {file = "google_auth-2.37.0.tar.gz", hash = "sha256:0054623abf1f9c83492c63d3f47e77f0a544caa3d40b2d98e099a611c2dd5d00"},
]

[package.dependencies]
cachetools = ">=2.0.0,<6.0"
pyasn1-modules = ">=0.2.1"
rsa = ">=3.1.4,<5"

[package.extras]
aiohttp = ["aiohttp (>=3.6.2,<4.0.0.dev0)", "requests (>=2.20.0,<3.0.0.dev0)"]
enterprise-cert = ["cryptography", "pyopenssl"]
pyjwt = ["cryptography (>=38.0.3)", "pyjwt (>=2.0)"]
pyopenssl = ["cryptography (>=38.0.3)", "pyopenssl (>=20.0.0)"]
reauth = ["pyu2f (>=0.1.5)"]
requests = ["requests (>=2.20.0,<3.0.0.dev0)"]

[[package]]
name = "google-genai"
version = "0.3.0"
description = "GenAI Python SDK"
optional = false
python-versions = ">=3.9"
files = [
    {file = "google_genai-0.3.0-py3-none-any.whl", hash = "sha256:e45eb1732cf5b1f7c5a4103fe64cc4b577981d7e592e3edfba6d34ec734f56be"},
    {file = "google_genai-0.3.0.tar.gz", hash = "sha256:1e080ca381268912dacc8e0cb15eb203eb4e38f51f6ae35cc5768e5af323c8cc"},
]

[package.dependencies]
google-auth = ">=2.14.1,<3.0.0dev"
pillow = ">=10.0.0,<12.0.0"
pydantic = ">=2.0.0,<3.0.0dev"
requests = ">=2.28.1,<3.0.0dev"
websockets = ">=13.0,<15.0dev"

[[package]]
name = "h11"
version = "0.14.0"
description = "A pure-Python, bring-your-own-I/O implementation of HTTP/1.1"
optional = false
python-versions = ">=3.7"
files = [
    {file = "h11-0.14.0-py3-none-any.whl", hash = "sha256:e3fe4ac4b851c468cc8363d500db52c2ead036020723024a109d37346efaa761"},
    {file = "h11-0.14.0.tar.gz", hash = "sha256:8f19fbbe99e72420ff35c00b27a34cb9937e902a8b810e2c88300c6f0a3b699d"},
]

[[package]]
name = "httpcore"
version = "1.0.7"
description = "A minimal low-level HTTP client."
optional = false
python-versions = ">=3.8"
files = [
    {file = "httpcore-1.0.7-py3-none-any.whl", hash = "sha256:a3fff8f43dc260d5bd363d9f9cf1830fa3a458b332856f34282de498ed420edd"},
    {file = "httpcore-1.0.7.tar.gz", hash = "sha256:8551cb62a169ec7162ac7be8d4817d561f60e08eaa485234898414bb5a8a0b4c"},
]

[package.dependencies]
certifi = "*"
h11 = ">=0.13,<0.15"

[package.extras]
asyncio = ["anyio (>=4.0,<5.0)"]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (==1.*)"]
trio = ["trio (>=0.22.0,<1.0)"]

[[package]]
name = "httpx"
version = "0.25.2"
description = "The next generation HTTP client."
optional = false
python-versions = ">=3.8"
files = [
    {file = "httpx-0.25.2-py3-none-any.whl", hash = "sha256:a05d3d052d9b2dfce0e3896636467f8a5342fb2b902c819428e1ac65413ca118"},
    {file = "httpx-0.25.2.tar.gz", hash = "sha256:8b8fcaa0c8ea7b05edd69a094e63a2094c4efcb48129fb757361bc423c0ad9e8"},
]

[package.dependencies]
anyio = "*"
certifi = "*"
httpcore = "==1.*"
idna = "*"
sniffio = "*"

[package.extras]
brotli = ["brotli", "brotlicffi"]
cli = ["click (==8.*)", "pygments (==2.*)", "rich (>=10,<14)"]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (==1.*)"]

[[package]]
name = "huggingface-hub"
version = "0.27.0"
description = "Client library to download and publish models, datasets and other repos on the huggingface.co hub"
optional = false
python-versions = ">=3.8.0"
files = [
    {file = "huggingface_hub-0.27.0-py3-none-any.whl", hash = "sha256:8f2e834517f1f1ddf1ecc716f91b120d7333011b7485f665a9a412eacb1a2a81"},
    {file = "huggingface_hub-0.27.0.tar.gz", hash = "sha256:902cce1a1be5739f5589e560198a65a8edcfd3b830b1666f36e4b961f0454fac"},
]

[package.dependencies]
filelock = "*"
fsspec = ">=2023.5.0"
packaging = ">=20.9"
pyyaml = ">=5.1"
requests = "*"
tqdm = ">=4.42.1"
typing-extensions = ">=3.7.4.3"

[package.extras]
all = ["InquirerPy (==0.3.4)", "Jinja2", "Pillow", "aiohttp", "fastapi", "gradio (>=4.0.0)", "jedi", "libcst (==1.4.0)", "mypy (==1.5.1)", "numpy", "pytest (>=8.1.1,<8.2.2)", "pytest-asyncio", "pytest-cov", "pytest-env", "pytest-mock", "pytest-rerunfailures", "pytest-vcr", "pytest-xdist", "ruff (>=0.5.0)", "soundfile", "types-PyYAML", "types-requests", "types-simplejson", "types-toml", "types-tqdm", "types-urllib3", "typing-extensions (>=4.8.0)", "urllib3 (<2.0)"]
cli = ["InquirerPy (==0.3.4)"]
dev = ["InquirerPy (==0.3.4)", "Jinja2", "Pillow", "aiohttp", "fastapi", "gradio (>=4.0.0)", "jedi", "libcst (==1.4.0)", "mypy (==1.5.1)", "numpy", "pytest (>=8.1.1,<8.2.2)", "pytest-asyncio", "pytest-cov", "pytest-env", "pytest-mock", "pytest-rerunfailures", "pytest-vcr", "pytest-xdist", "ruff (>=0.5.0)", "soundfile", "types-PyYAML", "types-requests", "types-simplejson", "types-toml", "types-tqdm", "types-urllib3", "typing-extensions (>=4.8.0)", "urllib3 (<2.0)"]
fastai = ["fastai (>=2.4)", "fastcore (>=1.3.27)", "toml"]
hf-transfer = ["hf-transfer (>=0.1.4)"]
inference = ["aiohttp"]
quality = ["libcst (==1.4.0)", "mypy (==1.5.1)", "ruff (>=0.5.0)"]
tensorflow = ["graphviz", "pydot", "tensorflow"]
tensorflow-testing = ["keras (<3.0)", "tensorflow"]
testing = ["InquirerPy (==0.3.4)", "Jinja2", "Pillow", "aiohttp", "fastapi", "gradio (>=4.0.0)", "jedi", "numpy", "pytest (>=8.1.1,<8.2.2)", "pytest-asyncio", "pytest-cov", "pytest-env", "pytest-mock", "pytest-rerunfailures", "pytest-vcr", "pytest-xdist", "soundfile", "urllib3 (<2.0)"]
torch = ["safetensors[torch]", "torch"]
typing = ["types-PyYAML", "types-requests", "types-simplejson", "types-toml", "types-tqdm", "types-urllib3", "typing-extensions (>=4.8.0)"]

[[package]]
name = "identify"
version = "2.6.3"
description = "File identification library for Python"
optional = false
python-versions = ">=3.9"
files = [
    {file = "identify-2.6.3-py2.py3-none-any.whl", hash = "sha256:9edba65473324c2ea9684b1f944fe3191db3345e50b6d04571d10ed164f8d7bd"},
    {file = "identify-2.6.3.tar.gz", hash = "sha256:62f5dae9b5fef52c84cc188514e9ea4f3f636b1d8799ab5ebc475471f9e47a02"},
]

[package.extras]
license = ["ukkonen"]

[[package]]
name = "idna"
version = "3.10"
description = "Internationalized Domain Names in Applications (IDNA)"
optional = false
python-versions = ">=3.6"
files = [
    {file = "idna-3.10-py3-none-any.whl", hash = "sha256:946d195a0d259cbba61165e88e65941f16e9b36ea6ddb97f00452bae8b1287d3"},
    {file = "idna-3.10.tar.gz", hash = "sha256:12f65c9b470abda6dc35cf8e63cc574b1c52b11df2c86030af0ac09b01b13ea9"},
]

[package.extras]
all = ["flake8 (>=7.1.1)", "mypy (>=1.11.2)", "pytest (>=8.3.2)", "ruff (>=0.6.2)"]

[[package]]
name = "imageio"
version = "2.36.1"
description = "Library for reading and writing a wide range of image, video, scientific, and volumetric data formats."
optional = false
python-versions = ">=3.9"
files = [
    {file = "imageio-2.36.1-py3-none-any.whl", hash = "sha256:20abd2cae58e55ca1af8a8dcf43293336a59adf0391f1917bf8518633cfc2cdf"},
    {file = "imageio-2.36.1.tar.gz", hash = "sha256:e4e1d231f47f9a9e16100b0f7ce1a86e8856fb4d1c0fa2c4365a316f1746be62"},
]

[package.dependencies]
numpy = "*"
pillow = ">=8.3.2"

[package.extras]
all-plugins = ["astropy", "av", "imageio-ffmpeg", "numpy (>2)", "pillow-heif", "psutil", "rawpy", "tifffile"]
all-plugins-pypy = ["av", "imageio-ffmpeg", "pillow-heif", "psutil", "tifffile"]
build = ["wheel"]
dev = ["black", "flake8", "fsspec[github]", "pytest", "pytest-cov"]
docs = ["numpydoc", "pydata-sphinx-theme", "sphinx (<6)"]
ffmpeg = ["imageio-ffmpeg", "psutil"]
fits = ["astropy"]
full = ["astropy", "av", "black", "flake8", "fsspec[github]", "gdal", "imageio-ffmpeg", "itk", "numpy (>2)", "numpydoc", "pillow-heif", "psutil", "pydata-sphinx-theme", "pytest", "pytest-cov", "rawpy", "sphinx (<6)", "tifffile", "wheel"]
gdal = ["gdal"]
itk = ["itk"]
linting = ["black", "flake8"]
pillow-heif = ["pillow-heif"]
pyav = ["av"]
rawpy = ["numpy (>2)", "rawpy"]
test = ["fsspec[github]", "pytest", "pytest-cov"]
tifffile = ["tifffile"]

[[package]]
name = "imageio-ffmpeg"
version = "0.5.1"
description = "FFMPEG wrapper for Python"
optional = false
python-versions = ">=3.5"
files = [
    {file = "imageio-ffmpeg-0.5.1.tar.gz", hash = "sha256:0ed7a9b31f560b0c9d929c5291cd430edeb9bed3ce9a497480e536dd4326484c"},
    {file = "imageio_ffmpeg-0.5.1-py3-none-macosx_10_9_intel.macosx_10_9_x86_64.macosx_10_10_intel.macosx_10_10_x86_64.whl", hash = "sha256:1460e84712b9d06910c1f7bb524096b0341d4b7844cea6c20e099d0a24e795b1"},
    {file = "imageio_ffmpeg-0.5.1-py3-none-manylinux2010_x86_64.whl", hash = "sha256:5289f75c7f755b499653f3209fea4efd1430cba0e39831c381aad2d458f7a316"},
    {file = "imageio_ffmpeg-0.5.1-py3-none-manylinux2014_aarch64.whl", hash = "sha256:7fa9132a291d5eb28c44553550deb40cbdab831f2a614e55360301a6582eb205"},
    {file = "imageio_ffmpeg-0.5.1-py3-none-win32.whl", hash = "sha256:89efe2c79979d8174ba8476deb7f74d74c331caee3fb2b65ba2883bec0737625"},
    {file = "imageio_ffmpeg-0.5.1-py3-none-win_amd64.whl", hash = "sha256:1521e79e253bedbdd36a547e0cbd94a025ba0b558e17f08fea687d805a0e4698"},
]

[package.dependencies]
setuptools = "*"

[[package]]
name = "iniconfig"
version = "2.0.0"
description = "brain-dead simple config-ini parsing"
optional = false
python-versions = ">=3.7"
files = [
    {file = "iniconfig-2.0.0-py3-none-any.whl", hash = "sha256:b6a85871a79d2e3b22d2d1b94ac2824226a63c6b741c88f7ae975f18b6778374"},
    {file = "iniconfig-2.0.0.tar.gz", hash = "sha256:2d91e135bf72d31a410b17c16da610a82cb55f6b0477d1a902134b24a455b8b3"},
]

[[package]]
name = "jiter"
version = "0.8.2"
description = "Fast iterable JSON parser."
optional = false
python-versions = ">=3.8"
files = [
    {file = "jiter-0.8.2-cp310-cp310-macosx_10_12_x86_64.whl", hash = "sha256:ca8577f6a413abe29b079bc30f907894d7eb07a865c4df69475e868d73e71c7b"},
    {file = "jiter-0.8.2-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:b25bd626bde7fb51534190c7e3cb97cee89ee76b76d7585580e22f34f5e3f393"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:d5c826a221851a8dc028eb6d7d6429ba03184fa3c7e83ae01cd6d3bd1d4bd17d"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:d35c864c2dff13dfd79fb070fc4fc6235d7b9b359efe340e1261deb21b9fcb66"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f557c55bc2b7676e74d39d19bcb8775ca295c7a028246175d6a8b431e70835e5"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:580ccf358539153db147e40751a0b41688a5ceb275e6f3e93d91c9467f42b2e3"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:af102d3372e917cffce49b521e4c32c497515119dc7bd8a75665e90a718bbf08"},
    {file = "jiter-0.8.2-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:cadcc978f82397d515bb2683fc0d50103acff2a180552654bb92d6045dec2c49"},
    {file = "jiter-0.8.2-cp310-cp310-musllinux_1_1_aarch64.whl", hash = "sha256:ba5bdf56969cad2019d4e8ffd3f879b5fdc792624129741d3d83fc832fef8c7d"},
    {file = "jiter-0.8.2-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:3b94a33a241bee9e34b8481cdcaa3d5c2116f575e0226e421bed3f7a6ea71cff"},
    {file = "jiter-0.8.2-cp310-cp310-win32.whl", hash = "sha256:6e5337bf454abddd91bd048ce0dca5134056fc99ca0205258766db35d0a2ea43"},
    {file = "jiter-0.8.2-cp310-cp310-win_amd64.whl", hash = "sha256:4a9220497ca0cb1fe94e3f334f65b9b5102a0b8147646118f020d8ce1de70105"},
    {file = "jiter-0.8.2-cp311-cp311-macosx_10_12_x86_64.whl", hash = "sha256:2dd61c5afc88a4fda7d8b2cf03ae5947c6ac7516d32b7a15bf4b49569a5c076b"},
    {file = "jiter-0.8.2-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:a6c710d657c8d1d2adbbb5c0b0c6bfcec28fd35bd6b5f016395f9ac43e878a15"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:a9584de0cd306072635fe4b89742bf26feae858a0683b399ad0c2509011b9dc0"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:5a90a923338531b7970abb063cfc087eebae6ef8ec8139762007188f6bc69a9f"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d21974d246ed0181558087cd9f76e84e8321091ebfb3a93d4c341479a736f099"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:32475a42b2ea7b344069dc1e81445cfc00b9d0e3ca837f0523072432332e9f74"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:8b9931fd36ee513c26b5bf08c940b0ac875de175341cbdd4fa3be109f0492586"},
    {file = "jiter-0.8.2-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:ce0820f4a3a59ddced7fce696d86a096d5cc48d32a4183483a17671a61edfddc"},
    {file = "jiter-0.8.2-cp311-cp311-musllinux_1_1_aarch64.whl", hash = "sha256:8ffc86ae5e3e6a93765d49d1ab47b6075a9c978a2b3b80f0f32628f39caa0c88"},
    {file = "jiter-0.8.2-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:5127dc1abd809431172bc3fbe8168d6b90556a30bb10acd5ded41c3cfd6f43b6"},
    {file = "jiter-0.8.2-cp311-cp311-win32.whl", hash = "sha256:66227a2c7b575720c1871c8800d3a0122bb8ee94edb43a5685aa9aceb2782d44"},
    {file = "jiter-0.8.2-cp311-cp311-win_amd64.whl", hash = "sha256:cde031d8413842a1e7501e9129b8e676e62a657f8ec8166e18a70d94d4682855"},
    {file = "jiter-0.8.2-cp312-cp312-macosx_10_12_x86_64.whl", hash = "sha256:e6ec2be506e7d6f9527dae9ff4b7f54e68ea44a0ef6b098256ddf895218a2f8f"},
    {file = "jiter-0.8.2-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:76e324da7b5da060287c54f2fabd3db5f76468006c811831f051942bf68c9d44"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:180a8aea058f7535d1c84183c0362c710f4750bef66630c05f40c93c2b152a0f"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:025337859077b41548bdcbabe38698bcd93cfe10b06ff66617a48ff92c9aec60"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:ecff0dc14f409599bbcafa7e470c00b80f17abc14d1405d38ab02e4b42e55b57"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:ffd9fee7d0775ebaba131f7ca2e2d83839a62ad65e8e02fe2bd8fc975cedeb9e"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:14601dcac4889e0a1c75ccf6a0e4baf70dbc75041e51bcf8d0e9274519df6887"},
    {file = "jiter-0.8.2-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:92249669925bc1c54fcd2ec73f70f2c1d6a817928480ee1c65af5f6b81cdf12d"},
    {file = "jiter-0.8.2-cp312-cp312-musllinux_1_1_aarch64.whl", hash = "sha256:e725edd0929fa79f8349ab4ec7f81c714df51dc4e991539a578e5018fa4a7152"},
    {file = "jiter-0.8.2-cp312-cp312-musllinux_1_1_x86_64.whl", hash = "sha256:bf55846c7b7a680eebaf9c3c48d630e1bf51bdf76c68a5f654b8524335b0ad29"},
    {file = "jiter-0.8.2-cp312-cp312-win32.whl", hash = "sha256:7efe4853ecd3d6110301665a5178b9856be7e2a9485f49d91aa4d737ad2ae49e"},
    {file = "jiter-0.8.2-cp312-cp312-win_amd64.whl", hash = "sha256:83c0efd80b29695058d0fd2fa8a556490dbce9804eac3e281f373bbc99045f6c"},
    {file = "jiter-0.8.2-cp313-cp313-macosx_10_12_x86_64.whl", hash = "sha256:ca1f08b8e43dc3bd0594c992fb1fd2f7ce87f7bf0d44358198d6da8034afdf84"},
    {file = "jiter-0.8.2-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:5672a86d55416ccd214c778efccf3266b84f87b89063b582167d803246354be4"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:58dc9bc9767a1101f4e5e22db1b652161a225874d66f0e5cb8e2c7d1c438b587"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:37b2998606d6dadbb5ccda959a33d6a5e853252d921fec1792fc902351bb4e2c"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:4ab9a87f3784eb0e098f84a32670cfe4a79cb6512fd8f42ae3d0709f06405d18"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:79aec8172b9e3c6d05fd4b219d5de1ac616bd8da934107325a6c0d0e866a21b6"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:711e408732d4e9a0208008e5892c2966b485c783cd2d9a681f3eb147cf36c7ef"},
    {file = "jiter-0.8.2-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:653cf462db4e8c41995e33d865965e79641ef45369d8a11f54cd30888b7e6ff1"},
    {file = "jiter-0.8.2-cp313-cp313-musllinux_1_1_aarch64.whl", hash = "sha256:9c63eaef32b7bebac8ebebf4dabebdbc6769a09c127294db6babee38e9f405b9"},
    {file = "jiter-0.8.2-cp313-cp313-musllinux_1_1_x86_64.whl", hash = "sha256:eb21aaa9a200d0a80dacc7a81038d2e476ffe473ffdd9c91eb745d623561de05"},
    {file = "jiter-0.8.2-cp313-cp313-win32.whl", hash = "sha256:789361ed945d8d42850f919342a8665d2dc79e7e44ca1c97cc786966a21f627a"},
    {file = "jiter-0.8.2-cp313-cp313-win_amd64.whl", hash = "sha256:ab7f43235d71e03b941c1630f4b6e3055d46b6cb8728a17663eaac9d8e83a865"},
    {file = "jiter-0.8.2-cp313-cp313t-macosx_11_0_arm64.whl", hash = "sha256:b426f72cd77da3fec300ed3bc990895e2dd6b49e3bfe6c438592a3ba660e41ca"},
    {file = "jiter-0.8.2-cp313-cp313t-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:b2dd880785088ff2ad21ffee205e58a8c1ddabc63612444ae41e5e4b321b39c0"},
    {file = "jiter-0.8.2-cp313-cp313t-win_amd64.whl", hash = "sha256:3ac9f578c46f22405ff7f8b1f5848fb753cc4b8377fbec8470a7dc3997ca7566"},
    {file = "jiter-0.8.2-cp38-cp38-macosx_10_12_x86_64.whl", hash = "sha256:9e1fa156ee9454642adb7e7234a383884452532bc9d53d5af2d18d98ada1d79c"},
    {file = "jiter-0.8.2-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:0cf5dfa9956d96ff2efb0f8e9c7d055904012c952539a774305aaaf3abdf3d6c"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:e52bf98c7e727dd44f7c4acb980cb988448faeafed8433c867888268899b298b"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:a2ecaa3c23e7a7cf86d00eda3390c232f4d533cd9ddea4b04f5d0644faf642c5"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:08d4c92bf480e19fc3f2717c9ce2aa31dceaa9163839a311424b6862252c943e"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:99d9a1eded738299ba8e106c6779ce5c3893cffa0e32e4485d680588adae6db8"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d20be8b7f606df096e08b0b1b4a3c6f0515e8dac296881fe7461dfa0fb5ec817"},
    {file = "jiter-0.8.2-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:d33f94615fcaf872f7fd8cd98ac3b429e435c77619777e8a449d9d27e01134d1"},
    {file = "jiter-0.8.2-cp38-cp38-musllinux_1_1_aarch64.whl", hash = "sha256:317b25e98a35ffec5c67efe56a4e9970852632c810d35b34ecdd70cc0e47b3b6"},
    {file = "jiter-0.8.2-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:fc9043259ee430ecd71d178fccabd8c332a3bf1e81e50cae43cc2b28d19e4cb7"},
    {file = "jiter-0.8.2-cp38-cp38-win32.whl", hash = "sha256:fc5adda618205bd4678b146612ce44c3cbfdee9697951f2c0ffdef1f26d72b63"},
    {file = "jiter-0.8.2-cp38-cp38-win_amd64.whl", hash = "sha256:cd646c827b4f85ef4a78e4e58f4f5854fae0caf3db91b59f0d73731448a970c6"},
    {file = "jiter-0.8.2-cp39-cp39-macosx_10_12_x86_64.whl", hash = "sha256:e41e75344acef3fc59ba4765df29f107f309ca9e8eace5baacabd9217e52a5ee"},
    {file = "jiter-0.8.2-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:7f22b16b35d5c1df9dfd58843ab2cd25e6bf15191f5a236bed177afade507bfc"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:f7200b8f7619d36aa51c803fd52020a2dfbea36ffec1b5e22cab11fd34d95a6d"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:70bf4c43652cc294040dbb62256c83c8718370c8b93dd93d934b9a7bf6c4f53c"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f9d471356dc16f84ed48768b8ee79f29514295c7295cb41e1133ec0b2b8d637d"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:859e8eb3507894093d01929e12e267f83b1d5f6221099d3ec976f0c995cb6bd9"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:eaa58399c01db555346647a907b4ef6d4f584b123943be6ed5588c3f2359c9f4"},
    {file = "jiter-0.8.2-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:8f2d5ed877f089862f4c7aacf3a542627c1496f972a34d0474ce85ee7d939c27"},
    {file = "jiter-0.8.2-cp39-cp39-musllinux_1_1_aarch64.whl", hash = "sha256:03c9df035d4f8d647f8c210ddc2ae0728387275340668fb30d2421e17d9a0841"},
    {file = "jiter-0.8.2-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:8bd2a824d08d8977bb2794ea2682f898ad3d8837932e3a74937e93d62ecbb637"},
    {file = "jiter-0.8.2-cp39-cp39-win32.whl", hash = "sha256:ca29b6371ebc40e496995c94b988a101b9fbbed48a51190a4461fcb0a68b4a36"},
    {file = "jiter-0.8.2-cp39-cp39-win_amd64.whl", hash = "sha256:1c0dfbd1be3cbefc7510102370d86e35d1d53e5a93d48519688b1bf0f761160a"},
    {file = "jiter-0.8.2.tar.gz", hash = "sha256:cd73d3e740666d0e639f678adb176fad25c1bcbdae88d8d7b857e1783bb4212d"},
]

[[package]]
name = "moviepy"
version = "1.0.3"
description = "Video editing with Python"
optional = false
python-versions = "*"
files = [
    {file = "moviepy-1.0.3.tar.gz", hash = "sha256:2884e35d1788077db3ff89e763c5ba7bfddbd7ae9108c9bc809e7ba58fa433f5"},
]

[package.dependencies]
decorator = ">=4.0.2,<5.0"
imageio = {version = ">=2.5,<3.0", markers = "python_version >= \"3.4\""}
imageio_ffmpeg = {version = ">=0.2.0", markers = "python_version >= \"3.4\""}
numpy = {version = ">=1.17.3", markers = "python_version > \"2.7\""}
proglog = "<=1.0.0"
requests = ">=2.8.1,<3.0"
tqdm = ">=4.11.2,<5.0"

[package.extras]
doc = ["Sphinx (>=1.5.2,<2.0)", "numpydoc (>=0.6.0,<1.0)", "pygame (>=1.9.3,<2.0)", "sphinx_rtd_theme (>=0.1.10b0,<1.0)"]
optional = ["matplotlib (>=2.0.0,<3.0)", "opencv-python (>=3.0,<4.0)", "scikit-image (>=0.13.0,<1.0)", "scikit-learn", "scipy (>=0.19.0,<1.5)", "youtube_dl"]
test = ["coverage (<5.0)", "coveralls (>=1.1,<2.0)", "pytest (>=3.0.0,<4.0)", "pytest-cov (>=2.5.1,<3.0)", "requests (>=2.8.1,<3.0)"]

[[package]]
name = "multidict"
version = "6.1.0"
description = "multidict implementation"
optional = false
python-versions = ">=3.8"
files = [
    {file = "multidict-6.1.0-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:3380252550e372e8511d49481bd836264c009adb826b23fefcc5dd3c69692f60"},
    {file = "multidict-6.1.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:99f826cbf970077383d7de805c0681799491cb939c25450b9b5b3ced03ca99f1"},
    {file = "multidict-6.1.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:a114d03b938376557927ab23f1e950827c3b893ccb94b62fd95d430fd0e5cf53"},
    {file = "multidict-6.1.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b1c416351ee6271b2f49b56ad7f308072f6f44b37118d69c2cad94f3fa8a40d5"},
    {file = "multidict-6.1.0-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:6b5d83030255983181005e6cfbac1617ce9746b219bc2aad52201ad121226581"},
    {file = "multidict-6.1.0-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:3e97b5e938051226dc025ec80980c285b053ffb1e25a3db2a3aa3bc046bf7f56"},
    {file = "multidict-6.1.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d618649d4e70ac6efcbba75be98b26ef5078faad23592f9b51ca492953012429"},
    {file = "multidict-6.1.0-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:10524ebd769727ac77ef2278390fb0068d83f3acb7773792a5080f2b0abf7748"},
    {file = "multidict-6.1.0-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:ff3827aef427c89a25cc96ded1759271a93603aba9fb977a6d264648ebf989db"},
    {file = "multidict-6.1.0-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:06809f4f0f7ab7ea2cabf9caca7d79c22c0758b58a71f9d32943ae13c7ace056"},
    {file = "multidict-6.1.0-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:f179dee3b863ab1c59580ff60f9d99f632f34ccb38bf67a33ec6b3ecadd0fd76"},
    {file = "multidict-6.1.0-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:aaed8b0562be4a0876ee3b6946f6869b7bcdb571a5d1496683505944e268b160"},
    {file = "multidict-6.1.0-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:3c8b88a2ccf5493b6c8da9076fb151ba106960a2df90c2633f342f120751a9e7"},
    {file = "multidict-6.1.0-cp310-cp310-win32.whl", hash = "sha256:4a9cb68166a34117d6646c0023c7b759bf197bee5ad4272f420a0141d7eb03a0"},
    {file = "multidict-6.1.0-cp310-cp310-win_amd64.whl", hash = "sha256:20b9b5fbe0b88d0bdef2012ef7dee867f874b72528cf1d08f1d59b0e3850129d"},
    {file = "multidict-6.1.0-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:3efe2c2cb5763f2f1b275ad2bf7a287d3f7ebbef35648a9726e3b69284a4f3d6"},
    {file = "multidict-6.1.0-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:c7053d3b0353a8b9de430a4f4b4268ac9a4fb3481af37dfe49825bf45ca24156"},
    {file = "multidict-6.1.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:27e5fc84ccef8dfaabb09d82b7d179c7cf1a3fbc8a966f8274fcb4ab2eb4cadb"},
    {file = "multidict-6.1.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0e2b90b43e696f25c62656389d32236e049568b39320e2735d51f08fd362761b"},
    {file = "multidict-6.1.0-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d83a047959d38a7ff552ff94be767b7fd79b831ad1cd9920662db05fec24fe72"},
    {file = "multidict-6.1.0-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:d1a9dd711d0877a1ece3d2e4fea11a8e75741ca21954c919406b44e7cf971304"},
    {file = "multidict-6.1.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ec2abea24d98246b94913b76a125e855eb5c434f7c46546046372fe60f666351"},
    {file = "multidict-6.1.0-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:4867cafcbc6585e4b678876c489b9273b13e9fff9f6d6d66add5e15d11d926cb"},
    {file = "multidict-6.1.0-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:5b48204e8d955c47c55b72779802b219a39acc3ee3d0116d5080c388970b76e3"},
    {file = "multidict-6.1.0-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:d8fff389528cad1618fb4b26b95550327495462cd745d879a8c7c2115248e399"},
    {file = "multidict-6.1.0-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:a7a9541cd308eed5e30318430a9c74d2132e9a8cb46b901326272d780bf2d423"},
    {file = "multidict-6.1.0-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:da1758c76f50c39a2efd5e9859ce7d776317eb1dd34317c8152ac9251fc574a3"},
    {file = "multidict-6.1.0-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:c943a53e9186688b45b323602298ab727d8865d8c9ee0b17f8d62d14b56f0753"},
    {file = "multidict-6.1.0-cp311-cp311-win32.whl", hash = "sha256:90f8717cb649eea3504091e640a1b8568faad18bd4b9fcd692853a04475a4b80"},
    {file = "multidict-6.1.0-cp311-cp311-win_amd64.whl", hash = "sha256:82176036e65644a6cc5bd619f65f6f19781e8ec2e5330f51aa9ada7504cc1926"},
    {file = "multidict-6.1.0-cp312-cp312-macosx_10_9_universal2.whl", hash = "sha256:b04772ed465fa3cc947db808fa306d79b43e896beb677a56fb2347ca1a49c1fa"},
    {file = "multidict-6.1.0-cp312-cp312-macosx_10_9_x86_64.whl", hash = "sha256:6180c0ae073bddeb5a97a38c03f30c233e0a4d39cd86166251617d1bbd0af436"},
    {file = "multidict-6.1.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:071120490b47aa997cca00666923a83f02c7fbb44f71cf7f136df753f7fa8761"},
    {file = "multidict-6.1.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:50b3a2710631848991d0bf7de077502e8994c804bb805aeb2925a981de58ec2e"},
    {file = "multidict-6.1.0-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b58c621844d55e71c1b7f7c498ce5aa6985d743a1a59034c57a905b3f153c1ef"},
    {file = "multidict-6.1.0-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:55b6d90641869892caa9ca42ff913f7ff1c5ece06474fbd32fb2cf6834726c95"},
    {file = "multidict-6.1.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4b820514bfc0b98a30e3d85462084779900347e4d49267f747ff54060cc33925"},
    {file = "multidict-6.1.0-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:10a9b09aba0c5b48c53761b7c720aaaf7cf236d5fe394cd399c7ba662d5f9966"},
    {file = "multidict-6.1.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:1e16bf3e5fc9f44632affb159d30a437bfe286ce9e02754759be5536b169b305"},
    {file = "multidict-6.1.0-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:76f364861c3bfc98cbbcbd402d83454ed9e01a5224bb3a28bf70002a230f73e2"},
    {file = "multidict-6.1.0-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:820c661588bd01a0aa62a1283f20d2be4281b086f80dad9e955e690c75fb54a2"},
    {file = "multidict-6.1.0-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:0e5f362e895bc5b9e67fe6e4ded2492d8124bdf817827f33c5b46c2fe3ffaca6"},
    {file = "multidict-6.1.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:3ec660d19bbc671e3a6443325f07263be452c453ac9e512f5eb935e7d4ac28b3"},
    {file = "multidict-6.1.0-cp312-cp312-win32.whl", hash = "sha256:58130ecf8f7b8112cdb841486404f1282b9c86ccb30d3519faf301b2e5659133"},
    {file = "multidict-6.1.0-cp312-cp312-win_amd64.whl", hash = "sha256:188215fc0aafb8e03341995e7c4797860181562380f81ed0a87ff455b70bf1f1"},
    {file = "multidict-6.1.0-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:d569388c381b24671589335a3be6e1d45546c2988c2ebe30fdcada8457a31008"},
    {file = "multidict-6.1.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:052e10d2d37810b99cc170b785945421141bf7bb7d2f8799d431e7db229c385f"},
    {file = "multidict-6.1.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:f90c822a402cb865e396a504f9fc8173ef34212a342d92e362ca498cad308e28"},
    {file = "multidict-6.1.0-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b225d95519a5bf73860323e633a664b0d85ad3d5bede6d30d95b35d4dfe8805b"},
    {file = "multidict-6.1.0-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:23bfd518810af7de1116313ebd9092cb9aa629beb12f6ed631ad53356ed6b86c"},
    {file = "multidict-6.1.0-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:5c09fcfdccdd0b57867577b719c69e347a436b86cd83747f179dbf0cc0d4c1f3"},
    {file = "multidict-6.1.0-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bf6bea52ec97e95560af5ae576bdac3aa3aae0b6758c6efa115236d9e07dae44"},
    {file = "multidict-6.1.0-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:57feec87371dbb3520da6192213c7d6fc892d5589a93db548331954de8248fd2"},
    {file = "multidict-6.1.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:0c3f390dc53279cbc8ba976e5f8035eab997829066756d811616b652b00a23a3"},
    {file = "multidict-6.1.0-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:59bfeae4b25ec05b34f1956eaa1cb38032282cd4dfabc5056d0a1ec4d696d3aa"},
    {file = "multidict-6.1.0-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:b2f59caeaf7632cc633b5cf6fc449372b83bbdf0da4ae04d5be36118e46cc0aa"},
    {file = "multidict-6.1.0-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:37bb93b2178e02b7b618893990941900fd25b6b9ac0fa49931a40aecdf083fe4"},
    {file = "multidict-6.1.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:4e9f48f58c2c523d5a06faea47866cd35b32655c46b443f163d08c6d0ddb17d6"},
    {file = "multidict-6.1.0-cp313-cp313-win32.whl", hash = "sha256:3a37ffb35399029b45c6cc33640a92bef403c9fd388acce75cdc88f58bd19a81"},
    {file = "multidict-6.1.0-cp313-cp313-win_amd64.whl", hash = "sha256:e9aa71e15d9d9beaad2c6b9319edcdc0a49a43ef5c0a4c8265ca9ee7d6c67774"},
    {file = "multidict-6.1.0-cp38-cp38-macosx_10_9_universal2.whl", hash = "sha256:db7457bac39421addd0c8449933ac32d8042aae84a14911a757ae6ca3eef1392"},
    {file = "multidict-6.1.0-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:d094ddec350a2fb899fec68d8353c78233debde9b7d8b4beeafa70825f1c281a"},
    {file = "multidict-6.1.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:5845c1fd4866bb5dd3125d89b90e57ed3138241540897de748cdf19de8a2fca2"},
    {file = "multidict-6.1.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:9079dfc6a70abe341f521f78405b8949f96db48da98aeb43f9907f342f627cdc"},
    {file = "multidict-6.1.0-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:3914f5aaa0f36d5d60e8ece6a308ee1c9784cd75ec8151062614657a114c4478"},
    {file = "multidict-6.1.0-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:c08be4f460903e5a9d0f76818db3250f12e9c344e79314d1d570fc69d7f4eae4"},
    {file = "multidict-6.1.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d093be959277cb7dee84b801eb1af388b6ad3ca6a6b6bf1ed7585895789d027d"},
    {file = "multidict-6.1.0-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:3702ea6872c5a2a4eeefa6ffd36b042e9773f05b1f37ae3ef7264b1163c2dcf6"},
    {file = "multidict-6.1.0-cp38-cp38-musllinux_1_2_aarch64.whl", hash = "sha256:2090f6a85cafc5b2db085124d752757c9d251548cedabe9bd31afe6363e0aff2"},
    {file = "multidict-6.1.0-cp38-cp38-musllinux_1_2_i686.whl", hash = "sha256:f67f217af4b1ff66c68a87318012de788dd95fcfeb24cc889011f4e1c7454dfd"},
    {file = "multidict-6.1.0-cp38-cp38-musllinux_1_2_ppc64le.whl", hash = "sha256:189f652a87e876098bbc67b4da1049afb5f5dfbaa310dd67c594b01c10388db6"},
    {file = "multidict-6.1.0-cp38-cp38-musllinux_1_2_s390x.whl", hash = "sha256:6bb5992037f7a9eff7991ebe4273ea7f51f1c1c511e6a2ce511d0e7bdb754492"},
    {file = "multidict-6.1.0-cp38-cp38-musllinux_1_2_x86_64.whl", hash = "sha256:ac10f4c2b9e770c4e393876e35a7046879d195cd123b4f116d299d442b335bcd"},
    {file = "multidict-6.1.0-cp38-cp38-win32.whl", hash = "sha256:e27bbb6d14416713a8bd7aaa1313c0fc8d44ee48d74497a0ff4c3a1b6ccb5167"},
    {file = "multidict-6.1.0-cp38-cp38-win_amd64.whl", hash = "sha256:22f3105d4fb15c8f57ff3959a58fcab6ce36814486500cd7485651230ad4d4ef"},
    {file = "multidict-6.1.0-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:4e18b656c5e844539d506a0a06432274d7bd52a7487e6828c63a63d69185626c"},
    {file = "multidict-6.1.0-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:a185f876e69897a6f3325c3f19f26a297fa058c5e456bfcff8015e9a27e83ae1"},
    {file = "multidict-6.1.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:ab7c4ceb38d91570a650dba194e1ca87c2b543488fe9309b4212694174fd539c"},
    {file = "multidict-6.1.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:e617fb6b0b6953fffd762669610c1c4ffd05632c138d61ac7e14ad187870669c"},
    {file = "multidict-6.1.0-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:16e5f4bf4e603eb1fdd5d8180f1a25f30056f22e55ce51fb3d6ad4ab29f7d96f"},
    {file = "multidict-6.1.0-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:f4c035da3f544b1882bac24115f3e2e8760f10a0107614fc9839fd232200b875"},
    {file = "multidict-6.1.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:957cf8e4b6e123a9eea554fa7ebc85674674b713551de587eb318a2df3e00255"},
    {file = "multidict-6.1.0-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:483a6aea59cb89904e1ceabd2b47368b5600fb7de78a6e4a2c2987b2d256cf30"},
    {file = "multidict-6.1.0-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:87701f25a2352e5bf7454caa64757642734da9f6b11384c1f9d1a8e699758057"},
    {file = "multidict-6.1.0-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:682b987361e5fd7a139ed565e30d81fd81e9629acc7d925a205366877d8c8657"},
    {file = "multidict-6.1.0-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:ce2186a7df133a9c895dea3331ddc5ddad42cdd0d1ea2f0a51e5d161e4762f28"},
    {file = "multidict-6.1.0-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:9f636b730f7e8cb19feb87094949ba54ee5357440b9658b2a32a5ce4bce53972"},
    {file = "multidict-6.1.0-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:73eae06aa53af2ea5270cc066dcaf02cc60d2994bbb2c4ef5764949257d10f43"},
    {file = "multidict-6.1.0-cp39-cp39-win32.whl", hash = "sha256:1ca0083e80e791cffc6efce7660ad24af66c8d4079d2a750b29001b53ff59ada"},
    {file = "multidict-6.1.0-cp39-cp39-win_amd64.whl", hash = "sha256:aa466da5b15ccea564bdab9c89175c762bc12825f4659c11227f515cee76fa4a"},
    {file = "multidict-6.1.0-py3-none-any.whl", hash = "sha256:48e171e52d1c4d33888e529b999e5900356b9ae588c2f09a52dcefb158b27506"},
    {file = "multidict-6.1.0.tar.gz", hash = "sha256:22ae2ebf9b0c69d206c003e2f6a914ea33f0a932d4aa16f236afc049d9958f4a"},
]

[package.dependencies]
typing-extensions = {version = ">=4.1.0", markers = "python_version < \"3.11\""}

[[package]]
name = "nodeenv"
version = "1.9.1"
description = "Node.js virtual environment builder"
optional = false
python-versions = "!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,!=3.4.*,!=3.5.*,!=3.6.*,>=2.7"
files = [
    {file = "nodeenv-1.9.1-py2.py3-none-any.whl", hash = "sha256:ba11c9782d29c27c70ffbdda2d7415098754709be8a7056d79a737cd901155c9"},
    {file = "nodeenv-1.9.1.tar.gz", hash = "sha256:6ec12890a2dab7946721edbfbcd91f3319c6ccc9aec47be7c7e6b7011ee6645f"},
]

[[package]]
name = "numpy"
version = "2.2.0"
description = "Fundamental package for array computing in Python"
optional = false
python-versions = ">=3.10"
files = [
    {file = "numpy-2.2.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:1e25507d85da11ff5066269d0bd25d06e0a0f2e908415534f3e603d2a78e4ffa"},
    {file = "numpy-2.2.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:a62eb442011776e4036af5c8b1a00b706c5bc02dc15eb5344b0c750428c94219"},
    {file = "numpy-2.2.0-cp310-cp310-macosx_14_0_arm64.whl", hash = "sha256:b606b1aaf802e6468c2608c65ff7ece53eae1a6874b3765f69b8ceb20c5fa78e"},
    {file = "numpy-2.2.0-cp310-cp310-macosx_14_0_x86_64.whl", hash = "sha256:36b2b43146f646642b425dd2027730f99bac962618ec2052932157e213a040e9"},
    {file = "numpy-2.2.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:7fe8f3583e0607ad4e43a954e35c1748b553bfe9fdac8635c02058023277d1b3"},
    {file = "numpy-2.2.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:122fd2fcfafdefc889c64ad99c228d5a1f9692c3a83f56c292618a59aa60ae83"},
    {file = "numpy-2.2.0-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:3f2f5cddeaa4424a0a118924b988746db6ffa8565e5829b1841a8a3bd73eb59a"},
    {file = "numpy-2.2.0-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:7fe4bb0695fe986a9e4deec3b6857003b4cfe5c5e4aac0b95f6a658c14635e31"},
    {file = "numpy-2.2.0-cp310-cp310-win32.whl", hash = "sha256:b30042fe92dbd79f1ba7f6898fada10bdaad1847c44f2dff9a16147e00a93661"},
    {file = "numpy-2.2.0-cp310-cp310-win_amd64.whl", hash = "sha256:54dc1d6d66f8d37843ed281773c7174f03bf7ad826523f73435deb88ba60d2d4"},
    {file = "numpy-2.2.0-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:9874bc2ff574c40ab7a5cbb7464bf9b045d617e36754a7bc93f933d52bd9ffc6"},
    {file = "numpy-2.2.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:0da8495970f6b101ddd0c38ace92edea30e7e12b9a926b57f5fabb1ecc25bb90"},
    {file = "numpy-2.2.0-cp311-cp311-macosx_14_0_arm64.whl", hash = "sha256:0557eebc699c1c34cccdd8c3778c9294e8196df27d713706895edc6f57d29608"},
    {file = "numpy-2.2.0-cp311-cp311-macosx_14_0_x86_64.whl", hash = "sha256:3579eaeb5e07f3ded59298ce22b65f877a86ba8e9fe701f5576c99bb17c283da"},
    {file = "numpy-2.2.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:40deb10198bbaa531509aad0cd2f9fadb26c8b94070831e2208e7df543562b74"},
    {file = "numpy-2.2.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c2aed8fcf8abc3020d6a9ccb31dbc9e7d7819c56a348cc88fd44be269b37427e"},
    {file = "numpy-2.2.0-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:a222d764352c773aa5ebde02dd84dba3279c81c6db2e482d62a3fa54e5ece69b"},
    {file = "numpy-2.2.0-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:4e58666988605e251d42c2818c7d3d8991555381be26399303053b58a5bbf30d"},
    {file = "numpy-2.2.0-cp311-cp311-win32.whl", hash = "sha256:4723a50e1523e1de4fccd1b9a6dcea750c2102461e9a02b2ac55ffeae09a4410"},
    {file = "numpy-2.2.0-cp311-cp311-win_amd64.whl", hash = "sha256:16757cf28621e43e252c560d25b15f18a2f11da94fea344bf26c599b9cf54b73"},
    {file = "numpy-2.2.0-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:cff210198bb4cae3f3c100444c5eaa573a823f05c253e7188e1362a5555235b3"},
    {file = "numpy-2.2.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:58b92a5828bd4d9aa0952492b7de803135038de47343b2aa3cc23f3b71a3dc4e"},
    {file = "numpy-2.2.0-cp312-cp312-macosx_14_0_arm64.whl", hash = "sha256:ebe5e59545401fbb1b24da76f006ab19734ae71e703cdb4a8b347e84a0cece67"},
    {file = "numpy-2.2.0-cp312-cp312-macosx_14_0_x86_64.whl", hash = "sha256:e2b8cd48a9942ed3f85b95ca4105c45758438c7ed28fff1e4ce3e57c3b589d8e"},
    {file = "numpy-2.2.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:57fcc997ffc0bef234b8875a54d4058afa92b0b0c4223fc1f62f24b3b5e86038"},
    {file = "numpy-2.2.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:85ad7d11b309bd132d74397fcf2920933c9d1dc865487128f5c03d580f2c3d03"},
    {file = "numpy-2.2.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:cb24cca1968b21355cc6f3da1a20cd1cebd8a023e3c5b09b432444617949085a"},
    {file = "numpy-2.2.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:0798b138c291d792f8ea40fe3768610f3c7dd2574389e37c3f26573757c8f7ef"},
    {file = "numpy-2.2.0-cp312-cp312-win32.whl", hash = "sha256:afe8fb968743d40435c3827632fd36c5fbde633b0423da7692e426529b1759b1"},
    {file = "numpy-2.2.0-cp312-cp312-win_amd64.whl", hash = "sha256:3a4199f519e57d517ebd48cb76b36c82da0360781c6a0353e64c0cac30ecaad3"},
    {file = "numpy-2.2.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:f8c8b141ef9699ae777c6278b52c706b653bf15d135d302754f6b2e90eb30367"},
    {file = "numpy-2.2.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:0f0986e917aca18f7a567b812ef7ca9391288e2acb7a4308aa9d265bd724bdae"},
    {file = "numpy-2.2.0-cp313-cp313-macosx_14_0_arm64.whl", hash = "sha256:1c92113619f7b272838b8d6702a7f8ebe5edea0df48166c47929611d0b4dea69"},
    {file = "numpy-2.2.0-cp313-cp313-macosx_14_0_x86_64.whl", hash = "sha256:5a145e956b374e72ad1dff82779177d4a3c62bc8248f41b80cb5122e68f22d13"},
    {file = "numpy-2.2.0-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:18142b497d70a34b01642b9feabb70156311b326fdddd875a9981f34a369b671"},
    {file = "numpy-2.2.0-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a7d41d1612c1a82b64697e894b75db6758d4f21c3ec069d841e60ebe54b5b571"},
    {file = "numpy-2.2.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:a98f6f20465e7618c83252c02041517bd2f7ea29be5378f09667a8f654a5918d"},
    {file = "numpy-2.2.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:e09d40edfdb4e260cb1567d8ae770ccf3b8b7e9f0d9b5c2a9992696b30ce2742"},
    {file = "numpy-2.2.0-cp313-cp313-win32.whl", hash = "sha256:3905a5fffcc23e597ee4d9fb3fcd209bd658c352657548db7316e810ca80458e"},
    {file = "numpy-2.2.0-cp313-cp313-win_amd64.whl", hash = "sha256:a184288538e6ad699cbe6b24859206e38ce5fba28f3bcfa51c90d0502c1582b2"},
    {file = "numpy-2.2.0-cp313-cp313t-macosx_10_13_x86_64.whl", hash = "sha256:7832f9e8eb00be32f15fdfb9a981d6955ea9adc8574c521d48710171b6c55e95"},
    {file = "numpy-2.2.0-cp313-cp313t-macosx_11_0_arm64.whl", hash = "sha256:f0dd071b95bbca244f4cb7f70b77d2ff3aaaba7fa16dc41f58d14854a6204e6c"},
    {file = "numpy-2.2.0-cp313-cp313t-macosx_14_0_arm64.whl", hash = "sha256:b0b227dcff8cdc3efbce66d4e50891f04d0a387cce282fe1e66199146a6a8fca"},
    {file = "numpy-2.2.0-cp313-cp313t-macosx_14_0_x86_64.whl", hash = "sha256:6ab153263a7c5ccaf6dfe7e53447b74f77789f28ecb278c3b5d49db7ece10d6d"},
    {file = "numpy-2.2.0-cp313-cp313t-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:e500aba968a48e9019e42c0c199b7ec0696a97fa69037bea163b55398e390529"},
    {file = "numpy-2.2.0-cp313-cp313t-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:440cfb3db4c5029775803794f8638fbdbf71ec702caf32735f53b008e1eaece3"},
    {file = "numpy-2.2.0-cp313-cp313t-musllinux_1_2_aarch64.whl", hash = "sha256:a55dc7a7f0b6198b07ec0cd445fbb98b05234e8b00c5ac4874a63372ba98d4ab"},
    {file = "numpy-2.2.0-cp313-cp313t-musllinux_1_2_x86_64.whl", hash = "sha256:4bddbaa30d78c86329b26bd6aaaea06b1e47444da99eddac7bf1e2fab717bd72"},
    {file = "numpy-2.2.0-cp313-cp313t-win32.whl", hash = "sha256:30bf971c12e4365153afb31fc73f441d4da157153f3400b82db32d04de1e4066"},
    {file = "numpy-2.2.0-cp313-cp313t-win_amd64.whl", hash = "sha256:d35717333b39d1b6bb8433fa758a55f1081543de527171543a2b710551d40881"},
    {file = "numpy-2.2.0-pp310-pypy310_pp73-macosx_10_15_x86_64.whl", hash = "sha256:e12c6c1ce84628c52d6367863773f7c8c8241be554e8b79686e91a43f1733773"},
    {file = "numpy-2.2.0-pp310-pypy310_pp73-macosx_14_0_x86_64.whl", hash = "sha256:b6207dc8fb3c8cb5668e885cef9ec7f70189bec4e276f0ff70d5aa078d32c88e"},
    {file = "numpy-2.2.0-pp310-pypy310_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a50aeff71d0f97b6450d33940c7181b08be1441c6c193e678211bff11aa725e7"},
    {file = "numpy-2.2.0-pp310-pypy310_pp73-win_amd64.whl", hash = "sha256:df12a1f99b99f569a7c2ae59aa2d31724e8d835fc7f33e14f4792e3071d11221"},
    {file = "numpy-2.2.0.tar.gz", hash = "sha256:140dd80ff8981a583a60980be1a655068f8adebf7a45a06a6858c873fcdcd4a0"},
]

[[package]]
name = "openai"
version = "1.58.1"
description = "The official Python library for the openai API"
optional = false
python-versions = ">=3.8"
files = [
    {file = "openai-1.58.1-py3-none-any.whl", hash = "sha256:e2910b1170a6b7f88ef491ac3a42c387f08bd3db533411f7ee391d166571d63c"},
    {file = "openai-1.58.1.tar.gz", hash = "sha256:f5a035fd01e141fc743f4b0e02c41ca49be8fab0866d3b67f5f29b4f4d3c0973"},
]

[package.dependencies]
anyio = ">=3.5.0,<5"
distro = ">=1.7.0,<2"
httpx = ">=0.23.0,<1"
jiter = ">=0.4.0,<1"
pydantic = ">=1.9.0,<3"
sniffio = "*"
tqdm = ">4"
typing-extensions = ">=4.11,<5"

[package.extras]
datalib = ["numpy (>=1)", "pandas (>=1.2.3)", "pandas-stubs (>=1.1.0.11)"]
realtime = ["websockets (>=13,<15)"]

[[package]]
name = "packaging"
version = "24.2"
description = "Core utilities for Python packages"
optional = false
python-versions = ">=3.8"
files = [
    {file = "packaging-24.2-py3-none-any.whl", hash = "sha256:09abb1bccd265c01f4a3aa3f7a7db064b36514d2cba19a2f694fe6150451a759"},
    {file = "packaging-24.2.tar.gz", hash = "sha256:c228a6dc5e932d346bc5739379109d49e8853dd8223571c7c5b55260edc0b97f"},
]

[[package]]
name = "pillow"
version = "10.4.0"
description = "Python Imaging Library (Fork)"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pillow-10.4.0-cp310-cp310-macosx_10_10_x86_64.whl", hash = "sha256:4d9667937cfa347525b319ae34375c37b9ee6b525440f3ef48542fcf66f2731e"},
    {file = "pillow-10.4.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:543f3dc61c18dafb755773efc89aae60d06b6596a63914107f75459cf984164d"},
    {file = "pillow-10.4.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:7928ecbf1ece13956b95d9cbcfc77137652b02763ba384d9ab508099a2eca856"},
    {file = "pillow-10.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e4d49b85c4348ea0b31ea63bc75a9f3857869174e2bf17e7aba02945cd218e6f"},
    {file = "pillow-10.4.0-cp310-cp310-manylinux_2_28_aarch64.whl", hash = "sha256:6c762a5b0997f5659a5ef2266abc1d8851ad7749ad9a6a5506eb23d314e4f46b"},
    {file = "pillow-10.4.0-cp310-cp310-manylinux_2_28_x86_64.whl", hash = "sha256:a985e028fc183bf12a77a8bbf36318db4238a3ded7fa9df1b9a133f1cb79f8fc"},
    {file = "pillow-10.4.0-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:812f7342b0eee081eaec84d91423d1b4650bb9828eb53d8511bcef8ce5aecf1e"},
    {file = "pillow-10.4.0-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:ac1452d2fbe4978c2eec89fb5a23b8387aba707ac72810d9490118817d9c0b46"},
    {file = "pillow-10.4.0-cp310-cp310-win32.whl", hash = "sha256:bcd5e41a859bf2e84fdc42f4edb7d9aba0a13d29a2abadccafad99de3feff984"},
    {file = "pillow-10.4.0-cp310-cp310-win_amd64.whl", hash = "sha256:ecd85a8d3e79cd7158dec1c9e5808e821feea088e2f69a974db5edf84dc53141"},
    {file = "pillow-10.4.0-cp310-cp310-win_arm64.whl", hash = "sha256:ff337c552345e95702c5fde3158acb0625111017d0e5f24bf3acdb9cc16b90d1"},
    {file = "pillow-10.4.0-cp311-cp311-macosx_10_10_x86_64.whl", hash = "sha256:0a9ec697746f268507404647e531e92889890a087e03681a3606d9b920fbee3c"},
    {file = "pillow-10.4.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:dfe91cb65544a1321e631e696759491ae04a2ea11d36715eca01ce07284738be"},
    {file = "pillow-10.4.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:5dc6761a6efc781e6a1544206f22c80c3af4c8cf461206d46a1e6006e4429ff3"},
    {file = "pillow-10.4.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:5e84b6cc6a4a3d76c153a6b19270b3526a5a8ed6b09501d3af891daa2a9de7d6"},
    {file = "pillow-10.4.0-cp311-cp311-manylinux_2_28_aarch64.whl", hash = "sha256:bbc527b519bd3aa9d7f429d152fea69f9ad37c95f0b02aebddff592688998abe"},
    {file = "pillow-10.4.0-cp311-cp311-manylinux_2_28_x86_64.whl", hash = "sha256:76a911dfe51a36041f2e756b00f96ed84677cdeb75d25c767f296c1c1eda1319"},
    {file = "pillow-10.4.0-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:59291fb29317122398786c2d44427bbd1a6d7ff54017075b22be9d21aa59bd8d"},
    {file = "pillow-10.4.0-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:416d3a5d0e8cfe4f27f574362435bc9bae57f679a7158e0096ad2beb427b8696"},
    {file = "pillow-10.4.0-cp311-cp311-win32.whl", hash = "sha256:7086cc1d5eebb91ad24ded9f58bec6c688e9f0ed7eb3dbbf1e4800280a896496"},
    {file = "pillow-10.4.0-cp311-cp311-win_amd64.whl", hash = "sha256:cbed61494057c0f83b83eb3a310f0bf774b09513307c434d4366ed64f4128a91"},
    {file = "pillow-10.4.0-cp311-cp311-win_arm64.whl", hash = "sha256:f5f0c3e969c8f12dd2bb7e0b15d5c468b51e5017e01e2e867335c81903046a22"},
    {file = "pillow-10.4.0-cp312-cp312-macosx_10_10_x86_64.whl", hash = "sha256:673655af3eadf4df6b5457033f086e90299fdd7a47983a13827acf7459c15d94"},
    {file = "pillow-10.4.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:866b6942a92f56300012f5fbac71f2d610312ee65e22f1aa2609e491284e5597"},
    {file = "pillow-10.4.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:29dbdc4207642ea6aad70fbde1a9338753d33fb23ed6956e706936706f52dd80"},
    {file = "pillow-10.4.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bf2342ac639c4cf38799a44950bbc2dfcb685f052b9e262f446482afaf4bffca"},
    {file = "pillow-10.4.0-cp312-cp312-manylinux_2_28_aarch64.whl", hash = "sha256:f5b92f4d70791b4a67157321c4e8225d60b119c5cc9aee8ecf153aace4aad4ef"},
    {file = "pillow-10.4.0-cp312-cp312-manylinux_2_28_x86_64.whl", hash = "sha256:86dcb5a1eb778d8b25659d5e4341269e8590ad6b4e8b44d9f4b07f8d136c414a"},
    {file = "pillow-10.4.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:780c072c2e11c9b2c7ca37f9a2ee8ba66f44367ac3e5c7832afcfe5104fd6d1b"},
    {file = "pillow-10.4.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:37fb69d905be665f68f28a8bba3c6d3223c8efe1edf14cc4cfa06c241f8c81d9"},
    {file = "pillow-10.4.0-cp312-cp312-win32.whl", hash = "sha256:7dfecdbad5c301d7b5bde160150b4db4c659cee2b69589705b6f8a0c509d9f42"},
    {file = "pillow-10.4.0-cp312-cp312-win_amd64.whl", hash = "sha256:1d846aea995ad352d4bdcc847535bd56e0fd88d36829d2c90be880ef1ee4668a"},
    {file = "pillow-10.4.0-cp312-cp312-win_arm64.whl", hash = "sha256:e553cad5179a66ba15bb18b353a19020e73a7921296a7979c4a2b7f6a5cd57f9"},
    {file = "pillow-10.4.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:8bc1a764ed8c957a2e9cacf97c8b2b053b70307cf2996aafd70e91a082e70df3"},
    {file = "pillow-10.4.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:6209bb41dc692ddfee4942517c19ee81b86c864b626dbfca272ec0f7cff5d9fb"},
    {file = "pillow-10.4.0-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:bee197b30783295d2eb680b311af15a20a8b24024a19c3a26431ff83eb8d1f70"},
    {file = "pillow-10.4.0-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:1ef61f5dd14c300786318482456481463b9d6b91ebe5ef12f405afbba77ed0be"},
    {file = "pillow-10.4.0-cp313-cp313-manylinux_2_28_aarch64.whl", hash = "sha256:297e388da6e248c98bc4a02e018966af0c5f92dfacf5a5ca22fa01cb3179bca0"},
    {file = "pillow-10.4.0-cp313-cp313-manylinux_2_28_x86_64.whl", hash = "sha256:e4db64794ccdf6cb83a59d73405f63adbe2a1887012e308828596100a0b2f6cc"},
    {file = "pillow-10.4.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:bd2880a07482090a3bcb01f4265f1936a903d70bc740bfcb1fd4e8a2ffe5cf5a"},
    {file = "pillow-10.4.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:4b35b21b819ac1dbd1233317adeecd63495f6babf21b7b2512d244ff6c6ce309"},
    {file = "pillow-10.4.0-cp313-cp313-win32.whl", hash = "sha256:551d3fd6e9dc15e4c1eb6fc4ba2b39c0c7933fa113b220057a34f4bb3268a060"},
    {file = "pillow-10.4.0-cp313-cp313-win_amd64.whl", hash = "sha256:030abdbe43ee02e0de642aee345efa443740aa4d828bfe8e2eb11922ea6a21ea"},
    {file = "pillow-10.4.0-cp313-cp313-win_arm64.whl", hash = "sha256:5b001114dd152cfd6b23befeb28d7aee43553e2402c9f159807bf55f33af8a8d"},
    {file = "pillow-10.4.0-cp38-cp38-macosx_10_10_x86_64.whl", hash = "sha256:8d4d5063501b6dd4024b8ac2f04962d661222d120381272deea52e3fc52d3736"},
    {file = "pillow-10.4.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:7c1ee6f42250df403c5f103cbd2768a28fe1a0ea1f0f03fe151c8741e1469c8b"},
    {file = "pillow-10.4.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b15e02e9bb4c21e39876698abf233c8c579127986f8207200bc8a8f6bb27acf2"},
    {file = "pillow-10.4.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7a8d4bade9952ea9a77d0c3e49cbd8b2890a399422258a77f357b9cc9be8d680"},
    {file = "pillow-10.4.0-cp38-cp38-manylinux_2_28_aarch64.whl", hash = "sha256:43efea75eb06b95d1631cb784aa40156177bf9dd5b4b03ff38979e048258bc6b"},
    {file = "pillow-10.4.0-cp38-cp38-manylinux_2_28_x86_64.whl", hash = "sha256:950be4d8ba92aca4b2bb0741285a46bfae3ca699ef913ec8416c1b78eadd64cd"},
    {file = "pillow-10.4.0-cp38-cp38-musllinux_1_2_aarch64.whl", hash = "sha256:d7480af14364494365e89d6fddc510a13e5a2c3584cb19ef65415ca57252fb84"},
    {file = "pillow-10.4.0-cp38-cp38-musllinux_1_2_x86_64.whl", hash = "sha256:73664fe514b34c8f02452ffb73b7a92c6774e39a647087f83d67f010eb9a0cf0"},
    {file = "pillow-10.4.0-cp38-cp38-win32.whl", hash = "sha256:e88d5e6ad0d026fba7bdab8c3f225a69f063f116462c49892b0149e21b6c0a0e"},
    {file = "pillow-10.4.0-cp38-cp38-win_amd64.whl", hash = "sha256:5161eef006d335e46895297f642341111945e2c1c899eb406882a6c61a4357ab"},
    {file = "pillow-10.4.0-cp39-cp39-macosx_10_10_x86_64.whl", hash = "sha256:0ae24a547e8b711ccaaf99c9ae3cd975470e1a30caa80a6aaee9a2f19c05701d"},
    {file = "pillow-10.4.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:298478fe4f77a4408895605f3482b6cc6222c018b2ce565c2b6b9c354ac3229b"},
    {file = "pillow-10.4.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:134ace6dc392116566980ee7436477d844520a26a4b1bd4053f6f47d096997fd"},
    {file = "pillow-10.4.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:930044bb7679ab003b14023138b50181899da3f25de50e9dbee23b61b4de2126"},
    {file = "pillow-10.4.0-cp39-cp39-manylinux_2_28_aarch64.whl", hash = "sha256:c76e5786951e72ed3686e122d14c5d7012f16c8303a674d18cdcd6d89557fc5b"},
    {file = "pillow-10.4.0-cp39-cp39-manylinux_2_28_x86_64.whl", hash = "sha256:b2724fdb354a868ddf9a880cb84d102da914e99119211ef7ecbdc613b8c96b3c"},
    {file = "pillow-10.4.0-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:dbc6ae66518ab3c5847659e9988c3b60dc94ffb48ef9168656e0019a93dbf8a1"},
    {file = "pillow-10.4.0-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:06b2f7898047ae93fad74467ec3d28fe84f7831370e3c258afa533f81ef7f3df"},
    {file = "pillow-10.4.0-cp39-cp39-win32.whl", hash = "sha256:7970285ab628a3779aecc35823296a7869f889b8329c16ad5a71e4901a3dc4ef"},
    {file = "pillow-10.4.0-cp39-cp39-win_amd64.whl", hash = "sha256:961a7293b2457b405967af9c77dcaa43cc1a8cd50d23c532e62d48ab6cdd56f5"},
    {file = "pillow-10.4.0-cp39-cp39-win_arm64.whl", hash = "sha256:32cda9e3d601a52baccb2856b8ea1fc213c90b340c542dcef77140dfa3278a9e"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-macosx_10_15_x86_64.whl", hash = "sha256:5b4815f2e65b30f5fbae9dfffa8636d992d49705723fe86a3661806e069352d4"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-macosx_11_0_arm64.whl", hash = "sha256:8f0aef4ef59694b12cadee839e2ba6afeab89c0f39a3adc02ed51d109117b8da"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:9f4727572e2918acaa9077c919cbbeb73bd2b3ebcfe033b72f858fc9fbef0026"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ff25afb18123cea58a591ea0244b92eb1e61a1fd497bf6d6384f09bc3262ec3e"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-manylinux_2_28_aarch64.whl", hash = "sha256:dc3e2db6ba09ffd7d02ae9141cfa0ae23393ee7687248d46a7507b75d610f4f5"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-manylinux_2_28_x86_64.whl", hash = "sha256:02a2be69f9c9b8c1e97cf2713e789d4e398c751ecfd9967c18d0ce304efbf885"},
    {file = "pillow-10.4.0-pp310-pypy310_pp73-win_amd64.whl", hash = "sha256:0755ffd4a0c6f267cccbae2e9903d95477ca2f77c4fcf3a3a09570001856c8a5"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-macosx_10_15_x86_64.whl", hash = "sha256:a02364621fe369e06200d4a16558e056fe2805d3468350df3aef21e00d26214b"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-macosx_11_0_arm64.whl", hash = "sha256:1b5dea9831a90e9d0721ec417a80d4cbd7022093ac38a568db2dd78363b00908"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:9b885f89040bb8c4a1573566bbb2f44f5c505ef6e74cec7ab9068c900047f04b"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:87dd88ded2e6d74d31e1e0a99a726a6765cda32d00ba72dc37f0651f306daaa8"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-manylinux_2_28_aarch64.whl", hash = "sha256:2db98790afc70118bd0255c2eeb465e9767ecf1f3c25f9a1abb8ffc8cfd1fe0a"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-manylinux_2_28_x86_64.whl", hash = "sha256:f7baece4ce06bade126fb84b8af1c33439a76d8a6fd818970215e0560ca28c27"},
    {file = "pillow-10.4.0-pp39-pypy39_pp73-win_amd64.whl", hash = "sha256:cfdd747216947628af7b259d274771d84db2268ca062dd5faf373639d00113a3"},
    {file = "pillow-10.4.0.tar.gz", hash = "sha256:166c1cd4d24309b30d61f79f4a9114b7b2313d7450912277855ff5dfd7cd4a06"},
]

[package.extras]
docs = ["furo", "olefile", "sphinx (>=7.3)", "sphinx-copybutton", "sphinx-inline-tabs", "sphinxext-opengraph"]
fpx = ["olefile"]
mic = ["olefile"]
tests = ["check-manifest", "coverage", "defusedxml", "markdown2", "olefile", "packaging", "pyroma", "pytest", "pytest-cov", "pytest-timeout"]
typing = ["typing-extensions"]
xmp = ["defusedxml"]

[[package]]
name = "platformdirs"
version = "4.3.6"
description = "A small Python package for determining appropriate platform-specific dirs, e.g. a `user data dir`."
optional = false
python-versions = ">=3.8"
files = [
    {file = "platformdirs-4.3.6-py3-none-any.whl", hash = "sha256:73e575e1408ab8103900836b97580d5307456908a03e92031bab39e4554cc3fb"},
    {file = "platformdirs-4.3.6.tar.gz", hash = "sha256:357fb2acbc885b0419afd3ce3ed34564c13c9b95c89360cd9563f73aa5e2b907"},
]

[package.extras]
docs = ["furo (>=2024.8.6)", "proselint (>=0.14)", "sphinx (>=8.0.2)", "sphinx-autodoc-typehints (>=2.4)"]
test = ["appdirs (==1.4.4)", "covdefaults (>=2.3)", "pytest (>=8.3.2)", "pytest-cov (>=5)", "pytest-mock (>=3.14)"]
type = ["mypy (>=1.11.2)"]

[[package]]
name = "pluggy"
version = "1.5.0"
description = "plugin and hook calling mechanisms for python"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pluggy-1.5.0-py3-none-any.whl", hash = "sha256:44e1ad92c8ca002de6377e165f3e0f1be63266ab4d554740532335b9d75ea669"},
    {file = "pluggy-1.5.0.tar.gz", hash = "sha256:2cffa88e94fdc978c4c574f15f9e59b7f4201d439195c3715ca9e2486f1d0cf1"},
]

[package.extras]
dev = ["pre-commit", "tox"]
testing = ["pytest", "pytest-benchmark"]

[[package]]
name = "pre-commit"
version = "3.8.0"
description = "A framework for managing and maintaining multi-language pre-commit hooks."
optional = false
python-versions = ">=3.9"
files = [
    {file = "pre_commit-3.8.0-py2.py3-none-any.whl", hash = "sha256:9a90a53bf82fdd8778d58085faf8d83df56e40dfe18f45b19446e26bf1b3a63f"},
    {file = "pre_commit-3.8.0.tar.gz", hash = "sha256:8bb6494d4a20423842e198980c9ecf9f96607a07ea29549e180eef9ae80fe7af"},
]

[package.dependencies]
cfgv = ">=2.0.0"
identify = ">=1.0.0"
nodeenv = ">=0.11.1"
pyyaml = ">=5.1"
virtualenv = ">=20.10.0"

[[package]]
name = "proglog"
version = "0.1.10"
description = "Log and progress bar manager for console, notebooks, web..."
optional = false
python-versions = "*"
files = [
    {file = "proglog-0.1.10-py3-none-any.whl", hash = "sha256:19d5da037e8c813da480b741e3fa71fb1ac0a5b02bf21c41577c7f327485ec50"},
    {file = "proglog-0.1.10.tar.gz", hash = "sha256:658c28c9c82e4caeb2f25f488fff9ceace22f8d69b15d0c1c86d64275e4ddab4"},
]

[package.dependencies]
tqdm = "*"

[[package]]
name = "propcache"
version = "0.2.1"
description = "Accelerated property cache"
optional = false
python-versions = ">=3.9"
files = [
    {file = "propcache-0.2.1-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:6b3f39a85d671436ee3d12c017f8fdea38509e4f25b28eb25877293c98c243f6"},
    {file = "propcache-0.2.1-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:39d51fbe4285d5db5d92a929e3e21536ea3dd43732c5b177c7ef03f918dff9f2"},
    {file = "propcache-0.2.1-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:6445804cf4ec763dc70de65a3b0d9954e868609e83850a47ca4f0cb64bd79fea"},
    {file = "propcache-0.2.1-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:f9479aa06a793c5aeba49ce5c5692ffb51fcd9a7016e017d555d5e2b0045d212"},
    {file = "propcache-0.2.1-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d9631c5e8b5b3a0fda99cb0d29c18133bca1e18aea9effe55adb3da1adef80d3"},
    {file = "propcache-0.2.1-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:3156628250f46a0895f1f36e1d4fbe062a1af8718ec3ebeb746f1d23f0c5dc4d"},
    {file = "propcache-0.2.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6b6fb63ae352e13748289f04f37868099e69dba4c2b3e271c46061e82c745634"},
    {file = "propcache-0.2.1-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:887d9b0a65404929641a9fabb6452b07fe4572b269d901d622d8a34a4e9043b2"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:a96dc1fa45bd8c407a0af03b2d5218392729e1822b0c32e62c5bf7eeb5fb3958"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_armv7l.whl", hash = "sha256:a7e65eb5c003a303b94aa2c3852ef130230ec79e349632d030e9571b87c4698c"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:999779addc413181912e984b942fbcc951be1f5b3663cd80b2687758f434c583"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:19a0f89a7bb9d8048d9c4370c9c543c396e894c76be5525f5e1ad287f1750ddf"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:1ac2f5fe02fa75f56e1ad473f1175e11f475606ec9bd0be2e78e4734ad575034"},
    {file = "propcache-0.2.1-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:574faa3b79e8ebac7cb1d7930f51184ba1ccf69adfdec53a12f319a06030a68b"},
    {file = "propcache-0.2.1-cp310-cp310-win32.whl", hash = "sha256:03ff9d3f665769b2a85e6157ac8b439644f2d7fd17615a82fa55739bc97863f4"},
    {file = "propcache-0.2.1-cp310-cp310-win_amd64.whl", hash = "sha256:2d3af2e79991102678f53e0dbf4c35de99b6b8b58f29a27ca0325816364caaba"},
    {file = "propcache-0.2.1-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:1ffc3cca89bb438fb9c95c13fc874012f7b9466b89328c3c8b1aa93cdcfadd16"},
    {file = "propcache-0.2.1-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:f174bbd484294ed9fdf09437f889f95807e5f229d5d93588d34e92106fbf6717"},
    {file = "propcache-0.2.1-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:70693319e0b8fd35dd863e3e29513875eb15c51945bf32519ef52927ca883bc3"},
    {file = "propcache-0.2.1-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b480c6a4e1138e1aa137c0079b9b6305ec6dcc1098a8ca5196283e8a49df95a9"},
    {file = "propcache-0.2.1-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d27b84d5880f6d8aa9ae3edb253c59d9f6642ffbb2c889b78b60361eed449787"},
    {file = "propcache-0.2.1-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:857112b22acd417c40fa4595db2fe28ab900c8c5fe4670c7989b1c0230955465"},
    {file = "propcache-0.2.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:cf6c4150f8c0e32d241436526f3c3f9cbd34429492abddbada2ffcff506c51af"},
    {file = "propcache-0.2.1-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:66d4cfda1d8ed687daa4bc0274fcfd5267873db9a5bc0418c2da19273040eeb7"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:c2f992c07c0fca81655066705beae35fc95a2fa7366467366db627d9f2ee097f"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_armv7l.whl", hash = "sha256:4a571d97dbe66ef38e472703067021b1467025ec85707d57e78711c085984e54"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:bb6178c241278d5fe853b3de743087be7f5f4c6f7d6d22a3b524d323eecec505"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:ad1af54a62ffe39cf34db1aa6ed1a1873bd548f6401db39d8e7cd060b9211f82"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:e7048abd75fe40712005bcfc06bb44b9dfcd8e101dda2ecf2f5aa46115ad07ca"},
    {file = "propcache-0.2.1-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:160291c60081f23ee43d44b08a7e5fb76681221a8e10b3139618c5a9a291b84e"},
    {file = "propcache-0.2.1-cp311-cp311-win32.whl", hash = "sha256:819ce3b883b7576ca28da3861c7e1a88afd08cc8c96908e08a3f4dd64a228034"},
    {file = "propcache-0.2.1-cp311-cp311-win_amd64.whl", hash = "sha256:edc9fc7051e3350643ad929df55c451899bb9ae6d24998a949d2e4c87fb596d3"},
    {file = "propcache-0.2.1-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:081a430aa8d5e8876c6909b67bd2d937bfd531b0382d3fdedb82612c618bc41a"},
    {file = "propcache-0.2.1-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:d2ccec9ac47cf4e04897619c0e0c1a48c54a71bdf045117d3a26f80d38ab1fb0"},
    {file = "propcache-0.2.1-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:14d86fe14b7e04fa306e0c43cdbeebe6b2c2156a0c9ce56b815faacc193e320d"},
    {file = "propcache-0.2.1-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:049324ee97bb67285b49632132db351b41e77833678432be52bdd0289c0e05e4"},
    {file = "propcache-0.2.1-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:1cd9a1d071158de1cc1c71a26014dcdfa7dd3d5f4f88c298c7f90ad6f27bb46d"},
    {file = "propcache-0.2.1-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:98110aa363f1bb4c073e8dcfaefd3a5cea0f0834c2aab23dda657e4dab2f53b5"},
    {file = "propcache-0.2.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:647894f5ae99c4cf6bb82a1bb3a796f6e06af3caa3d32e26d2350d0e3e3faf24"},
    {file = "propcache-0.2.1-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:bfd3223c15bebe26518d58ccf9a39b93948d3dcb3e57a20480dfdd315356baff"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:d71264a80f3fcf512eb4f18f59423fe82d6e346ee97b90625f283df56aee103f"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_armv7l.whl", hash = "sha256:e73091191e4280403bde6c9a52a6999d69cdfde498f1fdf629105247599b57ec"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:3935bfa5fede35fb202c4b569bb9c042f337ca4ff7bd540a0aa5e37131659348"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:f508b0491767bb1f2b87fdfacaba5f7eddc2f867740ec69ece6d1946d29029a6"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:1672137af7c46662a1c2be1e8dc78cb6d224319aaa40271c9257d886be4363a6"},
    {file = "propcache-0.2.1-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:b74c261802d3d2b85c9df2dfb2fa81b6f90deeef63c2db9f0e029a3cac50b518"},
    {file = "propcache-0.2.1-cp312-cp312-win32.whl", hash = "sha256:d09c333d36c1409d56a9d29b3a1b800a42c76a57a5a8907eacdbce3f18768246"},
    {file = "propcache-0.2.1-cp312-cp312-win_amd64.whl", hash = "sha256:c214999039d4f2a5b2073ac506bba279945233da8c786e490d411dfc30f855c1"},
    {file = "propcache-0.2.1-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:aca405706e0b0a44cc6bfd41fbe89919a6a56999157f6de7e182a990c36e37bc"},
    {file = "propcache-0.2.1-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:12d1083f001ace206fe34b6bdc2cb94be66d57a850866f0b908972f90996b3e9"},
    {file = "propcache-0.2.1-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:d93f3307ad32a27bda2e88ec81134b823c240aa3abb55821a8da553eed8d9439"},
    {file = "propcache-0.2.1-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ba278acf14471d36316159c94a802933d10b6a1e117b8554fe0d0d9b75c9d536"},
    {file = "propcache-0.2.1-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:4e6281aedfca15301c41f74d7005e6e3f4ca143584ba696ac69df4f02f40d629"},
    {file = "propcache-0.2.1-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:5b750a8e5a1262434fb1517ddf64b5de58327f1adc3524a5e44c2ca43305eb0b"},
    {file = "propcache-0.2.1-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bf72af5e0fb40e9babf594308911436c8efde3cb5e75b6f206c34ad18be5c052"},
    {file = "propcache-0.2.1-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:b2d0a12018b04f4cb820781ec0dffb5f7c7c1d2a5cd22bff7fb055a2cb19ebce"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:e800776a79a5aabdb17dcc2346a7d66d0777e942e4cd251defeb084762ecd17d"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_armv7l.whl", hash = "sha256:4160d9283bd382fa6c0c2b5e017acc95bc183570cd70968b9202ad6d8fc48dce"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:30b43e74f1359353341a7adb783c8f1b1c676367b011709f466f42fda2045e95"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:58791550b27d5488b1bb52bc96328456095d96206a250d28d874fafe11b3dfaf"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:0f022d381747f0dfe27e99d928e31bc51a18b65bb9e481ae0af1380a6725dd1f"},
    {file = "propcache-0.2.1-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:297878dc9d0a334358f9b608b56d02e72899f3b8499fc6044133f0d319e2ec30"},
    {file = "propcache-0.2.1-cp313-cp313-win32.whl", hash = "sha256:ddfab44e4489bd79bda09d84c430677fc7f0a4939a73d2bba3073036f487a0a6"},
    {file = "propcache-0.2.1-cp313-cp313-win_amd64.whl", hash = "sha256:556fc6c10989f19a179e4321e5d678db8eb2924131e64652a51fe83e4c3db0e1"},
    {file = "propcache-0.2.1-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:6a9a8c34fb7bb609419a211e59da8887eeca40d300b5ea8e56af98f6fbbb1541"},
    {file = "propcache-0.2.1-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:ae1aa1cd222c6d205853b3013c69cd04515f9d6ab6de4b0603e2e1c33221303e"},
    {file = "propcache-0.2.1-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:accb6150ce61c9c4b7738d45550806aa2b71c7668c6942f17b0ac182b6142fd4"},
    {file = "propcache-0.2.1-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:5eee736daafa7af6d0a2dc15cc75e05c64f37fc37bafef2e00d77c14171c2097"},
    {file = "propcache-0.2.1-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f7a31fc1e1bd362874863fdeed71aed92d348f5336fd84f2197ba40c59f061bd"},
    {file = "propcache-0.2.1-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:cba4cfa1052819d16699e1d55d18c92b6e094d4517c41dd231a8b9f87b6fa681"},
    {file = "propcache-0.2.1-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f089118d584e859c62b3da0892b88a83d611c2033ac410e929cb6754eec0ed16"},
    {file = "propcache-0.2.1-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:781e65134efaf88feb447e8c97a51772aa75e48b794352f94cb7ea717dedda0d"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:31f5af773530fd3c658b32b6bdc2d0838543de70eb9a2156c03e410f7b0d3aae"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_armv7l.whl", hash = "sha256:a7a078f5d37bee6690959c813977da5291b24286e7b962e62a94cec31aa5188b"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:cea7daf9fc7ae6687cf1e2c049752f19f146fdc37c2cc376e7d0032cf4f25347"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:8b3489ff1ed1e8315674d0775dc7d2195fb13ca17b3808721b54dbe9fd020faf"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:9403db39be1393618dd80c746cb22ccda168efce239c73af13c3763ef56ffc04"},
    {file = "propcache-0.2.1-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:5d97151bc92d2b2578ff7ce779cdb9174337390a535953cbb9452fb65164c587"},
    {file = "propcache-0.2.1-cp39-cp39-win32.whl", hash = "sha256:9caac6b54914bdf41bcc91e7eb9147d331d29235a7c967c150ef5df6464fd1bb"},
    {file = "propcache-0.2.1-cp39-cp39-win_amd64.whl", hash = "sha256:92fc4500fcb33899b05ba73276dfb684a20d31caa567b7cb5252d48f896a91b1"},
    {file = "propcache-0.2.1-py3-none-any.whl", hash = "sha256:52277518d6aae65536e9cea52d4e7fd2f7a66f4aa2d30ed3f2fcea620ace3c54"},
    {file = "propcache-0.2.1.tar.gz", hash = "sha256:3f77ce728b19cb537714499928fe800c3dda29e8d9428778fc7c186da4c09a64"},
]

[[package]]
name = "pyasn1"
version = "0.6.1"
description = "Pure-Python implementation of ASN.1 types and DER/BER/CER codecs (X.208)"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pyasn1-0.6.1-py3-none-any.whl", hash = "sha256:0d632f46f2ba09143da3a8afe9e33fb6f92fa2320ab7e886e2d0f7672af84629"},
    {file = "pyasn1-0.6.1.tar.gz", hash = "sha256:6f580d2bdd84365380830acf45550f2511469f673cb4a5ae3857a3170128b034"},
]

[[package]]
name = "pyasn1-modules"
version = "0.4.1"
description = "A collection of ASN.1-based protocols modules"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pyasn1_modules-0.4.1-py3-none-any.whl", hash = "sha256:49bfa96b45a292b711e986f222502c1c9a5e1f4e568fc30e2574a6c7d07838fd"},
    {file = "pyasn1_modules-0.4.1.tar.gz", hash = "sha256:c28e2dbf9c06ad61c71a075c7e0f9fd0f1b0bb2d2ad4377f240d33ac2ab60a7c"},
]

[package.dependencies]
pyasn1 = ">=0.4.6,<0.7.0"

[[package]]
name = "pydantic"
version = "2.10.4"
description = "Data validation using Python type hints"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pydantic-2.10.4-py3-none-any.whl", hash = "sha256:597e135ea68be3a37552fb524bc7d0d66dcf93d395acd93a00682f1efcb8ee3d"},
    {file = "pydantic-2.10.4.tar.gz", hash = "sha256:82f12e9723da6de4fe2ba888b5971157b3be7ad914267dea8f05f82b28254f06"},
]

[package.dependencies]
annotated-types = ">=0.6.0"
pydantic-core = "2.27.2"
typing-extensions = ">=4.12.2"

[package.extras]
email = ["email-validator (>=2.0.0)"]
timezone = ["tzdata"]

[[package]]
name = "pydantic-core"
version = "2.27.2"
description = "Core functionality for Pydantic validation and serialization"
optional = false
python-versions = ">=3.8"
files = [
    {file = "pydantic_core-2.27.2-cp310-cp310-macosx_10_12_x86_64.whl", hash = "sha256:2d367ca20b2f14095a8f4fa1210f5a7b78b8a20009ecced6b12818f455b1e9fa"},
    {file = "pydantic_core-2.27.2-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:491a2b73db93fab69731eaee494f320faa4e093dbed776be1a829c2eb222c34c"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:7969e133a6f183be60e9f6f56bfae753585680f3b7307a8e555a948d443cc05a"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:3de9961f2a346257caf0aa508a4da705467f53778e9ef6fe744c038119737ef5"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:e2bb4d3e5873c37bb3dd58714d4cd0b0e6238cebc4177ac8fe878f8b3aa8e74c"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:280d219beebb0752699480fe8f1dc61ab6615c2046d76b7ab7ee38858de0a4e7"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:47956ae78b6422cbd46f772f1746799cbb862de838fd8d1fbd34a82e05b0983a"},
    {file = "pydantic_core-2.27.2-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:14d4a5c49d2f009d62a2a7140d3064f686d17a5d1a268bc641954ba181880236"},
    {file = "pydantic_core-2.27.2-cp310-cp310-musllinux_1_1_aarch64.whl", hash = "sha256:337b443af21d488716f8d0b6164de833e788aa6bd7e3a39c005febc1284f4962"},
    {file = "pydantic_core-2.27.2-cp310-cp310-musllinux_1_1_armv7l.whl", hash = "sha256:03d0f86ea3184a12f41a2d23f7ccb79cdb5a18e06993f8a45baa8dfec746f0e9"},
    {file = "pydantic_core-2.27.2-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:7041c36f5680c6e0f08d922aed302e98b3745d97fe1589db0a3eebf6624523af"},
    {file = "pydantic_core-2.27.2-cp310-cp310-win32.whl", hash = "sha256:50a68f3e3819077be2c98110c1f9dcb3817e93f267ba80a2c05bb4f8799e2ff4"},
    {file = "pydantic_core-2.27.2-cp310-cp310-win_amd64.whl", hash = "sha256:e0fd26b16394ead34a424eecf8a31a1f5137094cabe84a1bcb10fa6ba39d3d31"},
    {file = "pydantic_core-2.27.2-cp311-cp311-macosx_10_12_x86_64.whl", hash = "sha256:8e10c99ef58cfdf2a66fc15d66b16c4a04f62bca39db589ae8cba08bc55331bc"},
    {file = "pydantic_core-2.27.2-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:26f32e0adf166a84d0cb63be85c562ca8a6fa8de28e5f0d92250c6b7e9e2aff7"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:8c19d1ea0673cd13cc2f872f6c9ab42acc4e4f492a7ca9d3795ce2b112dd7e15"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:5e68c4446fe0810e959cdff46ab0a41ce2f2c86d227d96dc3847af0ba7def306"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d9640b0059ff4f14d1f37321b94061c6db164fbe49b334b31643e0528d100d99"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:40d02e7d45c9f8af700f3452f329ead92da4c5f4317ca9b896de7ce7199ea459"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:1c1fd185014191700554795c99b347d64f2bb637966c4cfc16998a0ca700d048"},
    {file = "pydantic_core-2.27.2-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:d81d2068e1c1228a565af076598f9e7451712700b673de8f502f0334f281387d"},
    {file = "pydantic_core-2.27.2-cp311-cp311-musllinux_1_1_aarch64.whl", hash = "sha256:1a4207639fb02ec2dbb76227d7c751a20b1a6b4bc52850568e52260cae64ca3b"},
    {file = "pydantic_core-2.27.2-cp311-cp311-musllinux_1_1_armv7l.whl", hash = "sha256:3de3ce3c9ddc8bbd88f6e0e304dea0e66d843ec9de1b0042b0911c1663ffd474"},
    {file = "pydantic_core-2.27.2-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:30c5f68ded0c36466acede341551106821043e9afaad516adfb6e8fa80a4e6a6"},
    {file = "pydantic_core-2.27.2-cp311-cp311-win32.whl", hash = "sha256:c70c26d2c99f78b125a3459f8afe1aed4d9687c24fd677c6a4436bc042e50d6c"},
    {file = "pydantic_core-2.27.2-cp311-cp311-win_amd64.whl", hash = "sha256:08e125dbdc505fa69ca7d9c499639ab6407cfa909214d500897d02afb816e7cc"},
    {file = "pydantic_core-2.27.2-cp311-cp311-win_arm64.whl", hash = "sha256:26f0d68d4b235a2bae0c3fc585c585b4ecc51382db0e3ba402a22cbc440915e4"},
    {file = "pydantic_core-2.27.2-cp312-cp312-macosx_10_12_x86_64.whl", hash = "sha256:9e0c8cfefa0ef83b4da9588448b6d8d2a2bf1a53c3f1ae5fca39eb3061e2f0b0"},
    {file = "pydantic_core-2.27.2-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:83097677b8e3bd7eaa6775720ec8e0405f1575015a463285a92bfdfe254529ef"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:172fce187655fece0c90d90a678424b013f8fbb0ca8b036ac266749c09438cb7"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:519f29f5213271eeeeb3093f662ba2fd512b91c5f188f3bb7b27bc5973816934"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:05e3a55d124407fffba0dd6b0c0cd056d10e983ceb4e5dbd10dda135c31071d6"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:9c3ed807c7b91de05e63930188f19e921d1fe90de6b4f5cd43ee7fcc3525cb8c"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6fb4aadc0b9a0c063206846d603b92030eb6f03069151a625667f982887153e2"},
    {file = "pydantic_core-2.27.2-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:28ccb213807e037460326424ceb8b5245acb88f32f3d2777427476e1b32c48c4"},
    {file = "pydantic_core-2.27.2-cp312-cp312-musllinux_1_1_aarch64.whl", hash = "sha256:de3cd1899e2c279b140adde9357c4495ed9d47131b4a4eaff9052f23398076b3"},
    {file = "pydantic_core-2.27.2-cp312-cp312-musllinux_1_1_armv7l.whl", hash = "sha256:220f892729375e2d736b97d0e51466252ad84c51857d4d15f5e9692f9ef12be4"},
    {file = "pydantic_core-2.27.2-cp312-cp312-musllinux_1_1_x86_64.whl", hash = "sha256:a0fcd29cd6b4e74fe8ddd2c90330fd8edf2e30cb52acda47f06dd615ae72da57"},
    {file = "pydantic_core-2.27.2-cp312-cp312-win32.whl", hash = "sha256:1e2cb691ed9834cd6a8be61228471d0a503731abfb42f82458ff27be7b2186fc"},
    {file = "pydantic_core-2.27.2-cp312-cp312-win_amd64.whl", hash = "sha256:cc3f1a99a4f4f9dd1de4fe0312c114e740b5ddead65bb4102884b384c15d8bc9"},
    {file = "pydantic_core-2.27.2-cp312-cp312-win_arm64.whl", hash = "sha256:3911ac9284cd8a1792d3cb26a2da18f3ca26c6908cc434a18f730dc0db7bfa3b"},
    {file = "pydantic_core-2.27.2-cp313-cp313-macosx_10_12_x86_64.whl", hash = "sha256:7d14bd329640e63852364c306f4d23eb744e0f8193148d4044dd3dacdaacbd8b"},
    {file = "pydantic_core-2.27.2-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:82f91663004eb8ed30ff478d77c4d1179b3563df6cdb15c0817cd1cdaf34d154"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:71b24c7d61131bb83df10cc7e687433609963a944ccf45190cfc21e0887b08c9"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:fa8e459d4954f608fa26116118bb67f56b93b209c39b008277ace29937453dc9"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:ce8918cbebc8da707ba805b7fd0b382816858728ae7fe19a942080c24e5b7cd1"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:eda3f5c2a021bbc5d976107bb302e0131351c2ba54343f8a496dc8783d3d3a6a"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bd8086fa684c4775c27f03f062cbb9eaa6e17f064307e86b21b9e0abc9c0f02e"},
    {file = "pydantic_core-2.27.2-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:8d9b3388db186ba0c099a6d20f0604a44eabdeef1777ddd94786cdae158729e4"},
    {file = "pydantic_core-2.27.2-cp313-cp313-musllinux_1_1_aarch64.whl", hash = "sha256:7a66efda2387de898c8f38c0cf7f14fca0b51a8ef0b24bfea5849f1b3c95af27"},
    {file = "pydantic_core-2.27.2-cp313-cp313-musllinux_1_1_armv7l.whl", hash = "sha256:18a101c168e4e092ab40dbc2503bdc0f62010e95d292b27827871dc85450d7ee"},
    {file = "pydantic_core-2.27.2-cp313-cp313-musllinux_1_1_x86_64.whl", hash = "sha256:ba5dd002f88b78a4215ed2f8ddbdf85e8513382820ba15ad5ad8955ce0ca19a1"},
    {file = "pydantic_core-2.27.2-cp313-cp313-win32.whl", hash = "sha256:1ebaf1d0481914d004a573394f4be3a7616334be70261007e47c2a6fe7e50130"},
    {file = "pydantic_core-2.27.2-cp313-cp313-win_amd64.whl", hash = "sha256:953101387ecf2f5652883208769a79e48db18c6df442568a0b5ccd8c2723abee"},
    {file = "pydantic_core-2.27.2-cp313-cp313-win_arm64.whl", hash = "sha256:ac4dbfd1691affb8f48c2c13241a2e3b60ff23247cbcf981759c768b6633cf8b"},
    {file = "pydantic_core-2.27.2-cp38-cp38-macosx_10_12_x86_64.whl", hash = "sha256:d3e8d504bdd3f10835468f29008d72fc8359d95c9c415ce6e767203db6127506"},
    {file = "pydantic_core-2.27.2-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:521eb9b7f036c9b6187f0b47318ab0d7ca14bd87f776240b90b21c1f4f149320"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:85210c4d99a0114f5a9481b44560d7d1e35e32cc5634c656bc48e590b669b145"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:d716e2e30c6f140d7560ef1538953a5cd1a87264c737643d481f2779fc247fe1"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f66d89ba397d92f840f8654756196d93804278457b5fbede59598a1f9f90b228"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:669e193c1c576a58f132e3158f9dfa9662969edb1a250c54d8fa52590045f046"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9fdbe7629b996647b99c01b37f11170a57ae675375b14b8c13b8518b8320ced5"},
    {file = "pydantic_core-2.27.2-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:d262606bf386a5ba0b0af3b97f37c83d7011439e3dc1a9298f21efb292e42f1a"},
    {file = "pydantic_core-2.27.2-cp38-cp38-musllinux_1_1_aarch64.whl", hash = "sha256:cabb9bcb7e0d97f74df8646f34fc76fbf793b7f6dc2438517d7a9e50eee4f14d"},
    {file = "pydantic_core-2.27.2-cp38-cp38-musllinux_1_1_armv7l.whl", hash = "sha256:d2d63f1215638d28221f664596b1ccb3944f6e25dd18cd3b86b0a4c408d5ebb9"},
    {file = "pydantic_core-2.27.2-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:bca101c00bff0adb45a833f8451b9105d9df18accb8743b08107d7ada14bd7da"},
    {file = "pydantic_core-2.27.2-cp38-cp38-win32.whl", hash = "sha256:f6f8e111843bbb0dee4cb6594cdc73e79b3329b526037ec242a3e49012495b3b"},
    {file = "pydantic_core-2.27.2-cp38-cp38-win_amd64.whl", hash = "sha256:fd1aea04935a508f62e0d0ef1f5ae968774a32afc306fb8545e06f5ff5cdf3ad"},
    {file = "pydantic_core-2.27.2-cp39-cp39-macosx_10_12_x86_64.whl", hash = "sha256:c10eb4f1659290b523af58fa7cffb452a61ad6ae5613404519aee4bfbf1df993"},
    {file = "pydantic_core-2.27.2-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:ef592d4bad47296fb11f96cd7dc898b92e795032b4894dfb4076cfccd43a9308"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:c61709a844acc6bf0b7dce7daae75195a10aac96a596ea1b776996414791ede4"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:42c5f762659e47fdb7b16956c71598292f60a03aa92f8b6351504359dbdba6cf"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:4c9775e339e42e79ec99c441d9730fccf07414af63eac2f0e48e08fd38a64d76"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:57762139821c31847cfb2df63c12f725788bd9f04bc2fb392790959b8f70f118"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:0d1e85068e818c73e048fe28cfc769040bb1f475524f4745a5dc621f75ac7630"},
    {file = "pydantic_core-2.27.2-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:097830ed52fd9e427942ff3b9bc17fab52913b2f50f2880dc4a5611446606a54"},
    {file = "pydantic_core-2.27.2-cp39-cp39-musllinux_1_1_aarch64.whl", hash = "sha256:044a50963a614ecfae59bb1eaf7ea7efc4bc62f49ed594e18fa1e5d953c40e9f"},
    {file = "pydantic_core-2.27.2-cp39-cp39-musllinux_1_1_armv7l.whl", hash = "sha256:4e0b4220ba5b40d727c7f879eac379b822eee5d8fff418e9d3381ee45b3b0362"},
    {file = "pydantic_core-2.27.2-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:5e4f4bb20d75e9325cc9696c6802657b58bc1dbbe3022f32cc2b2b632c3fbb96"},
    {file = "pydantic_core-2.27.2-cp39-cp39-win32.whl", hash = "sha256:cca63613e90d001b9f2f9a9ceb276c308bfa2a43fafb75c8031c4f66039e8c6e"},
    {file = "pydantic_core-2.27.2-cp39-cp39-win_amd64.whl", hash = "sha256:77d1bca19b0f7021b3a982e6f903dcd5b2b06076def36a652e3907f596e29f67"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-macosx_10_12_x86_64.whl", hash = "sha256:2bf14caea37e91198329b828eae1618c068dfb8ef17bb33287a7ad4b61ac314e"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-macosx_11_0_arm64.whl", hash = "sha256:b0cb791f5b45307caae8810c2023a184c74605ec3bcbb67d13846c28ff731ff8"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:688d3fd9fcb71f41c4c015c023d12a79d1c4c0732ec9eb35d96e3388a120dcf3"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3d591580c34f4d731592f0e9fe40f9cc1b430d297eecc70b962e93c5c668f15f"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:82f986faf4e644ffc189a7f1aafc86e46ef70372bb153e7001e8afccc6e54133"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:bec317a27290e2537f922639cafd54990551725fc844249e64c523301d0822fc"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-musllinux_1_1_armv7l.whl", hash = "sha256:0296abcb83a797db256b773f45773da397da75a08f5fcaef41f2044adec05f50"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:0d75070718e369e452075a6017fbf187f788e17ed67a3abd47fa934d001863d9"},
    {file = "pydantic_core-2.27.2-pp310-pypy310_pp73-win_amd64.whl", hash = "sha256:7e17b560be3c98a8e3aa66ce828bdebb9e9ac6ad5466fba92eb74c4c95cb1151"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-macosx_10_12_x86_64.whl", hash = "sha256:c33939a82924da9ed65dab5a65d427205a73181d8098e79b6b426bdf8ad4e656"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-macosx_11_0_arm64.whl", hash = "sha256:00bad2484fa6bda1e216e7345a798bd37c68fb2d97558edd584942aa41b7d278"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:c817e2b40aba42bac6f457498dacabc568c3b7a986fc9ba7c8d9d260b71485fb"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:251136cdad0cb722e93732cb45ca5299fb56e1344a833640bf93b2803f8d1bfd"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:d2088237af596f0a524d3afc39ab3b036e8adb054ee57cbb1dcf8e09da5b29cc"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:d4041c0b966a84b4ae7a09832eb691a35aec90910cd2dbe7a208de59be77965b"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-musllinux_1_1_armv7l.whl", hash = "sha256:8083d4e875ebe0b864ffef72a4304827015cff328a1be6e22cc850753bfb122b"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:f141ee28a0ad2123b6611b6ceff018039df17f32ada8b534e6aa039545a3efb2"},
    {file = "pydantic_core-2.27.2-pp39-pypy39_pp73-win_amd64.whl", hash = "sha256:7d0c8399fcc1848491f00e0314bd59fb34a9c008761bcb422a057670c3f65e35"},
    {file = "pydantic_core-2.27.2.tar.gz", hash = "sha256:eb026e5a4c1fee05726072337ff51d1efb6f59090b7da90d30ea58625b1ffb39"},
]

[package.dependencies]
typing-extensions = ">=4.6.0,<4.7.0 || >4.7.0"

[[package]]
name = "pyright"
version = "1.1.391"
description = "Command line wrapper for pyright"
optional = false
python-versions = ">=3.7"
files = [
    {file = "pyright-1.1.391-py3-none-any.whl", hash = "sha256:54fa186f8b3e8a55a44ebfa842636635688670c6896dcf6cf4a7fc75062f4d15"},
    {file = "pyright-1.1.391.tar.gz", hash = "sha256:66b2d42cdf5c3cbab05f2f4b76e8bec8aa78e679bfa0b6ad7b923d9e027cadb2"},
]

[package.dependencies]
nodeenv = ">=1.6.0"
typing-extensions = ">=4.1"

[package.extras]
all = ["nodejs-wheel-binaries", "twine (>=3.4.1)"]
dev = ["twine (>=3.4.1)"]
nodejs = ["nodejs-wheel-binaries"]

[[package]]
name = "pytest"
version = "7.4.4"
description = "pytest: simple powerful testing with Python"
optional = false
python-versions = ">=3.7"
files = [
    {file = "pytest-7.4.4-py3-none-any.whl", hash = "sha256:b090cdf5ed60bf4c45261be03239c2c1c22df034fbffe691abe93cd80cea01d8"},
    {file = "pytest-7.4.4.tar.gz", hash = "sha256:2cf0005922c6ace4a3e2ec8b4080eb0d9753fdc93107415332f50ce9e7994280"},
]

[package.dependencies]
colorama = {version = "*", markers = "sys_platform == \"win32\""}
exceptiongroup = {version = ">=1.0.0rc8", markers = "python_version < \"3.11\""}
iniconfig = "*"
packaging = "*"
pluggy = ">=0.12,<2.0"
tomli = {version = ">=1.0.0", markers = "python_version < \"3.11\""}

[package.extras]
testing = ["argcomplete", "attrs (>=19.2.0)", "hypothesis (>=3.56)", "mock", "nose", "pygments (>=2.7.2)", "requests", "setuptools", "xmlschema"]

[[package]]
name = "python-dotenv"
version = "1.0.1"
description = "Read key-value pairs from a .env file and set them as environment variables"
optional = false
python-versions = ">=3.8"
files = [
    {file = "python-dotenv-1.0.1.tar.gz", hash = "sha256:e324ee90a023d808f1959c46bcbc04446a10ced277783dc6ee09987c37ec10ca"},
    {file = "python_dotenv-1.0.1-py3-none-any.whl", hash = "sha256:f7b63ef50f1b690dddf550d03497b66d609393b40b564ed0d674909a68ebf16a"},
]

[package.extras]
cli = ["click (>=5.0)"]

[[package]]
name = "pyyaml"
version = "6.0.2"
description = "YAML parser and emitter for Python"
optional = false
python-versions = ">=3.8"
files = [
    {file = "PyYAML-6.0.2-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:0a9a2848a5b7feac301353437eb7d5957887edbf81d56e903999a75a3d743086"},
    {file = "PyYAML-6.0.2-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:29717114e51c84ddfba879543fb232a6ed60086602313ca38cce623c1d62cfbf"},
    {file = "PyYAML-6.0.2-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:8824b5a04a04a047e72eea5cec3bc266db09e35de6bdfe34c9436ac5ee27d237"},
    {file = "PyYAML-6.0.2-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:7c36280e6fb8385e520936c3cb3b8042851904eba0e58d277dca80a5cfed590b"},
    {file = "PyYAML-6.0.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ec031d5d2feb36d1d1a24380e4db6d43695f3748343d99434e6f5f9156aaa2ed"},
    {file = "PyYAML-6.0.2-cp310-cp310-musllinux_1_1_aarch64.whl", hash = "sha256:936d68689298c36b53b29f23c6dbb74de12b4ac12ca6cfe0e047bedceea56180"},
    {file = "PyYAML-6.0.2-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:23502f431948090f597378482b4812b0caae32c22213aecf3b55325e049a6c68"},
    {file = "PyYAML-6.0.2-cp310-cp310-win32.whl", hash = "sha256:2e99c6826ffa974fe6e27cdb5ed0021786b03fc98e5ee3c5bfe1fd5015f42b99"},
    {file = "PyYAML-6.0.2-cp310-cp310-win_amd64.whl", hash = "sha256:a4d3091415f010369ae4ed1fc6b79def9416358877534caf6a0fdd2146c87a3e"},
    {file = "PyYAML-6.0.2-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:cc1c1159b3d456576af7a3e4d1ba7e6924cb39de8f67111c735f6fc832082774"},
    {file = "PyYAML-6.0.2-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:1e2120ef853f59c7419231f3bf4e7021f1b936f6ebd222406c3b60212205d2ee"},
    {file = "PyYAML-6.0.2-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:5d225db5a45f21e78dd9358e58a98702a0302f2659a3c6cd320564b75b86f47c"},
    {file = "PyYAML-6.0.2-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:5ac9328ec4831237bec75defaf839f7d4564be1e6b25ac710bd1a96321cc8317"},
    {file = "PyYAML-6.0.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3ad2a3decf9aaba3d29c8f537ac4b243e36bef957511b4766cb0057d32b0be85"},
    {file = "PyYAML-6.0.2-cp311-cp311-musllinux_1_1_aarch64.whl", hash = "sha256:ff3824dc5261f50c9b0dfb3be22b4567a6f938ccce4587b38952d85fd9e9afe4"},
    {file = "PyYAML-6.0.2-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:797b4f722ffa07cc8d62053e4cff1486fa6dc094105d13fea7b1de7d8bf71c9e"},
    {file = "PyYAML-6.0.2-cp311-cp311-win32.whl", hash = "sha256:11d8f3dd2b9c1207dcaf2ee0bbbfd5991f571186ec9cc78427ba5bd32afae4b5"},
    {file = "PyYAML-6.0.2-cp311-cp311-win_amd64.whl", hash = "sha256:e10ce637b18caea04431ce14fabcf5c64a1c61ec9c56b071a4b7ca131ca52d44"},
    {file = "PyYAML-6.0.2-cp312-cp312-macosx_10_9_x86_64.whl", hash = "sha256:c70c95198c015b85feafc136515252a261a84561b7b1d51e3384e0655ddf25ab"},
    {file = "PyYAML-6.0.2-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:ce826d6ef20b1bc864f0a68340c8b3287705cae2f8b4b1d932177dcc76721725"},
    {file = "PyYAML-6.0.2-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:1f71ea527786de97d1a0cc0eacd1defc0985dcf6b3f17bb77dcfc8c34bec4dc5"},
    {file = "PyYAML-6.0.2-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:9b22676e8097e9e22e36d6b7bda33190d0d400f345f23d4065d48f4ca7ae0425"},
    {file = "PyYAML-6.0.2-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:80bab7bfc629882493af4aa31a4cfa43a4c57c83813253626916b8c7ada83476"},
    {file = "PyYAML-6.0.2-cp312-cp312-musllinux_1_1_aarch64.whl", hash = "sha256:0833f8694549e586547b576dcfaba4a6b55b9e96098b36cdc7ebefe667dfed48"},
    {file = "PyYAML-6.0.2-cp312-cp312-musllinux_1_1_x86_64.whl", hash = "sha256:8b9c7197f7cb2738065c481a0461e50ad02f18c78cd75775628afb4d7137fb3b"},
    {file = "PyYAML-6.0.2-cp312-cp312-win32.whl", hash = "sha256:ef6107725bd54b262d6dedcc2af448a266975032bc85ef0172c5f059da6325b4"},
    {file = "PyYAML-6.0.2-cp312-cp312-win_amd64.whl", hash = "sha256:7e7401d0de89a9a855c839bc697c079a4af81cf878373abd7dc625847d25cbd8"},
    {file = "PyYAML-6.0.2-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:efdca5630322a10774e8e98e1af481aad470dd62c3170801852d752aa7a783ba"},
    {file = "PyYAML-6.0.2-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:50187695423ffe49e2deacb8cd10510bc361faac997de9efef88badc3bb9e2d1"},
    {file = "PyYAML-6.0.2-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0ffe8360bab4910ef1b9e87fb812d8bc0a308b0d0eef8c8f44e0254ab3b07133"},
    {file = "PyYAML-6.0.2-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:17e311b6c678207928d649faa7cb0d7b4c26a0ba73d41e99c4fff6b6c3276484"},
    {file = "PyYAML-6.0.2-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:70b189594dbe54f75ab3a1acec5f1e3faa7e8cf2f1e08d9b561cb41b845f69d5"},
    {file = "PyYAML-6.0.2-cp313-cp313-musllinux_1_1_aarch64.whl", hash = "sha256:41e4e3953a79407c794916fa277a82531dd93aad34e29c2a514c2c0c5fe971cc"},
    {file = "PyYAML-6.0.2-cp313-cp313-musllinux_1_1_x86_64.whl", hash = "sha256:68ccc6023a3400877818152ad9a1033e3db8625d899c72eacb5a668902e4d652"},
    {file = "PyYAML-6.0.2-cp313-cp313-win32.whl", hash = "sha256:bc2fa7c6b47d6bc618dd7fb02ef6fdedb1090ec036abab80d4681424b84c1183"},
    {file = "PyYAML-6.0.2-cp313-cp313-win_amd64.whl", hash = "sha256:8388ee1976c416731879ac16da0aff3f63b286ffdd57cdeb95f3f2e085687563"},
    {file = "PyYAML-6.0.2-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:24471b829b3bf607e04e88d79542a9d48bb037c2267d7927a874e6c205ca7e9a"},
    {file = "PyYAML-6.0.2-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:d7fded462629cfa4b685c5416b949ebad6cec74af5e2d42905d41e257e0869f5"},
    {file = "PyYAML-6.0.2-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:d84a1718ee396f54f3a086ea0a66d8e552b2ab2017ef8b420e92edbc841c352d"},
    {file = "PyYAML-6.0.2-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9056c1ecd25795207ad294bcf39f2db3d845767be0ea6e6a34d856f006006083"},
    {file = "PyYAML-6.0.2-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:82d09873e40955485746739bcb8b4586983670466c23382c19cffecbf1fd8706"},
    {file = "PyYAML-6.0.2-cp38-cp38-win32.whl", hash = "sha256:43fa96a3ca0d6b1812e01ced1044a003533c47f6ee8aca31724f78e93ccc089a"},
    {file = "PyYAML-6.0.2-cp38-cp38-win_amd64.whl", hash = "sha256:01179a4a8559ab5de078078f37e5c1a30d76bb88519906844fd7bdea1b7729ff"},
    {file = "PyYAML-6.0.2-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:688ba32a1cffef67fd2e9398a2efebaea461578b0923624778664cc1c914db5d"},
    {file = "PyYAML-6.0.2-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:a8786accb172bd8afb8be14490a16625cbc387036876ab6ba70912730faf8e1f"},
    {file = "PyYAML-6.0.2-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:d8e03406cac8513435335dbab54c0d385e4a49e4945d2909a581c83647ca0290"},
    {file = "PyYAML-6.0.2-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:f753120cb8181e736c57ef7636e83f31b9c0d1722c516f7e86cf15b7aa57ff12"},
    {file = "PyYAML-6.0.2-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3b1fdb9dc17f5a7677423d508ab4f243a726dea51fa5e70992e59a7411c89d19"},
    {file = "PyYAML-6.0.2-cp39-cp39-musllinux_1_1_aarch64.whl", hash = "sha256:0b69e4ce7a131fe56b7e4d770c67429700908fc0752af059838b1cfb41960e4e"},
    {file = "PyYAML-6.0.2-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:a9f8c2e67970f13b16084e04f134610fd1d374bf477b17ec1599185cf611d725"},
    {file = "PyYAML-6.0.2-cp39-cp39-win32.whl", hash = "sha256:6395c297d42274772abc367baaa79683958044e5d3835486c16da75d2a694631"},
    {file = "PyYAML-6.0.2-cp39-cp39-win_amd64.whl", hash = "sha256:39693e1f8320ae4f43943590b49779ffb98acb81f788220ea932a6b6c51004d8"},
    {file = "pyyaml-6.0.2.tar.gz", hash = "sha256:d584d9ec91ad65861cc08d42e834324ef890a082e591037abe114850ff7bbc3e"},
]

[[package]]
name = "requests"
version = "2.32.3"
description = "Python HTTP for Humans."
optional = false
python-versions = ">=3.8"
files = [
    {file = "requests-2.32.3-py3-none-any.whl", hash = "sha256:70761cfe03c773ceb22aa2f671b4757976145175cdfca038c02654d061d6dcc6"},
    {file = "requests-2.32.3.tar.gz", hash = "sha256:55365417734eb18255590a9ff9eb97e9e1da868d4ccd6402399eaf68af20a760"},
]

[package.dependencies]
certifi = ">=2017.4.17"
charset-normalizer = ">=2,<4"
idna = ">=2.5,<4"
urllib3 = ">=1.21.1,<3"

[package.extras]
socks = ["PySocks (>=1.5.6,!=1.5.7)"]
use-chardet-on-py3 = ["chardet (>=3.0.2,<6)"]

[[package]]
name = "rsa"
version = "4.9"
description = "Pure-Python RSA implementation"
optional = false
python-versions = ">=3.6,<4"
files = [
    {file = "rsa-4.9-py3-none-any.whl", hash = "sha256:90260d9058e514786967344d0ef75fa8727eed8a7d2e43ce9f4bcf1b536174f7"},
    {file = "rsa-4.9.tar.gz", hash = "sha256:e38464a49c6c85d7f1351b0126661487a7e0a14a50f1675ec50eb34d4f20ef21"},
]

[package.dependencies]
pyasn1 = ">=0.1.3"

[[package]]
name = "setuptools"
version = "75.6.0"
description = "Easily download, build, install, upgrade, and uninstall Python packages"
optional = false
python-versions = ">=3.9"
files = [
    {file = "setuptools-75.6.0-py3-none-any.whl", hash = "sha256:ce74b49e8f7110f9bf04883b730f4765b774ef3ef28f722cce7c273d253aaf7d"},
    {file = "setuptools-75.6.0.tar.gz", hash = "sha256:8199222558df7c86216af4f84c30e9b34a61d8ba19366cc914424cdbd28252f6"},
]

[package.extras]
check = ["pytest-checkdocs (>=2.4)", "pytest-ruff (>=0.2.1)", "ruff (>=0.7.0)"]
core = ["importlib_metadata (>=6)", "jaraco.collections", "jaraco.functools (>=4)", "jaraco.text (>=3.7)", "more_itertools", "more_itertools (>=8.8)", "packaging", "packaging (>=24.2)", "platformdirs (>=4.2.2)", "tomli (>=2.0.1)", "wheel (>=0.43.0)"]
cover = ["pytest-cov"]
doc = ["furo", "jaraco.packaging (>=9.3)", "jaraco.tidelift (>=1.4)", "pygments-github-lexers (==0.0.5)", "pyproject-hooks (!=1.1)", "rst.linker (>=1.9)", "sphinx (>=3.5)", "sphinx-favicon", "sphinx-inline-tabs", "sphinx-lint", "sphinx-notfound-page (>=1,<2)", "sphinx-reredirects", "sphinxcontrib-towncrier", "towncrier (<24.7)"]
enabler = ["pytest-enabler (>=2.2)"]
test = ["build[virtualenv] (>=1.0.3)", "filelock (>=3.4.0)", "ini2toml[lite] (>=0.14)", "jaraco.develop (>=7.21)", "jaraco.envs (>=2.2)", "jaraco.path (>=3.2.0)", "jaraco.test (>=5.5)", "packaging (>=24.2)", "pip (>=19.1)", "pyproject-hooks (!=1.1)", "pytest (>=6,!=8.1.*)", "pytest-home (>=0.5)", "pytest-perf", "pytest-subprocess", "pytest-timeout", "pytest-xdist (>=3)", "tomli-w (>=1.0.0)", "virtualenv (>=13.0.0)", "wheel (>=0.44.0)"]
type = ["importlib_metadata (>=7.0.2)", "jaraco.develop (>=7.21)", "mypy (>=1.12,<1.14)", "pytest-mypy"]

[[package]]
name = "sniffio"
version = "1.3.1"
description = "Sniff out which async library your code is running under"
optional = false
python-versions = ">=3.7"
files = [
    {file = "sniffio-1.3.1-py3-none-any.whl", hash = "sha256:2f6da418d1f1e0fddd844478f41680e794e6051915791a034ff65e5f100525a2"},
    {file = "sniffio-1.3.1.tar.gz", hash = "sha256:f4324edc670a0f49750a81b895f35c3adb843cca46f0530f79fc1babb23789dc"},
]

[[package]]
name = "soupsieve"
version = "2.6"
description = "A modern CSS selector implementation for Beautiful Soup."
optional = false
python-versions = ">=3.8"
files = [
    {file = "soupsieve-2.6-py3-none-any.whl", hash = "sha256:e72c4ff06e4fb6e4b5a9f0f55fe6e81514581fca1515028625d0f299c602ccc9"},
    {file = "soupsieve-2.6.tar.gz", hash = "sha256:e2e68417777af359ec65daac1057404a3c8a5455bb8abc36f1a9866ab1a51abb"},
]

[[package]]
name = "starlette"
version = "0.41.3"
description = "The little ASGI library that shines."
optional = false
python-versions = ">=3.8"
files = [
    {file = "starlette-0.41.3-py3-none-any.whl", hash = "sha256:44cedb2b7c77a9de33a8b74b2b90e9f50d11fcf25d8270ea525ad71a25374ff7"},
    {file = "starlette-0.41.3.tar.gz", hash = "sha256:0e4ab3d16522a255be6b28260b938eae2482f98ce5cc934cb08dce8dc3ba5835"},
]

[package.dependencies]
anyio = ">=3.4.0,<5"

[package.extras]
full = ["httpx (>=0.22.0)", "itsdangerous", "jinja2", "python-multipart (>=0.0.7)", "pyyaml"]

[[package]]
name = "tokenizers"
version = "0.21.0"
description = ""
optional = false
python-versions = ">=3.7"
files = [
    {file = "tokenizers-0.21.0-cp39-abi3-macosx_10_12_x86_64.whl", hash = "sha256:3c4c93eae637e7d2aaae3d376f06085164e1660f89304c0ab2b1d08a406636b2"},
    {file = "tokenizers-0.21.0-cp39-abi3-macosx_11_0_arm64.whl", hash = "sha256:f53ea537c925422a2e0e92a24cce96f6bc5046bbef24a1652a5edc8ba975f62e"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:6b177fb54c4702ef611de0c069d9169f0004233890e0c4c5bd5508ae05abf193"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:6b43779a269f4629bebb114e19c3fca0223296ae9fea8bb9a7a6c6fb0657ff8e"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:9aeb255802be90acfd363626753fda0064a8df06031012fe7d52fd9a905eb00e"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:d8b09dbeb7a8d73ee204a70f94fc06ea0f17dcf0844f16102b9f414f0b7463ba"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:400832c0904f77ce87c40f1a8a27493071282f785724ae62144324f171377273"},
    {file = "tokenizers-0.21.0-cp39-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e84ca973b3a96894d1707e189c14a774b701596d579ffc7e69debfc036a61a04"},
    {file = "tokenizers-0.21.0-cp39-abi3-musllinux_1_2_aarch64.whl", hash = "sha256:eb7202d231b273c34ec67767378cd04c767e967fda12d4a9e36208a34e2f137e"},
    {file = "tokenizers-0.21.0-cp39-abi3-musllinux_1_2_armv7l.whl", hash = "sha256:089d56db6782a73a27fd8abf3ba21779f5b85d4a9f35e3b493c7bbcbbf0d539b"},
    {file = "tokenizers-0.21.0-cp39-abi3-musllinux_1_2_i686.whl", hash = "sha256:c87ca3dc48b9b1222d984b6b7490355a6fdb411a2d810f6f05977258400ddb74"},
    {file = "tokenizers-0.21.0-cp39-abi3-musllinux_1_2_x86_64.whl", hash = "sha256:4145505a973116f91bc3ac45988a92e618a6f83eb458f49ea0790df94ee243ff"},
    {file = "tokenizers-0.21.0-cp39-abi3-win32.whl", hash = "sha256:eb1702c2f27d25d9dd5b389cc1f2f51813e99f8ca30d9e25348db6585a97e24a"},
    {file = "tokenizers-0.21.0-cp39-abi3-win_amd64.whl", hash = "sha256:87841da5a25a3a5f70c102de371db120f41873b854ba65e52bccd57df5a3780c"},
    {file = "tokenizers-0.21.0.tar.gz", hash = "sha256:ee0894bf311b75b0c03079f33859ae4b2334d675d4e93f5a4132e1eae2834fe4"},
]

[package.dependencies]
huggingface-hub = ">=0.16.4,<1.0"

[package.extras]
dev = ["tokenizers[testing]"]
docs = ["setuptools-rust", "sphinx", "sphinx-rtd-theme"]
testing = ["black (==22.3)", "datasets", "numpy", "pytest", "requests", "ruff"]

[[package]]
name = "tomli"
version = "2.2.1"
description = "A lil' TOML parser"
optional = false
python-versions = ">=3.8"
files = [
    {file = "tomli-2.2.1-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:678e4fa69e4575eb77d103de3df8a895e1591b48e740211bd1067378c69e8249"},
    {file = "tomli-2.2.1-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:023aa114dd824ade0100497eb2318602af309e5a55595f76b626d6d9f3b7b0a6"},
    {file = "tomli-2.2.1-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ece47d672db52ac607a3d9599a9d48dcb2f2f735c6c2d1f34130085bb12b112a"},
    {file = "tomli-2.2.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6972ca9c9cc9f0acaa56a8ca1ff51e7af152a9f87fb64623e31d5c83700080ee"},
    {file = "tomli-2.2.1-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:c954d2250168d28797dd4e3ac5cf812a406cd5a92674ee4c8f123c889786aa8e"},
    {file = "tomli-2.2.1-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:8dd28b3e155b80f4d54beb40a441d366adcfe740969820caf156c019fb5c7ec4"},
    {file = "tomli-2.2.1-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:e59e304978767a54663af13c07b3d1af22ddee3bb2fb0618ca1593e4f593a106"},
    {file = "tomli-2.2.1-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:33580bccab0338d00994d7f16f4c4ec25b776af3ffaac1ed74e0b3fc95e885a8"},
    {file = "tomli-2.2.1-cp311-cp311-win32.whl", hash = "sha256:465af0e0875402f1d226519c9904f37254b3045fc5084697cefb9bdde1ff99ff"},
    {file = "tomli-2.2.1-cp311-cp311-win_amd64.whl", hash = "sha256:2d0f2fdd22b02c6d81637a3c95f8cd77f995846af7414c5c4b8d0545afa1bc4b"},
    {file = "tomli-2.2.1-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:4a8f6e44de52d5e6c657c9fe83b562f5f4256d8ebbfe4ff922c495620a7f6cea"},
    {file = "tomli-2.2.1-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:8d57ca8095a641b8237d5b079147646153d22552f1c637fd3ba7f4b0b29167a8"},
    {file = "tomli-2.2.1-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:4e340144ad7ae1533cb897d406382b4b6fede8890a03738ff1683af800d54192"},
    {file = "tomli-2.2.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:db2b95f9de79181805df90bedc5a5ab4c165e6ec3fe99f970d0e302f384ad222"},
    {file = "tomli-2.2.1-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:40741994320b232529c802f8bc86da4e1aa9f413db394617b9a256ae0f9a7f77"},
    {file = "tomli-2.2.1-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:400e720fe168c0f8521520190686ef8ef033fb19fc493da09779e592861b78c6"},
    {file = "tomli-2.2.1-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:02abe224de6ae62c19f090f68da4e27b10af2b93213d36cf44e6e1c5abd19fdd"},
    {file = "tomli-2.2.1-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:b82ebccc8c8a36f2094e969560a1b836758481f3dc360ce9a3277c65f374285e"},
    {file = "tomli-2.2.1-cp312-cp312-win32.whl", hash = "sha256:889f80ef92701b9dbb224e49ec87c645ce5df3fa2cc548664eb8a25e03127a98"},
    {file = "tomli-2.2.1-cp312-cp312-win_amd64.whl", hash = "sha256:7fc04e92e1d624a4a63c76474610238576942d6b8950a2d7f908a340494e67e4"},
    {file = "tomli-2.2.1-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:f4039b9cbc3048b2416cc57ab3bda989a6fcf9b36cf8937f01a6e731b64f80d7"},
    {file = "tomli-2.2.1-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:286f0ca2ffeeb5b9bd4fcc8d6c330534323ec51b2f52da063b11c502da16f30c"},
    {file = "tomli-2.2.1-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:a92ef1a44547e894e2a17d24e7557a5e85a9e1d0048b0b5e7541f76c5032cb13"},
    {file = "tomli-2.2.1-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9316dc65bed1684c9a98ee68759ceaed29d229e985297003e494aa825ebb0281"},
    {file = "tomli-2.2.1-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e85e99945e688e32d5a35c1ff38ed0b3f41f43fad8df0bdf79f72b2ba7bc5272"},
    {file = "tomli-2.2.1-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:ac065718db92ca818f8d6141b5f66369833d4a80a9d74435a268c52bdfa73140"},
    {file = "tomli-2.2.1-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:d920f33822747519673ee656a4b6ac33e382eca9d331c87770faa3eef562aeb2"},
    {file = "tomli-2.2.1-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:a198f10c4d1b1375d7687bc25294306e551bf1abfa4eace6650070a5c1ae2744"},
    {file = "tomli-2.2.1-cp313-cp313-win32.whl", hash = "sha256:d3f5614314d758649ab2ab3a62d4f2004c825922f9e370b29416484086b264ec"},
    {file = "tomli-2.2.1-cp313-cp313-win_amd64.whl", hash = "sha256:a38aa0308e754b0e3c67e344754dff64999ff9b513e691d0e786265c93583c69"},
    {file = "tomli-2.2.1-py3-none-any.whl", hash = "sha256:cb55c73c5f4408779d0cf3eef9f762b9c9f147a77de7b258bef0a5628adc85cc"},
    {file = "tomli-2.2.1.tar.gz", hash = "sha256:cd45e1dc79c835ce60f7404ec8119f2eb06d38b1deba146f07ced3bbc44505ff"},
]

[[package]]
name = "tqdm"
version = "4.67.1"
description = "Fast, Extensible Progress Meter"
optional = false
python-versions = ">=3.7"
files = [
    {file = "tqdm-4.67.1-py3-none-any.whl", hash = "sha256:26445eca388f82e72884e0d580d5464cd801a3ea01e63e5601bdff9ba6a48de2"},
    {file = "tqdm-4.67.1.tar.gz", hash = "sha256:f8aef9c52c08c13a65f30ea34f4e5aac3fd1a34959879d7e59e63027286627f2"},
]

[package.dependencies]
colorama = {version = "*", markers = "platform_system == \"Windows\""}

[package.extras]
dev = ["nbval", "pytest (>=6)", "pytest-asyncio (>=0.24)", "pytest-cov", "pytest-timeout"]
discord = ["requests"]
notebook = ["ipywidgets (>=6)"]
slack = ["slack-sdk"]
telegram = ["requests"]

[[package]]
name = "types-pillow"
version = "10.2.0.20240822"
description = "Typing stubs for Pillow"
optional = false
python-versions = ">=3.8"
files = [
    {file = "types-Pillow-10.2.0.20240822.tar.gz", hash = "sha256:559fb52a2ef991c326e4a0d20accb3bb63a7ba8d40eb493e0ecb0310ba52f0d3"},
    {file = "types_Pillow-10.2.0.20240822-py3-none-any.whl", hash = "sha256:d9dab025aba07aeb12fd50a6799d4eac52a9603488eca09d7662543983f16c5d"},
]

[[package]]
name = "typing-extensions"
version = "4.12.2"
description = "Backported and Experimental Type Hints for Python 3.8+"
optional = false
python-versions = ">=3.8"
files = [
    {file = "typing_extensions-4.12.2-py3-none-any.whl", hash = "sha256:04e5ca0351e0f3f85c6853954072df659d0d13fac324d0072316b67d7794700d"},
    {file = "typing_extensions-4.12.2.tar.gz", hash = "sha256:1a7ead55c7e559dd4dee8856e3a88b41225abfe1ce8df57b7c13915fe121ffb8"},
]

[[package]]
name = "urllib3"
version = "2.2.3"
description = "HTTP library with thread-safe connection pooling, file post, and more."
optional = false
python-versions = ">=3.8"
files = [
    {file = "urllib3-2.2.3-py3-none-any.whl", hash = "sha256:ca899ca043dcb1bafa3e262d73aa25c465bfb49e0bd9dd5d59f1d0acba2f8fac"},
    {file = "urllib3-2.2.3.tar.gz", hash = "sha256:e7d814a81dad81e6caf2ec9fdedb284ecc9c73076b62654547cc64ccdcae26e9"},
]

[package.extras]
brotli = ["brotli (>=1.0.9)", "brotlicffi (>=0.8.0)"]
h2 = ["h2 (>=4,<5)"]
socks = ["pysocks (>=1.5.6,!=1.5.7,<2.0)"]
zstd = ["zstandard (>=0.18.0)"]

[[package]]
name = "uvicorn"
version = "0.25.0"
description = "The lightning-fast ASGI server."
optional = false
python-versions = ">=3.8"
files = [
    {file = "uvicorn-0.25.0-py3-none-any.whl", hash = "sha256:ce107f5d9bd02b4636001a77a4e74aab5e1e2b146868ebbad565237145af444c"},
    {file = "uvicorn-0.25.0.tar.gz", hash = "sha256:6dddbad1d7ee0f5140aba5ec138ddc9612c5109399903828b4874c9937f009c2"},
]

[package.dependencies]
click = ">=7.0"
h11 = ">=0.8"
typing-extensions = {version = ">=4.0", markers = "python_version < \"3.11\""}

[package.extras]
standard = ["colorama (>=0.4)", "httptools (>=0.5.0)", "python-dotenv (>=0.13)", "pyyaml (>=5.1)", "uvloop (>=0.14.0,!=0.15.0,!=0.15.1)", "watchfiles (>=0.13)", "websockets (>=10.4)"]

[[package]]
name = "virtualenv"
version = "20.28.0"
description = "Virtual Python Environment builder"
optional = false
python-versions = ">=3.8"
files = [
    {file = "virtualenv-20.28.0-py3-none-any.whl", hash = "sha256:23eae1b4516ecd610481eda647f3a7c09aea295055337331bb4e6892ecce47b0"},
    {file = "virtualenv-20.28.0.tar.gz", hash = "sha256:2c9c3262bb8e7b87ea801d715fae4495e6032450c71d2309be9550e7364049aa"},
]

[package.dependencies]
distlib = ">=0.3.7,<1"
filelock = ">=3.12.2,<4"
platformdirs = ">=3.9.1,<5"

[package.extras]
docs = ["furo (>=2023.7.26)", "proselint (>=0.13)", "sphinx (>=7.1.2,!=7.3)", "sphinx-argparse (>=0.4)", "sphinxcontrib-towncrier (>=0.2.1a0)", "towncrier (>=23.6)"]
test = ["covdefaults (>=2.3)", "coverage (>=7.2.7)", "coverage-enable-subprocess (>=1)", "flaky (>=3.7)", "packaging (>=23.1)", "pytest (>=7.4)", "pytest-env (>=0.8.2)", "pytest-freezer (>=0.4.8)", "pytest-mock (>=3.11.1)", "pytest-randomly (>=3.12)", "pytest-timeout (>=2.1)", "setuptools (>=68)", "time-machine (>=2.10)"]

[[package]]
name = "websockets"
version = "14.1"
description = "An implementation of the WebSocket Protocol (RFC 6455 & 7692)"
optional = false
python-versions = ">=3.9"
files = [
    {file = "websockets-14.1-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:a0adf84bc2e7c86e8a202537b4fd50e6f7f0e4a6b6bf64d7ccb96c4cd3330b29"},
    {file = "websockets-14.1-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:90b5d9dfbb6d07a84ed3e696012610b6da074d97453bd01e0e30744b472c8179"},
    {file = "websockets-14.1-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:2177ee3901075167f01c5e335a6685e71b162a54a89a56001f1c3e9e3d2ad250"},
    {file = "websockets-14.1-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:3f14a96a0034a27f9d47fd9788913924c89612225878f8078bb9d55f859272b0"},
    {file = "websockets-14.1-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:1f874ba705deea77bcf64a9da42c1f5fc2466d8f14daf410bc7d4ceae0a9fcb0"},
    {file = "websockets-14.1-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9607b9a442392e690a57909c362811184ea429585a71061cd5d3c2b98065c199"},
    {file = "websockets-14.1-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:bea45f19b7ca000380fbd4e02552be86343080120d074b87f25593ce1700ad58"},
    {file = "websockets-14.1-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:219c8187b3ceeadbf2afcf0f25a4918d02da7b944d703b97d12fb01510869078"},
    {file = "websockets-14.1-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:ad2ab2547761d79926effe63de21479dfaf29834c50f98c4bf5b5480b5838434"},
    {file = "websockets-14.1-cp310-cp310-win32.whl", hash = "sha256:1288369a6a84e81b90da5dbed48610cd7e5d60af62df9851ed1d1d23a9069f10"},
    {file = "websockets-14.1-cp310-cp310-win_amd64.whl", hash = "sha256:e0744623852f1497d825a49a99bfbec9bea4f3f946df6eb9d8a2f0c37a2fec2e"},
    {file = "websockets-14.1-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:449d77d636f8d9c17952628cc7e3b8faf6e92a17ec581ec0c0256300717e1512"},
    {file = "websockets-14.1-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:a35f704be14768cea9790d921c2c1cc4fc52700410b1c10948511039be824aac"},
    {file = "websockets-14.1-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:b1f3628a0510bd58968c0f60447e7a692933589b791a6b572fcef374053ca280"},
    {file = "websockets-14.1-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:3c3deac3748ec73ef24fc7be0b68220d14d47d6647d2f85b2771cb35ea847aa1"},
    {file = "websockets-14.1-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:7048eb4415d46368ef29d32133134c513f507fff7d953c18c91104738a68c3b3"},
    {file = "websockets-14.1-cp311-cp311-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f6cf0ad281c979306a6a34242b371e90e891bce504509fb6bb5246bbbf31e7b6"},
    {file = "websockets-14.1-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:cc1fc87428c1d18b643479caa7b15db7d544652e5bf610513d4a3478dbe823d0"},
    {file = "websockets-14.1-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:f95ba34d71e2fa0c5d225bde3b3bdb152e957150100e75c86bc7f3964c450d89"},
    {file = "websockets-14.1-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:9481a6de29105d73cf4515f2bef8eb71e17ac184c19d0b9918a3701c6c9c4f23"},
    {file = "websockets-14.1-cp311-cp311-win32.whl", hash = "sha256:368a05465f49c5949e27afd6fbe0a77ce53082185bbb2ac096a3a8afaf4de52e"},
    {file = "websockets-14.1-cp311-cp311-win_amd64.whl", hash = "sha256:6d24fc337fc055c9e83414c94e1ee0dee902a486d19d2a7f0929e49d7d604b09"},
    {file = "websockets-14.1-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:ed907449fe5e021933e46a3e65d651f641975a768d0649fee59f10c2985529ed"},
    {file = "websockets-14.1-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:87e31011b5c14a33b29f17eb48932e63e1dcd3fa31d72209848652310d3d1f0d"},
    {file = "websockets-14.1-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:bc6ccf7d54c02ae47a48ddf9414c54d48af9c01076a2e1023e3b486b6e72c707"},
    {file = "websockets-14.1-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:9777564c0a72a1d457f0848977a1cbe15cfa75fa2f67ce267441e465717dcf1a"},
    {file = "websockets-14.1-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:a655bde548ca98f55b43711b0ceefd2a88a71af6350b0c168aa77562104f3f45"},
    {file = "websockets-14.1-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a3dfff83ca578cada2d19e665e9c8368e1598d4e787422a460ec70e531dbdd58"},
    {file = "websockets-14.1-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:6a6c9bcf7cdc0fd41cc7b7944447982e8acfd9f0d560ea6d6845428ed0562058"},
    {file = "websockets-14.1-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:4b6caec8576e760f2c7dd878ba817653144d5f369200b6ddf9771d64385b84d4"},
    {file = "websockets-14.1-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:eb6d38971c800ff02e4a6afd791bbe3b923a9a57ca9aeab7314c21c84bf9ff05"},
    {file = "websockets-14.1-cp312-cp312-win32.whl", hash = "sha256:1d045cbe1358d76b24d5e20e7b1878efe578d9897a25c24e6006eef788c0fdf0"},
    {file = "websockets-14.1-cp312-cp312-win_amd64.whl", hash = "sha256:90f4c7a069c733d95c308380aae314f2cb45bd8a904fb03eb36d1a4983a4993f"},
    {file = "websockets-14.1-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:3630b670d5057cd9e08b9c4dab6493670e8e762a24c2c94ef312783870736ab9"},
    {file = "websockets-14.1-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:36ebd71db3b89e1f7b1a5deaa341a654852c3518ea7a8ddfdf69cc66acc2db1b"},
    {file = "websockets-14.1-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:5b918d288958dc3fa1c5a0b9aa3256cb2b2b84c54407f4813c45d52267600cd3"},
    {file = "websockets-14.1-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:00fe5da3f037041da1ee0cf8e308374e236883f9842c7c465aa65098b1c9af59"},
    {file = "websockets-14.1-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:8149a0f5a72ca36720981418eeffeb5c2729ea55fa179091c81a0910a114a5d2"},
    {file = "websockets-14.1-cp313-cp313-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:77569d19a13015e840b81550922056acabc25e3f52782625bc6843cfa034e1da"},
    {file = "websockets-14.1-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:cf5201a04550136ef870aa60ad3d29d2a59e452a7f96b94193bee6d73b8ad9a9"},
    {file = "websockets-14.1-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:88cf9163ef674b5be5736a584c999e98daf3aabac6e536e43286eb74c126b9c7"},
    {file = "websockets-14.1-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:836bef7ae338a072e9d1863502026f01b14027250a4545672673057997d5c05a"},
    {file = "websockets-14.1-cp313-cp313-win32.whl", hash = "sha256:0d4290d559d68288da9f444089fd82490c8d2744309113fc26e2da6e48b65da6"},
    {file = "websockets-14.1-cp313-cp313-win_amd64.whl", hash = "sha256:8621a07991add373c3c5c2cf89e1d277e49dc82ed72c75e3afc74bd0acc446f0"},
    {file = "websockets-14.1-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:01bb2d4f0a6d04538d3c5dfd27c0643269656c28045a53439cbf1c004f90897a"},
    {file = "websockets-14.1-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:414ffe86f4d6f434a8c3b7913655a1a5383b617f9bf38720e7c0799fac3ab1c6"},
    {file = "websockets-14.1-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:8fda642151d5affdee8a430bd85496f2e2517be3a2b9d2484d633d5712b15c56"},
    {file = "websockets-14.1-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:cd7c11968bc3860d5c78577f0dbc535257ccec41750675d58d8dc66aa47fe52c"},
    {file = "websockets-14.1-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:a032855dc7db987dff813583d04f4950d14326665d7e714d584560b140ae6b8b"},
    {file = "websockets-14.1-cp39-cp39-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:b7e7ea2f782408c32d86b87a0d2c1fd8871b0399dd762364c731d86c86069a78"},
    {file = "websockets-14.1-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:39450e6215f7d9f6f7bc2a6da21d79374729f5d052333da4d5825af8a97e6735"},
    {file = "websockets-14.1-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:ceada5be22fa5a5a4cdeec74e761c2ee7db287208f54c718f2df4b7e200b8d4a"},
    {file = "websockets-14.1-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:3fc753451d471cff90b8f467a1fc0ae64031cf2d81b7b34e1811b7e2691bc4bc"},
    {file = "websockets-14.1-cp39-cp39-win32.whl", hash = "sha256:14839f54786987ccd9d03ed7f334baec0f02272e7ec4f6e9d427ff584aeea8b4"},
    {file = "websockets-14.1-cp39-cp39-win_amd64.whl", hash = "sha256:d9fd19ecc3a4d5ae82ddbfb30962cf6d874ff943e56e0c81f5169be2fda62979"},
    {file = "websockets-14.1-pp310-pypy310_pp73-macosx_10_15_x86_64.whl", hash = "sha256:e5dc25a9dbd1a7f61eca4b7cb04e74ae4b963d658f9e4f9aad9cd00b688692c8"},
    {file = "websockets-14.1-pp310-pypy310_pp73-macosx_11_0_arm64.whl", hash = "sha256:04a97aca96ca2acedf0d1f332c861c5a4486fdcba7bcef35873820f940c4231e"},
    {file = "websockets-14.1-pp310-pypy310_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:df174ece723b228d3e8734a6f2a6febbd413ddec39b3dc592f5a4aa0aff28098"},
    {file = "websockets-14.1-pp310-pypy310_pp73-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:034feb9f4286476f273b9a245fb15f02c34d9586a5bc936aff108c3ba1b21beb"},
    {file = "websockets-14.1-pp310-pypy310_pp73-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:660c308dabd2b380807ab64b62985eaccf923a78ebc572bd485375b9ca2b7dc7"},
    {file = "websockets-14.1-pp310-pypy310_pp73-win_amd64.whl", hash = "sha256:5a42d3ecbb2db5080fc578314439b1d79eef71d323dc661aa616fb492436af5d"},
    {file = "websockets-14.1-pp39-pypy39_pp73-macosx_10_15_x86_64.whl", hash = "sha256:ddaa4a390af911da6f680be8be4ff5aaf31c4c834c1a9147bc21cbcbca2d4370"},
    {file = "websockets-14.1-pp39-pypy39_pp73-macosx_11_0_arm64.whl", hash = "sha256:a4c805c6034206143fbabd2d259ec5e757f8b29d0a2f0bf3d2fe5d1f60147a4a"},
    {file = "websockets-14.1-pp39-pypy39_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:205f672a6c2c671a86d33f6d47c9b35781a998728d2c7c2a3e1cf3333fcb62b7"},
    {file = "websockets-14.1-pp39-pypy39_pp73-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:5ef440054124728cc49b01c33469de06755e5a7a4e83ef61934ad95fc327fbb0"},
    {file = "websockets-14.1-pp39-pypy39_pp73-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e7591d6f440af7f73c4bd9404f3772bfee064e639d2b6cc8c94076e71b2471c1"},
    {file = "websockets-14.1-pp39-pypy39_pp73-win_amd64.whl", hash = "sha256:25225cc79cfebc95ba1d24cd3ab86aaa35bcd315d12fa4358939bd55e9bd74a5"},
    {file = "websockets-14.1-py3-none-any.whl", hash = "sha256:4d4fc827a20abe6d544a119896f6b78ee13fe81cbfef416f3f2ddf09a03f0e2e"},
    {file = "websockets-14.1.tar.gz", hash = "sha256:398b10c77d471c0aab20a845e7a60076b6390bfdaac7a6d2edb0d2c59d75e8d8"},
]

[[package]]
name = "yarl"
version = "1.18.3"
description = "Yet another URL library"
optional = false
python-versions = ">=3.9"
files = [
    {file = "yarl-1.18.3-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:7df647e8edd71f000a5208fe6ff8c382a1de8edfbccdbbfe649d263de07d8c34"},
    {file = "yarl-1.18.3-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:c69697d3adff5aa4f874b19c0e4ed65180ceed6318ec856ebc423aa5850d84f7"},
    {file = "yarl-1.18.3-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:602d98f2c2d929f8e697ed274fbadc09902c4025c5a9963bf4e9edfc3ab6f7ed"},
    {file = "yarl-1.18.3-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:c654d5207c78e0bd6d749f6dae1dcbbfde3403ad3a4b11f3c5544d9906969dde"},
    {file = "yarl-1.18.3-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:5094d9206c64181d0f6e76ebd8fb2f8fe274950a63890ee9e0ebfd58bf9d787b"},
    {file = "yarl-1.18.3-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:35098b24e0327fc4ebdc8ffe336cee0a87a700c24ffed13161af80124b7dc8e5"},
    {file = "yarl-1.18.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3236da9272872443f81fedc389bace88408f64f89f75d1bdb2256069a8730ccc"},
    {file = "yarl-1.18.3-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e2c08cc9b16f4f4bc522771d96734c7901e7ebef70c6c5c35dd0f10845270bcd"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_aarch64.whl", hash = "sha256:80316a8bd5109320d38eef8833ccf5f89608c9107d02d2a7f985f98ed6876990"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_armv7l.whl", hash = "sha256:c1e1cc06da1491e6734f0ea1e6294ce00792193c463350626571c287c9a704db"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_i686.whl", hash = "sha256:fea09ca13323376a2fdfb353a5fa2e59f90cd18d7ca4eaa1fd31f0a8b4f91e62"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_ppc64le.whl", hash = "sha256:e3b9fd71836999aad54084906f8663dffcd2a7fb5cdafd6c37713b2e72be1760"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_s390x.whl", hash = "sha256:757e81cae69244257d125ff31663249b3013b5dc0a8520d73694aed497fb195b"},
    {file = "yarl-1.18.3-cp310-cp310-musllinux_1_2_x86_64.whl", hash = "sha256:b1771de9944d875f1b98a745bc547e684b863abf8f8287da8466cf470ef52690"},
    {file = "yarl-1.18.3-cp310-cp310-win32.whl", hash = "sha256:8874027a53e3aea659a6d62751800cf6e63314c160fd607489ba5c2edd753cf6"},
    {file = "yarl-1.18.3-cp310-cp310-win_amd64.whl", hash = "sha256:93b2e109287f93db79210f86deb6b9bbb81ac32fc97236b16f7433db7fc437d8"},
    {file = "yarl-1.18.3-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:8503ad47387b8ebd39cbbbdf0bf113e17330ffd339ba1144074da24c545f0069"},
    {file = "yarl-1.18.3-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:02ddb6756f8f4517a2d5e99d8b2f272488e18dd0bfbc802f31c16c6c20f22193"},
    {file = "yarl-1.18.3-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:67a283dd2882ac98cc6318384f565bffc751ab564605959df4752d42483ad889"},
    {file = "yarl-1.18.3-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:d980e0325b6eddc81331d3f4551e2a333999fb176fd153e075c6d1c2530aa8a8"},
    {file = "yarl-1.18.3-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b643562c12680b01e17239be267bc306bbc6aac1f34f6444d1bded0c5ce438ca"},
    {file = "yarl-1.18.3-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:c017a3b6df3a1bd45b9fa49a0f54005e53fbcad16633870104b66fa1a30a29d8"},
    {file = "yarl-1.18.3-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:75674776d96d7b851b6498f17824ba17849d790a44d282929c42dbb77d4f17ae"},
    {file = "yarl-1.18.3-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:ccaa3a4b521b780a7e771cc336a2dba389a0861592bbce09a476190bb0c8b4b3"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_aarch64.whl", hash = "sha256:2d06d3005e668744e11ed80812e61efd77d70bb7f03e33c1598c301eea20efbb"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_armv7l.whl", hash = "sha256:9d41beda9dc97ca9ab0b9888cb71f7539124bc05df02c0cff6e5acc5a19dcc6e"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_i686.whl", hash = "sha256:ba23302c0c61a9999784e73809427c9dbedd79f66a13d84ad1b1943802eaaf59"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_ppc64le.whl", hash = "sha256:6748dbf9bfa5ba1afcc7556b71cda0d7ce5f24768043a02a58846e4a443d808d"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_s390x.whl", hash = "sha256:0b0cad37311123211dc91eadcb322ef4d4a66008d3e1bdc404808992260e1a0e"},
    {file = "yarl-1.18.3-cp311-cp311-musllinux_1_2_x86_64.whl", hash = "sha256:0fb2171a4486bb075316ee754c6d8382ea6eb8b399d4ec62fde2b591f879778a"},
    {file = "yarl-1.18.3-cp311-cp311-win32.whl", hash = "sha256:61b1a825a13bef4a5f10b1885245377d3cd0bf87cba068e1d9a88c2ae36880e1"},
    {file = "yarl-1.18.3-cp311-cp311-win_amd64.whl", hash = "sha256:b9d60031cf568c627d028239693fd718025719c02c9f55df0a53e587aab951b5"},
    {file = "yarl-1.18.3-cp312-cp312-macosx_10_13_universal2.whl", hash = "sha256:1dd4bdd05407ced96fed3d7f25dbbf88d2ffb045a0db60dbc247f5b3c5c25d50"},
    {file = "yarl-1.18.3-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:7c33dd1931a95e5d9a772d0ac5e44cac8957eaf58e3c8da8c1414de7dd27c576"},
    {file = "yarl-1.18.3-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:25b411eddcfd56a2f0cd6a384e9f4f7aa3efee14b188de13048c25b5e91f1640"},
    {file = "yarl-1.18.3-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:436c4fc0a4d66b2badc6c5fc5ef4e47bb10e4fd9bf0c79524ac719a01f3607c2"},
    {file = "yarl-1.18.3-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:e35ef8683211db69ffe129a25d5634319a677570ab6b2eba4afa860f54eeaf75"},
    {file = "yarl-1.18.3-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:84b2deecba4a3f1a398df819151eb72d29bfeb3b69abb145a00ddc8d30094512"},
    {file = "yarl-1.18.3-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:00e5a1fea0fd4f5bfa7440a47eff01d9822a65b4488f7cff83155a0f31a2ecba"},
    {file = "yarl-1.18.3-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:d0e883008013c0e4aef84dcfe2a0b172c4d23c2669412cf5b3371003941f72bb"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:5a3f356548e34a70b0172d8890006c37be92995f62d95a07b4a42e90fba54272"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_armv7l.whl", hash = "sha256:ccd17349166b1bee6e529b4add61727d3f55edb7babbe4069b5764c9587a8cc6"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_i686.whl", hash = "sha256:b958ddd075ddba5b09bb0be8a6d9906d2ce933aee81100db289badbeb966f54e"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_ppc64le.whl", hash = "sha256:c7d79f7d9aabd6011004e33b22bc13056a3e3fb54794d138af57f5ee9d9032cb"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_s390x.whl", hash = "sha256:4891ed92157e5430874dad17b15eb1fda57627710756c27422200c52d8a4e393"},
    {file = "yarl-1.18.3-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:ce1af883b94304f493698b00d0f006d56aea98aeb49d75ec7d98cd4a777e9285"},
    {file = "yarl-1.18.3-cp312-cp312-win32.whl", hash = "sha256:f91c4803173928a25e1a55b943c81f55b8872f0018be83e3ad4938adffb77dd2"},
    {file = "yarl-1.18.3-cp312-cp312-win_amd64.whl", hash = "sha256:7e2ee16578af3b52ac2f334c3b1f92262f47e02cc6193c598502bd46f5cd1477"},
    {file = "yarl-1.18.3-cp313-cp313-macosx_10_13_universal2.whl", hash = "sha256:90adb47ad432332d4f0bc28f83a5963f426ce9a1a8809f5e584e704b82685dcb"},
    {file = "yarl-1.18.3-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:913829534200eb0f789d45349e55203a091f45c37a2674678744ae52fae23efa"},
    {file = "yarl-1.18.3-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:ef9f7768395923c3039055c14334ba4d926f3baf7b776c923c93d80195624782"},
    {file = "yarl-1.18.3-cp313-cp313-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:88a19f62ff30117e706ebc9090b8ecc79aeb77d0b1f5ec10d2d27a12bc9f66d0"},
    {file = "yarl-1.18.3-cp313-cp313-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:e17c9361d46a4d5addf777c6dd5eab0715a7684c2f11b88c67ac37edfba6c482"},
    {file = "yarl-1.18.3-cp313-cp313-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:1a74a13a4c857a84a845505fd2d68e54826a2cd01935a96efb1e9d86c728e186"},
    {file = "yarl-1.18.3-cp313-cp313-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:41f7ce59d6ee7741af71d82020346af364949314ed3d87553763a2df1829cc58"},
    {file = "yarl-1.18.3-cp313-cp313-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:f52a265001d830bc425f82ca9eabda94a64a4d753b07d623a9f2863fde532b53"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:82123d0c954dc58db301f5021a01854a85bf1f3bb7d12ae0c01afc414a882ca2"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_armv7l.whl", hash = "sha256:2ec9bbba33b2d00999af4631a3397d1fd78290c48e2a3e52d8dd72db3a067ac8"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_i686.whl", hash = "sha256:fbd6748e8ab9b41171bb95c6142faf068f5ef1511935a0aa07025438dd9a9bc1"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_ppc64le.whl", hash = "sha256:877d209b6aebeb5b16c42cbb377f5f94d9e556626b1bfff66d7b0d115be88d0a"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_s390x.whl", hash = "sha256:b464c4ab4bfcb41e3bfd3f1c26600d038376c2de3297760dfe064d2cb7ea8e10"},
    {file = "yarl-1.18.3-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:8d39d351e7faf01483cc7ff7c0213c412e38e5a340238826be7e0e4da450fdc8"},
    {file = "yarl-1.18.3-cp313-cp313-win32.whl", hash = "sha256:61ee62ead9b68b9123ec24bc866cbef297dd266175d53296e2db5e7f797f902d"},
    {file = "yarl-1.18.3-cp313-cp313-win_amd64.whl", hash = "sha256:578e281c393af575879990861823ef19d66e2b1d0098414855dd367e234f5b3c"},
    {file = "yarl-1.18.3-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:61e5e68cb65ac8f547f6b5ef933f510134a6bf31bb178be428994b0cb46c2a04"},
    {file = "yarl-1.18.3-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:fe57328fbc1bfd0bd0514470ac692630f3901c0ee39052ae47acd1d90a436719"},
    {file = "yarl-1.18.3-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:a440a2a624683108a1b454705ecd7afc1c3438a08e890a1513d468671d90a04e"},
    {file = "yarl-1.18.3-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:09c7907c8548bcd6ab860e5f513e727c53b4a714f459b084f6580b49fa1b9cee"},
    {file = "yarl-1.18.3-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b4f6450109834af88cb4cc5ecddfc5380ebb9c228695afc11915a0bf82116789"},
    {file = "yarl-1.18.3-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a9ca04806f3be0ac6d558fffc2fdf8fcef767e0489d2684a21912cc4ed0cd1b8"},
    {file = "yarl-1.18.3-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:77a6e85b90a7641d2e07184df5557132a337f136250caafc9ccaa4a2a998ca2c"},
    {file = "yarl-1.18.3-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:6333c5a377c8e2f5fae35e7b8f145c617b02c939d04110c76f29ee3676b5f9a5"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_aarch64.whl", hash = "sha256:0b3c92fa08759dbf12b3a59579a4096ba9af8dd344d9a813fc7f5070d86bbab1"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_armv7l.whl", hash = "sha256:4ac515b860c36becb81bb84b667466885096b5fc85596948548b667da3bf9f24"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_i686.whl", hash = "sha256:045b8482ce9483ada4f3f23b3774f4e1bf4f23a2d5c912ed5170f68efb053318"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_ppc64le.whl", hash = "sha256:a4bb030cf46a434ec0225bddbebd4b89e6471814ca851abb8696170adb163985"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_s390x.whl", hash = "sha256:54d6921f07555713b9300bee9c50fb46e57e2e639027089b1d795ecd9f7fa910"},
    {file = "yarl-1.18.3-cp39-cp39-musllinux_1_2_x86_64.whl", hash = "sha256:1d407181cfa6e70077df3377938c08012d18893f9f20e92f7d2f314a437c30b1"},
    {file = "yarl-1.18.3-cp39-cp39-win32.whl", hash = "sha256:ac36703a585e0929b032fbaab0707b75dc12703766d0b53486eabd5139ebadd5"},
    {file = "yarl-1.18.3-cp39-cp39-win_amd64.whl", hash = "sha256:ba87babd629f8af77f557b61e49e7c7cac36f22f871156b91e10a6e9d4f829e9"},
    {file = "yarl-1.18.3-py3-none-any.whl", hash = "sha256:b57f4f58099328dfb26c6a771d09fb20dbbae81d20cfb66141251ea063bd101b"},
    {file = "yarl-1.18.3.tar.gz", hash = "sha256:ac1801c45cbf77b6c99242eeff4fffb5e4e73a800b5c4ad4fc0be5def634d2e1"},
]

[package.dependencies]
idna = ">=2.0"
multidict = ">=4.0"
propcache = ">=0.2.0"

[metadata]
lock-version = "2.0"
python-versions = "^3.10"
content-hash = "93868f80563b845bf5aacd5a752a1dcdb957c59357b2b31b7a95685bcfefb5c2"

```

## File: backend/main.py

- Extension: .py
- Language: python
- Size: 614 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Load environment variables first
from dotenv import load_dotenv

load_dotenv()


from fastapi import FastAPI
from fastapi.middleware.cors import CORSMiddleware
from routes import screenshot, generate_code, home, evals

app = FastAPI(openapi_url=None, docs_url=None, redoc_url=None)

# Configure CORS settings
app.add_middleware(
    CORSMiddleware,
    allow_origins=["*"],
    allow_credentials=True,
    allow_methods=["*"],
    allow_headers=["*"],
)

# Add routes
app.include_router(generate_code.router)
app.include_router(screenshot.router)
app.include_router(home.router)
app.include_router(evals.router)

```

## File: backend/run_image_generation_evals.py

- Extension: .py
- Language: python
- Size: 3276 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import asyncio
import os
from typing import List, Optional, Literal
from dotenv import load_dotenv
import aiohttp
from image_generation.core import process_tasks

EVALS = [
    "Romantic Background",
    "Company logo: A stylized green sprout emerging from a circle",
    "Placeholder image of a PDF cover with abstract design",
    "A complex bubble diagram showing various interconnected features and aspects of FestivalPro, with a large central bubble surrounded by smaller bubbles of different colors representing different categories and functionalities",
    "A vibrant, abstract visualization of the RhythmRise experience ecosystem, featuring interconnected neon elements representing music, technology, and human connection",
    "Banner with text 'LiblibAI学院 课程入口'",
    "Profile picture of Pierre-Louis Labonne",
    "Two hands holding iPhone 14 models with colorful displays",
    "Portrait of a woman with long dark hair smiling at the camera",
    "Threadless logo on a gradient background from light pink to coral",
    "Jordan Schlansky Shows Conan His Favorite Nose Hair Trimmer",
    "Team Coco",
    "Intro to Large Language Models",
    "Andrej Karpathy",
    "He built a $200 million toy company",
    "CNBC International",
    "What will happen in year three of the war?",
    "Channel",
    "This is it",
    "How ASML Dominates Chip Machines",
]

# Load environment variables
load_dotenv()

# Get API keys from environment variables
OPENAI_API_KEY: Optional[str] = os.getenv("OPENAI_API_KEY")
REPLICATE_API_TOKEN: Optional[str] = os.getenv("REPLICATE_API_TOKEN")

# Directory to save generated images
OUTPUT_DIR: str = "generated_images"


async def generate_and_save_images(
    prompts: List[str],
    model: Literal["dalle3", "flux"],
    api_key: Optional[str],
) -> None:
    # Ensure the output directory exists
    os.makedirs(OUTPUT_DIR, exist_ok=True)

    if api_key is None:
        raise ValueError(f"API key for {model} is not set in the environment variables")

    # Generate images
    results: List[Optional[str]] = await process_tasks(
        prompts, api_key, None, model=model
    )

    # Save images to disk
    async with aiohttp.ClientSession() as session:
        for i, image_url in enumerate(results):
            if image_url:
                # Get the image data
                async with session.get(image_url) as response:
                    image_data: bytes = await response.read()

                # Save the image with a filename based on the input eval
                prefix = "replicate_" if model == "flux" else "dalle3_"
                filename: str = (
                    f"{prefix}{prompts[i][:50].replace(' ', '_').replace(':', '')}.png"
                )
                filepath: str = os.path.join(OUTPUT_DIR, filename)
                with open(filepath, "wb") as f:
                    f.write(image_data)
                print(f"Saved {model} image: {filepath}")
            else:
                print(f"Failed to generate {model} image for prompt: {prompts[i]}")


async def main() -> None:
    # await generate_and_save_images(EVALS, "dalle3", OPENAI_API_KEY)
    await generate_and_save_images(EVALS, "flux", REPLICATE_API_TOKEN)


if __name__ == "__main__":
    asyncio.run(main())

```

## File: backend/video_to_app.py

- Extension: .py
- Language: python
- Size: 3472 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Load environment variables first

from dotenv import load_dotenv

load_dotenv()


import base64
import mimetypes
import time
import subprocess
import os
import asyncio
from datetime import datetime
from prompts.claude_prompts import VIDEO_PROMPT
from utils import pprint_prompt
from config import ANTHROPIC_API_KEY
from video.utils import extract_tag_content, assemble_claude_prompt_video
from llm import (
    Llm,
    stream_claude_response_native,
)

STACK = "html_tailwind"

VIDEO_DIR = "./video_evals/videos"
SCREENSHOTS_DIR = "./video_evals/screenshots"
OUTPUTS_DIR = "./video_evals/outputs"


async def main():
    video_filename = "shortest.mov"
    is_followup = False

    if not ANTHROPIC_API_KEY:
        raise ValueError("ANTHROPIC_API_KEY is not set")

    # Get previous HTML
    previous_html = ""
    if is_followup:
        previous_html_file = max(
            [
                os.path.join(OUTPUTS_DIR, f)
                for f in os.listdir(OUTPUTS_DIR)
                if f.endswith(".html")
            ],
            key=os.path.getctime,
        )
        with open(previous_html_file, "r") as file:
            previous_html = file.read()

    video_file = os.path.join(VIDEO_DIR, video_filename)
    mime_type = mimetypes.guess_type(video_file)[0]
    with open(video_file, "rb") as file:
        video_content = file.read()
    video_data_url = (
        f"data:{mime_type};base64,{base64.b64encode(video_content).decode('utf-8')}"
    )

    prompt_messages = await assemble_claude_prompt_video(video_data_url)

    # Tell the model to continue
    # {"role": "assistant", "content": SECOND_MESSAGE},
    # {"role": "user", "content": "continue"},

    if is_followup:
        prompt_messages += [
            {"role": "assistant", "content": previous_html},
            {
                "role": "user",
                "content": "You've done a good job with a first draft. Improve this further based on the original instructions so that the app is fully functional like in the original video.",
            },
        ]  # type: ignore

    async def process_chunk(content: str):
        print(content, end="", flush=True)

    response_prefix = "<thinking>"

    pprint_prompt(prompt_messages)  # type: ignore

    start_time = time.time()

    completion = await stream_claude_response_native(
        system_prompt=VIDEO_PROMPT,
        messages=prompt_messages,
        api_key=ANTHROPIC_API_KEY,
        callback=lambda x: process_chunk(x),
        model=Llm.CLAUDE_3_OPUS,
        include_thinking=True,
    )

    end_time = time.time()

    # Prepend the response prefix to the completion
    completion = response_prefix + completion

    # Extract the outputs
    html_content = extract_tag_content("html", completion)
    thinking = extract_tag_content("thinking", completion)

    print(thinking)
    print(f"Operation took {end_time - start_time} seconds")

    os.makedirs(OUTPUTS_DIR, exist_ok=True)

    # Generate a unique filename based on the current time
    timestamp = datetime.now().strftime("%Y-%m-%d_%H-%M-%S")
    filename = f"video_test_output_{timestamp}.html"
    output_path = os.path.join(OUTPUTS_DIR, filename)

    # Write the HTML content to the file
    with open(output_path, "w") as file:
        file.write(html_content)

    print(f"Output file path: {output_path}")

    # Show a notification
    subprocess.run(["osascript", "-e", 'display notification "Coding Complete"'])


asyncio.run(main())

```

## File: backend/video/utils.py

- Extension: .py
- Language: python
- Size: 4405 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Extract HTML content from the completion string
import base64
import io
import mimetypes
import os
import tempfile
import uuid
from typing import Any, Union, cast
from moviepy.editor import VideoFileClip  # type: ignore
from PIL import Image
import math


DEBUG = True
TARGET_NUM_SCREENSHOTS = (
    20  # Should be max that Claude supports (20) - reduce to save tokens on testing
)


async def assemble_claude_prompt_video(video_data_url: str) -> list[Any]:
    images = split_video_into_screenshots(video_data_url)

    # Save images to tmp if we're debugging
    if DEBUG:
        save_images_to_tmp(images)

    # Validate number of images
    print(f"Number of frames extracted from video: {len(images)}")
    if len(images) > 20:
        print(f"Too many screenshots: {len(images)}")
        raise ValueError("Too many screenshots extracted from video")

    # Convert images to the message format for Claude
    content_messages: list[dict[str, Union[dict[str, str], str]]] = []
    for image in images:

        # Convert Image to buffer
        buffered = io.BytesIO()
        image.save(buffered, format="JPEG")

        # Encode bytes as base64
        base64_data = base64.b64encode(buffered.getvalue()).decode("utf-8")
        media_type = "image/jpeg"

        content_messages.append(
            {
                "type": "image",
                "source": {
                    "type": "base64",
                    "media_type": media_type,
                    "data": base64_data,
                },
            }
        )

    return [
        {
            "role": "user",
            "content": content_messages,
        },
    ]


# Returns a list of images/frame (RGB format)
def split_video_into_screenshots(video_data_url: str) -> list[Image.Image]:
    target_num_screenshots = TARGET_NUM_SCREENSHOTS

    # Decode the base64 URL to get the video bytes
    video_encoded_data = video_data_url.split(",")[1]
    video_bytes = base64.b64decode(video_encoded_data)

    mime_type = video_data_url.split(";")[0].split(":")[1]
    suffix = mimetypes.guess_extension(mime_type)

    with tempfile.NamedTemporaryFile(suffix=suffix, delete=True) as temp_video_file:
        print(temp_video_file.name)
        temp_video_file.write(video_bytes)
        temp_video_file.flush()
        clip = VideoFileClip(temp_video_file.name)
        images: list[Image.Image] = []
        total_frames = cast(int, clip.reader.nframes)  # type: ignore

        # Calculate frame skip interval by dividing total frames by the target number of screenshots
        # Ensuring a minimum skip of 1 frame
        frame_skip = max(1, math.ceil(total_frames / target_num_screenshots))

        # Iterate over each frame in the clip
        for i, frame in enumerate(clip.iter_frames()):
            # Save every nth frame
            if i % frame_skip == 0:
                frame_image = Image.fromarray(frame)  # type: ignore
                images.append(frame_image)
                # Ensure that we don't capture more than the desired number of frames
                if len(images) >= target_num_screenshots:
                    break

        # Close the video file to release resources
        clip.close()

        return images


# Save a list of PIL images to a random temporary directory
def save_images_to_tmp(images: list[Image.Image]):

    # Create a unique temporary directory
    unique_dir_name = f"screenshots_{uuid.uuid4()}"
    tmp_screenshots_dir = os.path.join(tempfile.gettempdir(), unique_dir_name)
    os.makedirs(tmp_screenshots_dir, exist_ok=True)

    for idx, image in enumerate(images):
        # Generate a unique image filename using index
        image_filename = f"screenshot_{idx}.jpg"
        tmp_filepath = os.path.join(tmp_screenshots_dir, image_filename)
        image.save(tmp_filepath, format="JPEG")

    print("Saved to " + tmp_screenshots_dir)


def extract_tag_content(tag: str, text: str) -> str:
    """
    Extracts content for a given tag from the provided text.

    :param tag: The tag to search for.
    :param text: The text to search within.
    :return: The content found within the tag, if any.
    """
    tag_start = f"<{tag}>"
    tag_end = f"</{tag}>"
    start_idx = text.find(tag_start)
    end_idx = text.find(tag_end, start_idx)
    if start_idx != -1 and end_idx != -1:
        return text[start_idx : end_idx + len(tag_end)]
    return ""

```

## File: backend/evals/runner.py

- Extension: .py
- Language: python
- Size: 2592 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from typing import Any, Coroutine, List, Optional
import asyncio
import os
from datetime import datetime
from llm import Llm
from prompts.types import Stack
from .core import generate_code_for_image
from .utils import image_to_data_url
from .config import EVALS_DIR


async def run_image_evals(
    stack: Optional[Stack] = None, model: Optional[str] = None, n: int = 1
) -> List[str]:
    INPUT_DIR = EVALS_DIR + "/inputs"
    OUTPUT_DIR = EVALS_DIR + "/outputs"

    # Get all the files in the directory (only grab pngs)
    evals = [f for f in os.listdir(INPUT_DIR) if f.endswith(".png")]

    if not stack:
        raise ValueError("No stack was provided")

    print("User selected stack:", stack)
    print("User selected model:", model)

    # If model is provided as string, convert it to Llm enum
    if not model:
        raise ValueError("No model was provided")

    selected_model = Llm(model)
    print(f"Running evals for {selected_model} model")

    # Create output subfolder with date, model and stack
    today = datetime.now().strftime("%b_%d_%Y")
    output_subfolder = os.path.join(
        OUTPUT_DIR, f"{today}_{selected_model.value}_{stack}"
    )
    os.makedirs(output_subfolder, exist_ok=True)

    tasks: list[Coroutine[Any, Any, str]] = []
    for filename in evals:
        filepath = os.path.join(INPUT_DIR, filename)
        data_url = await image_to_data_url(filepath)
        for n_idx in range(n):  # Generate N tasks for each input
            if n_idx == 0:
                task = generate_code_for_image(
                    image_url=data_url,
                    stack=stack,
                    model=selected_model,
                )
            else:
                task = generate_code_for_image(
                    image_url=data_url, stack=stack, model=Llm.GPT_4O_2024_05_13
                )
            tasks.append(task)

    print(f"Generating {len(tasks)} codes")

    results = await asyncio.gather(*tasks)

    output_files: List[str] = []
    for i, content in enumerate(results):
        # Calculate index for filename and output number
        eval_index = i // n
        output_number = i % n
        filename = evals[eval_index]
        # File name is derived from the original filename in evals with an added output number
        output_filename = f"{os.path.splitext(filename)[0]}_{output_number}.html"
        output_filepath = os.path.join(output_subfolder, output_filename)
        with open(output_filepath, "w") as file:
            file.write(content)
        output_files.append(output_filename)

    return output_files

```

## File: backend/evals/config.py

- Extension: .py
- Language: python
- Size: 27 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
EVALS_DIR = "./evals_data"

```

## File: backend/evals/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/evals/core.py

- Extension: .py
- Language: python
- Size: 1805 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from config import ANTHROPIC_API_KEY, GEMINI_API_KEY, OPENAI_API_KEY
from llm import (
    Llm,
    stream_claude_response,
    stream_gemini_response,
    stream_openai_response,
)
from prompts import assemble_prompt
from prompts.types import Stack
from openai.types.chat import ChatCompletionMessageParam


async def generate_code_for_image(image_url: str, stack: Stack, model: Llm) -> str:
    prompt_messages = assemble_prompt(image_url, stack)
    return await generate_code_core(prompt_messages, model)


async def generate_code_core(
    prompt_messages: list[ChatCompletionMessageParam], model: Llm
) -> str:

    async def process_chunk(_: str):
        pass

    if (
        model == Llm.CLAUDE_3_SONNET
        or model == Llm.CLAUDE_3_5_SONNET_2024_06_20
        or model == Llm.CLAUDE_3_5_SONNET_2024_10_22
    ):
        if not ANTHROPIC_API_KEY:
            raise Exception("Anthropic API key not found")

        completion = await stream_claude_response(
            prompt_messages,
            api_key=ANTHROPIC_API_KEY,
            callback=lambda x: process_chunk(x),
            model=model,
        )
    elif model == Llm.GEMINI_2_0_FLASH_EXP:
        if not GEMINI_API_KEY:
            raise Exception("Gemini API key not found")

        completion = await stream_gemini_response(
            prompt_messages,
            api_key=GEMINI_API_KEY,
            callback=lambda x: process_chunk(x),
            model=model,
        )
    else:
        if not OPENAI_API_KEY:
            raise Exception("OpenAI API key not found")

        completion = await stream_openai_response(
            prompt_messages,
            api_key=OPENAI_API_KEY,
            base_url=None,
            callback=lambda x: process_chunk(x),
            model=model,
        )

    return completion

```

## File: backend/evals/utils.py

- Extension: .py
- Language: python
- Size: 228 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import base64


async def image_to_data_url(filepath: str):
    with open(filepath, "rb") as image_file:
        encoded_string = base64.b64encode(image_file.read()).decode()
    return f"data:image/png;base64,{encoded_string}"

```

## File: backend/image_generation/replicate.py

- Extension: .py
- Language: python
- Size: 2547 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import asyncio
import httpx


async def call_replicate(input: dict[str, str | int], api_token: str) -> str:
    headers = {
        "Authorization": f"Bearer {api_token}",
        "Content-Type": "application/json",
    }

    data = {"input": input}

    async with httpx.AsyncClient() as client:
        try:
            response = await client.post(
                "https://api.replicate.com/v1/models/black-forest-labs/flux-schnell/predictions",
                headers=headers,
                json=data,
            )
            response.raise_for_status()
            response_json = response.json()

            # Extract the id from the response
            prediction_id = response_json.get("id")
            if not prediction_id:
                raise ValueError("Prediction ID not found in initial response.")

            # Polling every 0.1 seconds until the status is succeeded or error (upto 10s)
            num_polls = 0
            max_polls = 100
            while num_polls < max_polls:
                num_polls += 1

                await asyncio.sleep(0.1)

                # Check the status
                status_check_url = (
                    f"https://api.replicate.com/v1/predictions/{prediction_id}"
                )
                status_response = await client.get(status_check_url, headers=headers)
                status_response.raise_for_status()
                status_response_json = status_response.json()
                status = status_response_json.get("status")

                # If status is succeeded or if there's an error, break out of the loop
                if status == "succeeded":
                    return status_response_json["output"][0]
                elif status == "error":
                    raise ValueError(
                        f"Inference errored out: {status_response_json.get('error', 'Unknown error')}"
                    )
                elif status == "failed":
                    raise ValueError("Inference failed")

            # If we've reached here, it means we've exceeded the max number of polls
            raise TimeoutError("Inference timed out")

        except httpx.HTTPStatusError as e:
            raise ValueError(f"HTTP error occurred: {e}")
        except httpx.RequestError as e:
            raise ValueError(f"An error occurred while requesting: {e}")
        except asyncio.TimeoutError:
            raise TimeoutError("Request timed out")
        except Exception as e:
            raise ValueError(f"An unexpected error occurred: {e}")

```

## File: backend/image_generation/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/image_generation/core.py

- Extension: .py
- Language: python
- Size: 4584 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import asyncio
import re
from typing import Dict, List, Literal, Union
from openai import AsyncOpenAI
from bs4 import BeautifulSoup

from image_generation.replicate import call_replicate


async def process_tasks(
    prompts: List[str],
    api_key: str,
    base_url: str | None,
    model: Literal["dalle3", "flux"],
):
    import time

    start_time = time.time()
    if model == "dalle3":
        tasks = [generate_image_dalle(prompt, api_key, base_url) for prompt in prompts]
    else:
        tasks = [generate_image_replicate(prompt, api_key) for prompt in prompts]
    results = await asyncio.gather(*tasks, return_exceptions=True)
    end_time = time.time()
    generation_time = end_time - start_time
    print(f"Image generation time: {generation_time:.2f} seconds")

    processed_results: List[Union[str, None]] = []
    for result in results:
        if isinstance(result, BaseException):
            print(f"An exception occurred: {result}")
            processed_results.append(None)
        else:
            processed_results.append(result)

    return processed_results


async def generate_image_dalle(
    prompt: str, api_key: str, base_url: str | None
) -> Union[str, None]:
    client = AsyncOpenAI(api_key=api_key, base_url=base_url)
    res = await client.images.generate(
        model="dall-e-3",
        quality="standard",
        style="natural",
        n=1,
        size="1024x1024",
        prompt=prompt,
    )
    await client.close()
    return res.data[0].url


async def generate_image_replicate(prompt: str, api_key: str) -> str:

    # We use Flux Schnell
    return await call_replicate(
        {
            "prompt": prompt,
            "num_outputs": 1,
            "aspect_ratio": "1:1",
            "output_format": "png",
            "output_quality": 100,
        },
        api_key,
    )


def extract_dimensions(url: str):
    # Regular expression to match numbers in the format '300x200'
    matches = re.findall(r"(\d+)x(\d+)", url)

    if matches:
        width, height = matches[0]  # Extract the first match
        width = int(width)
        height = int(height)
        return (width, height)
    else:
        return (100, 100)


def create_alt_url_mapping(code: str) -> Dict[str, str]:
    soup = BeautifulSoup(code, "html.parser")
    images = soup.find_all("img")

    mapping: Dict[str, str] = {}

    for image in images:
        if not image["src"].startswith("https://placehold.co"):
            mapping[image["alt"]] = image["src"]

    return mapping


async def generate_images(
    code: str,
    api_key: str,
    base_url: Union[str, None],
    image_cache: Dict[str, str],
    model: Literal["dalle3", "flux"] = "dalle3",
) -> str:
    # Find all images
    soup = BeautifulSoup(code, "html.parser")
    images = soup.find_all("img")

    # Extract alt texts as image prompts
    alts: List[str | None] = []
    for img in images:
        # Only include URL if the image starts with https://placehold.co
        # and it's not already in the image_cache
        if (
            img["src"].startswith("https://placehold.co")
            and image_cache.get(img.get("alt")) is None
        ):
            alts.append(img.get("alt", None))

    # Exclude images with no alt text
    filtered_alts: List[str] = [alt for alt in alts if alt is not None]

    # Remove duplicates
    prompts = list(set(filtered_alts))

    # Return early if there are no images to replace
    if len(prompts) == 0:
        return code

    # Generate images
    results = await process_tasks(prompts, api_key, base_url, model)

    # Create a dict mapping alt text to image URL
    mapped_image_urls = dict(zip(prompts, results))

    # Merge with image_cache
    mapped_image_urls = {**mapped_image_urls, **image_cache}

    # Replace old image URLs with the generated URLs
    for img in images:
        # Skip images that don't start with https://placehold.co (leave them alone)
        if not img["src"].startswith("https://placehold.co"):
            continue

        new_url = mapped_image_urls[img.get("alt")]

        if new_url:
            # Set width and height attributes
            width, height = extract_dimensions(img["src"])
            img["width"] = width
            img["height"] = height
            # Replace img['src'] with the mapped image URL
            img["src"] = new_url
        else:
            print("Image generation failed for alt text:" + img.get("alt"))

    # Return the modified HTML
    # (need to prettify it because BeautifulSoup messes up the formatting)
    return soup.prettify()

```

## File: backend/codegen/test_utils.py

- Extension: .py
- Language: python
- Size: 2328 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import unittest
from codegen.utils import extract_html_content


class TestUtils(unittest.TestCase):

    def test_extract_html_content_with_html_tags(self):
        text = "<html><body><p>Hello, World!</p></body></html>"
        expected = "<html><body><p>Hello, World!</p></body></html>"
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    def test_extract_html_content_without_html_tags(self):
        text = "No HTML content here."
        expected = "No HTML content here."
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    def test_extract_html_content_with_partial_html_tags(self):
        text = "<html><body><p>Hello, World!</p></body>"
        expected = "<html><body><p>Hello, World!</p></body>"
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    def test_extract_html_content_with_multiple_html_tags(self):
        text = "<html><body><p>First</p></body></html> Some text <html><body><p>Second</p></body></html>"
        expected = "<html><body><p>First</p></body></html>"
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    ## The following are tests based on actual LLM outputs

    def test_extract_html_content_some_explanation_before(self):
        text = """Got it! You want the song list to be displayed horizontally. I'll update the code to ensure that the song list is displayed in a horizontal layout.

        Here's the updated code:

        <html lang="en"><head></head><body class="bg-black text-white"></body></html>"""
        expected = '<html lang="en"><head></head><body class="bg-black text-white"></body></html>'
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    def test_markdown_tags(self):
        text = "```html<head></head>```"
        expected = "```html<head></head>```"
        result = extract_html_content(text)
        self.assertEqual(result, expected)

    def test_doctype_text(self):
        text = '<!DOCTYPE html><html lang="en"><head></head><body></body></html>'
        expected = '<html lang="en"><head></head><body></body></html>'
        result = extract_html_content(text)
        self.assertEqual(result, expected)


if __name__ == "__main__":
    unittest.main()

```

## File: backend/codegen/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/codegen/utils.py

- Extension: .py
- Language: python
- Size: 440 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import re


def extract_html_content(text: str):
    # Use regex to find content within <html> tags and include the tags themselves
    match = re.search(r"(<html.*?>.*?</html>)", text, re.DOTALL)
    if match:
        return match.group(1)
    else:
        # Otherwise, we just send the previous HTML over
        print(
            "[HTML Extraction] No <html> tags found in the generated content: " + text
        )
        return text

```

## File: backend/fs_logging/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/fs_logging/core.py

- Extension: .py
- Language: python
- Size: 966 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from datetime import datetime
import json
import os
from openai.types.chat import ChatCompletionMessageParam


def write_logs(prompt_messages: list[ChatCompletionMessageParam], completion: str):
    # Get the logs path from environment, default to the current working directory
    logs_path = os.environ.get("LOGS_PATH", os.getcwd())

    # Create run_logs directory if it doesn't exist within the specified logs path
    logs_directory = os.path.join(logs_path, "run_logs")
    if not os.path.exists(logs_directory):
        os.makedirs(logs_directory)

    print("Writing to logs directory:", logs_directory)

    # Generate a unique filename using the current timestamp within the logs directory
    filename = datetime.now().strftime(f"{logs_directory}/messages_%Y%m%d_%H%M%S.json")

    # Write the messages dict into a new file for each run
    with open(filename, "w") as f:
        f.write(json.dumps({"prompt": prompt_messages, "completion": completion}))

```

## File: backend/prompts/test_prompts.py

- Extension: .py
- Language: python
- Size: 25545 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from llm import Llm
from prompts import assemble_imported_code_prompt, assemble_prompt

TAILWIND_SYSTEM_PROMPT = """
You are an expert Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Tailwind, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

HTML_CSS_SYSTEM_PROMPT = """
You are an expert CSS developer
You take screenshots of a reference web page from the user, and then build single page apps 
using CSS, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

BOOTSTRAP_SYSTEM_PROMPT = """
You are an expert Bootstrap developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Bootstrap, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Bootstrap: <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

REACT_TAILWIND_SYSTEM_PROMPT = """
You are an expert React/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using React and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include React so that it can run on a standalone page:
    <script src="https://unpkg.com/react/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IONIC_TAILWIND_SYSTEM_PROMPT = """
You are an expert Ionic/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Ionic and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Ionic so that it can run on a standalone page:
    <script type="module" src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js"></script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css" />
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- ionicons for icons, add the following <script > tags near the end of the page, right before the closing </body> tag:
    <script type="module">
        import ionicons from 'https://cdn.jsdelivr.net/npm/ionicons/+esm'
    </script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/ionicons/dist/esm/ionicons.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/ionicons/dist/collection/components/icon/icon.min.css" rel="stylesheet">

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

VUE_TAILWIND_SYSTEM_PROMPT = """
You are an expert Vue/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Vue and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- Use Vue using the global build like so:

<div id="app">{{ message }}</div>
<script>
  const { createApp, ref } = Vue
  createApp({
    setup() {
      const message = ref('Hello vue!')
      return {
        message
      }
    }
  }).mount('#app')
</script>

In terms of libraries,

- Use these script to include Vue so that it can run on a standalone page:
  <script src="https://registry.npmmirror.com/vue/3.3.11/files/dist/vue.global.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
The return result must only include the code.
"""

SVG_SYSTEM_PROMPT = """
You are an expert at building SVGs.
You take screenshots of a reference web page from the user, and then build a SVG that looks exactly like the screenshot.

- Make sure the SVG looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- You can use Google Fonts

Return only the full code in <svg></svg> tags.
Do not include markdown "```" or "```svg" at the start or end.
"""

IMPORTED_CODE_TAILWIND_SYSTEM_PROMPT = """
You are an expert Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_HTML_CSS_SYSTEM_PROMPT = """
You are an expert CSS developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_REACT_TAILWIND_SYSTEM_PROMPT = """
You are an expert React/Tailwind developer

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include React so that it can run on a standalone page:
    <script src="https://unpkg.com/react/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_BOOTSTRAP_SYSTEM_PROMPT = """
You are an expert Bootstrap developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Bootstrap: <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_IONIC_TAILWIND_SYSTEM_PROMPT = """
You are an expert Ionic/Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Ionic so that it can run on a standalone page:
    <script type="module" src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js"></script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css" />
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- ionicons for icons, add the following <script > tags near the end of the page, right before the closing </body> tag:
    <script type="module">
        import ionicons from 'https://cdn.jsdelivr.net/npm/ionicons/+esm'
    </script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/ionicons/dist/esm/ionicons.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/ionicons/dist/collection/components/icon/icon.min.css" rel="stylesheet">

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""


IMPORTED_CODE_VUE_TAILWIND_PROMPT = """
You are an expert Vue/Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Vue so that it can run on a standalone page:
  <script src="https://registry.npmmirror.com/vue/3.3.11/files/dist/vue.global.js"></script>
- Use Vue using the global build like so:
    <div id="app">{{ message }}</div>
    <script>
    const { createApp, ref } = Vue
    createApp({
        setup() {
        const message = ref('Hello vue!')
        return {
            message
        }
        }
    }).mount('#app')
    </script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
The return result must only include the code."""

IMPORTED_CODE_SVG_SYSTEM_PROMPT = """
You are an expert at building SVGs.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- You can use Google Fonts

Return only the full code in <svg></svg> tags.
Do not include markdown "```" or "```svg" at the start or end.
"""

USER_PROMPT = """
Generate code for a web page that looks exactly like this.
"""

SVG_USER_PROMPT = """
Generate code for a SVG that looks exactly like this.
"""


def test_prompts():
    tailwind_prompt = assemble_prompt(
        "image_data_url", "html_tailwind", "result_image_data_url"
    )
    assert tailwind_prompt[0].get("content") == TAILWIND_SYSTEM_PROMPT
    assert tailwind_prompt[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    html_css_prompt = assemble_prompt(
        "image_data_url", "html_css", "result_image_data_url"
    )
    assert html_css_prompt[0].get("content") == HTML_CSS_SYSTEM_PROMPT
    assert html_css_prompt[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    react_tailwind_prompt = assemble_prompt(
        "image_data_url", "react_tailwind", "result_image_data_url"
    )
    assert react_tailwind_prompt[0].get("content") == REACT_TAILWIND_SYSTEM_PROMPT
    assert react_tailwind_prompt[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    bootstrap_prompt = assemble_prompt(
        "image_data_url", "bootstrap", "result_image_data_url"
    )
    assert bootstrap_prompt[0].get("content") == BOOTSTRAP_SYSTEM_PROMPT
    assert bootstrap_prompt[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    ionic_tailwind = assemble_prompt(
        "image_data_url", "ionic_tailwind", "result_image_data_url"
    )
    assert ionic_tailwind[0].get("content") == IONIC_TAILWIND_SYSTEM_PROMPT
    assert ionic_tailwind[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    vue_tailwind = assemble_prompt(
        "image_data_url", "vue_tailwind", "result_image_data_url"
    )
    assert vue_tailwind[0].get("content") == VUE_TAILWIND_SYSTEM_PROMPT
    assert vue_tailwind[1]["content"][2]["text"] == USER_PROMPT  # type: ignore

    svg_prompt = assemble_prompt("image_data_url", "svg", "result_image_data_url")
    assert svg_prompt[0].get("content") == SVG_SYSTEM_PROMPT
    assert svg_prompt[1]["content"][2]["text"] == SVG_USER_PROMPT  # type: ignore


def test_imported_code_prompts():
    code = "Sample code"

    tailwind_prompt = assemble_imported_code_prompt(code, "html_tailwind")
    expected_tailwind_prompt = [
        {
            "role": "system",
            "content": IMPORTED_CODE_TAILWIND_SYSTEM_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert tailwind_prompt == expected_tailwind_prompt

    html_css_prompt = assemble_imported_code_prompt(code, "html_css")
    expected_html_css_prompt = [
        {
            "role": "system",
            "content": IMPORTED_CODE_HTML_CSS_SYSTEM_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert html_css_prompt == expected_html_css_prompt

    react_tailwind_prompt = assemble_imported_code_prompt(code, "react_tailwind")
    expected_react_tailwind_prompt = [
        {
            "role": "system",
            "content": IMPORTED_CODE_REACT_TAILWIND_SYSTEM_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert react_tailwind_prompt == expected_react_tailwind_prompt

    bootstrap_prompt = assemble_imported_code_prompt(code, "bootstrap")
    expected_bootstrap_prompt = [
        {
            "role": "system",
            "content": IMPORTED_CODE_BOOTSTRAP_SYSTEM_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert bootstrap_prompt == expected_bootstrap_prompt

    ionic_tailwind = assemble_imported_code_prompt(code, "ionic_tailwind")
    expected_ionic_tailwind = [
        {
            "role": "system",
            "content": IMPORTED_CODE_IONIC_TAILWIND_SYSTEM_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert ionic_tailwind == expected_ionic_tailwind

    vue_tailwind = assemble_imported_code_prompt(code, "vue_tailwind")
    expected_vue_tailwind = [
        {
            "role": "system",
            "content": IMPORTED_CODE_VUE_TAILWIND_PROMPT
            + "\n Here is the code of the app: "
            + code,
        }
    ]
    assert vue_tailwind == expected_vue_tailwind

    svg = assemble_imported_code_prompt(code, "svg")
    expected_svg = [
        {
            "role": "system",
            "content": IMPORTED_CODE_SVG_SYSTEM_PROMPT
            + "\n Here is the code of the SVG: "
            + code,
        }
    ]
    assert svg == expected_svg

```

## File: backend/prompts/__init__.py

- Extension: .py
- Language: python
- Size: 4227 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from typing import Union
from openai.types.chat import ChatCompletionMessageParam, ChatCompletionContentPartParam

from custom_types import InputMode
from image_generation.core import create_alt_url_mapping
from prompts.imported_code_prompts import IMPORTED_CODE_SYSTEM_PROMPTS
from prompts.screenshot_system_prompts import SYSTEM_PROMPTS
from prompts.types import Stack
from video.utils import assemble_claude_prompt_video


USER_PROMPT = """
Generate code for a web page that looks exactly like this.
"""

SVG_USER_PROMPT = """
Generate code for a SVG that looks exactly like this.
"""


async def create_prompt(
    params: dict[str, str], stack: Stack, input_mode: InputMode
) -> tuple[list[ChatCompletionMessageParam], dict[str, str]]:

    image_cache: dict[str, str] = {}

    # If this generation started off with imported code, we need to assemble the prompt differently
    if params.get("isImportedFromCode"):
        original_imported_code = params["history"][0]
        prompt_messages = assemble_imported_code_prompt(original_imported_code, stack)
        for index, text in enumerate(params["history"][1:]):
            if index % 2 == 0:
                message: ChatCompletionMessageParam = {
                    "role": "user",
                    "content": text,
                }
            else:
                message: ChatCompletionMessageParam = {
                    "role": "assistant",
                    "content": text,
                }
            prompt_messages.append(message)
    else:
        # Assemble the prompt for non-imported code
        if params.get("resultImage"):
            prompt_messages = assemble_prompt(
                params["image"], stack, params["resultImage"]
            )
        else:
            prompt_messages = assemble_prompt(params["image"], stack)

        if params["generationType"] == "update":
            # Transform the history tree into message format
            # TODO: Move this to frontend
            for index, text in enumerate(params["history"]):
                if index % 2 == 0:
                    message: ChatCompletionMessageParam = {
                        "role": "assistant",
                        "content": text,
                    }
                else:
                    message: ChatCompletionMessageParam = {
                        "role": "user",
                        "content": text,
                    }
                prompt_messages.append(message)

            image_cache = create_alt_url_mapping(params["history"][-2])

    if input_mode == "video":
        video_data_url = params["image"]
        prompt_messages = await assemble_claude_prompt_video(video_data_url)

    return prompt_messages, image_cache


def assemble_imported_code_prompt(
    code: str, stack: Stack
) -> list[ChatCompletionMessageParam]:
    system_content = IMPORTED_CODE_SYSTEM_PROMPTS[stack]

    user_content = (
        "Here is the code of the app: " + code
        if stack != "svg"
        else "Here is the code of the SVG: " + code
    )

    return [
        {
            "role": "system",
            "content": system_content + "\n " + user_content,
        }
    ]
    # TODO: Use result_image_data_url


def assemble_prompt(
    image_data_url: str,
    stack: Stack,
    result_image_data_url: Union[str, None] = None,
) -> list[ChatCompletionMessageParam]:
    system_content = SYSTEM_PROMPTS[stack]
    user_prompt = USER_PROMPT if stack != "svg" else SVG_USER_PROMPT

    user_content: list[ChatCompletionContentPartParam] = [
        {
            "type": "image_url",
            "image_url": {"url": image_data_url, "detail": "high"},
        },
        {
            "type": "text",
            "text": user_prompt,
        },
    ]

    # Include the result image if it exists
    if result_image_data_url:
        user_content.insert(
            1,
            {
                "type": "image_url",
                "image_url": {"url": result_image_data_url, "detail": "high"},
            },
        )
    return [
        {
            "role": "system",
            "content": system_content,
        },
        {
            "role": "user",
            "content": user_content,
        },
    ]

```

## File: backend/prompts/types.py

- Extension: .py
- Language: python
- Size: 365 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from typing import Literal, TypedDict


class SystemPrompts(TypedDict):
    html_css: str
    html_tailwind: str
    react_tailwind: str
    bootstrap: str
    ionic_tailwind: str
    vue_tailwind: str
    svg: str


Stack = Literal[
    "html_css",
    "html_tailwind",
    "react_tailwind",
    "bootstrap",
    "ionic_tailwind",
    "vue_tailwind",
    "svg",
]

```

## File: backend/prompts/screenshot_system_prompts.py

- Extension: .py
- Language: python
- Size: 12689 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from prompts.types import SystemPrompts


HTML_TAILWIND_SYSTEM_PROMPT = """
You are an expert Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Tailwind, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

HTML_CSS_SYSTEM_PROMPT = """
You are an expert CSS developer
You take screenshots of a reference web page from the user, and then build single page apps 
using CSS, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

BOOTSTRAP_SYSTEM_PROMPT = """
You are an expert Bootstrap developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Bootstrap, HTML and JS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Bootstrap: <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

REACT_TAILWIND_SYSTEM_PROMPT = """
You are an expert React/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using React and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include React so that it can run on a standalone page:
    <script src="https://unpkg.com/react@18.0.0/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18.0.0/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IONIC_TAILWIND_SYSTEM_PROMPT = """
You are an expert Ionic/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Ionic and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Ionic so that it can run on a standalone page:
    <script type="module" src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js"></script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css" />
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- ionicons for icons, add the following <script > tags near the end of the page, right before the closing </body> tag:
    <script type="module">
        import ionicons from 'https://cdn.jsdelivr.net/npm/ionicons/+esm'
    </script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/ionicons/dist/esm/ionicons.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/ionicons/dist/collection/components/icon/icon.min.css" rel="stylesheet">

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

VUE_TAILWIND_SYSTEM_PROMPT = """
You are an expert Vue/Tailwind developer
You take screenshots of a reference web page from the user, and then build single page apps 
using Vue and Tailwind CSS.
You might also be given a screenshot(The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- Use Vue using the global build like so:

<div id="app">{{ message }}</div>
<script>
  const { createApp, ref } = Vue
  createApp({
    setup() {
      const message = ref('Hello vue!')
      return {
        message
      }
    }
  }).mount('#app')
</script>

In terms of libraries,

- Use these script to include Vue so that it can run on a standalone page:
  <script src="https://registry.npmmirror.com/vue/3.3.11/files/dist/vue.global.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
The return result must only include the code.
"""


SVG_SYSTEM_PROMPT = """
You are an expert at building SVGs.
You take screenshots of a reference web page from the user, and then build a SVG that looks exactly like the screenshot.

- Make sure the SVG looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- You can use Google Fonts

Return only the full code in <svg></svg> tags.
Do not include markdown "```" or "```svg" at the start or end.
"""


SYSTEM_PROMPTS = SystemPrompts(
    html_css=HTML_CSS_SYSTEM_PROMPT,
    html_tailwind=HTML_TAILWIND_SYSTEM_PROMPT,
    react_tailwind=REACT_TAILWIND_SYSTEM_PROMPT,
    bootstrap=BOOTSTRAP_SYSTEM_PROMPT,
    ionic_tailwind=IONIC_TAILWIND_SYSTEM_PROMPT,
    vue_tailwind=VUE_TAILWIND_SYSTEM_PROMPT,
    svg=SVG_SYSTEM_PROMPT,
)

```

## File: backend/prompts/imported_code_prompts.py

- Extension: .py
- Language: python
- Size: 9169 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from prompts.types import SystemPrompts


IMPORTED_CODE_TAILWIND_SYSTEM_PROMPT = """
You are an expert Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_HTML_CSS_SYSTEM_PROMPT = """
You are an expert CSS developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_REACT_TAILWIND_SYSTEM_PROMPT = """
You are an expert React/Tailwind developer

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include React so that it can run on a standalone page:
    <script src="https://unpkg.com/react@18.0.0/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18.0.0/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_BOOTSTRAP_SYSTEM_PROMPT = """
You are an expert Bootstrap developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Bootstrap: <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_IONIC_TAILWIND_SYSTEM_PROMPT = """
You are an expert Ionic/Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Ionic so that it can run on a standalone page:
    <script type="module" src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js"></script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css" />
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- ionicons for icons, add the following <script > tags near the end of the page, right before the closing </body> tag:
    <script type="module">
        import ionicons from 'https://cdn.jsdelivr.net/npm/ionicons/+esm'
    </script>
    <script nomodule src="https://cdn.jsdelivr.net/npm/ionicons/dist/esm/ionicons.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/ionicons/dist/collection/components/icon/icon.min.css" rel="stylesheet">

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

IMPORTED_CODE_VUE_TAILWIND_SYSTEM_PROMPT = """
You are an expert Vue/Tailwind developer.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include Vue so that it can run on a standalone page:
  <script src="https://registry.npmmirror.com/vue/3.3.11/files/dist/vue.global.js"></script>
- Use Vue using the global build like so:
    <div id="app">{{ message }}</div>
    <script>
    const { createApp, ref } = Vue
    createApp({
        setup() {
        const message = ref('Hello vue!')
        return {
            message
        }
        }
    }).mount('#app')
    </script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
The return result must only include the code."""

IMPORTED_CODE_SVG_SYSTEM_PROMPT = """
You are an expert at building SVGs.

- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- You can use Google Fonts

Return only the full code in <svg></svg> tags.
Do not include markdown "```" or "```svg" at the start or end.
"""

IMPORTED_CODE_SYSTEM_PROMPTS = SystemPrompts(
    html_tailwind=IMPORTED_CODE_TAILWIND_SYSTEM_PROMPT,
    html_css=IMPORTED_CODE_HTML_CSS_SYSTEM_PROMPT,
    react_tailwind=IMPORTED_CODE_REACT_TAILWIND_SYSTEM_PROMPT,
    bootstrap=IMPORTED_CODE_BOOTSTRAP_SYSTEM_PROMPT,
    ionic_tailwind=IMPORTED_CODE_IONIC_TAILWIND_SYSTEM_PROMPT,
    vue_tailwind=IMPORTED_CODE_VUE_TAILWIND_SYSTEM_PROMPT,
    svg=IMPORTED_CODE_SVG_SYSTEM_PROMPT,
)

```

## File: backend/prompts/claude_prompts.py

- Extension: .py
- Language: python
- Size: 8055 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# Not used yet
# References:
# https://github.com/hundredblocks/transcription_demo
# https://docs.anthropic.com/claude/docs/prompt-engineering
# https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb

VIDEO_PROMPT = """
You are an expert at building single page, funtional apps using HTML, Jquery and Tailwind CSS.
You also have perfect vision and pay great attention to detail.

You will be given screenshots in order at consistent intervals from a video of a user interacting with a web app. You need to re-create the same app exactly such that the same user interactions will produce the same results in the app you build.

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- If some fuctionality requires a backend call, just mock the data instead.
- MAKE THE APP FUNCTIONAL using Javascript. Allow the user to interact with the app and get the same behavior as the video.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
- Use jQuery: <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>

Before generating the code for the app, think step-by-step: first, about the user flow depicated in the video and then about you how would you build it and how you would structure the code. Do the thinking within <thinking></thinking> tags. Then, provide your code within <html></html> tags.
"""

VIDEO_PROMPT_ALPINE_JS = """
You are an expert at building single page, funtional apps using HTML, Alpine.js and Tailwind CSS.
You also have perfect vision and pay great attention to detail.

You will be given screenshots in order at consistent intervals from a video of a user interacting with a web app. You need to re-create the same app exactly such that the same user interactions will produce the same results in the app you build.

- Make sure the app looks exactly like the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.
- If some fuctionality requires a backend call, just mock the data instead.
- MAKE THE APP FUNCTIONAL using Javascript. Allow the user to interact with the app and get the same behavior as the video.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
- Use Alpine.js: <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>

Before generating the code for the app, think step-by-step: first, about the user flow depicated in the video and then about you how would you build it and how you would structure the code. Do the thinking within <thinking></thinking> tags. Then, provide your code within <html></html> tags.
"""


HTML_TAILWIND_CLAUDE_SYSTEM_PROMPT = """
You have perfect vision and pay great attention to detail which makes you an expert at building single page apps using Tailwind, HTML and JS.
You take screenshots of a reference web page from the user, and then build single page apps 
using Tailwind, HTML and JS.
You might also be given a screenshot (The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Do not leave out smaller UI elements. Make sure to include every single thing in the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- In particular, pay attention to background color and overall color scheme.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Make sure to always get the layout right (if things are arranged in a row in the screenshot, they should be in a row in the app as well)
- Repeat elements as needed to match the screenshot. For example, if there are 15 items, the code should have 15 items. DO NOT LEAVE comments like "<!-- Repeat for each news item -->" or bad things will happen.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

#

REACT_TAILWIND_CLAUDE_SYSTEM_PROMPT = """
You have perfect vision and pay great attention to detail which makes you an expert at building single page apps using React/Tailwind.
You take screenshots of a reference web page from the user, and then build single page apps 
using React and Tailwind CSS.
You might also be given a screenshot (The second image) of a web page that you have already built, and asked to
update it to look more like the reference image(The first image).

- Make sure the app looks exactly like the screenshot.
- Do not leave out smaller UI elements. Make sure to include every single thing in the screenshot.
- Pay close attention to background color, text color, font size, font family, 
padding, margin, border, etc. Match the colors and sizes exactly.
- In particular, pay attention to background color and overall color scheme.
- Use the exact text from the screenshot.
- Do not add comments in the code such as "<!-- Add other navigation links as needed -->" and "<!-- ... other news items ... -->" in place of writing the full code. WRITE THE FULL CODE.
- Make sure to always get the layout right (if things are arranged in a row in the screenshot, they should be in a row in the app as well)
- CREATE REUSABLE COMPONENTS FOR REPEATING ELEMENTS. For example, if there are 15 similar items in the screenshot, your code should include a reusable component that generates these items. and use loops to instantiate these components as needed.
- For images, use placeholder images from https://placehold.co and include a detailed description of the image in the alt text so that an image generation AI can generate the image later.

In terms of libraries,

- Use these script to include React so that it can run on a standalone page:
    <script src="https://unpkg.com/react@18.0.0/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18.0.0/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.js"></script>
- Use this script to include Tailwind: <script src="https://cdn.tailwindcss.com"></script>
- You can use Google Fonts
- Font Awesome for icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>

Return only the full code in <html></html> tags.
Do not include markdown "```" or "```html" at the start or end.
"""

```

## File: backend/routes/generate_code.py

- Extension: .py
- Language: python
- Size: 16630 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import asyncio
from dataclasses import dataclass
import traceback
from fastapi import APIRouter, WebSocket
import openai
from codegen.utils import extract_html_content
from config import (
    ANTHROPIC_API_KEY,
    GEMINI_API_KEY,
    IS_PROD,
    NUM_VARIANTS,
    OPENAI_API_KEY,
    OPENAI_BASE_URL,
    REPLICATE_API_KEY,
    SHOULD_MOCK_AI_RESPONSE,
)
from custom_types import InputMode
from llm import (
    Completion,
    Llm,
    stream_claude_response,
    stream_claude_response_native,
    stream_gemini_response,
    stream_openai_response,
)
from fs_logging.core import write_logs
from mock_llm import mock_completion
from typing import Any, Callable, Coroutine, Dict, List, Literal, cast, get_args
from image_generation.core import generate_images
from prompts import create_prompt
from prompts.claude_prompts import VIDEO_PROMPT
from prompts.types import Stack

# from utils import pprint_prompt
from ws.constants import APP_ERROR_WEB_SOCKET_CODE  # type: ignore


router = APIRouter()


# Generate images, if needed
async def perform_image_generation(
    completion: str,
    should_generate_images: bool,
    openai_api_key: str | None,
    openai_base_url: str | None,
    image_cache: dict[str, str],
):
    replicate_api_key = REPLICATE_API_KEY
    if not should_generate_images:
        return completion

    if replicate_api_key:
        image_generation_model = "flux"
        api_key = replicate_api_key
    else:
        if not openai_api_key:
            print(
                "No OpenAI API key and Replicate key found. Skipping image generation."
            )
            return completion
        image_generation_model = "dalle3"
        api_key = openai_api_key

    print("Generating images with model: ", image_generation_model)

    return await generate_images(
        completion,
        api_key=api_key,
        base_url=openai_base_url,
        image_cache=image_cache,
        model=image_generation_model,
    )


@dataclass
class ExtractedParams:
    stack: Stack
    input_mode: InputMode
    should_generate_images: bool
    openai_api_key: str | None
    anthropic_api_key: str | None
    openai_base_url: str | None
    generation_type: Literal["create", "update"]


async def extract_params(
    params: Dict[str, str], throw_error: Callable[[str], Coroutine[Any, Any, None]]
) -> ExtractedParams:
    # Read the code config settings (stack) from the request.
    generated_code_config = params.get("generatedCodeConfig", "")
    if generated_code_config not in get_args(Stack):
        await throw_error(f"Invalid generated code config: {generated_code_config}")
        raise ValueError(f"Invalid generated code config: {generated_code_config}")
    validated_stack = cast(Stack, generated_code_config)

    # Validate the input mode
    input_mode = params.get("inputMode")
    if input_mode not in get_args(InputMode):
        await throw_error(f"Invalid input mode: {input_mode}")
        raise ValueError(f"Invalid input mode: {input_mode}")
    validated_input_mode = cast(InputMode, input_mode)

    openai_api_key = get_from_settings_dialog_or_env(
        params, "openAiApiKey", OPENAI_API_KEY
    )

    # If neither is provided, we throw an error later only if Claude is used.
    anthropic_api_key = get_from_settings_dialog_or_env(
        params, "anthropicApiKey", ANTHROPIC_API_KEY
    )

    # Base URL for OpenAI API
    openai_base_url: str | None = None
    # Disable user-specified OpenAI Base URL in prod
    if not IS_PROD:
        openai_base_url = get_from_settings_dialog_or_env(
            params, "openAiBaseURL", OPENAI_BASE_URL
        )
    if not openai_base_url:
        print("Using official OpenAI URL")

    # Get the image generation flag from the request. Fall back to True if not provided.
    should_generate_images = bool(params.get("isImageGenerationEnabled", True))

    # Extract and validate generation type
    generation_type = params.get("generationType", "create")
    if generation_type not in ["create", "update"]:
        await throw_error(f"Invalid generation type: {generation_type}")
        raise ValueError(f"Invalid generation type: {generation_type}")
    generation_type = cast(Literal["create", "update"], generation_type)

    return ExtractedParams(
        stack=validated_stack,
        input_mode=validated_input_mode,
        should_generate_images=should_generate_images,
        openai_api_key=openai_api_key,
        anthropic_api_key=anthropic_api_key,
        openai_base_url=openai_base_url,
        generation_type=generation_type,
    )


def get_from_settings_dialog_or_env(
    params: dict[str, str], key: str, env_var: str | None
) -> str | None:
    value = params.get(key)
    if value:
        print(f"Using {key} from client-side settings dialog")
        return value

    if env_var:
        print(f"Using {key} from environment variable")
        return env_var

    return None


@router.websocket("/generate-code")
async def stream_code(websocket: WebSocket):
    await websocket.accept()
    print("Incoming websocket connection...")

    ## Communication protocol setup
    async def throw_error(
        message: str,
    ):
        print(message)
        await websocket.send_json({"type": "error", "value": message})
        await websocket.close(APP_ERROR_WEB_SOCKET_CODE)

    async def send_message(
        type: Literal["chunk", "status", "setCode", "error"],
        value: str,
        variantIndex: int,
    ):
        # Print for debugging on the backend
        if type == "error":
            print(f"Error (variant {variantIndex}): {value}")
        elif type == "status":
            print(f"Status (variant {variantIndex}): {value}")

        await websocket.send_json(
            {"type": type, "value": value, "variantIndex": variantIndex}
        )

    ## Parameter extract and validation

    # TODO: Are the values always strings?
    params: dict[str, str] = await websocket.receive_json()
    print("Received params")

    extracted_params = await extract_params(params, throw_error)
    stack = extracted_params.stack
    input_mode = extracted_params.input_mode
    openai_api_key = extracted_params.openai_api_key
    openai_base_url = extracted_params.openai_base_url
    anthropic_api_key = extracted_params.anthropic_api_key
    should_generate_images = extracted_params.should_generate_images
    generation_type = extracted_params.generation_type

    print(f"Generating {stack} code in {input_mode} mode")

    for i in range(NUM_VARIANTS):
        await send_message("status", "Generating code...", i)

    ### Prompt creation

    # Image cache for updates so that we don't have to regenerate images
    image_cache: Dict[str, str] = {}

    try:
        prompt_messages, image_cache = await create_prompt(params, stack, input_mode)
    except:
        await throw_error(
            "Error assembling prompt. Contact support at support@picoapps.xyz"
        )
        raise

    # pprint_prompt(prompt_messages)  # type: ignore

    ### Code generation

    async def process_chunk(content: str, variantIndex: int):
        await send_message("chunk", content, variantIndex)

    if SHOULD_MOCK_AI_RESPONSE:
        completion_results = [
            await mock_completion(process_chunk, input_mode=input_mode)
        ]
        completions = [result["code"] for result in completion_results]
    else:
        try:
            if input_mode == "video":
                if not anthropic_api_key:
                    await throw_error(
                        "Video only works with Anthropic models. No Anthropic API key found. Please add the environment variable ANTHROPIC_API_KEY to backend/.env or in the settings dialog"
                    )
                    raise Exception("No Anthropic key")

                completion_results = [
                    await stream_claude_response_native(
                        system_prompt=VIDEO_PROMPT,
                        messages=prompt_messages,  # type: ignore
                        api_key=anthropic_api_key,
                        callback=lambda x: process_chunk(x, 0),
                        model=Llm.CLAUDE_3_OPUS,
                        include_thinking=True,
                    )
                ]
                completions = [result["code"] for result in completion_results]
            else:

                # Depending on the presence and absence of various keys,
                # we decide which models to run
                variant_models = []

                # For creation, use Claude Sonnet 3.6 but it can be lazy
                # so for updates, we use Claude Sonnet 3.5
                if generation_type == "create":
                    claude_model = Llm.CLAUDE_3_5_SONNET_2024_10_22
                else:
                    claude_model = Llm.CLAUDE_3_5_SONNET_2024_06_20

                if openai_api_key and anthropic_api_key:
                    variant_models = [
                        claude_model,
                        Llm.GPT_4O_2024_11_20,
                    ]
                elif openai_api_key:
                    variant_models = [
                        Llm.GPT_4O_2024_11_20,
                        Llm.GPT_4O_2024_11_20,
                    ]
                elif anthropic_api_key:
                    variant_models = [
                        claude_model,
                        Llm.CLAUDE_3_5_SONNET_2024_06_20,
                    ]
                else:
                    await throw_error(
                        "No OpenAI or Anthropic API key found. Please add the environment variable OPENAI_API_KEY or ANTHROPIC_API_KEY to backend/.env or in the settings dialog. If you add it to .env, make sure to restart the backend server."
                    )
                    raise Exception("No OpenAI or Anthropic key")

                tasks: List[Coroutine[Any, Any, Completion]] = []
                for index, model in enumerate(variant_models):
                    if model == Llm.GPT_4O_2024_11_20 or model == Llm.O1_2024_12_17:
                        if openai_api_key is None:
                            await throw_error("OpenAI API key is missing.")
                            raise Exception("OpenAI API key is missing.")

                        tasks.append(
                            stream_openai_response(
                                prompt_messages,
                                api_key=openai_api_key,
                                base_url=openai_base_url,
                                callback=lambda x, i=index: process_chunk(x, i),
                                model=model,
                            )
                        )
                    elif model == Llm.GEMINI_2_0_FLASH_EXP and GEMINI_API_KEY:
                        tasks.append(
                            stream_gemini_response(
                                prompt_messages,
                                api_key=GEMINI_API_KEY,
                                callback=lambda x, i=index: process_chunk(x, i),
                                model=Llm.GEMINI_2_0_FLASH_EXP,
                            )
                        )
                    elif (
                        model == Llm.CLAUDE_3_5_SONNET_2024_06_20
                        or model == Llm.CLAUDE_3_5_SONNET_2024_10_22
                    ):
                        if anthropic_api_key is None:
                            await throw_error("Anthropic API key is missing.")
                            raise Exception("Anthropic API key is missing.")

                        # For creation, use Claude Sonnet 3.6 but it can be lazy
                        # so for updates, we use Claude Sonnet 3.5
                        if params["generationType"] == "create":
                            claude_model = Llm.CLAUDE_3_5_SONNET_2024_10_22
                        else:
                            claude_model = Llm.CLAUDE_3_5_SONNET_2024_06_20

                        tasks.append(
                            stream_claude_response(
                                prompt_messages,
                                api_key=anthropic_api_key,
                                callback=lambda x, i=index: process_chunk(x, i),
                                model=claude_model,
                            )
                        )

                # Run the models in parallel and capture exceptions if any
                completions = await asyncio.gather(*tasks, return_exceptions=True)

                # If all generations failed, throw an error
                all_generations_failed = all(
                    isinstance(completion, BaseException) for completion in completions
                )
                if all_generations_failed:
                    await throw_error("Error generating code. Please contact support.")

                    # Print the all the underlying exceptions for debugging
                    for completion in completions:
                        if isinstance(completion, BaseException):
                            traceback.print_exception(completion)
                    raise Exception("All generations failed")

                # If some completions failed, replace them with empty strings
                for index, completion in enumerate(completions):
                    if isinstance(completion, BaseException):
                        completions[index] = Completion(duration=0, code="")
                        print("Generation failed for variant", index)
                        print(completion)
                    else:
                        print(
                            f"{variant_models[index].value} completion took {completion['duration']:.2f} seconds"
                        )

                completions = [
                    result["code"]
                    for result in completions
                    if not isinstance(result, BaseException)
                ]

        except openai.AuthenticationError as e:
            print("[GENERATE_CODE] Authentication failed", e)
            error_message = (
                "Incorrect OpenAI key. Please make sure your OpenAI API key is correct, or create a new OpenAI API key on your OpenAI dashboard."
                + (
                    " Alternatively, you can purchase code generation credits directly on this website."
                    if IS_PROD
                    else ""
                )
            )
            return await throw_error(error_message)
        except openai.NotFoundError as e:
            print("[GENERATE_CODE] Model not found", e)
            error_message = (
                e.message
                + ". Please make sure you have followed the instructions correctly to obtain an OpenAI key with GPT vision access: https://github.com/abi/screenshot-to-code/blob/main/Troubleshooting.md"
                + (
                    " Alternatively, you can purchase code generation credits directly on this website."
                    if IS_PROD
                    else ""
                )
            )
            return await throw_error(error_message)
        except openai.RateLimitError as e:
            print("[GENERATE_CODE] Rate limit exceeded", e)
            error_message = (
                "OpenAI error - 'You exceeded your current quota, please check your plan and billing details.'"
                + (
                    " Alternatively, you can purchase code generation credits directly on this website."
                    if IS_PROD
                    else ""
                )
            )
            return await throw_error(error_message)

    ## Post-processing

    # Strip the completion of everything except the HTML content
    completions = [extract_html_content(completion) for completion in completions]

    # Write the messages dict into a log so that we can debug later
    write_logs(prompt_messages, completions[0])

    ## Image Generation

    for index, _ in enumerate(completions):
        await send_message("status", "Generating images...", index)

    image_generation_tasks = [
        perform_image_generation(
            completion,
            should_generate_images,
            openai_api_key,
            openai_base_url,
            image_cache,
        )
        for completion in completions
    ]

    updated_completions = await asyncio.gather(*image_generation_tasks)

    for index, updated_html in enumerate(updated_completions):
        await send_message("setCode", updated_html, index)
        await send_message("status", "Code generation complete.", index)

    await websocket.close()

```

## File: backend/routes/home.py

- Extension: .py
- Language: python
- Size: 324 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
from fastapi import APIRouter
from fastapi.responses import HTMLResponse


router = APIRouter()


@router.get("/")
async def get_status():
    return HTMLResponse(
        content="<h3>Your backend is running correctly. Please open the front-end URL (default is http://localhost:5173) to use screenshot-to-code.</h3>"
    )

```

## File: backend/routes/evals.py

- Extension: .py
- Language: python
- Size: 8756 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import os
from fastapi import APIRouter, Query, Request, HTTPException
from pydantic import BaseModel
from evals.utils import image_to_data_url
from evals.config import EVALS_DIR
from typing import Set
from evals.runner import run_image_evals
from typing import List, Dict
from llm import Llm
from prompts.types import Stack
from pathlib import Path
import base64

router = APIRouter()

# Update this if the number of outputs generated per input changes
N = 1


class Eval(BaseModel):
    input: str
    outputs: list[str]


@router.get("/evals", response_model=list[Eval])
async def get_evals(folder: str):
    if not folder:
        raise HTTPException(status_code=400, detail="Folder path is required")

    folder_path = Path(folder)
    if not folder_path.exists():
        raise HTTPException(status_code=404, detail=f"Folder not found: {folder}")

    try:
        evals: list[Eval] = []
        # Get all HTML files from folder
        files = {
            f: os.path.join(folder, f)
            for f in os.listdir(folder)
            if f.endswith(".html")
        }

        # Extract base names
        base_names: Set[str] = set()
        for filename in files.keys():
            base_name = (
                filename.rsplit("_", 1)[0]
                if "_" in filename
                else filename.replace(".html", "")
            )
            base_names.add(base_name)

        for base_name in base_names:
            input_path = os.path.join(EVALS_DIR, "inputs", f"{base_name}.png")
            if not os.path.exists(input_path):
                continue

            # Find matching output file
            output_file = None
            for filename, filepath in files.items():
                if filename.startswith(base_name):
                    output_file = filepath
                    break

            if output_file:
                input_data = await image_to_data_url(input_path)
                with open(output_file, "r", encoding="utf-8") as f:
                    output_html = f.read()
                evals.append(Eval(input=input_data, outputs=[output_html]))

        return evals

    except Exception as e:
        raise HTTPException(status_code=500, detail=f"Error processing evals: {str(e)}")


class PairwiseEvalResponse(BaseModel):
    evals: list[Eval]
    folder1_name: str
    folder2_name: str


@router.get("/pairwise-evals", response_model=PairwiseEvalResponse)
async def get_pairwise_evals(
    folder1: str = Query(
        "...",
        description="Absolute path to first folder",
    ),
    folder2: str = Query(
        "..",
        description="Absolute path to second folder",
    ),
):
    if not os.path.exists(folder1) or not os.path.exists(folder2):
        return {"error": "One or both folders do not exist"}

    evals: list[Eval] = []

    # Get all HTML files from first folder
    files1 = {
        f: os.path.join(folder1, f) for f in os.listdir(folder1) if f.endswith(".html")
    }
    files2 = {
        f: os.path.join(folder2, f) for f in os.listdir(folder2) if f.endswith(".html")
    }

    # Find common base names (ignoring any suffixes)
    common_names: Set[str] = set()
    for f1 in files1.keys():
        base_name: str = f1.rsplit("_", 1)[0] if "_" in f1 else f1.replace(".html", "")
        for f2 in files2.keys():
            if f2.startswith(base_name):
                common_names.add(base_name)

    # For each matching pair, create an eval
    for base_name in common_names:
        # Find the corresponding input image
        input_image = None
        input_path = os.path.join(EVALS_DIR, "inputs", f"{base_name}.png")
        if os.path.exists(input_path):
            input_image = await image_to_data_url(input_path)
        else:
            input_image = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII="  # 1x1 transparent PNG

        # Get the HTML contents
        output1 = None
        output2 = None

        # Find matching files in folder1
        for f1 in files1.keys():
            if f1.startswith(base_name):
                with open(files1[f1], "r") as f:
                    output1 = f.read()
                break

        # Find matching files in folder2
        for f2 in files2.keys():
            if f2.startswith(base_name):
                with open(files2[f2], "r") as f:
                    output2 = f.read()
                break

        if output1 and output2:
            evals.append(Eval(input=input_image, outputs=[output1, output2]))

    # Extract folder names for the UI
    folder1_name = os.path.basename(folder1)
    folder2_name = os.path.basename(folder2)

    return PairwiseEvalResponse(
        evals=evals, folder1_name=folder1_name, folder2_name=folder2_name
    )


class RunEvalsRequest(BaseModel):
    models: List[str]
    stack: Stack


@router.post("/run_evals", response_model=List[str])
async def run_evals(request: RunEvalsRequest) -> List[str]:
    """Run evaluations on all images in the inputs directory for multiple models"""
    all_output_files: List[str] = []

    for model in request.models:
        output_files = await run_image_evals(model=model, stack=request.stack)
        all_output_files.extend(output_files)

    return all_output_files


@router.get("/models", response_model=Dict[str, List[str]])
async def get_models():
    current_models = [
        model.value
        for model in Llm
        if model != Llm.GPT_4_TURBO_2024_04_09
        and model != Llm.GPT_4_VISION
        and model != Llm.CLAUDE_3_SONNET
        and model != Llm.CLAUDE_3_OPUS
        and model != Llm.CLAUDE_3_HAIKU
    ]

    # Import Stack type from prompts.types and get all literal values
    available_stacks = list(Stack.__args__)

    return {"models": current_models, "stacks": available_stacks}


class BestOfNEvalsResponse(BaseModel):
    evals: list[Eval]
    folder_names: list[str]


@router.get("/best-of-n-evals", response_model=BestOfNEvalsResponse)
async def get_best_of_n_evals(request: Request):
    # Get all query parameters
    query_params = dict(request.query_params)

    # Extract all folder paths (folder1, folder2, folder3, etc.)
    folders = []
    i = 1
    while f"folder{i}" in query_params:
        folders.append(query_params[f"folder{i}"])
        i += 1

    if not folders:
        return {"error": "No folders provided"}

    # Validate folders exist
    for folder in folders:
        if not os.path.exists(folder):
            return {"error": f"Folder does not exist: {folder}"}

    evals: list[Eval] = []
    folder_names = [os.path.basename(folder) for folder in folders]

    # Get HTML files from all folders
    files_by_folder = []
    for folder in folders:
        files = {
            f: os.path.join(folder, f)
            for f in os.listdir(folder)
            if f.endswith(".html")
        }
        files_by_folder.append(files)

    # Find common base names across all folders
    common_names: Set[str] = set()
    base_names_first_folder = {
        f.rsplit("_", 1)[0] if "_" in f else f.replace(".html", "")
        for f in files_by_folder[0].keys()
    }

    for base_name in base_names_first_folder:
        found_in_all = True
        for folder_files in files_by_folder[1:]:
            if not any(f.startswith(base_name) for f in folder_files.keys()):
                found_in_all = False
                break
        if found_in_all:
            common_names.add(base_name)

    # For each matching set, create an eval
    for base_name in common_names:
        # Find the corresponding input image
        input_image = None
        input_path = os.path.join(EVALS_DIR, "inputs", f"{base_name}.png")
        if os.path.exists(input_path):
            input_image = await image_to_data_url(input_path)
        else:
            input_image = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII="

        # Get HTML contents from all folders
        outputs = []
        for folder_files in files_by_folder:
            output_content = None
            for filename in folder_files.keys():
                if filename.startswith(base_name):
                    with open(folder_files[filename], "r") as f:
                        output_content = f.read()
                    break
            if output_content:
                outputs.append(output_content)
            else:
                outputs.append("<html><body>Output not found</body></html>")

        if len(outputs) == len(folders):  # Only add if we have outputs from all folders
            evals.append(Eval(input=input_image, outputs=outputs))

    return BestOfNEvalsResponse(evals=evals, folder_names=folder_names)

```

## File: backend/routes/screenshot.py

- Extension: .py
- Language: python
- Size: 1770 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import base64
from fastapi import APIRouter
from pydantic import BaseModel
import httpx

router = APIRouter()


def bytes_to_data_url(image_bytes: bytes, mime_type: str) -> str:
    base64_image = base64.b64encode(image_bytes).decode("utf-8")
    return f"data:{mime_type};base64,{base64_image}"


async def capture_screenshot(
    target_url: str, api_key: str, device: str = "desktop"
) -> bytes:
    api_base_url = "https://api.screenshotone.com/take"

    params = {
        "access_key": api_key,
        "url": target_url,
        "full_page": "true",
        "device_scale_factor": "1",
        "format": "png",
        "block_ads": "true",
        "block_cookie_banners": "true",
        "block_trackers": "true",
        "cache": "false",
        "viewport_width": "342",
        "viewport_height": "684",
    }

    if device == "desktop":
        params["viewport_width"] = "1280"
        params["viewport_height"] = "832"

    async with httpx.AsyncClient(timeout=60) as client:
        response = await client.get(api_base_url, params=params)
        if response.status_code == 200 and response.content:
            return response.content
        else:
            raise Exception("Error taking screenshot")


class ScreenshotRequest(BaseModel):
    url: str
    apiKey: str


class ScreenshotResponse(BaseModel):
    url: str


@router.post("/api/screenshot")
async def app_screenshot(request: ScreenshotRequest):
    # Extract the URL from the request body
    url = request.url
    api_key = request.apiKey

    # TODO: Add error handling
    image_bytes = await capture_screenshot(url, api_key=api_key)

    # Convert the image bytes to a data url
    data_url = bytes_to_data_url(image_bytes, "image/png")

    return ScreenshotResponse(url=data_url)

```

## File: backend/ws/constants.py

- Extension: .py
- Language: python
- Size: 129 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
# WebSocket protocol (RFC 6455) allows for the use of custom close codes in the range 4000-4999
APP_ERROR_WEB_SOCKET_CODE = 4332

```

## File: backend/ws/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/debug/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/debug/DebugFileWriter.py

- Extension: .py
- Language: python
- Size: 987 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import os
import logging
import uuid

from config import DEBUG_DIR, IS_DEBUG_ENABLED


class DebugFileWriter:
    def __init__(self):
        if not IS_DEBUG_ENABLED:
            return

        try:
            self.debug_artifacts_path = os.path.expanduser(
                f"{DEBUG_DIR}/{str(uuid.uuid4())}"
            )
            os.makedirs(self.debug_artifacts_path, exist_ok=True)
            print(f"Debugging artifacts will be stored in: {self.debug_artifacts_path}")
        except:
            logging.error("Failed to create debug directory")

    def write_to_file(self, filename: str, content: str) -> None:
        try:
            with open(os.path.join(self.debug_artifacts_path, filename), "w") as file:
                file.write(content)
        except Exception as e:
            logging.error(f"Failed to write to file: {e}")

    def extract_html_content(self, text: str) -> str:
        return str(text.split("<html>")[-1].rsplit("</html>", 1)[0] + "</html>")

```

## File: backend/image_processing/__init__.py

- Extension: .py
- Language: python
- Size: 0 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python

```

## File: backend/image_processing/utils.py

- Extension: .py
- Language: python
- Size: 2910 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```python
import base64
import io
import time
from PIL import Image

CLAUDE_IMAGE_MAX_SIZE = 5 * 1024 * 1024
CLAUDE_MAX_IMAGE_DIMENSION = 7990


# Process image so it meets Claude requirements
def process_image(image_data_url: str) -> tuple[str, str]:

    # Extract bytes and media type from base64 data URL
    media_type = image_data_url.split(";")[0].split(":")[1]
    base64_data = image_data_url.split(",")[1]
    image_bytes = base64.b64decode(base64_data)

    img = Image.open(io.BytesIO(image_bytes))

    # Check if image is under max dimensions and size
    is_under_dimension_limit = (
        img.width < CLAUDE_MAX_IMAGE_DIMENSION
        and img.height < CLAUDE_MAX_IMAGE_DIMENSION
    )
    is_under_size_limit = len(base64_data) <= CLAUDE_IMAGE_MAX_SIZE

    # If image is under both limits, no processing needed
    if is_under_dimension_limit and is_under_size_limit:
        print("[CLAUDE IMAGE PROCESSING] no processing needed")
        return (media_type, base64_data)

    # Time image processing
    start_time = time.time()

    # Check if either dimension exceeds 7900px (Claude disallows >= 8000px)
    # Resize image if needed
    if not is_under_dimension_limit:
        # Calculate the new dimensions while maintaining aspect ratio
        if img.width > img.height:
            new_width = CLAUDE_MAX_IMAGE_DIMENSION
            new_height = int((CLAUDE_MAX_IMAGE_DIMENSION / img.width) * img.height)
        else:
            new_height = CLAUDE_MAX_IMAGE_DIMENSION
            new_width = int((CLAUDE_MAX_IMAGE_DIMENSION / img.height) * img.width)

        # Resize the image
        img = img.resize((new_width, new_height), Image.DEFAULT_STRATEGY)
        print(
            f"[CLAUDE IMAGE PROCESSING] image resized: width = {new_width}, height = {new_height}"
        )

    # Convert and compress as JPEG
    # We always compress as JPEG (95% at the least) even when we resize and the original image
    # is under the size limit.
    quality = 95
    output = io.BytesIO()
    img = img.convert("RGB")  # Ensure image is in RGB mode for JPEG conversion
    img.save(output, format="JPEG", quality=quality)

    # Reduce quality until image is under max size
    while (
        len(base64.b64encode(output.getvalue())) > CLAUDE_IMAGE_MAX_SIZE
        and quality > 10
    ):
        output = io.BytesIO()
        img.save(output, format="JPEG", quality=quality)
        quality -= 5

    # Log so we know it was modified
    old_size = len(base64_data)
    new_size = len(base64.b64encode(output.getvalue()))
    print(
        f"[CLAUDE IMAGE PROCESSING] image size updated: old size = {old_size} bytes, new size = {new_size} bytes"
    )

    end_time = time.time()
    processing_time = end_time - start_time
    print(f"[CLAUDE IMAGE PROCESSING] processing time: {processing_time:.2f} seconds")

    return ("image/jpeg", base64.b64encode(output.getvalue()).decode("utf-8"))

```

## File: blog/evaluating-claude.md

- Extension: .md
- Language: markdown
- Size: 5101 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
# Claude 3 for converting screenshots to code

Claude 3 dropped yesterday, claiming to rival GPT-4 on a wide variety of tasks. I maintain a very popular open source project called “screenshot-to-code” (this one!) that uses GPT-4 vision to convert screenshots/designs into clean code. Naturally, I was excited to see how good Claude 3 was at this task.

**TLDR:** Claude 3 is on par with GPT-4 vision for screenshot to code, better in some ways but worse in others.

## Evaluation Setup

I don’t know of a public benchmark for “screenshot to code” so I created simple evaluation setup for the purposes of testing:

- **Evaluation Dataset**: 16 screenshots with a mix of UI elements, landing pages, dashboards and popular websites.
<img width="784" alt="Screenshot 2024-03-05 at 3 05 52 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/c32af2db-eb5a-44c1-9a19-2f0c3dd11ab4">

- **Evaluation Metric**: Replication accuracy, as in “How close does the generated code look to the screenshot?” While there are other metrics that are important like code quality, speed and so on, this is by far the #1 thing most users of the repo care about.
- **Evaluation Mechanism**: Each output is subjectively rated by a human on a rating scale from 0 to 4. 4 = very close to an exact replica while 0 = nothing like the screenshot. With 16 screenshots, the maximum any model can score is 64.


To make the evaluation process easy, I created [a Python script](https://github.com/abi/screenshot-to-code/blob/main/backend/run_evals.py) that runs code for all the inputs in parallel. I also made a simple UI to do a side-by-side comparison of the input and output.

![Google Chrome](https://github.com/abi/screenshot-to-code/assets/23818/38126f8f-205d-4ed1-b8cf-039e81dcc3d0)


## Results

Quick note about what kind of code we’ll be generating: currently, screenshot-to-code supports generating code in HTML + Tailwind, React, Vue, and several other frameworks. Stacks can impact the replication accuracy quite a bit. For example, because Bootstrap uses a relatively restrictive set of user elements, generations using Bootstrap tend to have a distinct "Bootstrap" style.

I only ran the evals on HTML/Tailwind here which is the stack where GPT-4 vision tends to perform the best.

Here are the results (average of 3 runs for each model):

- GPT-4 Vision obtains a score of **65.10%** - this is what we’re trying to beat
- Claude 3 Sonnet receives a score of **70.31%**, which is a bit better.
- Surprisingly, Claude 3 Opus which is supposed to be the smarter and slower model scores worse than both GPT-4 vision and Claude 3 Sonnet, comes in at **61.46%**.

Overall, a very strong showing for Claude 3. Obviously, there's a lot of subjectivity involved in this evaluation but Claude 3 is definitely on par with GPT-4 Vision, if not better.

You can see the [side-by-side comparison for a run of Claude 3 Sonnet here](https://github.com/abi/screenshot-to-code-files/blob/main/sonnet%20results.png). And for [a run of GPT-4 Vision here](https://github.com/abi/screenshot-to-code-files/blob/main/gpt%204%20vision%20results.png).

Other notes:

- The prompts used are optimized for GPT-4 vision. Adjusting the prompts a bit for Claude did yield a small improvement. But nothing game-changing and potentially not worth the trade-off of maintaining two sets of prompts.
- All the models excel at code quality - the quality is usually comparable to a human or better.
- Claude 3 is much less lazy than GPT-4 Vision. When asked to recreate Hacker News, GPT-4 Vision will only create two items in the list and leave comments in this code like `<!-- Repeat for each news item -->` and `<!-- ... other news items ... -->`.
<img width="699" alt="Screenshot 2024-03-05 at 9 25 04 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/04b03155-45e0-40b0-8de0-b1f0b4382bee">

While Claude 3 Sonnet can sometimes be lazy too, most of the time, it does what you ask it to do.

<img width="904" alt="Screenshot 2024-03-05 at 9 30 23 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/b7c7d1ba-47c1-414d-928f-6989e81cf41d">

- For some reason, all the models struggle with side-by-side "flex" layouts
<img width="1090" alt="Screenshot 2024-03-05 at 9 20 58 PM" src="https://github.com/abi/screenshot-to-code/assets/23818/8957bb3a-da66-467d-997d-1c7cc24e6d9a">

- Claude 3 Sonnet is a lot faster
- Claude 3 gets background and text colors wrong quite often! (like in the Hacker News image above)
- My suspicion is that Claude 3 Opus results can be improved to be on par with the other models through better prompting
  
Overall, I'm very impressed with Claude 3 Sonnet for this use case. I've added it as an alternative to GPT-4 Vision in the open source repo (hosted version update coming soon).

If you’d like to contribute to this effort, I have some documentation on [running these evals yourself here](https://github.com/abi/screenshot-to-code/blob/main/Evaluation.md). I'm also working on a better evaluation mechanism with Elo ratings and would love some help on that.

```

## File: .github/FUNDING.yml

- Extension: .yml
- Language: yaml
- Size: 14 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```yaml
github: [abi]

```

## File: .github/ISSUE_TEMPLATE/feature_request.md

- Extension: .md
- Language: markdown
- Size: 595 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

**Is your feature request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]

**Describe the solution you'd like**
A clear and concise description of what you want to happen.

**Describe alternatives you've considered**
A clear and concise description of any alternative solutions or features you've considered.

**Additional context**
Add any other context or screenshots about the feature request here.

```

## File: .github/ISSUE_TEMPLATE/bug_report.md

- Extension: .md
- Language: markdown
- Size: 416 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Screenshots of backend AND frontend terminal logs**
If applicable, add screenshots to help explain your problem.

```

## File: .github/ISSUE_TEMPLATE/custom.md

- Extension: .md
- Language: markdown
- Size: 126 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```markdown
---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---



```

## File: .vscode/settings.json

- Extension: .json
- Language: json
- Size: 149 bytes
- Created: 2025-01-14 15:32:20
- Modified: 2025-01-09 18:57:18

### Code

```json
{
  "python.analysis.typeCheckingMode": "strict",
  "python.analysis.extraPaths": ["./backend"],
  "python.autoComplete.extraPaths": ["./backend"]
}

```

