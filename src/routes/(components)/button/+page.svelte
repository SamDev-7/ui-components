<svelte:head>
    <title>Button - UI Components</title>
</svelte:head>

<!-- Title -->
<div class="py-32 text-center bg-gradient-to-br from-indigo-100 to-blue-300 dark:from-cyan-700 dark:to-blue-900">
    <h1 class="text-7xl font-medium dark:text-white">Buttons</h1>
</div>

<div class="w-full flex">
    <div class="m-auto min-h-full py-32 grid gap-8 grid-cols-5 grid-rows-2 place-items-center">
            <button class="bg-blue-500 hover:bg-blue-400 dark:hover:bg-blue-600 text-white py-2 px-4 rounded tracking-wide active:shadow-inner">
                Primary Button
            </button>
            <button class="bg-gray-500 hover:bg-gray-400 dark:hover:bg-gray-600 text-white py-2 px-4 rounded tracking-wide active:shadow-inner">
                Secondary Button
            </button>
            <button class="bg-red-500 hover:bg-red-400 dark:hover:bg-red-600 text-white py-2 px-4 rounded tracking-wide active:shadow-inner">
                Danger Button
            </button>
            <button class="bg-yellow-500 hover:bg-yellow-400 dark:hover:bg-yellow-600 text-white py-2 px-4 rounded tracking-wide active:shadow-inner">
                Warning Button
            </button>
            <button class="bg-green-500 hover:bg-green-400 dark:hover:bg-green-600 text-white py-2 px-4 rounded tracking-wide active:shadow-inner">
                Success Button
            </button>

            <button class="bg-transparent hover:bg-blue-500 text-blue-500 hover:text-white py-[calc(0.5rem-2px)] px-[calc(1rem-2px)] border-2 border-blue-500 rounded tracking-wide active:shadow-inner">
                Primary Outline
            </button>
            <button class="bg-transparent hover:bg-gray-500 text-gray-500 hover:text-white py-[calc(0.5rem-2px)] px-[calc(1rem-2px)] border-2 border-gray-500 rounded tracking-wide active:shadow-inner">
                Secondary Outline
            </button>
            <button class="bg-transparent hover:bg-red-500 text-red-500 hover:text-white py-[calc(0.5rem-2px)] px-[calc(1rem-2px)] border-2 border-red-500 rounded tracking-wide active:shadow-inner">
                Danger Outline
            </button>
            <button class="bg-transparent hover:bg-yellow-500 text-yellow-500 hover:text-white py-[calc(0.5rem-2px)] px-[calc(1rem-2px)] border-2 border-yellow-500 rounded tracking-wide active:shadow-inner">
                Warning Outline
            </button>
            <button class="bg-transparent hover:bg-green-500 text-green-500 hover:text-white py-[calc(0.5rem-2px)] px-[calc(1rem-2px)] border-2 border-green-500 rounded tracking-wide active:shadow-inner">
                Success Outline
            </button>

            <button class="bg-blue-300 text-white py-2 px-4 rounded tracking-wide cursor-not-allowed" disabled>
                Disabled Primary
            </button>
            <button class="bg-gray-300 text-white py-2 px-4 rounded tracking-wide cursor-not-allowed" disabled>
                Disabled Secondary
            </button>
            <button class="bg-red-300 text-white py-2 px-4 rounded tracking-wide cursor-not-allowed" disabled>
                Disabled Danger
            </button>
            <button class="bg-yellow-300 text-white py-2 px-4 rounded tracking-wide cursor-not-allowed" disabled>
                Disabled Warning
            </button>
            <button class="bg-green-300 text-white py-2 px-4 rounded tracking-wide cursor-not-allowed" disabled>
                Disabled Success
            </button>
        </div>
</div>