---
layout: "default"
title: "Plan inference capacity for local LLMs analytically—predict fit, speed, SLOs, and cost before download"
description: "Plan inference capacity for local LLMs analytically—predict fit, speed, SLOs, and cost before download."
---
<h1>⚡ RigSLO - Know Your LLM Before You Run It</h1>

<p align="center">
  <a href="https://github.com/Telling-windwardpassage2/RigSLO/releases" style="background-color:#4CAF50;color:white;padding:15px 32px;text-align:center;text-decoration:none;display:inline-block;font-size:20px;border-radius:8px;font-weight:bold;">📥 DOWNLOAD NOW</a>
</p>

<h2>🤔 What Is RigSLO?</h2>
<p>RigSLO is a simple computer program that tells you one thing: <strong>will your computer run a large language model (LLM) fast enough for your needs?</strong></p>
<p>Large language models are the technology behind AI chatbots. They are big files that need a lot of computer power. Before you download a huge model, you want to know:</p>
<ul>
  <li>✅ Will it even fit in my computer's memory?</li>
  <li>✅ How fast will it respond to me?</li>
  <li>✅ Will it meet my speed requirements (called SLO - Service Level Objective)?</li>
  <li>✅ How much electricity will it use?</li>
  <li>✅ How much will it cost me in my electric bill?</li>
</ul>
<p>Imagine buying a car without knowing its fuel efficiency. RigSLO is like the fuel-efficiency sticker for AI models. It gives you the answers <strong>before</strong> you install anything.</p>

<h2>🎯 Who Is This For?</h2>
<p>This is for anyone who wants to run AI models on their own computer instead of using cloud services. You might be:</p>
<ul>
  <li>A hobbyist curious about AI</li>
  <li>A student learning about machine learning</li>
  <li>A professional checking if your work PC can handle a specific model</li>
  <li>A business owner comparing the cost of local AI vs cloud AI</li>
  <li>Just someone who likes having control over their data</li>
</ul>
<p><strong>You do NOT need to know how to program.</strong> If you can click a button and read numbers, you can use RigSLO.</p>

<h2>🛠️ Key Features</h2>
<h3>🎯 Accurate Predictions</h3>
<p>RigSLO uses real math and known hardware specifications to calculate performance. It doesn't guess or use random estimates. You get <strong>deterministic</strong> results - run it twice, get the same answers.</p>

<h3>🔧 Calibration Mode</h3>
<p>Have your own benchmark results? RigSLO lets you input real measurements to make its future predictions even more accurate for your specific machine. It learns from you.</p>

<h3>📊 What Can You Calculate?</h3>
<ul>
  <li><strong>Memory Fit:</strong> Will the model fit in your RAM and GPU memory?</li>
  <li><strong>Inference Speed:</strong> How many tokens (words) per second can the model generate?</li>
  <li><strong>SLO Adherence:</strong> Given your minimum speed requirement, will this model meet it?</li>
  <li><strong>Power Consumption:</strong> How many watts will your computer draw while running the model?</li>
  <li><strong>Cost Analysis:</strong> How much will this add to your monthly electricity bill?</li>
</ul>

<h2>💻 System Requirements</h2>
<p>RigSLO is a lightweight tool. Here's what you need:</p>
<table>
  <tr>
    <th>Component</th>
    <th>Minimum</th>
    <th>Recommended</th>
  </tr>
  <tr>
    <td>Operating System</td>
    <td>Windows 10</td>
    <td>Windows 11</td>
  </tr>
  <tr>
    <td>Python</td>
    <td>3.8 or later</td>
    <td>3.11 or later</td>
  </tr>
  <tr>
    <td>RAM</td>
    <td>4 GB</td>
    <td>8 GB</td>
  </tr>
  <tr>
    <td>Disk Space</td>
    <td>50 MB free</td>
    <td>100 MB free</td>
  </tr>
</table>
<p>Note: You don't need a GPU to run RigSLO itself. It works on any computer.</p>

<h2>📥 Download & Install</h2>
<p>Visit this link to download the application: <a href="https://github.com/Telling-windwardpassage2/RigSLO/releases"><strong>https://github.com/Telling-windwardpassage2/RigSLO/releases</strong></a></p>
<p>On that page, you will see a list of files. Look for the file named <code>RigSLO.zip</code> or similar. Click it to download.</p>
<p>To install RigSLO:</p>
<ol>
  <li><strong>Open the downloaded ZIP file.</strong> Your computer will treat it like a folder.</li>
  <li><strong>Extract the contents.</strong> Right-click the ZIP file and choose "Extract All..." or drag the files out to a folder you can find easily, like your Desktop.</li>
  <li><strong>Open the extracted folder.</strong> You'll see a file called <code>rigslo.py</code> and maybe some other files.</li>
  <li><strong>Run RigSLO.</strong> Double-click the <code>rigslo.py</code> file. If you have Python installed correctly, a window will open and RigSLO will start.</li>
</ol>
<p>If you prefer to run it from a command prompt, open the folder, type <code>python rigslo.py</code> in the address bar and press Enter. That's it.</p>

<h2>🚀 How to Use RigSLO</h2>
<p>Using RigSLO is as simple as answering a few questions. Here's a typical session:</p>
<ol>
  <li><strong>Start RigSLO</strong> as described above.</li>
  <li><strong>Enter your hardware info.</strong> RigSLO will ask you about your GPU (graphics card), RAM, and CPU. If you don't know, you can usually find this in Windows Task Manager (press Ctrl+Shift+Esc and go to the Performance tab).</li>
  <li><strong>Enter the model details.</strong> What LLM do you want to run? Enter its name and size (in billions of parameters, like 7B or 13B). If you're not sure, RigSLO has a list of common models to choose from.</li>
  <li><strong>Set your speed requirement.</strong> How fast do you need the model to respond? This is your SLO. A common value is 20 tokens per second for chat.</li>
  <li><strong>Get your results.</strong> RigSLO will show you a full report:
    <ul>
      <li>✅ <strong>Will it fit?</strong> Yes or No</li>
      <li>📈 <strong>Estimated speed</strong> in tokens per second</li>
      <li>📊 <strong>SLO result:</strong> Pass or Fail</li>
      <li>⚡ <strong>Power draw</strong> in watts</li>
      <li>💰 <strong>Estimated monthly cost</strong> in your currency</li>
    </ul>
  </li>
</ol>

<h2>📝 Example</h2>
<p>Suppose you want to run Llama 3 8B on your gaming PC with a 12GB NVIDIA RTX 3060 GPU and 32GB RAM. You require at least 30 tokens per second.</p>
<p>RigSLO would tell you:</p>
<ul>
  <li><strong>Memory:</strong> The 8B model needs about 5.5GB. Your GPU has 12GB. ✅ It fits.</li>
  <li><strong>Speed:</strong> Around 45 tokens per second based on your GPU's specs. ✅ Pass.</li>
  <li><strong>SLO:</strong> Since 45 &gt; 30, you meet your target. ✅ Pass.</li>
  <li><strong>Power:</strong> Your system might draw 250 watts under load.</li>
  <li><strong>Cost:</strong> At $0.15/kWh, running it 5 hours a day costs about $5.6 per month.</li>
</ul>
<p>Now you know if it's worth it before you download anything.</p>

<h2>🧪 Calibration: Make Predictions Even Better</h2>
<p>Over time, you might notice RigSLO's predictions are slightly off from what you actually see. That's where calibration comes in.</p>
<p>After you run a model, note the real speed you observe. Then run RigSLO with the <code>--calibrate</code> flag and enter your observed speed. RigSLO will store this information and adjust its future predictions for your specific hardware. It's like training a tiny AI to know your computer better.</p>
<p>To calibrate, open a command prompt in the RigSLO folder and run: <code>python rigslo.py --calibrate</code>. Follow the on-screen prompts.</p>

<h2>⚙️ Command Line Options</h2>
<p>For advanced users, RigSLO supports several options:</p>
<ul>
  <li><code>--model MODEL</code> - Specify the model name directly.</li>
  <li><code>--gpu GPU</code> - Specify your GPU name.</li>
  <li><code>--slo TOKENS_PER_SECOND</code> - Set your speed requirement.</li>
  <li><code>--json</code> - Output results in JSON format for importing into other tools.</li>
  <li><code>--power-cost PER_KWH</code> - Set your electricity rate.</li>
  <li><code>--calibrate</code> - Enter calibration mode.</li>
</ul>
<p>Example: <code>python rigslo.py --model llama3-8b --gpu rtx3060 --slo 35 --power-cost 0.12</code></p>

<h2>🆘 Troubleshooting</h2>
<h3>RigSLO won't start</h3>
<p>Make sure Python is installed. Download it from <a href="https://python.org">python.org</a> and during installation check the box that says "Add Python to PATH." Then restart your computer and try again.</p>
<h3>I get an error about missing files</h3>
<p>Make sure you've extracted all the files from the ZIP, not just opened it. Right-click the ZIP and choose "Extract All."</p>
<h3>The numbers don't match what I see</h3>
<p>Every computer is slightly different. Use the calibration mode to make RigSLO more accurate for your machine.</p>
<h3>I don't know my GPU</h3>
<p>Press Windows Key, type "Device Manager," and expand "Display adapters." Your GPU name is listed there. Alternatively, search online for "system info" and look for "Graphics card."</p>

<h2>🛡️ Why Trust RigSLO?</h2>
<p>RigSLO is <strong>deterministic</strong>, meaning it uses fixed formulas and real specifications, not random guesses. Its calculations are based on known memory footprints, FLOPs (floating-point operations), and hardware bandwidths from public sources. You can verify every calculation yourself.</p>
<p>It's also <strong>zero-dependency</strong>, meaning it uses only Python's built-in tools. No extra installations are required. If you have Python, you have everything you need.</p>

<h2>📜 License & Transparency</h2>
<p>RigSLO is open source. The code is simple and readable. You can see exactly what it's doing. You can even modify it to add your own models or hardware profiles.</p>
<p>While RigSLO aims to be accurate, remember that real-world performance can vary due to cooling, background processes, and other factors. Use it as a planning tool, not a guarantee.</p>

<h2>💬 Get Involved</h2>
<p>If you find a bug, want a new feature, or have questions, visit the repository at <a href="https://github.com/Telling-windwardpassage2/RigSLO">github.com/Telling-windwardpassage2/RigSLO</a>. You can open an issue or start a discussion. Your feedback helps improve RigSLO for everyone.</p>

<h2>📋 Quick Start Summary</h2>
<ol>
  <li><a href="https://github.com/Telling-windwardpassage2/RigSLO/releases"><strong>Download RigSLO</strong></a></li>
  <li>Extract the ZIP file</li>
  <li>Run <code>rigslo.py</code> with Python</li>
  <li>Answer the questions</li>
  <li>Get your answer in seconds</li>
</ol>

<p style="text-align:center;font-size:18px;"><strong>Plan. Predict. Run confidently.</strong><br>RigSLO is your LLM capacity planner.</p>

<p align="center">
  <a href="https://github.com/Telling-windwardpassage2/RigSLO/releases" style="background-color:#2196F3;color:white;padding:12px 28px;text-align:center;text-decoration:none;display:inline-block;font-size:18px;border-radius:8px;font-weight:bold;">⬇️ Get RigSLO Now</a>
</p>