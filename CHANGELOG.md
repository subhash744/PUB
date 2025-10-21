# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased] - 2025-10-21

### Added
- **Login Requirement for Leaderboard**: Users must now be logged in to view the leaderboard
- **Centered Hall of Fame Header**: Title and description are now centered for better visual hierarchy
- **Always Visible Profile Details**: Profile names and bios now display by default in Hall of Fame (no hover required)
- **Production Readiness Guide**: Comprehensive `PRODUCTION-READINESS.md` document listing all placeholders and required changes

### Changed
- Leaderboard page now shows a login prompt for unauthenticated users
- Hall of Fame profile cards always show user information (previously hidden until hover)
- Hall of Fame title section is now centered instead of left-aligned

### Fixed
- Prevented automatic mock data login on leaderboard access
- Improved user experience by showing profile details immediately

### Documentation
- Added detailed placeholder list for production deployment
- Documented required backend changes (database, authentication, storage)
- Listed all mock data that needs to be removed
- Created pre-launch checklist
- Added environment variable examples

## [Initial Release] - 2025-10-21

### Features
- User profile creation with 8-step wizard
- Dynamic leaderboard with weighted ranking algorithm
- Project showcase with analytics
- Upvote system with confetti animations
- Badge achievement system
- Hall of Fame gallery
- Analytics dashboard
- Mock data generation for testing
- Developer tools page

### Tech Stack
- Next.js 14 with App Router
- TypeScript
- Tailwind CSS
- Radix UI components
- localStorage for data persistence
- Recharts for analytics visualization
- Leaflet for map integration

---

**Note**: This is currently a development version with mock data. See [PRODUCTION-READINESS.md](file://d:\VM\New%20folder%20(22)\PRODUCTION-READINESS.md) before deploying to production.
