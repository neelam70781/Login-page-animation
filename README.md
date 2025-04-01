# Interactive Vintage Login Page with GSAP Animations

## Features
- ✨ Interactive form validation with visual feedback
- 🎨 Vintage paper aesthetic with subtle textures
- ⚙️ Complex mechanical animations using SVG and GSAP
- 🖱️ Physics-inspired interactions (gears, spray, pull systems)
- 📱 Responsive design (works on desktop/mobile)

## Technologies Used
- **GSAP 3** - Professional-grade animations
- **SVG** - Scalable vector graphics for all animations
- **CSS3** - Modern styling with vintage aesthetic
- **JavaScript** - Form validation and animation triggers

## Project Structure

### Key Files Breakdown:
1. **index.html**  
   - Contains the login form structure  
   - SVG markup for all mechanical animations  
   - GSAP library import  

2. **style.css**  
   - Vintage color scheme (sepia tones)  
   - Form input styling fixes  
   - Animation container positioning  

3. **script.js**  
   - `createGearsTimelines()` - Handles gear rotations  
   - `validateEmail()` - Email regex and spray trigger  
   - `updatePullSystem()` - Checkbox physics logic  

4. **assets/** (Optional)  
   - Store `vintage-paper.png` here if self-hosting  
   - Custom font files (e.g., vintage-style typefaces)

     
## How It Works
1. **Form Validation**:
   - Name field (>3 chars) triggers gear animations
   - Valid email format activates spray animation
   - Checkbox controls the pull mechanism

2. **Animation Systems**:
   - **Gear Mechanism**: Rotates when name is valid
   - **Spray System**: Activates on valid email
   - **Pull Physics**: Checkbox controls submit button position

## 🛠️ Setup Instructions

```bash
# 1. Download the project
git clone https://github.com/your-username/Login-Page-Animation.git
cd Login-Page-Animation

# 2. Open directly in browser
open index.html       # Mac
start index.html      # Windows
xdg-open index.html   # Linux
