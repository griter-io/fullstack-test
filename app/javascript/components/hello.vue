<template>
  <div class="min-h-screen bg-gray-50 py-8 flex flex-col justify-center relative overflow-hidden lg:py-12">
    <div
      class="relative w-full px-6 py-12 bg-white shadow-xl shadow-slate-700/10 ring-1 ring-gray-900/5 md:max-w-3xl md:mx-auto lg:max-w-4xl lg:pt-16 lg:pb-28">
      <div class="mt-8 prose prose-slate mx-auto lg:prose-lg">
        <h1>
          {{ title }}
        </h1>
        <p>
          <strong>Scenario:</strong> You are required to develop simple & minimize book store web app. To help user to
          record and update the book information. We are providing a github repository for you to use as a starting
          point. You may fork this repo and create a pull request when you're done.
        </p>

        <p>
          <strong>Goal:</strong> To asses your skills level of Ruby on Rails.
        </p>

        <h2>
          <strong>Requirements</strong>
        </h2>

        <p>
        <ul>
          <li>
            Create CRUDs (Index, Show, New, Create, Edit, Update, Destroy) for the following resource:
            <ul>
              <li>Book: title, author, genre, serial_number, published_year, fiction(boolean)</li>
              <li>Author: name</li>
              <li>Genre: name</li>
            </ul>
          </li>
          <li>Form validation where you see fit</li>
        </ul>
        </p>

        <h2>Bonus Points</h2>
        <p>
        <ul>
          <li>Test Driven Development (TDD)</li>
          <li>User authentication, protect the app behind a login page (hint: an user account has been created, login with <i>user@griter.io:password</i>)</li>
          <li>File upload for book cover</li>
          <li>UI components using Vue.js</li>
          <li>Use of Tailwind CSS</li>
        </ul>
        </p>

        <h2>What we are looking for</h2>
        <p>
          <ul>
            <li>Completion of the requirements</li>
            <li>Small commits</li>
            <li>Comments on code when required</li>
            <li>DRY code</li>
          </ul>
          <span>You do not need to deploy the app but make sure it's ready for demo</span>
        </p>

        <h2>Codebase Setup</h2>
        <p>
        <ul>
          <li>
            <strong>Prerequisites:</strong> Ruby 2.7.2, Node.js 14 or above
          </li>
          <li>Run <code>bundle install</code></li>
          <li>Run <code>yarn install</code></li>
          <li>Run <code>rails s</code></li>
          <li>On second terminal, run <code>bin/webpack-dev-server</code></li>
          <li>Visit <a href="http://localhost:3000">localhost</a></li>
          <li>Voila! You're here.</li>
        </ul>
        </p>
        <p>
          Feel free to contact us if you have any questions.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      title: 'Book Store App'
    }
  }
}
</script>
