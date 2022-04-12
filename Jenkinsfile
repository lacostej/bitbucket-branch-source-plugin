#!groovy

buildPlugin(configurations: [
  [platform: 'linux', jdk: '8'],
  [platform: 'linux', jdk: '11'],
  [platform: 'windows', jdk: '11'],

  // Test the bleeding edge of the compatibility spectrum (i.e., the latest supported Java runtime).
  [platform: 'linux', jdk: '17', jenkins: '2.342'],
])
