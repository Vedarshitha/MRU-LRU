MRU-LRU Cache Visualizer 🚀

Overview 📝
The MRU-LRU Cache Visualizer is an interactive web-based tool that helps users understand how Most Recently Used (MRU) and Least Recently Used (LRU) cache replacement policies work. This project provides a hands-on approach to visualize cache operations dynamically.

Features ✨
✅ Set a custom cache size based on user input.
✅ Add elements using the Put operation.
✅ Retrieve elements using the Get operation.
✅ Highlight MRU (Most Recently Used) elements in 🟩 green.
✅ Highlight LRU (Least Recently Used) elements in 🔴 red.
✅ Automatically evict the LRU element when the cache is full.
✅ Fully interactive UI with real-time cache updates.

How It Works 🔍
🔹 Set Cache Size – Defines the maximum number of elements the cache can store.
🔹 Put Operation – Adds an element to the cache. If the element already exists, it moves to the MRU position. If the cache is full, the LRU element is removed.
🔹 Get Operation – Checks if an element exists in the cache. If found, it moves to the MRU position, representing recent usage. If not found, it's a cache miss.

Project Structure 📂
📁 MRU-LRU
├── 📄 index.html – Main HTML file with cache visualization
├── 🎨 style.css – (Optional) Separate CSS file for styling
├── 🖥️ script.js – JavaScript file for cache operations
├── 📜 README.md – Project Documentation

Technologies Used 💻
-HTML
-CSS
-JavaScript
