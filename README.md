## API Rate Limit Token Bucket Visualizer

Animates three classic rate-limiting algorithms in real time: Token Bucket (tokens refill steadily, each request consumes one), Leaky Bucket (requests queue and drain at a fixed rate), and Fixed Window (counter resets each window period). A canvas circle shows current fill level; a scrolling bar chart tracks accepted (green) vs rejected (red) requests.

**Tech:** Vanilla JS, requestAnimationFrame, HTML Canvas, Tailwind CSS CDN.  
**Usage:** Select a tab, adjust the three sliders, press Start/Pause to animate, Reset to clear counters.
