% Diff between report from "July 19, 2024" and reference report from "July 18, 2024"
% Strudy
% July 19, 2024

## Web IDL Standard

- Initial URL: [https://webidl.spec.whatwg.org/](https://webidl.spec.whatwg.org/)
- Crawled URL: [undefined](undefined)
- Editor's Draft: [https://webidl.spec.whatwg.org/](https://webidl.spec.whatwg.org/)
- Spec could not be rendered: *INS* Error: Loading https://webidl.spec.whatwg.org/ triggered network error
    at processSpecification (/home/runner/work/webref/webref/node_modules/reffy/src/lib/util.js:486:19)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async crawlSpec (/home/runner/work/webref/webref/node_modules/reffy/src/lib/specs-crawler.js:107:22)
    at async processSpec (/home/runner/work/webref/webref/node_modules/reffy/src/lib/specs-crawler.js:349:22)
    at async ThrottledQueue.runThrottled (/home/runner/work/webref/webref/node_modules/reffy/src/lib/throttled-queue.js:78:22)
    at async Promise.all (index 179)
    at async crawlList (/home/runner/work/webref/webref/node_modules/reffy/src/lib/specs-crawler.js:370:21) {
  [cause]: TypeError: fetch failed
      at node:internal/deps/undici/undici:12502:13
      at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
      at async fetchWithRetry (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:491:16)
      at async fetchWithRetry (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:497:16)
      at async fetchWithRetry (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:497:16)
      at async fetchWithRetry (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:497:16)
      at async conditionalFetch (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:501:20)
      at async cacheFetch (/home/runner/work/webref/webref/node_modules/fetch-filecache-for-crawling/fetch-filecache.js:531:24)
      at async processSpecification (/home/runner/work/webref/webref/node_modules/reffy/src/lib/util.js:480:24)
      at async crawlSpec (/home/runner/work/webref/webref/node_modules/reffy/src/lib/specs-crawler.js:107:22) {
    [cause]: ConnectTimeoutError: Connect Timeout Error
        at onConnectTimeout (node:internal/deps/undici/undici:6635:28)
        at node:internal/deps/undici/undici:6587:50
        at Immediate._onImmediate (node:internal/deps/undici/undici:6619:13)
        at process.processImmediate (node:internal/timers:478:21) {
      code: 'UND_ERR_CONNECT_TIMEOUT'
    }
  }
}



