pages:
  stage: deploy
  script:
    - mkdir public
    - cp -r * public
  artifacts:
    paths:
      - public
