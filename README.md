
<body>

<h1>Voice AI Assistant using LiveKit</h1>
<p><em>Infosys Springboard Internship Project</em></p>

<h2>Overview</h2>
<p>A real-time voice AI assistant built using <strong>LiveKit</strong>, <strong>Deepgram</strong>, and <strong>Google Gemini LLM</strong>.</p>
<ul>
    <li>Converts speech to text (STT)</li>
    <li>Generates AI responses (LLM)</li>
    <li>Speaks back responses (TTS)</li>
    <li>Handles noise and detects voice activity</li>
</ul>

<h2>Features</h2>
<ul>
    <li>Real-time conversation</li>
    <li>Multi-language support</li>
    <li>Noise cancellation</li>
    <li>Optional turn detection</li>
</ul>

<h2>Setup</h2>
<p>Install dependencies:</p>
<pre><code>pip install "livekit-agents[deepgram,google,silero]~=1.2"
pip install livekit-plugins-noise-cancellation
pip install livekit-plugins-turn-detector

</code></pre>

<p>Create a <code>.env</code> file with your LiveKit credentials:</p>
<pre><code>LIVEKIT_URL=wss://&lt;your-project&gt;.livekit.cloud
LIVEKIT_API_KEY=&lt;your-api-key&gt;
LIVEKIT_API_SECRET=&lt;your-api-secret&gt;</code></pre>

<h2>Run</h2>
<pre><code>python assistant.py dev

</code></pre>

<p>Join the room in <a href="https://agents-playground.livekit.io/" target="_blank">LiveKit Playground</a></p>

<h2>Project Structure</h2>
<pre><code>
assistant.py        # Main agent
.env                # Credentials
</code></pre>


</body>
