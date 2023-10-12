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
