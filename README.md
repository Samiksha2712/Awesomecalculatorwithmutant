using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator;
using NUnit.Framework;


namespace CalcAppTest

{
    [TestFixture]
    class CalcTests
    {
        [Test]
        public void GetAddition_Input1point4and8point6_Returns10point0()
        {

            //Arrange
            double number1 = 1.4;
            double number2 = 8.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

          
            [Test]
            public void GetAddition_Input6point4and8point6_Returns15point0()
            {

                //Arrange
                double number1 = 6.4;
                double number2 = 8.6;

                double expectedResult = number1 + number2;

                Calc testCalc = new Calc(number1, number2);

                //Act
                double actualResult = testCalc.GetAddition();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);
            }
        [Test]
        public void GetAddition_Input2point5and3point1_Returns5point6()
        {

            //Arrange
            double number1 = 2.5;
            double number2 = 3.1;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input5point4and1point0_Returns4point4()
        {

            //Arrange
            double number1 = 5.4;
            double number2 = 1.0;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input10point5and7point5_Returns3point0()
        {

            //Arrange
            double number1 = 10.5;
            double number2 = 7.5;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input55point5and20point5_Returns35point0()
        {

            //Arrange
            double number1 = 55.5;
            double number2 = 20.5;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input55point0and2point0_Returns110point0()
        {

            //Arrange
            double number1 = 55;
            double number2 = 2;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input45point0and200point0_Returns9000point0()
        {

            //Arrange
            double number1 = 45;
            double number2 = 200;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input7point4and10point0_Returns7point4()
        {

            //Arrange
            double number1 = 7.4;
            double number2 = 10;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input30point0and10point0_Returns3point0()
        {

            //Arrange
            double number1 = 30;
            double number2 = 10;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input30point0and15point0_Returns2point0()
        {

            //Arrange
            double number1 = 30;
            double number2 = 15;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input7point0and14point0_Returns7point5()
        {

            //Arrange
            double number1 = 7;
            double number2 = 14;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input1point0and3point0_Returns0point33()
        {

            //Arrange
            double number1 = 1;
            double number2 = 3;

            double expectedResult =   Math.Round((number1 / number2),2);

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input2point0and1point0_Returns2point0()
        {

            //Arrange
            double number1 = 2;
            double number2 = 1;

            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input9point0and3point0_Returns3point0()
        {

            //Arrange
            double number1 = 9;
            double number2 = 3;

            double expectedResult = number1 /number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
    }
}

    

