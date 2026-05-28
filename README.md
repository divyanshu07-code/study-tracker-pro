# study-tracker-core
# Productivity & Study Workspace Dashboard

A high-performance, single-page web dashboard designed to track tasks, organize study workflows, and provide built-in focus tools using advanced browser APIs. 

## 🔗 Live Demo
👉 [Click Here to Launch the Live Workspace Dashboard] (https://divyanshu07-code.github.io/study-tracker-core/)


## 🚀 Key Features & Technical Architecture

Instead of relying on heavy frameworks or basic, slow storage methods, this project is built entirely using vanilla web technologies and low-level browser APIs to ensure high performance:

* **Transactional Database (IndexedDB):** Moving past standard `localStorage` (which can slow down browsers and has very strict storage limits), this application uses a structured **IndexedDB object store**. This allows safe, asynchronous data persistence for thousands of tasks and subtasks without freezing the UI.
* **Custom Analytics Engine (HTML5 Canvas):** The visual progress tracking system is drawn directly onto an **HTML5 Canvas element**. It utilizes a `ResizeObserver` mapped to the screen's hardware Device Pixel Ratio (DPR) to ensure charts look perfectly sharp on any monitor or mobile device.
* **Dynamic Audio Synthesis (Web Audio API):** The focus background noise feature doesn't rely on downloading massive, slow-loading audio files. Instead, it uses the browser's native **Web Audio API** to mathematically synthesize sound waves (like white noise and pink noise) directly through audio nodes in real time.
* **Fluid Workflow Management:** Features full state tracking categorized across multiple productivity registers (Backlog, Active Processing, and Completed Outflows) combined with fast multi-parameter filtering and search controls.

---

## 🛠️ How to Run This Project

Since this entire system is optimized into a single, self-contained `index.html` file, it runs natively in any web browser. No installations, servers, or terminal commands are required.

* **Live Version:** Simply click the live link at the top of this page to use the workspace instantly.
* **Local Version:** Download the `index.html` file directly to your computer and double-click it to open it in Chrome, Brave, Safari, or Firefox.
   
