---
title: "Mini Artillery Duel"
excerpt: "An Artillery Duel clone written in MSX-BASIC 1.0 for the BASIC 10 Liner Contest."
---

<div id="wmsx" style="text-align: center; margin: 20px auto 0;">
    <div id="wmsx-screen" style="box-shadow: 2px 2px 10px rgba(0, 0, 0, .7);"></div>
</div>

<script src="{{ base.url | prepend: site.url }}/assets/js/wmsx.js">
</script>
<script>
    WMSX.MACHINE = "MSX1";
    WMSX.DISKA_URL = "{{ base.url | prepend: site.url }}/assets/js/miniduel.dsk";
    WMSX.BASIC_RUN = "miniduel.bas";
</script>
