# 🎨 GitHub Profile Customization Guide

This document explains how to customize your GitHub profile README with animations and dynamic content.

## 🚀 Features Included

### 1. Animated Typing Header
- Uses `readme-typing-svg` for animated text
- Customizable messages, colors, and timing
- Multiple lines with rotation effect

### 2. Dynamic GitHub Statistics
- **GitHub Stats**: Shows commits, PRs, issues, stars
- **Language Stats**: Most used programming languages
- **Streak Stats**: Contribution streak information
- **Activity Graph**: Contribution activity over time

### 3. Animated Snake Game
- Generated from your GitHub contributions
- Updates automatically via GitHub Actions
- Supports light/dark theme variants

### 4. Technology Stack Badges
- Colorful shields for technologies you use
- Organized by categories (Frontend, Backend, DevOps, etc.)
- Easy to add/remove technologies

### 5. Automated Updates
- GitHub Actions workflows for regular updates
- Snake animation regeneration
- Activity feed updates

## 🔧 Customization Instructions

### Update Personal Information
1. Replace `Adhwapw` with your GitHub username throughout the README
2. Update the bio information in the TypeScript code block
3. Modify the technology stack to match your skills
4. Update social media links

### Customize Colors and Themes
- **Stats Theme**: Change `theme=radical` to other themes like `dark`, `tokyonight`, `dracula`
- **Typing Animation**: Modify the `color` parameter in the typing SVG URL
- **Badges**: Update badge colors using the shield.io color scheme

### Add New Sections
You can add additional sections like:
- Blog posts integration
- Spotify playing status
- Custom widgets
- Project showcases

## 🔄 GitHub Actions Workflows

### Snake Animation (`snake.yml`)
- Runs every 24 hours
- Generates contribution snake game
- Pushes to `output` branch

### Profile Stats (`update-stats.yml`)
- Runs every 6 hours
- Updates recent activity
- Optional WakaTime integration (requires API key)

## 📝 Setup Requirements

1. **Repository Name**: Must be named same as your username (e.g., `username/username`)
2. **Repository Visibility**: Must be public
3. **GitHub Actions**: Enable Actions in repository settings
4. **Permissions**: Ensure Actions have write permissions

## 🎯 Optional Integrations

### WakaTime Integration
1. Sign up for [WakaTime](https://wakatime.com/)
2. Get your API key
3. Add `WAKATIME_API_KEY` to repository secrets
4. Uncomment WakaTime sections in the workflow

### Blog Integration
Add RSS feed integration to show latest blog posts automatically.

## 🔗 Resources Used

- [Typing SVG](https://github.com/DenverCoder1/readme-typing-svg)
- [GitHub Stats](https://github.com/anuraghazra/github-readme-stats)
- [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [Activity Graph](https://github.com/Ashutosh00710/github-readme-activity-graph)
- [Snake Game](https://github.com/Platane/snk)
- [Shields Badges](https://shields.io/)
- [GitHub Trophies](https://github.com/ryo-ma/github-profile-trophy)

## 🎨 Tips for Great Profiles

1. **Keep it Clean**: Don't overcrowd with too many elements
2. **Personal Touch**: Add unique sections that reflect your personality
3. **Regular Updates**: Keep content fresh and relevant
4. **Mobile Friendly**: Test how it looks on different screen sizes
5. **Loading Speed**: Be mindful of too many external resources

## 🔧 Troubleshooting

### Snake Animation Not Showing
- Check if Actions are enabled
- Verify the `output` branch exists
- Check workflow logs for errors

### Stats Not Loading
- Verify username is correct
- Check if repository is public
- API might be rate-limited (wait and retry)

### Typing Animation Issues
- Check URL encoding in the typing SVG
- Verify text parameters are properly formatted

---

Happy coding! 🚀