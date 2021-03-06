<template>
    <div>
        <header class="bg-red-500 h-20">

        </header>

        <nav class="bg-blue-200 text-blue-900">
            <a href="/jspage1" class="py-2 px-4 hover:bg-blue-300"> Page 1</a>
            <a href="/about-us" class="py-2 px-4 hover:bg-blue-300"> About Us</a>
        </nav>

        <!-- This will Slot in all page content -->
        <slot></slot>
    </div>
</template>

