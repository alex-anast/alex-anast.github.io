---
title: "Curriculum Vitae"
description: "My professional resume"
layout: "single" 
---

<div class="flex flex-col items-center gap-6">
    <!-- Download Button -->
    <a href="/assets/documents/resume_alexandros_anastasiou.pdf" 
       download="Alexandros_Anastasiou_Resume.pdf"
       class="inline-flex items-center gap-2 px-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-semibold rounded-lg transition-colors duration-200 shadow-md">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
            <polyline points="7 10 12 15 17 10"/>
            <line x1="12" y1="15" x2="12" y2="3"/>
        </svg>
        Download PDF
    </a>

    <!-- PDF Viewer -->
    <div class="w-full h-[800px] border border-gray-200 dark:border-gray-700 rounded-lg overflow-hidden shadow-lg bg-white">
        <object data="/assets/documents/resume_alexandros_anastasiou.pdf" type="application/pdf" width="100%" height="100%">
            <div class="flex flex-col items-center justify-center h-full p-8 text-center bg-gray-50 dark:bg-gray-800">
                <p class="text-lg text-gray-700 dark:text-gray-300 mb-4">
                    Unable to display PDF directly.
                </p>
                <a href="/assets/documents/resume_alexandros_anastasiou.pdf" class="text-blue-600 hover:text-blue-500 underline">
                    Click here to download the PDF
                </a>
            </div>
        </object>
    </div>
</div>
