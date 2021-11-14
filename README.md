# demo
Repository 1
package harshita;

public abstract class Compartment {
    public abstract String notice();
}
abstract class FirstClass extends Compartment{
    @Override
    public String notice() {
        System.out.println("First Class Compartment");
        return null;
    }
}
abstract class Ladies extends Compartment{
    @Override
    public String notice() {
        System.out.println("Ladies Compartment");
        return null;
    }
}
abstract class General extends Compartment{
    @Override
    public String notice() {
        System.out.println("General Compartment");
        return null;
    }
}
abstract class Luggage extends Compartment{
    @Override
    public String notice() {
        System.out.println("Luggage Compartment");
        return null;
    }
}

