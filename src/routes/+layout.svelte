<script lang="ts">
    import type { LayoutData } from './$types';
    import "../app.css";
    export let data: LayoutData;
</script>
<div class="w-full h-screen bg-white">
    <div class="navbar bg-black font-artifakt text-white ">
        <div class="flex-1">
          <a href="/" class="btn btn-ghost normal-case text-xl">Autodesk Ideas</a>
        </div>
        <div class="flex-none">
          <ul class="menu menu-horizontal px-1">
            <li><a href="/idea-1">Idea #1</a></li>
          </ul>
        </div>
      </div>
      <slot/>
</div>

