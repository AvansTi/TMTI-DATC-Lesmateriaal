>> ### Exercise 5-1 Unit test
>>
>> Schrijf een programma welke gebruik maakt van onderstaande structuur om testresultaten naar een bestand weg te schrijven.
>> * Gebruik de fixture om het bestand aan te maken en te sluiten, gebruik één bestand voor alle testen samen.
>> * Gebruik de de TEST_F structuur om 4 rekenkundige functies te testen, zoals: Add(), Sub(), Divide() en Multiply().
>>
>>```cpp
>>// Test fixture
>>class MyTest : public ::testing::Test {
>>protected:
>>    virtual void SetUp() {
>>        // init code hier
>>    }
>>
>>    virtual void TearDown() {
>>        // clean-up code hier
>>    }
>>};
>>```
>>
>> TEST_F structuur 4 rekenkundige functies
>>
>>```cpp
>>// Testcase met ASSERT_EQ macro
>>TEST_F(MyTest, TestAddition) {
>>    // De feitelijke test
>>    ASSERT_EQ(Add(2, 2), 4);
>>}
>>
>>int main(int argc, char** argv) {
>>
>>    // Initialiseer het Google Test-framework
>>    ::testing::InitGoogleTest(&argc, argv);
>>
>>    // Voer alle testcases uit
>>    return RUN_ALL_TESTS();
>>}
>>```
>>
>{: .exercise}