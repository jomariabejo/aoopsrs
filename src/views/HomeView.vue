<script setup lang="ts"></script>

<template>
  <main>
    <div
      class="flex flex-col lg:relative text-center lg:flex lg:items-center lg:justify-center shadow-black"
    >
      <img
        class="w-full max-h-screen object-cover opacity-70"
        src="https://images.pexels.com/photos/1413412/pexels-photo-1413412.jpeg?cs=srgb&dl=pexels-giorgio-de-angelis-482403-1413412.jpg&fm=jpg"
        alt="motorcycle photo"
      />
      <div
        class="relative lg:absolute lg:left-1/2 transform lg:-translate-x-1/2 bg-gray-50 hover:bg-gray-100 duration-100 p-4 rounded-lg"
      >
        <h1
          class="animate-pulse text-5xl p-4 text-center font-bold from-gray-800 via-gray-500 to-gray-300 bg-gradient-to-r bg-clip-text text-transparent max-w-screen-lg"
        >
          Expanded MotorPH Payroll System Software Requirements Specification
        </h1>
      </div>
    </div>
    <div class="flex flex-col items-center lg:flex-row lg:items-start lg:px-16">
      <div
        class="hover:bg-gray-800 duration-300 rounded-md hover:text-white container text-center my-16 p-4"
      >
        <h2 class="text-4xl font-bold my-4">Purpose</h2>
        <p class="text-justify text-2xl tracking-wide">
          The purpose of creating the Software Requirements Specification (SRS) is to provide a
          comprehensive and detailed description of the payroll system. This document aims to ensure
          that the system meets the intended requirements, and serves as a reference for the
          development, maintenance, and enhancement of the system. The SRS covers both functional
          and non-functional requirements and includes sections on project scope, product
          perspective, user needs, assumptions, dependencies, system features, and non-functional
          requirements. Key stakeholders, such as project managers, developers, testers, and
          end-users, will use this document to understand and implement the system accurately.
        </p>
      </div>
      <div
        class="hover:bg-gray-800 duration-300 rounded-md hover:text-white container text-center my-16 p-4"
      >
        <h2 class="text-4xl font-bold my-4">Scope</h2>
        <p class="text-justify text-2xl tracking-wide">
          The updated payroll system aims to enhance employee management and payroll processing
          capabilities. The system will provide a user-friendly interface and includes features such
          as employee management, payroll calculation, leave management, reporting, and a
          self-service portal for employees. The primary objectives are to improve efficiency,
          accuracy, and compliance with regulatory requirements. This system supports the corporate
          goal of enhancing operational efficiency and employee satisfaction.
        </p>
      </div>

      <div
        class="hover:bg-gray-800 duration-300 rounded-md hover:text-white container text-center my-16 p-4"
      >
        <h2 class="text-4xl font-bold my-4">Exclusion</h2>
        <p class="text-justify text-2xl tracking-wide">
          The payroll system does not extend to employee performance evaluations, goal setting, or
          other aspects of performance management. Additionally, integration with external
          third-party software, non-payroll HR functions such as recruitment, and multi-currency
          payroll processing are excluded from this system.
        </p>
      </div>
    </div>
  </main>
</template>
