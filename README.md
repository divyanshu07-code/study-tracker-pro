# Study Tracker Pro 🚀

### Smart Study Management System & High-Performance Workspace

A high-performance, single-page web dashboard designed to track tasks, organize complex study workflows, and provide built-in focus tools using low-level browser APIs. 

🔗 **[Launch the Live Workspace Dashboard](https://divyanshu07-code.github.io/study-tracker-pro/)**

---

## 🛠️ Key Features & Technical Architecture

Instead of relying on heavy frameworks or basic, blocking storage methods, this project is built entirely using vanilla web technologies and low-level browser APIs to ensure maximum performance and zero external dependencies:

* **Transactional Database (IndexedDB Pipeline):** Moving past standard `localStorage` (which blocks the main thread and has strict 5MB limits), this application implements a structured **IndexedDB object store**. This allows safe, asynchronous data persistence for thousands of tasks, checkpoint milestones, and logs without freezing the user interface.
* **Custom Analytics Engine (HTML5 Canvas):** The visual progress tracking and telemetry graph system is drawn directly onto an HTML5 Canvas element. It utilizes a `ResizeObserver` mapped to the display's hardware Device Pixel Ratio (DPR) to ensure line vectors look perfectly crisp on high-density monitors and mobile devices.
* **Dynamic Audio Synthesis (Web Audio API):** The built-in ambient focus machine doesn't rely on downloading massive, slow-loading MP3 audio files. Instead, it leverages the native **Web Audio API** to mathematically synthesize sound waves (such as white noise, pink noise, and focus tones) directly through mathematical oscillators and audio nodes in real time. It also features a real-time frequency visualizer.
* **Fluid Workflow Management:** Features full state tracking categorized across multiple productivity views (**List View** and a drag-and-drop **Kanban Board**) combined with fast multi-parameter filtering, custom subject tags, and keyword search controls.

## 🎮 How to Run This Project

Since this entire system is optimized into a single, self-contained `index.html` file, it runs natively in any modern web browser. No complex installations, local servers, or terminal build commands are required.

### Option 1: Live Version (Recommended)
Simply click the live link at the top of this page to use the workspace instantly.

### Option 2: Running Locally
1. **Clone the repository** or download the `index.html` file directly to your machine:
   ```bash
   git clone [https://github.com/divyanshu07-code/study-tracker-core.git](https://github.com/divyanshu07-code/study-tracker-core.git)

   ```
 ---
Author
Divyanshu

Web Development Enthusiast | Problem Solver


Thank you for visiting the repository.

If you like this project, consider giving it a ⭐ and sharing your feedback.
