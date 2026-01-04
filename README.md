# PDFToolkit

PDFToolkit is a modern, high-performance, client-side suite of PDF tools built with Next.js. Unlike traditional PDF editors that upload your documents to a server for processing, PDFToolkit performs all operations entirely in your browser. This ensures maximum privacy, as your sensitive files never leave your local device, and provides a faster experience.

Live Demo: xyz.com

## Key Features

- 100% Client-Side: No file uploads, no server-side processing, and no data collection.
- Privacy First: Your files stay on your device. Period.
- Fast and Simple: Instant processing using the power of your local CPU.
- Tools Included:
    - Merge PDFs: Combine multiple PDF files into one.
    - Split PDF: Extract specific pages or split a document into multiple files.
    - Rotate Pages: Fix orientation issues on a per-page or document-wide basis.
    - Reorder/Organize: Drag and drop pages to rearrange your document.
    - Protect/Unlock: Add or remove password protection.
    - Image to PDF: Convert JPG/PNG images into a single PDF document.

## Built With

- Framework: Next.js (App Router)
- PDF Engine: pdf-lib / PDF.js
- Styling: Tailwind CSS
- UI Components: Radix UI / Shadcn UI
- Drag and Drop: dnd-kit

## Getting Started

### Prerequisites

- Node.js (v18.0.0 or higher)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
   git clone https://github.com/Zintl-e/pdftoolkit.git
   cd pdftoolkit

2. Install dependencies:
   npm install

3. Run the development server:
   npm run dev

4. Open in Browser:
   Navigate to http://localhost:3000 to see the application in action.

## How to Use

1. Select a Tool: Choose the operation you want to perform (e.g., Merge PDF) from the dashboard.
2. Upload Files: Drag and drop your PDF files into the upload zone. These files are only loaded into your browser's memory.
3. Adjust Settings: Use the interactive interface to reorder pages, enter passwords, or set rotation angles.
4. Process: Click the action button (e.g., Generate PDF).
5. Download: Your processed file will be generated instantly for download.

## Deployment

To build the project for production:

npm run build
npm run start

This project can be easily deployed on Vercel, Netlify, or any static hosting provider since it is a Next.js application.

## Privacy and Security

PDFToolkit is designed to be a Zero-Knowledge tool. 
- No Analytics: We do not track your file names or content.
- Offline Capable: Once loaded, the tools can work without an internet connection.
- No Database: We do not store any user data.

## License

Distributed under the MIT License. See LICENSE for more information.




















This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
