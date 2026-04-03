# Personal Portfolio Website

A pixel-perfect clone of a minimalist portfolio website design. Clean, modern, and fully responsive with dark mode support.

## Features

- ✨ Minimalist design
- 🌓 Dark mode with system preference detection
- 📱 Fully responsive
- 🎨 Smooth hover animations
- ⚡ Lightweight and fast

## Customization

### 1. Update Your Information

Open `index.html` and replace the placeholder content:

- **Name**: Change "Your Name" to your actual name
- **Location**: Update "your location" to your city/location
- **Project**: Update the "your-project.com" link with your project URL
- **Experiments**: Add your projects in the experiments section
- **Writing**: Add your blog posts/articles in the writing section

### 2. Add More Projects

To add more projects to the experiments section, copy this structure:

```html
<li class="py-2 text-neutral-700 dark:text-neutral-300">
    <a class="group flex flex-col gap-1 hover:outline-[0.5px] outline-offset-[6px] hover:outline-neutral-400/50 dark:hover:outline-neutral-600/50 hover:[&>div>h3]:text-neutral-900 dark:hover:[&>div>h3]:text-white hover:[&>div>span]:text-neutral-900 dark:hover:[&>div>span]:text-white border-0 relative" href="#">
        <div class="cross-top-left absolute left-[-6.25px] top-[-6.25px] hidden group-hover:block">
            <div class="cross-vertical absolute left-0 top-0 h-[10px] w-[0.5px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
            <div class="cross-horizontal absolute left-0 top-0 h-[0.5px] w-[10px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
        </div>
        <div class="cross-bottom-right absolute bottom-[-6.25px] right-[-6.25px] hidden group-hover:block">
            <div class="cross-vertical absolute left-0 top-0 h-[10px] w-[0.5px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
            <div class="cross-horizontal absolute left-0 top-0 h-[0.5px] w-[10px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
        </div>
        <div class="flex items-center justify-between">
            <h3 class="font-medium text-neutral-800 dark:text-neutral-200 underline decoration-neutral-400/50 underline-offset-[3px] transition-colors">Project Name</h3>
            <span class="ml-1 whitespace-nowrap text-neutral-600 dark:text-neutral-500 transition-colors">2025</span>
        </div>
        <p class="text-sm text-neutral-600 dark:text-neutral-400 group-hover:text-neutral-700 dark:group-hover:text-neutral-300 transition-colors">Project description goes here.</p>
    </a>
</li>
```

### 3. Add More Blog Posts

To add more blog posts, copy this structure:

```html
<li class="py-2 text-neutral-700 dark:text-neutral-300">
    <a class="group flex items-center justify-between gap-1 hover:outline-[0.5px] outline-offset-[6px] hover:outline-neutral-400/50 dark:hover:outline-neutral-600/50 hover:[&>h3]:text-neutral-900 dark:hover:[&>h3]:text-white hover:[&>span]:text-neutral-900 dark:hover:[&>span]:text-white border-0 relative" href="#">
        <div class="cross-top-left absolute left-[-6.25px] top-[-6.25px] hidden group-hover:block">
            <div class="cross-vertical absolute left-0 top-0 h-[10px] w-[0.5px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
            <div class="cross-horizontal absolute left-0 top-0 h-[0.5px] w-[10px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
        </div>
        <div class="cross-bottom-right absolute bottom-[-6.25px] right-[-6.25px] hidden group-hover:block">
            <div class="cross-vertical absolute left-0 top-0 h-[10px] w-[0.5px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
            <div class="cross-horizontal absolute left-0 top-0 h-[0.5px] w-[10px] -translate-x-1/2 -translate-y-1/2 bg-neutral-400 dark:bg-neutral-500"></div>
        </div>
        <h3 class="grow font-medium text-neutral-800 dark:text-neutral-200 underline decoration-neutral-400/50 underline-offset-[3px] transition-colors">Blog Post Title</h3>
        <span class="ml-1 flex items-center gap-1 whitespace-nowrap transition-colors text-neutral-600 dark:text-neutral-400">
            <span>0</span> views • <span>Jan 1, 2025</span>
        </span>
    </a>
</li>
```

### 4. Customize Colors

Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --neutral-50: #fafafa;
    --neutral-100: #f5f5f5;
    /* ... more colors ... */
}
```

## Running the Website

1. Simply open `index.html` in your web browser
2. Or use a local server:
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve`
   - Then visit `http://localhost:8000`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Files Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles and themes
├── script.js       # Theme switcher functionality
└── README.md       # This file
```

## License

Feel free to use this template for your personal portfolio!

