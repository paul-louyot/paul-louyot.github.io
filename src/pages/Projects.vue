<template>
  <Layout>
  <h1 class="pb-4">Projects</h1>
    <div class="flex flex-col sm:flex-row sm:justify-around">
      <div class="rounded overflow-hidden shadow-lg flex-1 sm:max-w-md">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">This website</div>
          <p class="text-gray-700 text-base">
            This is my personal website.
          </p>
          <a
            href="https://github.com/paul-louyot/paul-louyot.github.io"
            target="_blank"
            rel="noopener"
          >
            Github
            <!-- add illustration -->
          </a>
        </div>
      </div>
      <div class="rounded overflow-hidden shadow-lg flex-1 sm:max-w-md">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Wiki</div>
          <p class="text-gray-700 text-base">
            A place to share what I learn.
          </p>
          <a
            href="https://paul-louyot.gitbook.io/wiki/"
            target="_blank"
            rel="noopener"
          >
            Website
            <!-- add illustration -->
          </a>
          </br>
          <a
            href="https://github.com/paul-louyot/wiki"
            target="_blank"
            rel="noopener"
          >
            Github
            <!-- add illustration -->
          </a>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Projects'
  }
}
</script>

<style>
</style>
