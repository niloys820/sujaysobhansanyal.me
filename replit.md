# Sujay Sobhan Sanyal Memorial Website

## Project Overview
A compassionate digital memorial website dedicated to Sujay Sobhan Sanyal, providing an immersive and respectful online tribute that celebrates his life through interactive storytelling and thoughtful multimedia presentation.

**Current State:** Post-ceremony memorial website with dynamic color palettes and memorial video hero section

## Technical Architecture
- **Frontend:** React.js with TypeScript, Vite build system
- **Backend:** Express.js with in-memory storage
- **Styling:** Tailwind CSS with custom memorial color schemes
- **Features:** 
  - Dynamic emotional color palette system (5 moods: Peaceful, Reflective, Hopeful, Warm, Serene)
  - Quote carousel with 10-second auto-rotation
  - Memorial video hero section
  - Fully responsive design optimized for mobile and desktop
  - Cross-browser compatibility

## Recent Changes (June 16, 2025)
- **Post-ceremony transformation:** Removed ceremony date, time, and map buttons
- **Added memorial video hero section:** Placeholder for memorial service recording with 16:9 responsive video player
- **Preserved emotional color system:** All dynamic color transitions intact
- **Cleaned unused code:** Removed map functionality and related imports
- **Updated content focus:** Shifted from event announcement to permanent memorial
- **Implemented site-wide wake lock:** Screen stays awake throughout entire memorial website visit for uninterrupted viewing experience

## Key Features
1. **Emotional Color Palette System**
   - Automatic mood detection based on quote keywords
   - Smooth 1-second transitions between 5 distinct color schemes
   - Dynamic backgrounds, cards, buttons, and text colors
   - No visible mood labels for clean user experience

2. **Quote Carousel**
   - 10-second auto-rotation
   - Manual navigation with subtle dots
   - Author attribution
   - Responsive typography

3. **Memorial Video Section**
   - Hero video placeholder ready for memorial service recording
   - 16:9 aspect ratio responsive container
   - Descriptive text about the memorial service
   - Integrates with dynamic color system

4. **Site-wide Wake Lock System**
   - Prevents screen sleep throughout entire memorial website visit
   - Automatically reactivates when page becomes visible after tab switching
   - Graceful fallback for browsers without wake lock support
   - Enhanced memorial viewing experience without interruption

5. **Responsive Design**
   - Mobile-first approach
   - Cross-device compatibility (iOS/Android, Chrome/Safari)
   - Touch-friendly navigation
   - Optimized typography scaling

## User Preferences
- Prefers clean, minimal design without clutter
- Values emotional resonance and respectful presentation
- Wants seamless color transitions without visible mood indicators
- Appreciates subtle navigation elements
- Requests responsive design for family access across devices

## Development Guidelines
- Follow fullstack_js guidelines for consistent architecture
- Use in-memory storage (MemStorage) unless database explicitly requested
- Maintain emotional color palette functionality in all UI updates
- Preserve 10-second quote carousel timing
- Keep responsive design principles for all new features
- Test across mobile and desktop breakpoints

## Next Steps
- User can upload memorial video file to replace placeholder
- Video integration requires updating video source path in memorial.tsx
- Consider adding photo gallery or tribute messages if requested