# 📔 Amphomeus
> *A journal and media gallery application*

## ✨ About Amphomeus

**Amphomeus** is a journaling gallery application developed for the StackUp May 2025 Coding Challenge. This Next.js application allows users to create journal entries with images and videos, organize them with tags, and search through their collection.

## 🌐 Live Demo

**Live App**: [https://amphomeus.vercel.app](https://amphomeus.vercel.app)

*Try it out by creating your own journal entries!*

## 📱 Contact

- **Discord**: $sudo
- **X/Twitter**: [@kal_xyz](https://x.com/@kal_xyz)

### 🎬 See It In Action

[![Amphomeus Demo](https://img.youtube.com/vi/PLACEHOLDER/0.jpg)](https://youtu.be/emIhQm7NYI0 "Amphomeus Demo")

### 🌟 Key Features

Amphomeus includes the following functionality:

- **Media Support** - Upload photos and videos with your journal entries
- **Tagging System** - Categorize entries with custom tags for easy filtering
- **Location Tracking** - Add location information to each journal entry
- **Responsive Design** - Works on desktop and mobile devices

Amphomeus provides a private space for storing memories, helping users maintain a digital record of experiences and moments without the distractions of social media.

### 🔧 Tech Stack

- **Frontend**: Next.js, React, TailwindCSS
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL (via Prisma)
- **Media Storage**: Cloudinary
- **Authentication**: Supabase Auth

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- PostgreSQL database (or Supabase account)
- Cloudinary account

### Installation

1. **Clone the repository**
   ```zsh
   git clone https://github.com/yourusername/amphomeus.git
   cd amphomeus
   ```

2. **Install dependencies**
   ```zsh
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   Create a `.env` file with the following:
   ```
   # Database
   DATABASE_URL="your-postgresql-connection-string"
   
   # Supabase
   NEXT_PUBLIC_SUPABASE_URL="your-supabase-url"
   NEXT_PUBLIC_SUPABASE_ANON_KEY="your-supabase-anon-key"
   
   # Cloudinary
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="your-cloud-name"
   CLOUDINARY_API_KEY="your-api-key"
   CLOUDINARY_API_SECRET="your-api-secret"
   ```

4. **Set up the database**
   ```zsh
   # Push the schema to your database
   npx prisma db push
   
   # Generate Prisma client
   npx prisma generate
   ```

5. **Run the development server**
   ```zsh
   npm run dev
   # or
   yarn dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📱 Features

- **Create Journal Entries** - Add title, content, date, and location
- **Upload Media** - Drag and drop photos and videos
- **Organize with Tags** - Create and assign custom tags
- **Filter & Search** - Find entries by text or tags
- **Responsive Gallery** - Toggle between grid and list views
- **Edit Entries** - Update your journals anytime

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<p align="center">
  Made with ❤️ by $sudo
</p>