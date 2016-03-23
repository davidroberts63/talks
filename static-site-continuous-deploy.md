# Test and continuously deploy with nearly any static site tool.

You may have used the Jekyll integration in Github Pages for your site; but moved onto some other static tool or web host. At the same time you may have lost that ease of deployment. No longer able to 'git push' and walk away knowing the site will get updated. There is a way to get that back.

In this talk you will see how to regain a continuous deployment process for virtually any static site generator or web host. You will also see a node app that provides site previews of changes as 'test' results in your github issue. Join us as we use PhantomJS and Express.js to discover how you can keep delivering and have your static site too.

### Points covered
- The few commands to gen and deploy your static site again automatically upon push
- Using PhantomJS to produce screenshots during build
- Using node to post screenshots to GitHub issue
- Note some functional style areas of the node app and how it helped
- Brief look at Express.js and the Github node module
- Security concerns with keys
- Live example (if possible but not required)
