<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Father's Day Card Generator</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 850px;
            margin: 0 auto;
            padding: 30px;
            background-color: #fafafa;
        }
        .container {
            background: #ffffff;
            padding: 40px;
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        h1 {
            color: #1e3a8a;
            border-bottom: 2px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 0;
        }
        h2 {
            color: #1e40af;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 1.5em;
        }
        h3 {
            color: #334155;
        }
        code {
            background-color: rgba(27, 31, 35, 0.05);
            padding: 0.2em 0.4em;
            border-radius: 3px;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
            font-size: 85%;
        }
        pre {
            background-color: #f6f8fa;
            padding: 16px;
            border-radius: 6px;
            overflow: auto;
            border: 1px solid #e1e4e8;
        }
        pre code {
            background-color: transparent;
            padding: 0;
            font-size: 90%;
        }
        ul {
            padding-left: 20px;
        }
        li {
            margin-bottom: 0.5em;
        }
        .badge {
            display: inline-block;
            padding: 4px 8px;
            font-size: 12px;
            font-weight: 600;
            color: #fff;
            background-color: #1e3a8a;
            border-radius: 20px;
            margin-right: 5px;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Father's Day Card Generator</h1>
    <p>A lightweight, responsive, single-file frontend web application designed to create customized, high-quality greetings for Father's Day. This project is optimized to run seamlessly as a standalone tool or integrated into a custom light theme layout.</p>

    <div>
        <span class="badge">HTML5 Canvas</span>
        <span class="badge">Vanilla JavaScript</span>
        <span class="badge">CSS3 Grid & Flexbox</span>
        <span class="badge">Zero Dependencies</span>
    </div>

    <h2>🚀 Features</h2>
    <ul>
        <li><strong>Dynamic Custom Typography:</strong> Users can input a personalized appreciation message with an automatic multi-line layout engine wrapping text perfectly within the canvas configuration.</li>
        <li><strong>Smart Image Crop Pipeline:</strong> Built-in <code>FileReader</code> image upload pipeline that automatically calculates a proportional layout vector to center and clip user-uploaded images into smooth, rounded rectangles.</li>
        <li><strong>Masculine Design Frameworks:</strong> Switch dynamically across 4 pre-configured color profiles:
            <ul>
                <li>Classic Navy</li>
                <li>Executive Gold</li>
                <li>Forest Minimal</li>
                <li>Vintage Charcoal</li>
            </ul>
        </li>
        <li><strong>Client-Side Processing:</strong> No server side requirements. Features a standalone image generation download bridge that renders and downloads high-quality 600x600 PNG images instantly.</li>
    </ul>

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li><strong>Structure:</strong> HTML5 semantic markup and layout wrapper interfaces.</li>
        <li><strong>Graphics Engine:</strong> HTML5 2D Context Canvas API (<code>CanvasRenderingContext2D</code>) handling high-contrast layouts and graphic border accents dynamically.</li>
        <li><strong>Styling:</strong> Embedded scoped CSS featuring fluid media queries targeting mobile breakpoints down to 480px.</li>
        <li><strong>Logic:</strong> Functional JavaScript handling canvas triggers, image upload states, and immediate text rendering pipelines.</li>
    </ul>

    <h2>📦 Quick Installation & Usage</h2>
    <p>Because this application contains zero dependencies, setup is instantaneous:</p>
    
    <ol>
        <li>Clone or download the project file.</li>
        <li>Save the code source package directly as an <code>.html</code> file (e.g., <code>index.html</code>).</li>
        <li>Double-click the file to launch it instantly in any modern web browser.</li>
    </ol>

    <h3>Integration Note</h3>
    <p>The layout styles are explicitly scoped under the wrapper class <code>.dad-maker-wrapper</code>, making it completely safe to copy and embed directly into content publishing networks like Blogger or WordPress text widgets without breaking parent page designs.</p>

    <h2>📄 License</h2>
    <p>This project is open-source and available under the MIT License.</p>
</div>

</body>
</html>
