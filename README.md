import React from "react"; import { Button } from "@/components/ui/button"; import { Card, CardContent } from "@/components/ui/card";

export default function AvaraBags() { return ( <div className="min-h-screen bg-white text-black font-serif"> <header className="p-6 shadow-md flex justify-between items-center"> <h1 className="text-3xl font-bold tracking-wide">AVARA BAGS</h1> <nav className="space-x-4"> <a href="#home" className="hover:underline">Home</a> <a href="#shop" className="hover:underline">Shop</a> <a href="#about" className="hover:underline">About</a> <a href="#contact" className="hover:underline">Contact</a> </nav> </header>

<section id="home" className="text-center py-20 bg-gray-100">
    <h2 className="text-5xl font-bold mb-4">Luxury Handcrafted Bags</h2>
    <p className="text-xl mb-6">Elevate your style with Avara’s premium collection</p>
    <Button className="text-lg px-6 py-3 rounded-2xl">Shop Now</Button>
  </section>

  <section id="shop" className="p-10 grid grid-cols-1 md:grid-cols-3 gap-6">
    {[1, 2, 3].map((item) => (
      <Card key={item} className="rounded-2xl shadow-lg">
        <CardContent className="p-4">
          <div className="h-64 bg-gray-200 mb-4 rounded-lg" />
          <h3 className="text-xl font-semibold">Bag Name {item}</h3>
          <p className="text-gray-600">₹2,499</p>
          <Button className="mt-2 w-full">Add to Cart</Button>
        </CardContent>
      </Card>
    ))}
  </section>

  <section id="about" className="p-10 bg-gray-100 text-center">
    <h2 className="text-3xl font-bold mb-4">About Avara</h2>
    <p className="max-w-2xl mx-auto text-lg">
      Avara Bags brings you a unique blend of tradition and modern design. Each bag is
      lovingly handcrafted to reflect elegance, durability, and timeless fashion.
    </p>
  </section>

  <section id="contact" className="p-10 text-center">
    <h2 className="text-3xl font-bold mb-4">Get in Touch</h2>
    <p className="text-lg mb-4">Have questions or want to collaborate?</p>
    <Button className="px-6 py-3 rounded-2xl">Message on WhatsApp</Button>
  </section>

  <footer className="bg-black text-white text-center py-6 mt-10">
    <p>&copy; 2025 AVARA BAGS. All rights reserved.</p>
  </footer>
</div>

); }

# AVARA-BAGS-6
 Welcome to AVARA BAGS  Crafted for Elegance. Designed for You.  Discover timeless luxury with AVARA BAGS — where premium craftsmanship meets modern design. Each bag is handmade with attention to detail, style, and durability.
