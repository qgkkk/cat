
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimum-scale=1.0, maximum-scale=0.0, viewport-fit=cover">
<title>CatVodOpen最新下载</title>
<style>
body{background-color: #0d1117;color:#fff;}
.wrap{margin:30px auto;Width:90%;font-size:14px;/*max-width:1024px;*/}
.wrap a.title{text-decoration:none;}
.wrap a.title h1{background-color: #8a57ea;padding: 10px;text-align: center;color:#eee;text-decoration: none;}
.wrap h3.title{background-color: #0d8050;padding: 5px 10px;background: linear-gradient(to right, #0d8050, #333) no-repeat right bottom;text-shadow: 0 1px white;}
.wrap .bb {
    /*border-bottom: 1px solid #999;*/flex-wrap: wrap;
    display: flex;
    flex-direction: row;
    padding: 2px 0;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(to right, #db3737, #48aff0) no-repeat right bottom;
    background-size: 0 2px;
    transition: background-size 500ms;
}
.wrap .bb:nth-child(odd){background-color:#6c899f38;}
.wrap .bb:hover{background-size: 100% 2px;background-position-x: left;}
.wrap .bb a{text-decoration: none;color:#fff;display: inline-block;padding: 2px 5px;line-height: 20px;white-space: nowrap;vertical-align: middle;cursor: pointer;user-select: none;font-size: 14px;}
.wrap .bb a:hover{background-color:#48aff078}
.wrap .bb .fast{}
.wrap .bb .fast span{display: inline-block;padding: 3px 5px;line-height: 20px;white-space: nowrap;vertical-align: middle;user-select: none;}
svg{position: relative;top: 5px;}
@media (max-width: 888px){
    .wrap {Width:100%;font-size:12px;}
    .wrap .bb{flex-wrap: wrap;}
    /*.wrap .bb a.title{display:block;}*/
    .wrap .bb .fast{float:none;display: flex;justify-content:center;flex-wrap: wrap;}
}
.wrap .bb.on{flex-wrap: wrap;}
.wrap .bb.on .name{white-space: normal;}
.wrap .bb.on .fast{flex-wrap: wrap;}
#show{color:white;text-decoration:none;font-size:20px;}
/*.markdown-body{display:none;}*/
</style>
</head>
<body class="line-numbers">
<div class="wrap">
<a id='show' href='javascript:show()'>🔗更新说明</a><div id='content' class='markdown-body' style='display:none;'><p><strong>2024/03/01 open_1.1.3_preview2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Fix  issue of config.js failing to load after reset the Node.js http port.</h2>
</li>
</ul>
<p><strong>2024/02/27 open_1.1.3_preview1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>The first version integrated the Node.js runtime, the current Node version is <code>18.17.1</code>.</li>
<li>Also add supports using the <code>.md5</code> extension for config files, which allows for quick detection of changes in the config files. If a change is detected, the files will be reloaded, otherwise, the cached version will be read. For example, &quot;index.js.md5&quot;.</li>
<li>
<h2>To enable the Node.js runtime, you can use the build dist (<a href="https://github.com/catvod/CatVodOpen/blob/main/nodejs/dist_demo/index.js"><code>index.js</code></a> / <a href="https://github.com/catvod/CatVodOpen/blob/main/nodejs/dist_demo/index.js.md5"><code>index.js.md5</code></a>) from the <a href="https://github.com/catvod/CatVodOpen/tree/main/nodejs"><code>Node.js project</code></a> as a api config. The old JSON format config will still be processed using the QuickJS runtime.</h2>
</li>
</ul>
<p><strong>2024/01/23 open_1.1.2_fix5</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Do not show startup warning tips again within a certain period of time.</h2>
</li>
</ul>
<p><strong>2024/01/23 open_1.1.2_fix4</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Bugfix.</li>
<li>Add chapter pagination  to txt novel reader &amp; comic reader.</li>
<li>Optimize the performance of infinite scrolling on the novel reader.</li>
<li>Imporve js dom selector speed.</li>
<li>Support line wrapping for category filtter buttons <a href="https://github.com/catvod/CatVodOpen/blob/main/open/copymanga_open.js#L80"><code>wrap: 1</code></a>.</li>
<li>
<h2>Add shared function to class JSFile, file to sharedBuffer.</h2>
</li>
</ul>
<p><strong>2024/01/19 open_1.1.2_fix3</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Merge the txt novel module, spider demo <a href="https://github.com/catvod/CatVodOpen/blob/main/open/13bqg_open.js"><code>13bqg_open.js</code></a>.</li>
<li>Note: Please add the <a href="https://github.com/catvod/CatVodOpen/blob/main/open/bookan_open.js#L67"><code>audio:1</code></a> flag to the data returned by the detail function for the existing audio book spider.</li>
<li>Fix occasional memory errors in the JS engine.</li>
<li>Optimize the eval speed of the JS engine.</li>
<li>
<h2>Bugfix.</h2>
</li>
</ul>
<p><strong>2024/01/15 open_1.1.2_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Bugfix.</li>
<li>Merge comic support.</li>
<li>
<h2>Please refer to <a href="https://github.com/catvod/CatVodOpen/blob/main/open/copymanga_open.js"><code>copymanga_open.js</code></a> and <a href="https://github.com/catvod/CatVodOpen/blob/main/open/config_open.json#L32"><code>config_open.json</code></a> for more details.</h2>
</li>
</ul>
<p><strong>2024/01/14 open_1.1.2_fix1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Merge config custom color support.</li>
<li>Bugfix.
<pre><code>"color": [
    {
        "light": { "bg": "https://i2.100024.xyz/2024/01/13/qrnuwt.webp", "bgMask": "0x50ffffff", "primary": "0xFF2B6C00", "onPrimary": "0xFFFFFFFF", "primaryContainer": "0xFFA6F779", "onPrimaryContainer": "0xFF082100", "secondary": "0xFF55624C", "onSecondary": "0xFFFFFFFF", "secondaryContainer": "0xFFD9E7CA", "onSecondaryContainer": "0xFF131F0D", "tertiary": "0xFF386666", "onTertiary": "0xFFFFFFFF", "tertiaryContainer": "0xFFBBEBEB", "onTertiaryContainer": "0xFF002020", "error": "0xFFBA1A1A", "onError": "0xFFFFFFFF", "errorContainer": "0xFFFFDAD6", "onErrorContainer": "0xFF410002", "background": "0xFFFDFDF5", "onBackground": "0xFF1A1C18", "surface": "0xFFFDFDF5", "onSurface": "0xFF1A1C18", "surfaceVariant": "0xFFE0E4D6", "onSurfaceVariant": "0xFF1A1C18", "inverseSurface": "0xFF2F312C", "onInverseSurface": "0xFFF1F1EA", "outline": "0xFF74796D", "outlineVariant": "0xFFC3C8BB", "shadow": "0xFF000000", "scrim": "0xFF000000", "inversePrimary": "0xFF8CDA60", "surfaceTint": "0xFF2B6C00" },
        "dark": { "bg": "https://i2.100024.xyz/2024/01/13/qrc37o.webp", "bgMask": "0x50000000", "primary": "0xFF8CDA60", "onPrimary": "0xFF133800", "primaryContainer": "0xFF1F5100", "onPrimaryContainer": "0xFFA6F779", "secondary": "0xFFBDCBAF", "onSecondary": "0xFF283420", "secondaryContainer": "0xFF3E4A35", "onSecondaryContainer": "0xFFD9E7CA", "tertiary": "0xFFA0CFCF", "onTertiary": "0xFF003737", "tertiaryContainer": "0xFF1E4E4E", "onTertiaryContainer": "0xFFBBEBEB", "error": "0xFFFFB4AB", "errorContainer": "0xFF93000A", "onError": "0xFF690005", "onErrorContainer": "0xFFFFDAD6", "background": "0xFF1A1C18", "onBackground": "0xFFE3E3DC", "outline": "0xFF8D9286", "onInverseSurface": "0xFF1A1C18", "inverseSurface": "0xFFE3E3DC", "inversePrimary": "0xFF2B6C00", "shadow": "0xFF000000", "surfaceTint": "0xFF8CDA60", "outlineVariant": "0xFF43483E", "scrim": "0xFF000000", "surface": "0xFF1A1C18", "onSurface": "0xFFC7C7C0", "surfaceVariant": "0xFF43483E", "onSurfaceVariant": "0xFFC7C7C0" }
    }
]</code></pre></li>
</ul>
<hr />
<p><strong>2024/01/13 open_1.1.2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Cumulative bug fixes and changes.</li>
<li>Fixing the issue of custom theme not being applied.</li>
<li>
<h2>Support url config with basic auth.  Such as <code>https://123486%40qq.com:88888888@dav.jianguoyun.com/dav/cat/config_open.json</code></h2>
</li>
</ul>
<p><strong>2024/01/12 open_1.1.1_fix6</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Bugfix.</li>
<li>Restore the zoom feature for the player.</li>
<li>
<h2>Optimize bytecode load speed.</h2>
</li>
</ul>
<p><strong>2024/01/10 open_1.1.1_fix5</strong></p>
<h2>Open version update (Android):</h2>
<ul>
<li>
<h2>Fixed the issue of the video player not being properly aligned on the Android platform. Tks (at) biqiguxuenai, youzou.</h2>
</li>
</ul>
<p><strong>2024/01/02 open_1.1.1_fix4</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Bugfix.</li>
<li>
<h2>Keep request headers case-sensitive.</h2>
</li>
</ul>
<p><strong>2023/12/27 open_1.1.1_fix3</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Fixed the issue of local.get &amp; local.set missmatch. Tks (at) qiao, youzou.</h2>
</li>
</ul>
<p><strong>2023/12/27 open_1.1.1_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Fixed the issue of <code>assets://</code> config load faild.</h2>
</li>
</ul>
<p><strong>2023/12/26 open_1.1.1_fix1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Cumulative bug fixes and changes.</li>
<li>Merge a lot of changes relate to  js engine.</li>
<li>All js spider export APIs support returning JavaScript objects without the need for <code>JSON.stringify</code>.</li>
<li>Adding <code>SharedBuffer</code> to improve the performance of JavaScript threads.</li>
<li>Optimize the memory copy speed between the web server thread and the js thread.</li>
<li>The timeout parameter of the req method supports setting separate timeout values for sending and receiving.</li>
<li>Support  http reqeust output to a file or a shared buffer, shared buffer can also be write to <code>JSProxyStream</code>.</li>
</ul>
<pre><code>req('xxx', {
    ...
    timeout: [1000, 10000],
    ...
})

// respnse to shared buffer
const resp = await req('xxx', {
    buffer: 1,
    shared: 1,
});
// write shared buffer to file
const tmp = new JSFile( 'x.tmp');
await tmp.open('w');
await tmp.write(resp.content);
await tmp.close();

// response to file
const tmp = new JSFile( 'x.tmp');
const resp = await req('xxx', {
    buffer: 3,
    stream: tmp,
});

// write shared buffer to JSProxyStream
var stream = new JSProxyStream();
req('xxx', {
    buffer: 3,
    shared: 1,
    stream: {
        async onResp(resp) {
            console.log(resp);
            stream.head(resp.code, resp.headers);
        },
        onData(buf) {
            // write shared buffer to js proxy stream
            const result = stream.write(buf);
            buf.free();
            if (result == -1) return false;
            return true;
        },
        async onDone() {
            console.log('--------------------- done');
        },
        async onError(error) {
            console.log('--------------------- ' + error);
        },
    },
});</code></pre>
<hr />
<p><strong>2023/12/18 open_1.1.1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Cumulative bug fixes and changes.</li>
<li>Merge missing JavaScript methods and classes from the main branch, including gbk.encode, gbk.decode, utf8.encode, utf8.decode, setTimeout, clearTimeout, setInterval, clearInterval, JSProxyStream and JSFile.</li>
<li>Merge the missing buffer type 3 support in the req function. </li>
<li>Please refer to the example below and <a href="https://github.com/catvod/CatVodOpen/blob/main/open/wrapper/index.js"><code>wrapper/index.js</code></a> for more details.
<pre><code>const file1 = new JSFile('file1.zip');
const file2 = new JSFile('file2.zip');
if ((await file1.open('r')) &amp;&amp; (await file2.open('w'))) {
while (true) {
    var bytes = await file1.read(1024);
    if (bytes.byteLength == 0) {
        break;
    }
    file2.write(bytes);
}
file2.close();
file1.close();
file2.delete();
}</code></pre></li>
</ul>
<pre><code>const baiduHtml = new JSFile('baidu.html');
console.log(await baiduHtml.path());
const writeable = await baiduHtml.open('w');

req('https://baidu.com', {
    buffer: 3,
    stream: {
        async onResp(resp) {
            console.log(resp);
        },
        async onData(buf) {
            if (writeable) {
                await baiduHtml.write(buf);
            }
            return true;
        },
        async onDone() {
            if (writeable) {
                await baiduHtml.close();
            }
        },
    },
});</code></pre>
<pre><code>async function proxy(segments, headers, reqHeaders) {
    var stream = new JSProxyStream();
    let fileReqHeaders = {};
    if (reqHeaders['range']) {
        fileReqHeaders['range'] = reqHeaders['range'];
    }
    req('https://www.artplayer.org/assets/sample/video.mp4', {
        buffer: 3,
        headers: fileReqHeaders,
        content: {
            async onResp(resp) {
                if (stream) stream.head(resp.code, resp.headers);
            },
            async onData(buf) {
                console.log('--------------------- ' + buf.byteLength);
                let result = await stream.write(buf);
                if (result == 0) {
                    // stream was paused need rewrite
                    await new Promise(function (resolve) {
                        const interval = setInterval(async () =&gt; {
                            console.log('--------------------- pause wait ');
                            result = await stream.write(buf);
                            if (result != 0) {
                                resolve();
                                clearInterval(interval);
                            }
                        }, 200);
                    });
                }
                if (result == -1) {
                    return false;
                }
                return true;
            },
            async onDone() {
                await stream.done();
            },
        },
    });
    return {
        buffer: 3,
        stream: stream,
    };
}</code></pre>
<hr />
<p><strong>2023/12/05 open_1.1.0_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Cumulative bug fixes and changes.</h2>
</li>
</ul>
<p><strong>2023/11/06 open_1.1.0_fix1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Bug fixes.</h2>
</li>
</ul>
<p><strong>2023/11/03 open_1.1.0</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>
<h2>Cumulative bug fixes and changes.</h2>
</li>
</ul>
<p><strong>2023/10/11 open_1.0.9</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fix the issue of failing relative js import when using <code>//bb</code> as the api.</li>
<li>Fix the inconsistent behavior of QuickJS on multiple platforms.</li>
<li>Support HTTP proxy (Windows &amp; MacOS):
<code>set http_proxy=http://127.0.0.1:7890 &amp; set https_proxy=http://127.0.0.1:7890 &amp; .\catvod.exe</code>
<code>https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 open ./猫影视.app</code></li>
<li>Support data protocol as playback addresses.</li>
<li>
<h2>Etc...</h2>
</li>
</ul>
<p><strong>2023/10/11 open_1.0.8_fix7</strong></p>
<h2>Open version update (Windows):</h2>
<ul>
<li>
<h2>Fix the issue of quickjs on windows only.</h2>
</li>
</ul>
<p><strong>2023/10/09 open_1.0.8_fix6</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Merge image header support. (url + '#+#' + encodeURIComponent(`{&quot;User-Agent&quot;:&quot;Mozi&quot;}`))</li>
<li>Specific search site.</li>
<li>Fix the issue of <code>doubanio</code> image load error.</li>
<li>Support use <code>//bb</code> string as api.</li>
<li>
<h2>New js crypto wrapper.</h2>
</li>
</ul>
<p><strong>2023/09/25 open_1.0.8_fix5</strong></p>
<h2>Open version update (iOS/Android):</h2>
<ul>
<li>
<h2>Fix the issue of incorrect color in the mobile status bar.</h2>
</li>
</ul>
<p><strong>2023/09/23 open_1.0.8_fix4</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Optimize the loading time of JS files.</li>
<li>Support loading bytecode (CATOP) that is not encoded in base64.</li>
<li>Fix some infrequent bugs.</li>
<li>
<h2>Etc...</h2>
</li>
</ul>
<p><strong>2023/09/14 open_1.0.8_fix3</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Improve video decoding on Android.</li>
<li>Add base64 data/image support.</li>
<li>Add clear cache button in the setting page.</li>
<li>Optimize the user experience of the player control UI.</li>
<li>Merge some changes related to FFmpeg from the main branch. </li>
<li>
<h2>Etc...</h2>
</li>
</ul>
<p><strong>2023/09/08 open_1.0.8_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fix quickjs bytecode load issue.</li>
<li>
<h2>Bytecode gen tool is available <a href="https://github.com/catvod/CatVodOpen/tree/main/open/qjsc">Link</a>. </h2>
</li>
</ul>
<p><strong>2023/09/08 open_1.0.8_fix1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fix the issue of abnormal deletion of audiobook history records.</li>
<li>Support load <a href="https://bellard.org/quickjs/quickjs.html#Bytecode">quickjs bytecode</a>. <code>//bb + base64(bytecode)</code></li>
<li>
<h2>Etc...</h2>
</li>
</ul>
<p><strong>2023/09/07 open_1.0.8</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Add Windows platform status bar control for audiobook playback (SMTC).</li>
<li>Fix random image loss when jumping from the record page to the details.</li>
<li>Add sorting to the audiobook details list.</li>
<li>Merge delete all records from the main branch.</li>
<li>Fix the infinite loop issue with playback retry.</li>
<li>Etc...</li>
</ul>
<hr />
<p><strong>2023/09/06 open_1.0.7_fix3</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Open audio book support.</li>
</ul>
<hr />
<p><strong>2023/09/05 open_1.0.7_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Support using private Gitee or GitHub repositories as remote config.
<blockquote>
<h2><code>github://&lt;your personal access token&gt;@github.com/&lt;owner&gt;/&lt;repo&gt;/&lt;ref&gt;/&lt;file path&gt;</code>
<code>gitee://&lt;your access token&gt;@gitee.com/&lt;owner&gt;/&lt;repo&gt;/&lt;ref&gt;/&lt;file path&gt;</code>
<code>github://ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx@github.com/catvod/TestCfg/main/config_open.json</code>
<code>gitee://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx@gitee.com/catvod/test-cfg/master/config_open.json</code></h2>
</blockquote></li>
</ul>
<p><strong>2023/09/05 open_1.0.7_fix1</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fixed random layout errors on the search page.</li>
</ul>
<hr />
<p><strong>2023/09/02 open_1.0.7</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Merge detail page hyperlink support from main branch (Tks the reminder from Wangzai).</li>
<li>Fixed the issue of incorrect filter on multi-level category pages.</li>
<li>Etc...</li>
</ul>
<p><strong><em>BTW, our studio has received a new project that is time-sensitive, so updates will be temporarily paused for a period of time.</em></strong></p>
<hr />
<p><strong>2023/08/15 open_1.0.6_fix2</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fixed issues with multiple external audio tracks playback failure.</li>
</ul>
<hr />
<p><strong>2023/08/12 open_1.0.6_fix1</strong></p>
<h2>Open version update (iOS/Android):</h2>
<ul>
<li>Fixed video player issues with screen orientation (Default follow system setting).</li>
</ul>
<hr />
<p><strong>2023/08/11 open_1.0.6</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Merge most of the ui modifications related to player controls from the main branch.</li>
<li>Do not display tabbar if there is only one category tab.</li>
<li>Support dynamic modification of category filter options.</li>
<li>Double-click the forward or backward button to switch the seek mode.</li>
<li>Fixed random layout errors in pagination search on the search page.</li>
<li>Etc...</li>
</ul>
<hr />
<p><strong>2023/08/07 open_1.0.5</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Improve dash segment seek speed.</li>
<li>Fixed issues with list layout.</li>
<li>Remove tab <code>all</code> in search page.</li>
<li>Optimize video player control experience.</li>
<li>Fixed iOS/MacOS partial format hardware decoding.</li>
<li>Support for setting name and language of external audio tracks and subtitles.</li>
<li>Fixing memory leak on the windows platform.</li>
<li>Fixed etc...</li>
</ul>
<hr />
<p><strong>2023/07/31 open_1.0.4 fix</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Fixed issues with dash play.</li>
</ul>
<hr />
<p><strong>2023/07/29 open_1.0.4 fix</strong></p>
<h2>Open version update (Windows/MacOS/iOS/Android):</h2>
<ul>
<li>Add Android.</li>
<li>Merge waterfall-flow category layout support from main branch.</li>
<li>Merge DASH support for android from main branch.</li>
<li>Fixed issues with list layout.</li>
<li>Fixed blur effect error on ios.</li>
</ul>
<hr />
<p><strong>2023/07/28 open_1.0.4</strong></p>
<h2>Open version update (Windows/MacOS/iOS):</h2>
<h3>Merge the following changes from the main branch:</h3>
<ul>
<li>Support unlimited nested categories in the category list.</li>
<li>Add pagination support for searching within a specific site tab on the search page. <a href="https://github.com/catvod/CatVodOpen/blob/main/open/kunyu77_open.js#L259">Demo</a></li>
<li>Enable horizontal image mode from JS spider on the category page.</li>
<li>Allow filter names to be empty.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>Issues with history records when changing config.</li>
<li>Issues with dynamic js proxy play url.</li>
<li>Etc.</li>
</ul>
<hr />
<p><strong>2023/07/24 open_1.0.3</strong> </p>
<p>Open version update (Windows/MacOS/iOS):</p>
<ul>
<li>Merge some changes related to FFmpeg from the main branch. </li>
<li>Merge changes related to optional fields in the JS spider from main branch.</li>
<li>Multiple embedded subtitles default select the Chinese language.</li>
<li>Increase the player default preloading size to 64MB. </li>
<li>Fixed the display issue with ASS subtitles.</li>
<li>Add js <code>console.debug</code> method for desktop platform JS logging, with log file <code>js_debug.log</code>.</li>
</ul>
<hr />
<p><strong>2023/07/19 open_1.0.2</strong></p>
<p>Open version update (Windows/MacOS/iOS):</p>
<ul>
<li>Try to fix UI adaptation issues. (iPadOS)</li>
<li>Fixed the issue of memory crash caused by failed image caching.</li>
</ul>
<hr />
<p><strong>2023/07/18 open_1.0.2</strong></p>
<p>Open version update (Windows/MacOS/iOS):</p>
<ul>
<li>Fixed the issue of missing button status when switching to full screen in the player.</li>
<li>Fixed the issue of full screen switching freezing on the windows version.</li>
<li>Fixed the issue of some ts 301 forward failures from js proxy.</li>
<li>Fixed the issue of random crashes with some play url.</li>
<li>Optimized the logic of concurrent execution in js.</li>
</ul>
<hr />
<p><strong>2023/07/15</strong></p>
<ul>
<li>Update windows. Bugfix.</li>
</ul>
<hr />
<p><strong>2023/07/14 open_1.0.1</strong></p>
<ul>
<li>Remove builtin config. Add it by yourself</li>
<li>Bugfix.</li>
</ul>
<hr />
<p><strong>2023/07/13</strong></p>
<ul>
<li>Add iOS.</li>
<li>Fix builtin <code>kunyu77</code>.</li>
<li>Merger main branch cloud disk module.</li>
</ul>
<hr />
<p><strong>2023/07/06</strong></p>
<ul>
<li>Update windows.</li>
<li>Add MacOS.</li>
</ul>
<hr />
<p><strong>2023/07/05</strong></p>
<ul>
<li>Add windows.</li>
</ul></div><a class='title' href='https://github.com/catvod/CatVodOpen/releases/tag/1.1.3'><h1>CatVodOpen 版本: 1.1.3</h1></a><div class='platforms'><h3 style='padding:10px;background: linear-gradient(to right, #0074cc,#bf7326,#5bb75b) no-repeat right bottom;'>🪟 Windows 平台：2024年01月23日</h3><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z' target='_blank'>windows_release_open_1.1.2_fix5.7z</a><div class='fast'><span>27.67 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.2_fix5.7z>加速</a></div></div><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z' target='_blank'>windows_release_open_1.1.3_preview2.7z</a><div class='fast'><span>44.69 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/windows_release_open_1.1.3_preview2.7z>加速</a></div></div></div><div class='platforms'><h3 style='padding:10px;background: linear-gradient(to right, #D9534F,Pink,#83007a) no-repeat right bottom;'>📱 Android 平台：2024年01月23日</h3><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk' target='_blank'>android_open_1.1.2_fix5.apk</a><div class='fast'><span>33.87 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.2_fix5.apk>加速</a></div></div><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk' target='_blank'>android_open_1.1.3_preview2.apk</a><div class='fast'><span>63.39 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/android_open_1.1.3_preview2.apk>加速</a></div></div></div><div class='platforms'><h3 style='padding:10px;background: linear-gradient(to right, #137cbd,#5bb75b,Pink) no-repeat right bottom;'>🍏 MAC 平台：2024年01月23日</h3><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz' target='_blank'>macos_release_open_1.1.2_fix5.tar.gz</a><div class='fast'><span>49.97 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.2_fix5.tar.gz>加速</a></div></div><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz' target='_blank'>macos_release_open_1.1.3_preview2.tar.gz</a><div class='fast'><span>103.21 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/macos_release_open_1.1.3_preview2.tar.gz>加速</a></div></div></div><div class='platforms'><h3 style='padding:10px;background: linear-gradient(to right, #5bb75b,Pink,#D9534F) no-repeat right bottom;'>🍏 iPhone 平台：2024年01月23日</h3><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa' target='_blank'>ios_open_1.1.2_fix5.ipa</a><div class='fast'><span>20.34 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.2_fix5.ipa>加速</a></div></div><div class='bb'><a class='name' href=' https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa' target='_blank'>ios_open_1.1.3_preview2.ipa</a><div class='fast'><span>35.61 MB&nbsp;&nbsp;⚡</span><a href=https://dl.ghpig.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://ghproxy.net/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://mirror.ghproxy.com/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://github.moeyy.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>中国</a><a href=https://gh.900110.xyz/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://hub.gitmirror.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://gh.con.sh/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://ghps.cc/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://gh.ddlc.top/https://github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a><a href=https://521github.com/catvod/CatVodOpen/releases/download/1.1.3/ios_open_1.1.3_preview2.ipa>加速</a></div></div></div><script>
// function handleResize() {
//     // console.log('Window has been resized');
//     // 使用setTimeout延迟执行代码
//     setTimeout(function() {
//         // 在这里执行你想要延迟的操作
//         // 例如，检查元素宽度并添加类
//         var elements = document.querySelectorAll('.name');
//         elements.forEach(function(element) {
//             if (element.offsetWidth > 500) {
//                 element.closest('.bb').classList.add('on');
//             }else{
//                 element.closest('.bb').classList.remove('on');
//             }
//         });
//     }, 500); // 延迟500毫秒
// }

// 监听窗口大小改变事件
// window.addEventListener('resize', handleResize);

// 也可以在页面加载时立即执行一次
// handleResize();
  
console.log("分支：main");
console.log("README：https://raw.gitmirror.com/catvod/CatVodOpen/main//README.md");
var platforms = document.querySelectorAll('.platforms');
platforms.forEach(function(platform) {
  var h3 = platform.querySelector('h3');
  var bgStyle = window.getComputedStyle(h3).backgroundImage;
  var bb = platform.querySelectorAll('.bb');
  bb.forEach(function(bb) {
    bb.style.backgroundImage = bgStyle;
  });
});
</script>
    <script src="https://cdn.bootcdn.net/ajax/libs/marked/9.0.0/marked.min.js"></script>
    <textarea name="" id="" cols="30" rows="10" style="display:none"># CatVodOpen
Open version of catvod.

[🚀TG](https://t.me/catvodapp_offical)

### **Notice**

The open version was originally planned to start in december of last year, but it was delayed due to other matters. So the open version is mainly based on the december version from last year, but will include some bug fixes and core feature merges.

Not being maintained and uncertain whether they will be updated.

**Those who need it can download and use it, and there is no need to provide feedback on any issues.**

### **Limits**

- Only local `assets://`, `github://`, `gitee://`, `http(s)://user:pwd@xxx` config is supported, and http config without basic auth is not available. 
- Only video & cloud disk & audio book & comic & txt novel module.
- Not supporting sniffing.
- Basic JS interface support.
- No builtin maccms api support.
- etc.

### **Download**
[Release](https://github.com/catvod/CatVodOpen/releases)

- Windows release only test on `windows11`.
  
  - Builtin config `data\flutter_assets\asset\js\config_open.json`
- MacOS only test on `Big Sur` and `Monterey`.

  - Builtin config `*.app/Contents/Frameworks/App.framework/Resources/flutter_assets/asset/js/config_open.json`
- iOS only test on `16.0+`.

  - Builtin config `*.ipa/Payload/Runner.app/Frameworks/App.framework/flutter_assets/asset/js/config_open.json` 
- Android only test on `8.0+`, maybe not supported to run on emulators, not support TV.

  - Builtin config `*.apk/assets/flutter_assets/asset/js/config_open.json` 
</textarea>
    <div class="markdown-body" id="markdown-body" style="padding:50px 0 0 0;"></div>
</div>
<link rel="stylesheet" href="https://cdn.bootcdn.net/ajax/libs/prism-themes/1.9.0/prism-xonokai.min.css">
<link rel="stylesheet" href="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/toolbar/prism-toolbar.min.css">
<link rel="stylesheet" href="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/line-numbers/prism-line-numbers.min.css">
<script src="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/prism.js"></script>
<script src="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/toolbar/prism-toolbar.min.js"></script>
<script src="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/show-language/prism-show-language.min.js"></script>
<script src="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/copy-to-clipboard/prism-copy-to-clipboard.min.js"></script>
<script src="https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/plugins/line-numbers/prism-line-numbers.min.js"></script>
<script>
document.getElementById('markdown-body').innerHTML = marked.parse(document.querySelector("textarea").value);
document.addEventListener('DOMContentLoaded', () => {
    //高亮显示
    const codeElements = document.querySelectorAll('pre code'); // 或者其他选择器
    const languageTypes = new Set(); // 存储已经加载过的 languageType
    // 初始化高亮效果 动态加载
    for (let i = 0; i < codeElements.length; i++) {
        const element = codeElements[i];
        const className = element.className;
        if (className && className.startsWith('language-')) {
            const languageType = className.substring(9); // 提取语言类型，去掉前缀 "language-"
            lt = languageType.toLowerCase(); // 确保比较不区分大小写
            lt = (lt === "shell" || lt === "sh") ? "powershell" : languageType;
            console.log(className);
            if (!languageTypes.has(lt)) {
                languageTypes.add(lt);
                const script = "https://cdn.bootcdn.net/ajax/libs/prism/1.29.0/components/prism-" + lt + ".min.js";
                const languageScript = document.createElement('script');
                languageScript.src = script;
                document.head.appendChild(languageScript);
            }
        }
    }
    Prism.highlightAll();
    // 查找所有的a链接并添加HTTPS协议
    const allLinks = document.querySelectorAll('.markdown-body a[href]');
    allLinks.forEach(link => {
        const href = link.getAttribute('href');
        if (!href.startsWith('http://') && !href.startsWith('https://') && !href.startsWith('#') && !href.startsWith('/catvod/CatVodOpen/')) {
            link.setAttribute('href', `https://github.com/catvod/CatVodOpen/blob/main/${href}`);
        }
    });
    // 图片加载错误
    // allLinks.forEach((el) => {
    //     el.addEventListener('error', function() {
    //         if (this.src.startsWith('/')) {
    //             this.src = '' + this.src;
    //         }
    //     });
    // });

    // 查找所有的img链接并补全地址
    const allImg = document.querySelectorAll('.markdown-body img');
    allImg.forEach(image => {
        image.removeAttribute('style');
    })
    const allImages = document.querySelectorAll('.markdown-body img[src]');
    allImages.forEach(image => {
        const src = image.getAttribute('src'); //获取 图片src
        image.setAttribute('src', src.replace('raw.githubusercontent.com', 'raw.gitmirror.com')); //替换域名
        if(!src.startsWith('http://') && !src.startsWith('https://')) {
            image.setAttribute('src', `https://raw.gitmirror.com/catvod/CatVodOpen/main/${src}`);
        }
        if (src.includes('https://github') && (src.includes('/raw/main/') || src.includes('/raw/master/') || src.includes('/blob/master/'))) { //图片链接必须包含 ,替换域名
            const newSrc = src.replace('/raw/main/', '/main/').replace('/raw/master/', '/master/').replace('/blob/master/', '/master/').replace('https://github.com', 'https://raw.gitmirror.com');
            image.setAttribute('src', newSrc);
        }
    });
    // h标签的文本改为id值
    var hNodes = document.querySelectorAll(['h1', 'h2', 'h3']);
    for (var i = 0; i < hNodes.length; i++) {
        hNodes[i].id = hNodes[i].textContent.trim();
    }
});
var content = document.querySelector('#content');
function show() {
    var link = document.querySelector('#show');
    var content = document.querySelector('#content');
    content.style.display = 'block';
    link.parentNode.removeChild(link);
}
removeStyleTags(content); 

// 移除style
function removeStyleTags(element) {
    // 获取当前元素内的所有子节点
    var childNodes = element.childNodes;
    for (var i = childNodes.length - 1; i >= 0; i--) {
        var child = childNodes[i];
        // 如果子节点是 <style> 标签，则移除它
        if (child.nodeName === 'STYLE') {
            element.removeChild(child);
        }
    }
}
</script>
<link href="//cdn.bootcdn.net/ajax/libs/github-markdown-css/5.2.0/github-markdown.css" rel="stylesheet">
</body>
</html>
