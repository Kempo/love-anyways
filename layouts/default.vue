<template>
  <div>
    <nuxt />
    <footer>
      <div class="d-flex justify-content-end">
        <div class="links">
          <p><b>Contact</b></p>
          <ul>
            <li>Facebook</li>
            <li>Instagram</li>
            <li>Email</li>
          </ul>
        </div>
      </div>
      <p>Made with ❤️ in Seattle</p>
    </footer>
  </div>
</template>

<style>
.links {
  margin-right: 25px;
}

footer {
  padding: 40px 40px 10px 40px;
  background-color: rgba(0, 0, 0, 0.03);
}

ul {
  margin: 0px; /* just removing default styles */
  padding: 0px;
  list-style-type: none;
}

html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
