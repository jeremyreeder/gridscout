---
layout: default
title: Home
permalink: /
hide_site_description: true
---
<style>
.blink {
  animation: blink 1s step-end infinite;
}
@keyframes blink {
  50% { opacity: 0; }
}
</style>

<div class="portal">
  <div class="portal-intro">
    <p class="portal-kicker">GridScout directory</p>
    <h1>Where to? <span class="blink">_</span></h1>
  </div>

  <nav aria-label="GridScout destinations">
    <div class="portal-grid">
      <a class="portal-card" href="https://threat.gridscout.net/">
        <span class="portal-card-meta">Security</span>
        <strong>Threat Level Indicator</strong>
        <span class="portal-card-desc">Four-level gauge, one-level action plan.</span>
        <span class="portal-card-path">threat.gridscout.net <span aria-hidden="true">↗</span></span>
      </a>
      <a class="portal-card" href="https://shenanigans.gridscout.net/">
        <span class="portal-card-meta">Laboratory</span>
        <strong>Internet Security Shenanigans</strong>
        <span class="portal-card-desc">An interactive lesson on network attacks and defenses.</span>
        <span class="portal-card-path">shenanigans.gridscout.net <span aria-hidden="true">↗</span></span>
      </a>
      <a class="portal-card" href="{{ '/maps/' | relative_url }}">
        <span class="portal-card-meta">Cartography</span>
        <strong>GridScout Map™</strong>
        <span class="portal-card-desc">MGRS search client, for planning with paper maps.</span>
        <span class="portal-card-path">/maps/ <span aria-hidden="true">↗</span></span>
      </a>
      <a class="portal-card" href="{{ '/gazette/' | relative_url }}">
        <span class="portal-card-meta">Project Log</span>
        <strong>GridScout Gazette™</strong>
        <span class="portal-card-desc">Field notes about manly projects and whatnot.</span>
        <span class="portal-card-path">/gazette/ <span aria-hidden="true">↗</span></span>
      </a>
      <a class="portal-card" href="https://www.youtube.com/@JeremyPicksLocks">
        <span class="portal-card-meta">Conquests</span>
        <strong>@JeremyPicksLocks</strong>
        <span class="portal-card-desc">Lockpicking demonstration videos.</span>
        <span class="portal-card-path">youtube.com <span aria-hidden="true">↗</span></span>
      </a>
      <a class="portal-card" href="https://safehouse.gridscout.net/">
        <span class="portal-card-meta">Archive</span>
        <strong>The Safe House™</strong>
        <span class="portal-card-desc">Jeremy's past life as a safecracker.</span>
        <span class="portal-card-path">safehouse.gridscout.net <span aria-hidden="true">↗</span></span>
      </a>
    </div>
  </nav>

  <p class="portal-footer">Copyright © 2026 GridScout</p>
</div>
