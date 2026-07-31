<h1 class="typing-header">Hey, I'm Saaket</h1>

<div class="fade-in-text">
  <p>I am an undergraduate Computer Science student minoring in Computational Mathematics and Computer Engineering.</p>
  <p>My interests lie in Computer Architecture, Systems Programming, Scientific AI/ML, and Optimization.</p>
  <p>I am currently exploring Physics Informed Neural Networks (PINNs).</p>
  <p>Check out my <a href="#">PINN repo</a> to see some of the experiments and work I have done with them.</p>
</div>

<style>
  /* Header Typing Effect */
  .typing-header {
    font-family: monospace;
    overflow: hidden;
    white-space: nowrap;
    border-right: 3px solid #007acc;
    width: 0;
    animation: 
      typing 2s steps(15, end) forwards,
      blink 0.75s step-end infinite alternate;
  }

  /* Body Content Fade-In */
  .fade-in-text {
    opacity: 0;
    animation: fadeIn 1.5s ease-in forwards;
    animation-delay: 2.2s; /* Waits for typing to finish */
  }

  /* Animations */
  @keyframes typing {
    from { width: 0 }
    to { width: 15ch; } /* Exact character count of "Hey, I'm Saaket" */
  }

  @keyframes blink {
    50% { border-color: transparent }
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>
