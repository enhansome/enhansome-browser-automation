# Awesome Browser Automation with stars

A curated list of awesome browser automation tools and resources.

Browser automation is the act of executing actions automatically in a web browser for testing, [web scraping](https://en.wikipedia.org/wiki/Web_scraping) or to perform repetitive tasks faster. Specialized software is usually required to do this. This software may control an external browser or be a browser itself.

## Contents

* [Tools](#tools)
  * [AI](#ai)
  * [Related tools](#related-tools)
* [Articles](#articles)
* [Resources](#resources)

## Tools

* [Playwright](https://github.com/microsoft/playwright) ⭐ 98,905 | 🐛 46 | 🌐 TypeScript | 📅 2026-10-31 - Cross-browser web automation platform for Node.js.
  * [invisible-playwright](https://github.com/feder-cr/invisible_playwright) ⭐ 2,541 | 🐛 6 | 🌐 Python | 📅 2026-10-31 - Drop-in Playwright wrapper that launches a stealth-patched Firefox 150 binary instead of vanilla Firefox.
* [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 95,772 | 🐛 214 | 🌐 TypeScript | 📅 2026-10-30 - High level API in Node.js to control Chrome.
  * [Puppeteer-Extra](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra) ⭐ 7,414 | 🐛 277 | 🌐 JavaScript | 📅 2024-07-18 - Plugin support for Puppeteer and several plugins including reCAPTCHA and adblocker.
  * [Pyppeteer](https://github.com/miyakogi/pyppeteer) ⚠️ Archived - Unofficial port of Puppeteer to Python.
  * [Browserless](https://browserless.js.org) - Complementary library for Puppeteer with sensible defaults, adblocker and pooling.
  * [Headless Recorder](https://www.checklyhq.com/docs/headless-recorder) - Chrome extension that records your browser interactions and generates a Puppeteer or Playwright script.
* [PhantomJS](https://github.com/ariya/phantomjs) ⚠️ Archived - Headless browser for Node.js.
* [Chromedp](https://github.com/chromedp/chromedp) ⭐ 13,346 | 🐛 1 | 🌐 Go | 📅 2026-10-11 - Browser automation through Chrome DevTools Protocol fully implemented in Go.
* [Capybara](https://github.com/teamcapybara/capybara) ⭐ 10,174 | 🐛 27 | 🌐 Ruby | 📅 2026-10-05 - Driver-agnostic tool and DSL to write automation tests in Ruby.
* [Codeception](https://github.com/codeception/codeception) ⭐ 4,853 | 🐛 170 | 🌐 PHP | 📅 2026-10-03 - PHP end-to-end testing with BDD style.
* [CodeceptJS](https://github.com/Codeception/CodeceptJS) ⭐ 4,248 | 🐛 187 | 🌐 JavaScript | 📅 2026-10-30 - BDD style tests with support for multiple headless browsers.
* [Erik](https://github.com/phimage/Erik) ⭐ 610 | 🐛 8 | 🌐 Swift | 📅 2022-08-05 - Headless browser for functional tests in Swift, based on WebKit and [Kanna](https://github.com/tid-kijyun/Kanna) ⭐ 2,487 | 🐛 13 | 🌐 Swift | 📅 2026-02-25.
* [SimpleBrowser](https://github.com/SimpleBrowserDotNet/SimpleBrowser) ⭐ 365 | 🐛 20 | 🌐 C# | 📅 2023-11-26 - Browser automation engine build on .NET.
* [Wendigo](https://github.com/angrykoala/wendigo) ⭐ 151 | 🐛 21 | 🌐 JavaScript | 📅 2024-03-08 - Test-oriented automation tool built on top of Puppeteer.
* [WebParsy](https://github.com/joseconstela/webparsy) ⭐ 48 | 🐛 19 | 🌐 JavaScript | 📅 2022-12-30 - Web scraping library and CLI using Puppeteer and YAML.
* [Axiom](https://axiom.ai) - No code browser automation tool, like Zapier.
* [Browserflow](https://browserflow.app) - Chrome extension to automate your local browser or in the cloud.
* [Cypress](https://www.cypress.io) - E2E testing for JavaScript through a browser.
* [Endtest](https://endtest.io) - Cloud-based codeless automated testing.
* [Katalon Recorder](https://chrome.google.com/webstore/detail/katalon-recorder-selenium/ljdobmomdgdljniojadhoplhkpialdid) - A solution to kick-start test automation for small companies & start-ups.
* [Mechanize](https://mechanize.readthedocs.io/en/latest) - Programmatic web browser emulation in Python.
* [QAWolf](https://docs.qawolf.com) - Create Puppeteer tests by recording actions.
* [PhantomBuster](https://phantombuster.com) - Automate web scraping and actions without coding.
* [Selenium](https://www.seleniumhq.org) - Suite to automate multiple browsers in different platforms.
  * [PHP-Webdriver](https://github.com/php-webdriver/php-webdriver) ⭐ 5,194 | 🐛 34 | 🌐 PHP | 📅 2026-10-28 - PHP Client for Selenium/WebDriver.
* [Splinter](https://splinter.readthedocs.io/en/latest/index.html) - Python abstraction of existing browser automation tools with a high-level API for testing.
* [TestCafe](https://devexpress.github.io/testcafe) - Full end-to-end testing environment supporting multiple browsers.
* [Watir](http://watir.com) - Ruby library for automating tests powered by Selenium.
* [WebdriverIO](http://webdriver.io) - WebDriver bindings to Node.js that lets you control a browser.

### AI

* [Browser-Use](https://github.com/browser-use/browser-use) ⭐ 119,599 | 🐛 641 | 🌐 Python | 📅 2026-10-31 - Python library and service to automate browsing using AI agents and Chrome DevTools Protocol.
* [Agent Browser](https://github.com/vercel-labs/agent-browser) ⭐ 44,935 | 🐛 616 | 🌐 Rust | 📅 2026-10-31 - Fast browser automation CLI for AI agents with semantic snapshots, session persistence, and MCP support.
* [Playwright MCP](https://github.com/microsoft/playwright-mcp) ⭐ 38,875 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-31 - Provides browser automation capabilities using [Playwright](https://github.com/microsoft/playwright) ⭐ 98,905 | 🐛 46 | 🌐 TypeScript | 📅 2026-10-31
* [Skyvern](https://github.com/Skyvern-AI/Skyvern) ⭐ 23,316 | 🐛 292 | 🌐 Python | 📅 2026-10-31 - Use prompts + AI to automate actions in the browser.
* [CamoFox Browser](https://github.com/jo-inc/camofox-browser) ⭐ 12,078 | 🐛 119 | 🌐 JavaScript | 📅 2026-10-23 - Stealth headless browser for AI agents built on a Firefox fork with C++ fingerprint spoofing to bypass Cloudflare, Akamai, and bot detection.
* [Openwork](https://github.com/accomplish-ai/openwork) ⭐ 10,824 | 🐛 13 | 📅 2026-08-13 - MIT-licensed, open alternative to Anthropic's Cowork. Supports multiple LLM providers for launching computer-use agents to automate browser workflows.
* [Steel Browser](https://github.com/steel-dev/steel-browser) ⭐ 7,893 | 🐛 77 | 🌐 TypeScript | 📅 2026-10-30 - Open-source browser sandbox and API for AI agents with session-backed automation, screenshots, PDFs, and anti-bot tooling.
* [Webcmd](https://github.com/agentrhq/webcmd) ⭐ 2,755 | 🐛 52 | 🌐 TypeScript | 📅 2026-10-20 - CLI that learns a site's navigation once and compiles it into reusable deterministic commands for AI agents.
* [Libretto](https://github.com/saffron-health/libretto) ⭐ 907 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-21 - Open-source Playwright-based toolkit and CLI for coding agents to inspect pages, capture network traffic, record actions, and generate automation scripts.
* [Clawbrowser](https://github.com/clawbrowser/clawbrowser) ⭐ 136 | 🐛 1 | 🌐 C++ | 📅 2026-10-23 - Managed Chromium runtime for AI agents with isolated profiles, built-in fingerprint and proxy management, exposed over CDP for Playwright and Puppeteer.
* [onUI](https://github.com/onllm-dev/onUI) ⭐ 105 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-28 - Browser extension and MCP server for annotation-first UI pair programming with AI agents.
* [Alumnium](https://alumnium.ai) - Open-source AI-powered test automation library on top of Playwright/Selenium.
* [BrowserBook](https://browserbook.com) - AI-powered browser automation IDE with inline browser & coding agent built on top of Playwright.

### Related tools

* [Cheerio](https://github.com/cheeriojs/cheerio) ⭐ 30,540 | 🐛 86 | 🌐 TypeScript | 📅 2026-10-30 - jQuery implementation in Node.js for DOM emulation.
* [jsdom](https://github.com/jsdom/jsdom) ⭐ 21,742 | 🐛 244 | 🌐 JavaScript | 📅 2026-10-30 - DOM implementation in Node.js to emulate real browsers.
* [Node-crawler](https://github.com/bda-research/node-crawler) ⭐ 6,796 | 🐛 30 | 🌐 TypeScript | 📅 2026-06-18 - Web Crawler/Spider for Node.js using server-side DOM.
* [X-Ray](https://github.com/matthewmueller/x-ray) ⭐ 5,902 | 🐛 74 | 🌐 JavaScript | 📅 2026-08-31 - Web Scraper with composable API and extra drivers.
* [Buglesstack](https://buglesstack.com/) - Debugging platform for browser automation tools.
* [Postman](https://www.getpostman.com) - API requests and development tool with automation options.

## Articles

* [Cucumber Browser Automation](https://cucumber.io/docs/guides/browser-automation) - Guide for [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development) testing using Selenium with Cucumber.
* [Guide to Web Automation](https://hackernoon.com/guide-to-web-automation-889557804453) - Guide covering different tools and techniques for web automation.
* [Martin Fowler - PageObject](https://martinfowler.com/bliki/PageObject.html) - An article describing the basic concepts of page object pattern.
* [Modern Web Automation With Python and Selenium](https://realpython.com/modern-web-automation-with-python-and-selenium) - Tutorial for getting started with Selenium in Python.

## Resources

* [Awesome Web Scraping](https://github.com/lorien/awesome-web-scraping) ⭐ 8,201 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-27 - Comprehensive list of tools, programming libraries and web services used in web scraping.
* [HeadlessBrowsers](https://github.com/dhamaniasad/HeadlessBrowsers) ⭐ 6,703 | 🐛 24 | 📅 2025-10-12 - Detailed list of multiple headless browsers.
* [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium#readme) ⭐ 1,136 | 🐛 13 | 📅 2026-09-19 - Curated list of Selenium resources and related tools.
* [WebDriver Specification](https://www.w3.org/TR/webdriver1) - Standard definition of agents to control a browser.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-31._
