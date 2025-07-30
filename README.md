## Hi there 👋
import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input"; import { Textarea } from "@/components/ui/textarea";

export default function BusinessWebsite() { return ( <div className="min-h-screen bg-gradient-to-br from-white to-blue-100 p-6"> <header className="text-center mb-10"> <h1 className="text-4xl font-bold text-blue-900">Welcome to Our Business</h1> <p className="text-lg text-gray-700 mt-2">Modern Solutions for Your Needs</p> </header>

<section className="mb-16">
    <h2 className="text-2xl font-semibold text-blue-800 mb-6 text-center">Image Gallery</h2>
    <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
      {[1, 2, 3, 4, 5, 6].map((num) => (
        <Card key={num} className="rounded-2xl shadow-md overflow-hidden">
          <img
            src={`https://source.unsplash.com/400x300/?business,office,${num}`}
            alt={`Gallery ${num}`}
            className="w-full h-60 object-cover"
          />
        </Card>
      ))}
    </div>
  </section>

  <section className="max-w-xl mx-auto bg-white p-6 rounded-2xl shadow-lg">
    <h2 className="text-2xl font-semibold text-blue-800 mb-4 text-center">Contact Us</h2>
    <form className="space-y-4">
      <Input type="text" placeholder="Your Name" className="rounded-xl" />
      <Input type="email" placeholder="Your Email" className="rounded-xl" />
      <Textarea placeholder="Your Message" className="rounded-xl" rows={4} />
      <Button className="w-full rounded-xl bg-blue-700 hover:bg-blue-800 text-white text-lg">
        Send Message
      </Button>
    </form>
  </section>

  <footer className="text-center text-gray-500 text-sm mt-16">
    © {new Date().getFullYear


<!--
**r46u/R46U** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
