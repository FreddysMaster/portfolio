<script>
  import { ProgressBar } from "@skeletonlabs/skeleton";
  import quizgame from "$lib/assets/quizgame.png";
  import cosmicsite from "$lib/assets/cosmicsplash.png";
</script>

<main>
  <div class="container mx-auto px-32 py-8">
    <h2 class="text-2xl font-bold mt-8 mb-4">Portfolio</h2>
    <hr class="border-t-2 border-gray-300" />
    <h3 class="text-xl font-semibold mt-4 mb-2">My Projects</h3>
    <p class="text-lg mb-4">
      Here are some of the projects I have been a part of.
    </p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto h-full flex flex-col">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Cosmic Boogeyman Website</h2>
        </header>
        <section class="p-4 flex-grow flex flex-col">
          <div class="flex justify-center">
            <img src={cosmicsite} alt="Cosmic Boogeyman Website Splashscreen" />
          </div>
          <p class="my-4 text-gray-300">
            I made this website for a tarot reader who asked me to make them a
            website for their youtube channel and allow people to book online
            readings with them.
          </p>
          <div class="mt-auto">
            <a href="/cosmicwebsite" class="btn variant-filled-secondary w-full">Learn More</a>
          </div>
        </section>
      </div>
      
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto h-full flex flex-col">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Quiz Game</h2>
        </header>
        <section class="p-4 flex-grow flex flex-col">
          <div class="flex justify-center">
            <img src={quizgame} alt="Quiz Game Main Screen" />
          </div>
          <p class="my-4 text-gray-300">
            This is a game I worked on in a group that challenges the user to
            get as many points as possible without getting any questions
            incorrect.
          </p>
          <div class="mt-auto">
            <a href="/quizgame" class="btn variant-filled-secondary w-full">Learn More</a>
          </div>
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto h-full flex flex-col">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Wizard Tower Survival</h2>
        </header>
        <section class="p-4 flex-grow flex flex-col">
          <div class="flex justify-center">
            <img
              src="https://img.itch.zone/aW1hZ2UvMzAyNTA3OC8xODA4NzI1Ni5qcGc=/794x1000/Oe4%2Bu1.jpg"
              alt="Wizard Tower Survival Gameplay"
            />
          </div>
          <p class="my-4 text-gray-300">
            In this survival game, you play as a wizard battling endless waves
            of golems. Cast spells and dodge attacks to maintain your health.
            Earn points by defeating golems and try to get the highest score.
          </p>
          <div class="mt-auto">
            <a href="/quizgame" class="btn variant-filled-secondary w-full">Learn More</a>
          </div>
        </section>
      </div>
    </div>

    <h2 class="text-2xl font-bold mt-8 mb-4">Skills</h2>
    <hr class="border-t-2 border-gray-300" />
    <p class="text-xl my-8 mx-4">Here are some of my skills</p>
    <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Python</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><g fill="none"
                ><g fill="white" clip-path="url(#akarIconsPythonFill0)"
                  ><path
                    d="M11.914 0C5.82 0 6.2 2.656 6.2 2.656l.007 2.752h5.814v.826H3.9S0 5.789 0 11.969s3.403 5.96 3.403 5.96h2.03v-2.867s-.109-3.42 3.35-3.42h5.766s3.24.052 3.24-3.148V3.202S18.28 0 11.913 0M8.708 1.85c.578 0 1.046.47 1.046 1.052c0 .581-.468 1.051-1.046 1.051s-1.046-.47-1.046-1.051c0-.582.467-1.052 1.046-1.052"
                  /><path
                    d="M12.087 24c6.092 0 5.712-2.656 5.712-2.656l-.007-2.752h-5.814v-.826h8.123s3.9.445 3.9-5.735s-3.404-5.96-3.404-5.96h-2.03v2.867s.109 3.42-3.35 3.42H9.452s-3.24-.052-3.24 3.148v5.292S5.72 24 12.087 24m3.206-1.85c-.579 0-1.046-.47-1.046-1.052c0-.581.467-1.051 1.046-1.051c.578 0 1.046.47 1.046 1.051c0 .582-.468 1.052-1.046 1.052"
                  /></g
                ><defs
                  ><clipPath id="akarIconsPythonFill0"
                    ><path fill="#fff" d="M0 0h24v24H0z" /></clipPath
                  ></defs
                ></g
              ></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={50} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">HTML</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="m3 2l1.578 17.824L12 22l7.467-2.175L21 2zm14.049 6.048H9.075l.172 2.016h7.697l-.626 6.565l-4.246 1.381l-4.281-1.455l-.288-2.932h2.024l.16 1.411l2.4.815l2.346-.763l.297-3.005H7.416l-.562-6.05h10.412z"
              /></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={85} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">CSS</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M10.5 15q-.425 0-.712-.288T9.5 14v-1H11v.5h2v-1h-2.5q-.425 0-.712-.288T9.5 11.5V10q0-.425.288-.712T10.5 9h3q.425 0 .713.288T14.5 10v1H13v-.5h-2v1h2.5q.425 0 .713.288t.287.712V14q0 .425-.288.713T13.5 15zm6.5 0q-.425 0-.712-.288T16 14v-1h1.5v.5h2v-1H17q-.425 0-.712-.288T16 11.5V10q0-.425.288-.712T17 9h3q.425 0 .713.288T21 10v1h-1.5v-.5h-2v1H20q.425 0 .713.288T21 12.5V14q0 .425-.288.713T20 15zM4 15q-.425 0-.712-.288T3 14v-4q0-.425.288-.712T4 9h3q.425 0 .713.288T8 10v1H6.5v-.5h-2v3h2V13H8v1q0 .425-.288.713T7 15z"
              /></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={75} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">JavaScript</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M3 3h18v18H3zm4.73 15.04c.4.85 1.19 1.55 2.54 1.55c1.5 0 2.53-.8 2.53-2.55v-5.78h-1.7V17c0 .86-.35 1.08-.9 1.08c-.58 0-.82-.4-1.09-.87zm5.98-.18c.5.98 1.51 1.73 3.09 1.73c1.6 0 2.8-.83 2.8-2.36c0-1.41-.81-2.04-2.25-2.66l-.42-.18c-.73-.31-1.04-.52-1.04-1.02c0-.41.31-.73.81-.73c.48 0 .8.21 1.09.73l1.31-.87c-.55-.96-1.33-1.33-2.4-1.33c-1.51 0-2.48.96-2.48 2.23c0 1.38.81 2.03 2.03 2.55l.42.18c.78.34 1.24.55 1.24 1.13c0 .48-.45.83-1.15.83c-.83 0-1.31-.43-1.67-1.03z"
              /></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={50} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Unity</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M10.11 17H7.5l-4.91-5L7.5 7h2.61l1.31-2.26L18.21 3l1.87 6.74L18.77 12l1.31 2.26L18.21 21l-6.79-1.74zm.14-.25l5.13 1.38L12.42 13H6.5zm6.87.38L18.5 12l-1.38-5.13L14.15 12zm-6.87-9.88L6.5 11h5.92l2.96-5.13z"
              /></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={70} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Git</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M2.6 10.59L8.38 4.8l1.69 1.7c-.24.85.15 1.78.93 2.23v5.54c-.6.34-1 .99-1 1.73a2 2 0 0 0 2 2a2 2 0 0 0 2-2c0-.74-.4-1.39-1-1.73V9.41l2.07 2.09c-.07.15-.07.32-.07.5a2 2 0 0 0 2 2a2 2 0 0 0 2-2a2 2 0 0 0-2-2c-.18 0-.35 0-.5.07L13.93 7.5a1.98 1.98 0 0 0-1.15-2.34c-.43-.16-.88-.2-1.28-.09L9.8 3.38l.79-.78c.78-.79 2.04-.79 2.82 0l7.99 7.99c.79.78.79 2.04 0 2.82l-7.99 7.99c-.78.79-2.04.79-2.82 0L2.6 13.41c-.79-.78-.79-2.04 0-2.82"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={70} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">C</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="m15.45 15.97l.42 2.44c-.26.14-.68.27-1.24.39c-.57.13-1.24.2-2.01.2c-2.21-.04-3.87-.7-4.98-1.96c-1.14-1.27-1.68-2.88-1.68-4.83C6 9.9 6.68 8.13 8 6.89C9.28 5.64 10.92 5 12.9 5c.75 0 1.4.07 1.94.19s.94.25 1.2.4l-.6 2.49l-1.04-.34c-.4-.1-.87-.15-1.4-.15c-1.15-.01-2.11.36-2.86 1.1c-.76.73-1.14 1.85-1.18 3.34c.01 1.36.37 2.42 1.08 3.2c.71.77 1.7 1.17 2.99 1.18l1.33-.12c.43-.08.79-.19 1.09-.32"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={65} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Windows</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M13 13h8v6q0 .825-.587 1.413T19 21h-6zm0-2V3h6q.825 0 1.413.588T21 5v6zm-2 0H3V5q0-.825.588-1.412T5 3h6zm0 2v8H5q-.825 0-1.412-.587T3 19v-6z"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={95} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Linux</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M12.504 0q-.232 0-.48.021c-4.226.333-3.105 4.807-3.17 6.298c-.076 1.092-.3 1.953-1.05 3.02c-.885 1.051-2.127 2.75-2.716 4.521c-.278.832-.41 1.684-.287 2.489a.4.4 0 0 0-.11.135c-.26.268-.45.6-.663.839c-.199.199-.485.267-.797.4c-.313.136-.658.269-.864.68c-.09.189-.136.394-.132.602c0 .199.027.4.055.536c.058.399.116.728.04.97c-.249.68-.28 1.145-.106 1.484c.174.334.535.47.94.601c.81.2 1.91.135 2.774.6c.926.466 1.866.67 2.616.47c.526-.116.97-.464 1.208-.946c.587-.003 1.23-.269 2.26-.334c.699-.058 1.574.267 2.577.2c.025.134.063.198.114.333l.003.003c.391.778 1.113 1.132 1.884 1.071s1.592-.536 2.257-1.306c.631-.765 1.683-1.084 2.378-1.503c.348-.199.629-.469.649-.853c.023-.4-.2-.811-.714-1.376v-.097l-.003-.003c-.17-.2-.25-.535-.338-.926c-.085-.401-.182-.786-.492-1.046h-.003c-.059-.054-.123-.067-.188-.135a.36.36 0 0 0-.19-.064c.431-1.278.264-2.55-.173-3.694c-.533-1.41-1.465-2.638-2.175-3.483c-.796-1.005-1.576-1.957-1.56-3.368c.026-2.152.236-6.133-3.544-6.139m.529 3.405h.013c.213 0 .396.062.584.198c.19.135.33.332.438.533c.105.259.158.459.166.724c0-.02.006-.04.006-.06v.105l-.004-.021l-.004-.024a1.8 1.8 0 0 1-.15.706a.95.95 0 0 1-.213.335a1 1 0 0 0-.088-.042c-.104-.045-.198-.064-.284-.133a1.3 1.3 0 0 0-.22-.066c.05-.06.146-.133.183-.198q.08-.193.088-.402v-.02a1.2 1.2 0 0 0-.061-.4c-.045-.134-.101-.2-.183-.333c-.084-.066-.167-.132-.267-.132h-.016c-.093 0-.176.03-.262.132a.8.8 0 0 0-.205.334a1.2 1.2 0 0 0-.09.4v.019q.002.134.02.267c-.193-.067-.438-.135-.607-.202a2 2 0 0 1-.018-.2v-.02a1.8 1.8 0 0 1 .15-.768a1.08 1.08 0 0 1 .43-.533a1 1 0 0 1 .594-.2zm-2.962.059h.036c.142 0 .27.048.399.135c.146.129.264.288.344.465c.09.199.14.4.153.667v.004c.007.134.006.2-.002.266v.08c-.03.007-.056.018-.083.024c-.152.055-.274.135-.393.2q.018-.136.003-.267v-.015c-.012-.133-.04-.2-.082-.333a.6.6 0 0 0-.166-.267a.25.25 0 0 0-.183-.064h-.021c-.071.006-.13.04-.186.132a.55.55 0 0 0-.12.27a1 1 0 0 0-.023.33v.015c.012.135.037.2.08.334c.046.134.098.2.166.268q.014.014.034.024c-.07.057-.117.07-.176.136a.3.3 0 0 1-.131.068a2.6 2.6 0 0 1-.275-.402a1.8 1.8 0 0 1-.155-.667a1.8 1.8 0 0 1 .08-.668a1.4 1.4 0 0 1 .283-.535c.128-.133.26-.2.418-.2m1.37 1.706c.332 0 .733.065 1.216.399c.293.2.523.269 1.052.468h.003c.255.136.405.266.478.399v-.131a.57.57 0 0 1 .016.47c-.123.31-.516.643-1.063.842v.002c-.268.135-.501.333-.775.465c-.276.135-.588.292-1.012.267a1.1 1.1 0 0 1-.448-.067a4 4 0 0 1-.322-.198c-.195-.135-.363-.332-.612-.465v-.005h-.005c-.4-.246-.616-.512-.686-.71q-.104-.403.193-.6c.224-.135.38-.271.483-.336c.104-.074.143-.102.176-.131h.002v-.003c.169-.202.436-.47.839-.601c.139-.036.294-.065.466-.065zm2.8 2.142c.358 1.417 1.196 3.475 1.735 4.473c.286.534.855 1.659 1.102 3.024c.156-.005.33.018.513.064c.646-1.671-.546-3.467-1.089-3.966c-.22-.2-.232-.335-.123-.335c.59.534 1.365 1.572 1.646 2.757c.13.535.16 1.104.021 1.67c.067.028.135.06.205.067c1.032.534 1.413.938 1.23 1.537v-.043c-.06-.003-.12 0-.18 0h-.016c.151-.467-.182-.825-1.065-1.224c-.915-.4-1.646-.336-1.77.465c-.008.043-.013.066-.018.135c-.068.023-.139.053-.209.064c-.43.268-.662.669-.793 1.187c-.13.533-.17 1.156-.205 1.869v.003c-.02.334-.17.838-.319 1.35c-1.5 1.072-3.58 1.538-5.348.334a2.7 2.7 0 0 0-.402-.533a1.5 1.5 0 0 0-.275-.333c.182 0 .338-.03.465-.067a.62.62 0 0 0 .314-.334c.108-.267 0-.697-.345-1.163s-.931-.995-1.788-1.521c-.63-.4-.986-.87-1.15-1.396c-.165-.534-.143-1.085-.015-1.645c.245-1.07.873-2.11 1.274-2.763c.107-.065.037.135-.408.974c-.396.751-1.14 2.497-.122 3.854a8.1 8.1 0 0 1 .647-2.876c.564-1.278 1.743-3.504 1.836-5.268c.048.036.217.135.289.202c.218.133.38.333.59.465c.21.201.477.335.876.335q.058.005.11.006c.412 0 .73-.134.997-.268c.29-.134.52-.334.74-.4h.005c.467-.135.835-.402 1.044-.7zm2.185 8.958c.037.6.343 1.245.882 1.377c.588.134 1.434-.333 1.791-.765l.211-.01c.315-.007.577.01.847.268l.003.003c.208.199.305.53.391.876c.085.4.154.78.409 1.066c.486.527.645.906.636 1.14l.003-.007v.018l-.003-.012c-.015.262-.185.396-.498.595c-.63.401-1.746.712-2.457 1.57c-.618.737-1.37 1.14-2.036 1.191c-.664.053-1.237-.2-1.574-.898l-.005-.003c-.21-.4-.12-1.025.056-1.69c.176-.668.428-1.344.463-1.897c.037-.714.076-1.335.195-1.814c.12-.465.308-.797.641-.984l.045-.022zm-10.814.049h.01q.08 0 .157.014c.376.055.706.333 1.023.752l.91 1.664l.003.003c.243.533.754 1.064 1.189 1.637c.434.598.77 1.131.729 1.57v.006c-.057.744-.48 1.148-1.125 1.294c-.645.135-1.52.002-2.395-.464c-.968-.536-2.118-.469-2.857-.602q-.553-.1-.723-.4c-.11-.2-.113-.602.123-1.23v-.004l.002-.003c.117-.334.03-.752-.027-1.118c-.055-.401-.083-.71.043-.94c.16-.334.396-.4.69-.533c.294-.135.64-.202.915-.47h.002v-.002c.256-.268.445-.601.668-.838c.19-.201.38-.336.663-.336m7.159-9.074c-.435.201-.945.535-1.488.535c-.542 0-.97-.267-1.28-.466c-.154-.134-.28-.268-.373-.335c-.164-.134-.144-.333-.074-.333c.109.016.129.134.199.2c.096.066.215.2.36.333c.292.2.68.467 1.167.467c.485 0 1.053-.267 1.398-.466c.195-.135.445-.334.648-.467c.156-.136.149-.267.279-.267c.128.016.034.134-.147.332a8 8 0 0 1-.69.468zm-1.082-1.583V5.64c-.006-.02.013-.042.029-.05c.074-.043.18-.027.26.004c.063 0 .16.067.15.135c-.006.049-.085.066-.135.066c-.055 0-.092-.043-.141-.068c-.052-.018-.146-.008-.163-.065m-.551 0c-.02.058-.113.049-.166.066c-.047.025-.086.068-.14.068c-.05 0-.13-.02-.136-.068c-.01-.066.088-.133.15-.133c.08-.031.184-.047.259-.005c.019.009.036.03.03.05v.02h.003z"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={85} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">SQL</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M23.56 14.723a.5.5 0 0 0-.057-.12q-.21-.395-1.007-.231c-1.654.34-2.294.13-2.526-.02c1.342-2.048 2.445-4.522 3.041-6.83c.272-1.05.798-3.523.122-4.73a1.6 1.6 0 0 0-.15-.236C21.693.91 19.8.025 17.51.001c-1.495-.016-2.77.346-3.116.479a10 10 0 0 0-.516-.082a8 8 0 0 0-1.312-.127c-1.182-.019-2.203.264-3.05.84C8.66.79 4.729-.534 2.296 1.19C.935 2.153.309 3.873.43 6.304c.041.818.507 3.334 1.243 5.744q.69 2.26 1.433 3.582q.83 1.493 1.714 1.79c.448.148 1.133.143 1.858-.729a56 56 0 0 1 1.945-2.206c.435.235.906.362 1.39.377v.004a11 11 0 0 0-.247.305c-.339.43-.41.52-1.5.745c-.31.064-1.134.233-1.146.811a.6.6 0 0 0 .091.327c.227.423.922.61 1.015.633c1.335.333 2.505.092 3.372-.679c-.017 2.231.077 4.418.345 5.088c.221.553.762 1.904 2.47 1.904q.375.001.829-.094c1.782-.382 2.556-1.17 2.855-2.906c.15-.87.402-2.875.539-4.101c.017-.07.036-.12.057-.136c0 0 .07-.048.427.03l.044.007l.254.022l.015.001c.847.039 1.911-.142 2.531-.43c.644-.3 1.806-1.033 1.595-1.67M2.37 11.876c-.744-2.435-1.178-4.885-1.212-5.571c-.109-2.172.417-3.683 1.562-4.493c1.837-1.299 4.84-.54 6.108-.13l-.01.01C6.795 3.734 6.843 7.226 6.85 7.44c0 .082.006.199.016.36c.034.586.1 1.68-.074 2.918c-.16 1.15.194 2.276.973 3.089q.12.126.252.237c-.347.371-1.1 1.193-1.903 2.158c-.568.682-.96.551-1.088.508c-.392-.13-.813-.587-1.239-1.322c-.48-.839-.963-2.032-1.415-3.512m6.007 5.088a1.6 1.6 0 0 1-.432-.178c.089-.039.237-.09.483-.14c1.284-.265 1.482-.451 1.915-1a8 8 0 0 1 .367-.443a.4.4 0 0 0 .074-.13c.17-.151.272-.11.436-.042c.156.065.308.26.37.475c.03.102.062.295-.045.445c-.904 1.266-2.222 1.25-3.168 1.013m2.094-3.988l-.052.14c-.133.357-.257.689-.334 1.004c-.667-.002-1.317-.288-1.81-.803c-.628-.655-.913-1.566-.783-2.5c.183-1.308.116-2.447.08-3.059l-.013-.22c.296-.262 1.666-.996 2.643-.772c.446.102.718.406.83.928c.585 2.704.078 3.83-.33 4.736a9 9 0 0 0-.23.546m7.364 4.572q-.024.266-.062.596l-.146.438a.4.4 0 0 0-.018.108c-.006.475-.054.649-.115.87a4.8 4.8 0 0 0-.18 1.057c-.11 1.414-.878 2.227-2.417 2.556c-1.515.325-1.784-.496-2.02-1.221a7 7 0 0 0-.078-.227c-.215-.586-.19-1.412-.157-2.555c.016-.561-.025-1.901-.33-2.646q.006-.44.019-.892a.4.4 0 0 0-.016-.113a2 2 0 0 0-.044-.208c-.122-.428-.42-.786-.78-.935c-.142-.059-.403-.167-.717-.087c.067-.276.183-.587.309-.925l.053-.142c.06-.16.134-.325.213-.5c.426-.948 1.01-2.246.376-5.178c-.237-1.098-1.03-1.634-2.232-1.51c-.72.075-1.38.366-1.709.532a6 6 0 0 0-.196.104c.092-1.106.439-3.174 1.736-4.482a4 4 0 0 1 .303-.276a.35.35 0 0 0 .145-.064c.752-.57 1.695-.85 2.802-.833q.616.01 1.174.081c1.94.355 3.244 1.447 4.036 2.383c.814.962 1.255 1.931 1.431 2.454c-1.323-.134-2.223.127-2.68.78c-.992 1.418.544 4.172 1.282 5.496c.135.242.252.452.289.54c.24.583.551.972.778 1.256c.07.087.138.171.189.245c-.4.116-1.12.383-1.055 1.717a35 35 0 0 1-.084.815c-.046.208-.07.46-.1.766m.89-1.621c-.04-.832.27-.919.597-1.01l.135-.041a1 1 0 0 0 .134.103c.57.376 1.583.421 3.007.134c-.202.177-.519.4-.953.601c-.41.19-1.096.333-1.747.364c-.72.034-1.086-.08-1.173-.151m.57-9.271a7 7 0 0 1-.105 1.001c-.055.358-.112.728-.127 1.177c-.014.436.04.89.093 1.33c.107.887.216 1.8-.207 2.701a4 4 0 0 1-.188-.385a8 8 0 0 0-.325-.617c-.616-1.104-2.057-3.69-1.32-4.744c.38-.543 1.342-.566 2.179-.463m.228 7.013l-.085-.107l-.035-.044c.726-1.2.584-2.387.457-3.439c-.052-.432-.1-.84-.088-1.222c.013-.407.066-.755.118-1.092c.064-.415.13-.844.111-1.35a.6.6 0 0 0 .012-.19c-.046-.486-.6-1.938-1.73-3.253a7.8 7.8 0 0 0-2.688-2.04A9.3 9.3 0 0 1 17.62.746c2.052.046 3.675.814 4.824 2.283a1 1 0 0 1 .067.1c.723 1.356-.276 6.275-2.987 10.54m-8.816-6.116c-.025.18-.31.423-.621.423l-.081-.006a.8.8 0 0 1-.506-.315c-.046-.06-.12-.178-.106-.285a.22.22 0 0 1 .093-.149c.118-.089.352-.122.61-.086c.316.044.642.193.61.418m7.93-.411c.011.08-.049.2-.153.31a.72.72 0 0 1-.408.223l-.075.005c-.293 0-.541-.234-.56-.371c-.024-.177.264-.31.56-.352c.298-.042.612.009.636.185"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={65} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Photoshop</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 24 24"
              ><path
                fill="white"
                d="M10.45 10.48a1.3 1.3 0 0 1-1 1.33a4.8 4.8 0 0 1-1.61.19c-.14 0-.15-.09-.15-.19V9.26c0-.07.07-.19.11-.19a4.9 4.9 0 0 1 1.71.11a1.28 1.28 0 0 1 .94 1.3"
              /><path
                fill="white"
                d="M17 2H7a5 5 0 0 0-5 5v10a5 5 0 0 0 5 5h10a5 5 0 0 0 5-5V7a5 5 0 0 0-5-5m-6 11a3.5 3.5 0 0 1-1.68.54H7.98c-.28 0-.28 0-.28.27v2.32c0 .2-.06.26-.26.26H6.12c-.19 0-.24-.07-.24-.25V7.71c0-.2 0-.26.25-.26h3.13a3.34 3.34 0 0 1 1.62.47a2.75 2.75 0 0 1 1.4 2.39A2.83 2.83 0 0 1 11 13m5.92 3.3a4.6 4.6 0 0 1-2.73.19q-.409-.09-.8-.24a.29.29 0 0 1-.16-.2v-1.51c.32.12.62.26.93.36a3.66 3.66 0 0 0 1.61.14q.162-.03.31-.1a.37.37 0 0 0 .08-.63a4 4 0 0 0-.73-.4c-.41-.2-.83-.36-1.22-.59a1.82 1.82 0 0 1-1-1.93a2 2 0 0 1 1.36-1.63a4.2 4.2 0 0 1 2-.17c.32 0 .63.12.95.18c.17 0 .23.14.22.31v1.17c0 .22-.05.24-.25.16a3.87 3.87 0 0 0-2-.34a.9.9 0 0 0-.28.08a.37.37 0 0 0-.1.63q.434.289.91.5c.38.19.78.34 1.15.55a1.73 1.73 0 0 1 1 1.79a1.92 1.92 0 0 1-1.26 1.64z"
              /></svg
            >
          </div>

          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={85} max={100} />
        </section>
      </div>
      <div class="card shadow-lg rounded-lg overflow-hidden max-w-xs mx-auto">
        <header class="card-header p-4">
          <h2 class="text-xl font-bold text-center">Blender</h2>
        </header>
        <section class="p-4">
          <div class="flex justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="5rem"
              height="5rem"
              viewBox="0 0 512 512"
              ><path
                fill="white"
                d="M449.5 177.293L289.101 54.105c-10.506-8.067-28.159-8.031-39.695.043c-11.681 8.158-13.028 21.682-2.647 30.21l66.707 54.286H109.794c-16.813.007-32.975 11.265-36.164 25.214c-3.297 14.202 8.115 25.848 25.596 25.902h103.08L17.632 331.506C.277 344.786-5.324 366.893 5.607 380.87c11.085 14.228 34.682 14.256 52.217.08l100.405-82.166s-1.473 11.084-1.356 17.742c3.019 56.204 45.868 108.306 98.923 131.381c91.42 40.492 214.849 3.424 249.557-102.103c16.506-55.355 3.852-121.18-55.854-168.51M279.463 373.509c-72.203-37.792-72.204-132.787 0-170.58s162.948 9.705 162.948 85.29s-90.744 123.083-162.948 85.29m21.989-34.01c-46.055-24.087-46.055-84.633 0-108.72s103.935 6.185 103.935 54.36s-57.881 78.448-103.935 54.36"
              /></svg
            >
          </div>
          <p class="my-4 text-gray-300">
            Python is a versatile programming language known for its readability
            and broad applicability in web development, data analysis,
            artificial intelligence, and more.
          </p>
          <ProgressBar value={75} max={100} />
        </section>
      </div>
    </div>

    <h2 class="text-2xl font-bold mt-8 mb-4">Resume</h2>
    <hr class="border-t-2 border-gray-300" />
    <h3 class="text-xl font-semibold mt-4 mb-2">Professional Experience</h3>
    <p class="text-lg mb-4">Here is a summary of my professional experience:</p>
    <ul class="list-disc pl-5 mb-4">
      <li>Software Developer at XYZ Corp</li>
      <li>Frontend Engineer at ABC Inc</li>
    </ul>

    <h2 class="text-2xl font-bold mt-8 mb-4">About</h2>
    <hr class="border-t-2 border-gray-300" />
    <h3 class="text-xl font-semibold mt-4 mb-2">About Me</h3>
    <p class="text-lg mb-4">
      I am a passionate software developer with a love for creating innovative
      solutions.
    </p>
  </div>
</main>

