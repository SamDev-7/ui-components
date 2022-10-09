<script lang="ts">
    export let title: string;
    export let description: string;
    export let thumbnail: string;
    export let dark_thumbnail: string = thumbnail;
    export let href: string;
</script>

<a {href}>
    <div class="bg-white dark:bg-slate-900 dark:border-slate-600 2xs:border-2 2xs:rounded-lg text-left transition-transform 2xs:hover:scale-105 2xs:hover:drop-shadow-xl flex flex-col 2xs:min-h-full overflow-hidden">
        <div style="background-image: url({thumbnail})" class="dark:hidden w-full h-32 bg-center bg-origin-border"></div>
        <div style="background-image: url({dark_thumbnail})" class="hidden dark:block w-full h-32 bg-center bg-origin-border"></div>
        <div class="px-6 py-6">
            <h3 class="text-xl font-medium dark:text-white">{title}</h3>
            <p class="mt-3 text-slate-800 dark:text-slate-200">{description}</p>
        </div>
    </div>
</a>