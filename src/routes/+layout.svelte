<script lang="ts">
    import "../app.css";
    import { base } from "$app/paths";
</script>

<div
    class="navbar
bg-base-200 text-base-content sticky top-0 z-30 flex w-full justify-center bg-opacity-90 backdrop-blur transition-all duration-100 [transform:translate3d(0,0,0)]
shadow-sm font-mono
"
>
    <div class="flex-1">
        <a class="btn btn-ghost normal-case text-xl" href="{base}/">Home</a>
    </div>
    <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
            <li><a href="{base}/about">About</a></li>
        </ul>
    </div>
</div>

<slot />
