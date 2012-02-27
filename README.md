Another QUnitAdapter for jsTestDriver
=========================
This is a QUnit adapter for jsTestDriver, which supports asyncTest/stop/start.

Extended from QUnitAdapter to support async test.

This adapter is implemented by analysing the source code of async test methods, and generating an totally new function for jsTestDriver AsyncTestCase object.

This adapter is used in unit test of objectjs currently.

### QUnitAdapter
QUnitAdapter : <https://github.com/mmonteleone/pavlov/blob/68a23a305f2caad8cbf8656e7d40a5398c07d0c1/spec/lib/js-test-driver/qunit/QUnitAdapter.js/>

QUnit-to-JsTestDriver-adapter : <https://github.com/exnor/QUnit-to-JsTestDriver-adapter/>

### jsTestDriver
<http://code.google.com/p/js-test-driver/>

### objectjs
<objectjs: <http://code.google.com/p/objectjs/>

Contact
=================
wangjeaf@gmail.com
