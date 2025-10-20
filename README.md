# raminOS — A web-based agentic AI OS, made with Cursor
  
- Shuffle and loop playback modes
  
- Create playlists and organize tracks
  
- Time-synced lyrics with multi-language translation
  
- Interactive lyric offset adjustment via gestures
  
- Multiple lyric alignment modes (Focus Three, Alternating, Center)
  
- Chinese character variants (Traditional/Simplified) and Korean romanization
  
- Fullscreen lyrics mode with video support
  
- Real-time lyric highlighting during playback
  
- Library persisted locally for offline playback
## Project Structure
```
project/
├── public/           # Static assets
│   ├── assets/       # Videos, sounds, and other media
│   ├── fonts/        # Font files
│   ├── icons/        # UI icons organized by category
│   ├── patterns/     # Pattern files
│   └── wallpapers/   # Wallpaper images (photos and tiles)
├── src/
│   ├── apps/         # Individual application modules
│   │   └── [app-name]/ # Each app has its own directory
│   │       ├── components/ # App-specific components
│   │       ├── hooks/      # Custom hooks specific to the app
│   │       └── utils/      # Utility functions for the app
│   ├── components/   # Shared React components
│   │   ├── dialogs/    # Dialog components
│   │   ├── layout/     # Layout components
│   │   ├── shared/     # Shared components across applications
│   │   └── ui/         # UI components (shadcn components)
│   ├── config/       # Configuration files
│   ├── contexts/     # React context providers
│   ├── hooks/        # Custom React hooks
│   ├── lib/          # Libraries and utilities
│   ├── stores/       # State management (e.g., Zustand stores)
│   ├── styles/       # CSS and styling utilities
│   ├── types/        # TypeScript type definitions
│   └── utils/        # Utility functions
├── api/              # API endpoints
└── ...config files   # e.g., vite.config.ts, tsconfig.json, package.json
```
## Development
The project uses:
- TypeScript for type safety
- ESLint for code quality
- Tailwind for utility-first CSS
- shadcn/ui components built on Radix UI primitives
- Lucide icons
- Vercel for deployment
## Scripts
- `bun dev` - Start development server
- `bun run build` - Build for production
- `bun run lint` - Run ESLint
- `bun run preview` - Preview production build
## License
This project is licensed under the AGPL-3.0 License - see the [LICENSE](LICENSE) file for details.
## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
