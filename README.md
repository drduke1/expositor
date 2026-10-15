<html lang="en" class="dark scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Technical Documentation | Expositor | Clarifier</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#ecfdf5',
              400: '#34d399',
              500: '#10b981',
              600: '#059669',
              900: '#064e3b',
              950: '#022c22'
            }
          },
          fontFamily: {
            sans: ['Inter', 'system-ui', 'sans-serif'],
            mono: ['JetBrains Mono', 'Fira Code', 'monospace'],
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; }
    code, pre { font-family: 'JetBrains Mono', monospace; }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 antialiased min-h-screen flex flex-col selection:bg-emerald-500/30 selection:text-emerald-200">

  <!-- Fixed Header Navbar -->
  <header class="border-b border-slate-800/80 bg-slate-950/90 backdrop-blur-md sticky top-0 z-50">
    <div class="max-w-4xl mx-auto px-6 h-16 flex items-center justify-between">
      <a href="#" class="flex items-center space-x-3 group">
        <span class="inline-block w-2.5 h-2.5 rounded-full bg-emerald-500 animate-pulse group-hover:scale-125 transition-transform"></span>
        <span class="font-mono text-sm font-semibold tracking-tight text-slate-200 group-hover:text-emerald-400 transition-colors">doc-consultant.io</span>
      </a>
      <nav class="flex items-center space-x-4 sm:space-x-6 text-xs sm:text-sm font-medium">
        <a href="#expertise" class="text-slate-400 hover:text-emerald-400 transition-colors">Domain Focus</a>
        <a href="#sample-work" class="text-slate-400 hover:text-emerald-400 transition-colors">Sample Work</a>
        <a href="#scopes" class="text-slate-400 hover:text-emerald-400 transition-colors">Scopes</a>
        <a href="#contact" class="px-3 py-1.5 rounded-md bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 hover:bg-emerald-500/20 transition-all font-mono text-xs">Contact</a>
      </nav>
    </div>
  </header>

  <main class="flex-grow max-w-4xl mx-auto px-6 py-10 space-y-16">

    <!-- Hero Section -->
    <section class="space-y-6 pt-2">
      <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-slate-900 border border-slate-800 text-xs font-mono text-slate-300">
        <span class="text-emerald-400">●</span>
        <span>Staff Technical Writer</span>
        <span class="text-slate-600">|</span>
        <span class="text-slate-400">Taking on 1–2 small projects per month</span>
      </div>

      <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight text-white leading-tight">
        Clear, accurate technical documentation for <span class="text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 to-cyan-400">complex engineering systems</span> & <span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-400">AI search</span>.
      </h1>

      <p class="text-slate-300 text-base sm:text-lg leading-relaxed max-w-3xl">
        I’m a Staff Technical Writer specializing in observability, cybersecurity, telemetry data pipelines, and developer tooling. I help tech companies document new releases, build clean doc suites from scratch, and structure technical content for both human engineers and LLM retrieval (RAG) systems.
      </p>

      <div class="pt-2 flex flex-wrap gap-3 text-xs sm:text-sm font-mono text-slate-300">
        <div class="flex items-center space-x-2 bg-slate-900/80 px-3.5 py-2 rounded-md border border-slate-800">
          <svg class="w-4 h-4 text-emerald-400 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
          <span>Short-term contracts</span>
        </div>
        <div class="flex items-center space-x-2 bg-slate-900/80 px-3.5 py-2 rounded-md border border-slate-800">
          <svg class="w-4 h-4 text-emerald-400 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
          <span>Fixed-scope deliverables</span>
        </div>
        <div class="flex items-center space-x-2 bg-slate-900/80 px-3.5 py-2 rounded-md border border-slate-800">
          <svg class="w-4 h-4 text-emerald-400 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
          <span>Zero onboarding overhead</span>
        </div>
      </div>
    </section>

    <hr class="border-slate-800/80">

    <!-- Domain Expertise Grid (4 Cards) -->
    <section id="expertise" class="space-y-6">
      <div>
        <h2 class="text-xs font-mono uppercase tracking-wider text-emerald-400 font-semibold mb-1">Domain Focus</h2>
        <h3 class="text-2xl font-bold text-white">Areas of Technical Expertise</h3>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <!-- Card 1 -->
        <div class="p-6 rounded-xl bg-slate-900/50 border border-slate-800/90 hover:border-emerald-500/40 transition-all duration-200 space-y-2 group">
          <div class="text-emerald-400 font-mono text-xs font-semibold uppercase tracking-wider">01. Observability & Telemetry Pipelines</div>
          <h4 class="text-white font-semibold text-base group-hover:text-emerald-300 transition-colors">Logs, Metrics, Traces & SIEM Data</h4>
          <p class="text-slate-400 text-sm leading-relaxed">
            Documenting complex data routing engines, telemetry processors, log transformers, OpenTelemetry setups, and enterprise SIEM ingest pipelines.
          </p>
        </div>

        <!-- Card 2 -->
        <div class="p-6 rounded-xl bg-slate-900/50 border border-slate-800/90 hover:border-emerald-500/40 transition-all duration-200 space-y-2 group">
          <div class="text-emerald-400 font-mono text-xs font-semibold uppercase tracking-wider">02. Cybersecurity & Threat Intel</div>
          <h4 class="text-white font-semibold text-base group-hover:text-emerald-300 transition-colors">SecOps, Rules & Agent Deployments</h4>
          <p class="text-slate-400 text-sm leading-relaxed">
            Structuring clear guides for threat detection rule formats, endpoint security agent configurations, vulnerability scanning, and incident workflows.
          </p>
        </div>

        <!-- Card 3 -->
        <div class="p-6 rounded-xl bg-slate-900/50 border border-slate-800/90 hover:border-emerald-500/40 transition-all duration-200 space-y-2 group">
          <div class="text-emerald-400 font-mono text-xs font-semibold uppercase tracking-wider">03. Developer Experience & APIs</div>
          <h4 class="text-white font-semibold text-base group-hover:text-emerald-300 transition-colors">REST APIs, SDKs & Quickstarts</h4>
          <p class="text-slate-400 text-sm leading-relaxed">
            Designing quickstarts that work on the first try, authentication guides, SDK documentation, and OpenAPI specs that reduce time-to-hello-world.
          </p>
        </div>

        <!-- Card 4 -->
        <div class="p-6 rounded-xl bg-slate-900/50 border border-slate-800/90 hover:border-emerald-500/40 transition-all duration-200 space-y-2 group">
          <div class="text-emerald-400 font-mono text-xs font-semibold uppercase tracking-wider">04. AI-Ready Docs & Context Engineering</div>
          <h4 class="text-white font-semibold text-base group-hover:text-emerald-300 transition-colors">RAG Optimization & Semantic Schemas</h4>
          <p class="text-slate-400 text-sm leading-relaxed">
            Structuring Markdown taxonomy, semantic headings, metadata schemas, and explicit context so LLMs and retrieval agents query your docs without hallucinating.
          </p>
        </div>
      </div>
    </section>

    <hr class="border-slate-800/80">

    <!-- Interactive Sample Work / Code Refactoring -->
    <section id="sample-work" class="space-y-6">
      <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-2">
        <div>
          <h2 class="text-xs font-mono uppercase tracking-wider text-emerald-400 font-semibold mb-1">Interactive Transformation</h2>
          <h3 class="text-2xl font-bold text-white">Before & After Doc Refactor</h3>
        </div>
        <p class="text-xs text-slate-400 font-mono">Toggle options below to inspect changes</p>
      </div>

      <p class="text-slate-300 text-sm leading-relaxed">
        Wall-of-text documentation leads to high ticket volumes and fails RAG chunking algorithms. See how raw, ambiguous developer notes get transformed into structured, human-friendly, and LLM-ready technical documentation:
      </p>

      <!-- Toggle Container -->
      <div class="rounded-xl bg-slate-900 border border-slate-800 overflow-hidden shadow-2xl">
        <!-- Tab Controls -->
        <div class="flex flex-wrap border-b border-slate-800 bg-slate-950/80 p-2 gap-2 text-xs font-mono">
          <button id="tab-btn-before" onclick="setDocTab('before')" class="px-3.5 py-1.5 rounded-md font-medium bg-red-500/20 border border-red-500/40 text-red-300 transition-all flex items-center space-x-1.5">
            <span class="w-2 h-2 rounded-full bg-red-400"></span>
            <span>Legacy / Raw Notes</span>
          </button>
          <button id="tab-btn-after" onclick="setDocTab('after')" class="px-3.5 py-1.5 rounded-md font-medium text-slate-400 hover:text-white transition-all flex items-center space-x-1.5">
            <span class="w-2 h-2 rounded-full bg-emerald-400"></span>
            <span>Refactored & AI-Ready</span>
          </button>
          <button id="tab-btn-diff" onclick="setDocTab('diff')" class="px-3.5 py-1.5 rounded-md font-medium text-slate-400 hover:text-white transition-all hidden sm:flex items-center space-x-1.5">
            <span class="w-2 h-2 rounded-full bg-cyan-400"></span>
            <span>Side-by-Side Comparison</span>
          </button>
        </div>

        <!-- Single View Box -->
        <div id="view-single" class="p-5 font-mono text-xs leading-relaxed overflow-x-auto">
          <!-- Legacy / Before View -->
          <div id="content-before" class="space-y-3">
            <div class="flex items-center space-x-2 text-red-400 text-[11px] font-semibold uppercase tracking-wider bg-red-950/40 px-3 py-1.5 rounded border border-red-900/40">
              <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path></svg>
              <span>Issues: Ambiguous prerequisites, unformatted command, no metadata, breaks RAG ingestion</span>
            </div>
            <pre class="bg-slate-950 p-4 rounded-lg border border-red-900/30 text-slate-300 whitespace-pre-wrap leading-6">
# Setting up the Security Collector

To set up the collector on your Linux box, you need to first make sure you have root or sudo permissions. Then download the tar file from our server or use curl if you have it. You need to make sure port 443 is open outgoing to our ingest endpoint otherwise it won't connect and logs will buffer locally until disk fills up. Once unpacked run `./install.sh --key YOUR_KEY`. Note that on Ubuntu 22.04 you might need glibc updated first. You can pass optional flags like `--env prod` if you want.
            </pre>
          </div>

          <!-- Refactored / After View -->
          <div id="content-after" class="hidden space-y-3">
            <div class="flex items-center space-x-2 text-emerald-400 text-[11px] font-semibold uppercase tracking-wider bg-emerald-950/40 px-3 py-1.5 rounded border border-emerald-900/40">
              <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
              <span>Improvements: Frontmatter YAML metadata, explicit prerequisites, copyable code, verified flags</span>
            </div>
            <pre class="bg-slate-950 p-4 rounded-lg border border-emerald-900/30 text-emerald-100 whitespace-pre-wrap leading-6">
<span class="text-slate-500">---
title: Install Security Telemetry Collector on Linux
category: Security Operations & Telemetry
tags: [collector, linux, installation, secops]
last_verified: 2026-10-01
---</span>

<span class="text-emerald-400"># Install Security Telemetry Collector on Linux</span>

Install and start the security collector agent to forward telemetry logs to the ingest pipeline.

<span class="text-emerald-300">## Prerequisites</span>
- **Operating System:** Linux (Ubuntu 20.04+, RHEL 8+, Debian 11+)
- **Privileges:** Root or `sudo` execution rights
- **Network:** Outbound HTTPS permitted on **Port 443** (`ingest.security.domain.com`)

<span class="text-emerald-300">## Installation Steps</span>

1. Download and unpack the collector binary:
   ```bash
   curl -sSL https://releases.security.domain.com/collector-latest.tar.gz | tar -xz
   ```

2. Execute the setup script with your API Key and target environment:
   ```bash
   sudo ./install.sh --key <YOUR_ORGANIZATION_API_KEY> --env prod
   ```

<span class="text-emerald-300">## Verification</span>
Confirm agent daemon status:
```bash
systemctl status security-collector
```
            </pre>
          </div>
        </div>

        <!-- Side-by-Side View -->
        <div id="view-diff" class="hidden p-5 grid grid-cols-1 md:grid-cols-2 gap-4 font-mono text-xs leading-relaxed">
          <div class="space-y-2">
            <div class="text-red-400 text-[10px] font-semibold uppercase tracking-wider">Raw Unstructured Text</div>
            <pre class="bg-slate-950 p-3.5 rounded-lg border border-red-900/30 text-slate-400 whitespace-pre-wrap leading-5 h-full">
# Setting up the Security Collector

To set up the collector on your Linux box, you need to first make sure you have root or sudo permissions. Then download the tar file from our server or use curl if you have it. You need to make sure port 443 is open outgoing...
            </pre>
          </div>
          <div class="space-y-2">
            <div class="text-emerald-400 text-[10px] font-semibold uppercase tracking-wider">Refactored & RAG-Ready</div>
            <pre class="bg-slate-950 p-3.5 rounded-lg border border-emerald-900/30 text-emerald-100 whitespace-pre-wrap leading-5 h-full">
# Install Security Collector

## Prerequisites
- **OS:** Linux (Ubuntu 20.04+, RHEL 8+)
- **Networking:** Outbound HTTPS Port 443

## Installation
```bash
curl -sSL https://releases.security.domain.com/collector.tar.gz | tar -xz
sudo ./install.sh --key <YOUR_KEY> --env prod
```
            </pre>
          </div>
        </div>

      </div>
    </section>

    <hr class="border-slate-800/80">

    <!-- Engagement Models / Scopes (3 Cards) -->
    <section id="scopes" class="space-y-6">
      <div>
        <h2 class="text-xs font-mono uppercase tracking-wider text-emerald-400 font-semibold mb-1">Engagement Models</h2>
        <h3 class="text-2xl font-bold text-white">Targeted Contract Scopes</h3>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <!-- Scope 1 -->
        <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all space-y-4 flex flex-col justify-between">
          <div class="space-y-2">
            <div class="text-xs font-mono text-cyan-400 font-semibold uppercase tracking-wider">Scope 01</div>
            <h4 class="text-white font-semibold text-lg">Incremental Doc Builds</h4>
            <p class="text-slate-400 text-xs leading-relaxed">
              Iterative documentation writing for new feature releases, individual system modules, or targeted product updates without requiring full-time hire commitments.
            </p>
          </div>
          <div class="text-xs font-mono text-slate-400 pt-3 border-t border-slate-800/80 flex items-center space-x-1">
            <span class="text-emerald-400">►</span>
            <span>Modular Markdown Deliverables</span>
          </div>
        </div>

        <!-- Scope 2 -->
        <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all space-y-4 flex flex-col justify-between">
          <div class="space-y-2">
            <div class="text-xs font-mono text-emerald-400 font-semibold uppercase tracking-wider">Scope 02</div>
            <h4 class="text-white font-semibold text-lg">Ground-Up Doc Suites</h4>
            <p class="text-slate-400 text-xs leading-relaxed">
              Building clean, well-organized documentation hubs from scratch for early-stage products, small teams, or newly launched engineering tools.
            </p>
          </div>
          <div class="text-xs font-mono text-slate-400 pt-3 border-t border-slate-800/80 flex items-center space-x-1">
            <span class="text-emerald-400">►</span>
            <span>Complete Architecture & Setup</span>
          </div>
        </div>

        <!-- Scope 3 -->
        <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all space-y-4 flex flex-col justify-between">
          <div class="space-y-2">
            <div class="text-xs font-mono text-blue-400 font-semibold uppercase tracking-wider">Scope 03</div>
            <h4 class="text-white font-semibold text-lg">AI-Readability & Structure Sweeps</h4>
            <p class="text-slate-400 text-xs leading-relaxed">
              Restructuring your existing documentation taxonomy, section chunking, headings, and code metadata so LLM assistants parse and answer questions correctly.
            </p>
          </div>
          <div class="text-xs font-mono text-slate-400 pt-3 border-t border-slate-800/80 flex items-center space-x-1">
            <span class="text-emerald-400">►</span>
            <span>RAG-Optimized Doc Ecosystem</span>
          </div>
        </div>
      </div>
    </section>

    <hr class="border-slate-800/80">

    <!-- Contact Section -->
    <section id="contact" class="p-8 sm:p-10 rounded-2xl bg-gradient-to-b from-slate-900 to-slate-950 border border-slate-800 text-center space-y-5 shadow-xl">
      <div class="inline-block px-3 py-1 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 font-mono text-xs">
        Limited Bandwidth Available
      </div>
      <h3 class="text-2xl sm:text-3xl font-bold text-white">Have a documentation project in mind?</h3>
      <p class="text-slate-300 text-sm sm:text-base max-w-xl mx-auto leading-relaxed">
        Send me a note with a link to your docs or repository. I’ll take a look and let you know if it’s a good fit for a short-term contract.
      </p>

      <div class="pt-2 flex flex-col sm:flex-row justify-center items-center gap-3">
        <a href="mailto:consulting@doc-consultant.io" class="w-full sm:w-auto px-6 py-3 rounded-lg bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-semibold text-sm transition-all shadow-lg shadow-emerald-500/20">
          Send An Email
        </a>
      </div>

      <p class="text-xs font-mono text-slate-500 pt-2">
        Taking on 1–2 small contract projects per month. Fast async responses.
      </p>
    </section>

  </main>

  <footer class="border-t border-slate-800/80 py-8 bg-slate-950 text-xs text-slate-500">
    <div class="max-w-4xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-3 font-mono">
      <div>© doc-consultant.io | Independent Technical Writing</div>
      <div>Minimalist GitHub Pages Portfolio</div>
    </div>
  </footer>

  <!-- Script for Interactive Sample Work Toggle -->
  <script>
    function setDocTab(view) {
      const btnBefore = document.getElementById('tab-btn-before');
      const btnAfter = document.getElementById('tab-btn-after');
      const btnDiff = document.getElementById('tab-btn-diff');

      const viewSingle = document.getElementById('view-single');
      const viewDiff = document.getElementById('view-diff');

      const contentBefore = document.getElementById('content-before');
      const contentAfter = document.getElementById('content-after');

      // Reset classes
      [btnBefore, btnAfter, btnDiff].forEach(btn => {
        if (btn) btn.className = "px-3.5 py-1.5 rounded-md font-medium text-slate-400 hover:text-white transition-all flex items-center space-x-1.5";
      });

      if (view === 'before') {
        btnBefore.className = "px-3.5 py-1.5 rounded-md font-medium bg-red-500/20 border border-red-500/40 text-red-300 transition-all flex items-center space-x-1.5";
        viewSingle.classList.remove('hidden');
        viewDiff.classList.add('hidden');
        contentBefore.classList.remove('hidden');
        contentAfter.classList.add('hidden');
      } else if (view === 'after') {
        btnAfter.className = "px-3.5 py-1.5 rounded-md font-medium bg-emerald-500/20 border border-emerald-500/40 text-emerald-300 transition-all flex items-center space-x-1.5";
        viewSingle.classList.remove('hidden');
        viewDiff.classList.add('hidden');
        contentBefore.classList.add('hidden');
        contentAfter.classList.remove('hidden');
      } else if (view === 'diff') {
        btnDiff.className = "px-3.5 py-1.5 rounded-md font-medium bg-cyan-500/20 border border-cyan-500/40 text-cyan-300 transition-all flex items-center space-x-1.5";
        viewSingle.classList.add('hidden');
        viewDiff.classList.remove('hidden');
      }
    }
  </script>
</body>
</html>
```
