public class Product {
    private String name;
    private double price;
    private int stock;
    private String ecoFriendlyAlternative;

    public Product(String name, double price, int stock, String ecoFriendlyAlternative) {
        this.name = name;
        this.price = price;
        this.stock = stock;
        this.ecoFriendlyAlternative = ecoFriendlyAlternative;
    }

    public String getName() {
        return name;
    }

    public double getPrice() {
        return price;
    }

    public int getStock() {
        return stock;
    }

    public String getEcoFriendlyAlternative() {
        return ecoFriendlyAlternative;
    }

    public boolean reduceStock(int quantity) {
        if (stock >= quantity) {
            stock -= quantity;
            return true;
        }
        return false;
    }
}
