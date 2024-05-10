// Function to change the user agent
function setUserAgent(userAgent) {
  Object.defineProperty(navigator, 'userAgent', {
    get: () => userAgent,
  });
}

// Set user agent to a mobile device
setUserAgent('Mozilla/5.0 (iPhone; CPU iPhone OS 13_2_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148');

// Now access the main part of the web app
