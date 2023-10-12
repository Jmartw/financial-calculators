# financial-calculators
mortgage project 
        
public class MortgageCalc {
private static final int months_in_a_year = 12
    public static void main (String [] args) {


        Scanner scanner = new Scanner (System.in) ;

        System.out.println("Enter the principal amount:") ;
        double principal = scanner.nextDouble();

        System.out.println("Enter the annual interest rate");
        float annualInterestRate = scanner.nextFloat();

        System.out.println("Enter the term in years");
        termInYears = scanner.nextInt();

        float monthlyInterestRate =annualInterestRatec/ months_in_a_year;
        int numberOfPayments = termInYears * months_in_a_year;

        double montlyPayment = principal * (monthlyInterestRate ( math.pow( 1 + monthlyInterestRate,
                numberOfPayments)) / ((math.pow (1 + monthlyInterestRate, numberOfPayments)) -1 ));

        System.out.println ("monthy payment"+ montlyPayment)

  principal= 100,000
   annual interest annualInterestRate=.06
  term in years = 20

  monthly rate = 716


      def cd_calculator(initial_deposit, annual_interest_rate, cd_term_years):

                annual_interest_rate_decimal = annual_interest_rate / 100


        future_value = initial_deposit * (1 + annual_interest_rate_decimal)**cd_term_years


        print(f"Initial Deposit: ${initial_deposit:,.2f}")
        print(f"Annual Interest Rate: {annual_interest_rate:.2f}%")
        print(f"CD Term: {cd_term_years} years")
        print(f"Future Value: ${future_value:,.2f}")

     CD with a $1,500 initial deposit, 2% annual interest rate, and a 6-year term
                initial_deposit = 1500
        annual_interest_rate = 2.0
        cd_term_years = 6

        cd_calculator(initial_deposit, annual_interest_rate, cd_term_years)

