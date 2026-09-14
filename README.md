# Pet Animals & Wildlife Welfare Platform

A comprehensive, modern web platform dedicated to pet care, wildlife conservation, and building stronger animal-loving communities. Built with React, TypeScript, and Tailwind CSS.

## 🌟 Features

### 16 Core Features

#### Pets
- **Adoption Events** - Host and join animal adoption events
- **Pet Surrender & Care** - Safe surrender services with real-time updates
- **Pet Doctors & Hospitals** - Directory of verified veterinarians
- **Pet Trainers** - Find certified trainers with ratings
- **Pet Shops & Products** - Browse food, accessories, and care products
- **Health & Vaccinations** - Track vaccination records and health reports
- **Pet Stories** - Share pet stories and earn community badges

#### Community
- **Lost & Found Pets** - Report missing pets and help reunite families
- **Report Animal Abuse** - Secure reporting system for welfare violations
- **Animal Welfare Clubs** - Join local community clubs
- **Animal Lovers Community** - Connect in group discussions
- **Awareness Campaigns** - Create and participate in welfare campaigns

#### Wildlife
- **Wildlife Sanctuaries** - Explore real and virtual sanctuaries
- **Endangered Species Info** - Learn about conservation efforts

#### News & Help
- **News & Updates** - Stay informed with latest wildlife and pet news
- **Emergency Rescue Numbers** - Quick access to emergency services

## 🚀 Tech Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **State Management**: React Query + Context API
- **Forms**: React Hook Form + Zod validation
- **Icons**: Lucide React
- **Maps**: Leaflet + OpenStreetMap
- **Notifications**: React Hot Toast

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Card.tsx        # Card component variants
│   ├── Button.tsx      # Button component with variants
│   ├── Badge.tsx       # Badge component with status indicators
│   ├── Header.tsx      # Navigation header with grouped menus
│   ├── Footer.tsx      # Site footer
│   └── ...             # Feature-specific components
├── pages/              # Route components (planned)
├── types.ts            # TypeScript interfaces
├── utils.ts            # Utility functions and mock data
├── AuthContext.tsx     # Authentication context
├── Home.tsx            # Homepage with feature grid
└── App.tsx             # Main app component with routing
```

## 🔐 Authentication

- **Registration**: Name, email, password (8+ chars)
- **Login**: Email + password
- **Roles**: Guest, User, Verified NGO, Verified Vet, Verified Trainer, Moderator, Admin
- **Storage**: Local storage (development) - ready for JWT implementation

## 🎨 Design System

- **Colors**: Emerald and blue gradients with neutral backgrounds
- **Spacing**: 8px scale (Tailwind default)
- **Typography**: Inter font family
- **Components**: Consistent rounded corners (rounded-2xl), soft shadows
- **Animations**: Hover effects, smooth transitions

## 📱 Responsive Design

- **Mobile-first**: Grid collapses 4→2→1 columns
- **Touch-friendly**: Appropriate target sizes
- **Navigation**: Collapsible mobile menu with grouped sections

## 🔧 Environment Variables

Create a `.env` file in the root directory:

```env
# API Configuration (when backend is implemented)
VITE_API_URL=http://localhost:3001
VITE_API_KEY=your_api_key

# Map Configuration
VITE_MAP_PROVIDER=openstreetmap

# Storage Configuration
VITE_STORAGE_PROVIDER=local
VITE_STORAGE_BUCKET=pet-welfare-uploads

# Email Configuration (for notifications)
VITE_EMAIL_PROVIDER=smtp
VITE_EMAIL_FROM=noreply@petwelfare.com
```

## 🚧 Development Status

### ✅ Completed
- Project setup with modern tooling
- Authentication system with context
- Responsive navigation with grouped menus
- Home page with 16 feature cards
- Adoption Events with full CRUD functionality
- Reusable UI components (Card, Button, Badge)
- TypeScript interfaces for all entities
- Mock data for development

### 🔄 In Progress
- Pet Surrender & Care with provider directory
- Lost & Found with matching system
- Report Abuse with case management
- All remaining 13 features

### 📋 Planned
- Backend API integration
- Real-time notifications
- Map integration with Leaflet
- Image upload functionality
- Admin dashboard
- Content moderation system
- Email notifications
- PWA capabilities

## Website link
https://pawcare2745-an2926.netlify.app/
