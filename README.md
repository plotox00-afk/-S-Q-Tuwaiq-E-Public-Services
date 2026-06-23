fetch("https://httpbin.org/get", {
  headers: {
    Date: new Date().toUTCString(),
  },
});
