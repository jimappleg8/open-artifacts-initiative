---
layout: sidebar-page
title: Open Artifacts Licenses
eleventyNavigation:
  key: OA Licenses
  parent: project
  order: 4
tags: project
navKey: project-section
---
{% section %}

# Open Artifacts Licenses

These are licenses that comply with the Open Artifacts Definition.

{% endsection %}

<div class="max-w-5xl mx-auto overflow-x-auto shadow ring-1 ring-black ring-opacity-5 sm:rounded-lg">
  <table class="min-w-full divide-y divide-gray-300">
    <thead class="bg-gray-50">
      <tr>
        <th scope="col" class="py-3.5 pl-4 pr-3 text-left text-sm font-semibold text-gray-900 sm:pl-6">License Name</th>
        <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900">Category</th>
        <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900">OAD Compliant?</th>
        <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900">Why? (The Critical Factor)</th>
      </tr>
    </thead>
    <tbody class="divide-y divide-gray-200 bg-white">
      <tr>
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          Creative Commons Attribution<br>(CC BY)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Content / Media</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800">YES</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-500">Allows everything; requires attribution.</td>
      </tr>
      <tr>
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          CC Attribution-ShareAlike<br>(CC BY-SA)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Content / Media</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800">YES</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-500">Compliant "Copyleft" (must share modifications).</td>
      </tr>
      <tr class="bg-red-50">
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          CC Non-Commercial<br>(CC BY-NC)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Content / Media</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-red-100 px-2.5 py-0.5 text-xs font-medium text-red-800">NO</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-900 font-medium">Violates OAD #1 & #6. Discriminates against commercial fields.</td>
      </tr>
      <tr class="bg-red-50">
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          CC No-Derivatives<br>(CC BY-ND)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Content / Media</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-red-100 px-2.5 py-0.5 text-xs font-medium text-red-800">NO</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-900 font-medium">Violates OAD #3. Forbids fixing/improving the artifact.</td>
      </tr>
      <tr>
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          MIT License
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Software</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800">YES</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-500">Simple and permissive. (Patent grant is implied).</td>
      </tr>
      <tr class="bg-blue-50">
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          Apache License 2.0
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Software</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-blue-100 px-2.5 py-0.5 text-xs font-medium text-blue-800">RECOMMENDED</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-900 font-medium">Gold Standard. Contains an explicit Patent Grant (Strong adherence to OAD #1).</td>
      </tr>
      <tr>
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          GNU GPL v3
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Software</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800">YES</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-500">Strong Copyleft. Explicit Patent Grant.</td>
      </tr>
      <tr class="bg-blue-50">
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          CERN-OHL-P (Permissive)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Hardware</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-blue-100 px-2.5 py-0.5 text-xs font-medium text-blue-800">RECOMMENDED</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-900 font-medium">Designed for hardware. Explicit Patent Grant.</td>
      </tr>
      <tr>
        <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-6">
          CERN-OHL-S (Strong)
        </td>
        <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Hardware</td>
        <td class="whitespace-nowrap px-3 py-4 text-sm">
          <span class="inline-flex items-center rounded-full bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800">YES</span>
        </td>
        <td class="px-3 py-4 text-sm text-gray-500">Hardware "Copyleft." Explicit Patent Grant.</td>
      </tr>
    </tbody>
  </table>
</div>
