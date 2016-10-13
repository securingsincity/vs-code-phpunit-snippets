# phpunit-snippets README

PHPUnit snippets for VSCode

Snippets
--------

List of snippets

### Assertions

- **assahk** `assertArrayHasKey()`
- **assae** `assertAttributeEquals()`
- **asscha** `assertClassHasAttribute()`
- **asschsa** `assertClassHasStaticAttribute()`
- **assc** `assertContains()`
- **assco** `assertContainsOnly()`
- **asscu** `assertCount()`
- **asse** `assertEquals()`
- **assem** `assertEmpty()`
- **assexml** `assertEqualXMLStructure()`
- **assf** `assertFalse()`
- **assfe** `assertFileEquals()`
- **assfx** `assertFileExists()`
- **assgt** `assertGreatherThan()`
- **assgte** `assertGreaterThanOrEqual()`
- **assio** `assertInstanceOf()`
- **assit** `assertInternalType()`
- **asslt** `assertLessThan()`
- **asslte** `assertLessThanOrEqual()`
- **assnn** `assertNotNull()`
- **assn** `assertNull()`
- **assoha** `assertObjectHasAttribute()`
- **assre** `assertRegExp()`
- **asss** `assertSame()`
- **asssc** `assertSelectCount()`
- **assse** `assertSelectEquals()`
- **asssef** `assertStringEqualsFile()`
- **asssew** `assertStringEndsWith()`
- **asssmf** `assertStringMatchesFormat()`
- **asssmff** `assertStringMatchesFormatFile()`
- **asssre** `assertSelectRegExp()`
- **assssw** `assertStringStartsWith()`
- **asst** `assertTrue()`
- **assta** `assertTag()`
- **assxmlfef** `assertXmlFileEqualsXmlFile()`
- **assxmlsef** `assertXmlStringEqualsXmlFile()`
- **assxmlses** `assertXmlStringEqualsXmlString()`

### Set up and tear down

**setup**

	public function setUp()
	{
		// set up
	}

**teardown**

	public function tearDown()
	{
		// tear down
	}

### Tests

**test**

	/**
	 * @covers [Class]::[Method]()
	 */
	public function test[Method]()
	{
		// assertions
	}

**test2**

	/**
	 * @covers [Class]::[Method1]()
	 * @covers [Class]::[Method2]()
	 */
	public function test[Method1]_[Method2]()
	{
		// assertions
	}

**testex**

	/**
	 * @covers [Class]::[Method]()
	 * @expectedException [Exception]
	 */
	public function test[Method]()
	{
		// assertions
	}

**testi**

	/**
	 * @covers [Class]::[Method]()
	 */
	public function test[Method]()
	{
	    $this->markTestIncomplete('Not yet implemented');
	}


### For more information
* [Github](https://github.com/securingsincity/vs-code-phpunit-snippets)
* Based on the work of [Florian Eckerstorfer](http://florianeckerstorfer.com)  
* based on this repo for sublime[fe-sublime-phpunit] https://github.com/florianeckerstorfer/fe-sublime-phpunit

**Enjoy!**
