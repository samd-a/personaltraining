import React, { useState } from 'react';
import { 
  Menu, X, Instagram, ShoppingCart, 
  ChevronRight, Dumbbell, BookOpen, Users, 
  ArrowRight, CheckCircle2 
} from 'lucide-react';

// --- MOCK DATA ---
const BLOG_POSTS = [
  {
    id: 1,
    title: "The Ultimate Guide to Progressive Overload",
    excerpt: "Discover how to effectively build muscle and strength by safely increasing the demands on your musculoskeletal system.",
    author: "Connor Williams",
    date: "May 20, 2026",
    image: "https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?auto=format&fit=crop&q=80&w=800"
  },
  {
    id: 2,
    title: "Fueling Your Workouts: Pre & Post Nutrition",
    excerpt: "What you eat before and after your training session can make or break your results. Here's exactly what to focus on.",
    author: "Leah Williams",
    date: "May 15, 2026",
    image: "https://images.unsplash.com/photo-1490645935967-10de6ba17061?auto=format&fit=crop&q=80&w=800"
  },
  {
    id: 3,
    title: "5 Functional Movements You Should Be Doing",
    excerpt: "Improve your daily life and athletic performance with these foundational functional fitness exercises.",
    author: "Leah Williams",
    date: "May 8, 2026",
    image: "https://images.unsplash.com/photo-1571019614242-c5c5dee9f50b?auto=format&fit=crop&q=80&w=800"
  }
];

const PRODUCTS = [
  {
    id: 1,
    title: "8-Week Hypertrophy Program",
    description: "A comprehensive 5-day/week program designed to maximize muscle growth. Includes video libraries and tracking sheets.",
    price: 49.99,
    type: "Training Guide",
    image: "https://images.unsplash.com/photo-1534438327276-14e5300c3a48?auto=format&fit=crop&q=80&w=800"
  },
  {
    id: 2,
    title: "Customizable Meal Plan Template",
    description: "Take the guesswork out of nutrition. Easy plug-and-play templates for cutting, maintaining, or bulking.",
    price: 29.99,
    type: "Nutrition",
    image: "https://images.unsplash.com/photo-1490645935967-10de6ba17061?auto=format&fit=crop&q=80&w=800"
  },
  {
    id: 3,
    title: "Beginner's At-Home Workout Guide",
    description: "No gym? No problem. Get fit from the comfort of your living room with minimal equipment required.",
    price: 19.99,
    type: "Training Guide",
    image: "https://images.unsplash.com/photo-1518611012118-696072aa579a?auto=format&fit=crop&q=80&w=800"
  },
  {
    id: 4,
    title: "1-on-1 Virtual Consultation (60 Min)",
    description: "Book an hour with Connor or Leah to discuss your goals, check your form, or formulate a custom strategy.",
    price: 99.00,
    type: "Consultation",
    image: "https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?auto=format&fit=crop&q=80&w=800"
  }
];

// --- COMPONENTS ---

const Navbar = ({ currentPage, setCurrentPage }) => {
  const [isOpen, setIsOpen] = useState(false);

  const navItems = [
    { name: 'Home', id: 'home' },
    { name: 'About Us', id: 'about' },
    { name: 'Blog', id: 'blog' },
    { name: 'Shop', id: 'shop' }
  ];

  return (
    <nav className="bg-zinc-950 border-b border-zinc-800 sticky top-0 z-50">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div className="flex justify-between h-20">
          <div className="flex items-center">
            <div 
              className="flex-shrink-0 flex items-center cursor-pointer gap-2"
              onClick={() => setCurrentPage('home')}
            >
              <Dumbbell className="h-8 w-8 text-orange-500" />
              <span className="font-bold text-2xl tracking-tighter text-white uppercase">
                Williams Fitness
              </span>
            </div>
          </div>
          
          {/* Desktop Menu */}
          <div className="hidden md:flex items-center space-x-8">
            {navItems.map((item) => (
              <button
                key={item.id}
                onClick={() => setCurrentPage(item.id)}
                className={`text-sm font-medium transition-colors hover:text-orange-500 uppercase tracking-wide ${
                  currentPage === item.id ? 'text-orange-500' : 'text-zinc-300'
                }`}
              >
                {item.name}
              </button>
            ))}
            <a 
              href="https://www.instagram.com/williamsfitness2024/" 
              target="_blank" 
              rel="noopener noreferrer"
              className="text-zinc-300 hover:text-orange-500 transition-colors"
            >
              <Instagram className="h-5 w-5" />
            </a>
          </div>

          {/* Mobile Menu Button */}
          <div className="flex items-center md:hidden">
            <button
              onClick={() => setIsOpen(!isOpen)}
              className="text-zinc-300 hover:text-white focus:outline-none"
            >
              {isOpen ? <X className="h-6 w-6" /> : <Menu className="h-6 w-6" />}
            </button>
          </div>
        </div>
      </div>

      {/* Mobile Menu */}
      {isOpen && (
        <div className="md:hidden bg-zinc-900 border-b border-zinc-800">
          <div className="px-2 pt-2 pb-3 space-y-1 sm:px-3">
            {navItems.map((item) => (
              <button
                key={item.id}
                onClick={() => {
                  setCurrentPage(item.id);
                  setIsOpen(false);
                }}
                className={`block w-full text-left px-3 py-4 rounded-md text-base font-medium uppercase tracking-wide ${
                  currentPage === item.id 
                    ? 'bg-zinc-800 text-orange-500' 
                    : 'text-zinc-300 hover:bg-zinc-800 hover:text-white'
                }`}
              >
                {item.name}
              </button>
            ))}
            <a 
              href="https://www.instagram.com/williamsfitness2024/" 
              target="_blank" 
              rel="noopener noreferrer"
              className="flex items-center gap-2 w-full px-3 py-4 text-base font-medium text-zinc-300 hover:bg-zinc-800 hover:text-orange-500 uppercase tracking-wide"
            >
              <Instagram className="h-5 w-5" />
              Instagram
            </a>
          </div>
        </div>
      )}
    </nav>
  );
};

const Footer = () => (
  <footer className="bg-zinc-950 border-t border-zinc-900 py-12 text-center">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col items-center">
      <Dumbbell className="h-8 w-8 text-orange-500 mb-4" />
      <p className="text-zinc-400 text-sm mb-4">
        © {new Date().getFullYear()} Williams Fitness. All rights reserved.
      </p>
      <a 
        href="https://www.instagram.com/williamsfitness2024/" 
        target="_blank" 
        rel="noopener noreferrer"
        className="flex items-center gap-2 text-zinc-400 hover:text-orange-500 transition-colors"
      >
        <Instagram className="h-5 w-5" />
        <span className="text-sm font-medium uppercase tracking-wider">Follow us on Instagram</span>
      </a>
    </div>
  </footer>
);

// --- PAGES ---

const HomePage = ({ setCurrentPage }) => (
  <div className="animate-in fade-in duration-500">
    {/* Hero Section */}
    <div className="relative h-[80vh] flex items-center justify-center overflow-hidden">
      <div className="absolute inset-0 z-0">
        <img 
          src="https://images.unsplash.com/photo-1534438327276-14e5300c3a48?auto=format&fit=crop&q=80&w=2000" 
          alt="Gym background" 
          className="w-full h-full object-cover opacity-30"
        />
        <div className="absolute inset-0 bg-gradient-to-t from-zinc-950 via-zinc-950/80 to-transparent"></div>
      </div>
      
      <div className="relative z-10 text-center px-4 max-w-4xl mx-auto">
        <h1 className="text-5xl md:text-7xl font-extrabold text-white tracking-tighter mb-6 uppercase leading-tight">
          Transform Your <span className="text-orange-500">Potential</span>
        </h1>
        <p className="text-lg md:text-2xl text-zinc-300 mb-10 max-w-2xl mx-auto font-light">
          Expert personal training, custom programs, and nutrition coaching to help you build the strongest version of yourself.
        </p>
        <div className="flex flex-col sm:flex-row gap-4 justify-center">
          <button 
            onClick={() => setCurrentPage('about')}
            className="px-8 py-4 bg-orange-500 hover:bg-orange-600 text-white font-bold rounded-none uppercase tracking-wide transition-colors flex items-center justify-center gap-2"
          >
            Meet the Trainers <ArrowRight className="h-5 w-5" />
          </button>
          <button 
            onClick={() => setCurrentPage('shop')}
            className="px-8 py-4 bg-white hover:bg-zinc-200 text-zinc-950 font-bold rounded-none uppercase tracking-wide transition-colors flex items-center justify-center gap-2"
          >
            View Programs
          </button>
        </div>
      </div>
    </div>

    {/* Quick Features */}
    <div className="bg-zinc-950 py-24">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div className="grid grid-cols-1 md:grid-cols-3 gap-12 text-center">
          <div className="p-6 border border-zinc-800 bg-zinc-900/50 flex flex-col items-center">
            <div className="h-16 w-16 bg-orange-500/10 rounded-full flex items-center justify-center mb-6">
              <Users className="h-8 w-8 text-orange-500" />
            </div>
            <h3 className="text-xl font-bold text-white mb-3 uppercase tracking-wide">Expert Coaching</h3>
            <p className="text-zinc-400">
              Guidance from Connor and Leah, certified professionals dedicated to your success.
            </p>
          </div>
          <div className="p-6 border border-zinc-800 bg-zinc-900/50 flex flex-col items-center">
            <div className="h-16 w-16 bg-orange-500/10 rounded-full flex items-center justify-center mb-6">
              <BookOpen className="h-8 w-8 text-orange-500" />
            </div>
            <h3 className="text-xl font-bold text-white mb-3 uppercase tracking-wide">Digital Guides</h3>
            <p className="text-zinc-400">
              Instantly access our proven training programs and nutrition plans from anywhere.
            </p>
          </div>
          <div className="p-6 border border-zinc-800 bg-zinc-900/50 flex flex-col items-center">
            <div className="h-16 w-16 bg-orange-500/10 rounded-full flex items-center justify-center mb-6">
              <CheckCircle2 className="h-8 w-8 text-orange-500" />
            </div>
            <h3 className="text-xl font-bold text-white mb-3 uppercase tracking-wide">Real Results</h3>
            <p className="text-zinc-400">
              Evidence-based approaches to help you build muscle, lose fat, and feel your best.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
);

const AboutPage = () => (
  <div className="bg-zinc-950 min-h-screen py-20 animate-in fade-in duration-500">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      {/* Business Intro */}
      <div className="text-center max-w-3xl mx-auto mb-20">
        <h1 className="text-4xl md:text-5xl font-extrabold text-white uppercase tracking-tighter mb-6">
          About <span className="text-orange-500">Williams Fitness</span>
        </h1>
        <p className="text-lg text-zinc-400 leading-relaxed">
          Founded in 2024, Williams Fitness was born from a shared passion for health, strength, and helping others realize their true potential. We believe that fitness is not a one-size-fits-all journey. Whether your goal is to pack on muscle, improve your functional strength, or completely overhaul your lifestyle, we provide the expert guidance, support, and tools you need to get there.
        </p>
      </div>

      {/* Trainers Section */}
      <div className="space-y-24">
        
        {/* Connor */}
        <div className="flex flex-col md:flex-row gap-12 items-center">
          <div className="w-full md:w-1/2">
            <div className="relative">
              <div className="absolute inset-0 bg-orange-500 translate-x-4 translate-y-4 rounded-none z-0"></div>
              <img 
                src="https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?auto=format&fit=crop&q=80&w=800" 
                alt="Connor Williams" 
                className="relative z-10 w-full h-[500px] object-cover grayscale hover:grayscale-0 transition-all duration-500"
              />
            </div>
          </div>
          <div className="w-full md:w-1/2 space-y-6">
            <div>
              <h2 className="text-3xl font-bold text-white uppercase tracking-wide">Connor Williams</h2>
              <p className="text-orange-500 font-medium tracking-widest uppercase text-sm mt-1">Co-Founder & Head Coach</p>
            </div>
            <p className="text-zinc-400 leading-relaxed text-lg">
              Connor specializes in strength and conditioning, hypertrophy, and biomechanics. With years of experience on the gym floor, he has developed an eye for detail when it comes to lifting technique and programming optimal training cycles.
            </p>
            <p className="text-zinc-400 leading-relaxed text-lg">
              His philosophy is rooted in progressive overload and consistency. Connor is dedicated to helping clients shatter their personal records and build physiques they are proud of, all while maintaining a healthy relationship with training.
            </p>
            <ul className="space-y-3 mt-6">
              {['Strength & Conditioning', 'Hypertrophy Specialist', 'Form Correction & Biomechanics'].map((item, i) => (
                <li key={i} className="flex items-center gap-3 text-zinc-300">
                  <CheckCircle2 className="h-5 w-5 text-orange-500 flex-shrink-0" />
                  {item}
                </li>
              ))}
            </ul>
          </div>
        </div>

        {/* Leah */}
        <div className="flex flex-col md:flex-row-reverse gap-12 items-center">
          <div className="w-full md:w-1/2">
            <div className="relative">
              <div className="absolute inset-0 bg-orange-500 -translate-x-4 translate-y-4 rounded-none z-0"></div>
              <img 
                src="https://images.unsplash.com/photo-1571019614242-c5c5dee9f50b?auto=format&fit=crop&q=80&w=800" 
                alt="Leah Williams" 
                className="relative z-10 w-full h-[500px] object-cover grayscale hover:grayscale-0 transition-all duration-500"
              />
            </div>
          </div>
          <div className="w-full md:w-1/2 space-y-6">
            <div>
              <h2 className="text-3xl font-bold text-white uppercase tracking-wide">Leah Williams</h2>
              <p className="text-orange-500 font-medium tracking-widest uppercase text-sm mt-1">Co-Founder & Nutrition Coach</p>
            </div>
            <p className="text-zinc-400 leading-relaxed text-lg">
              Leah takes a holistic approach to fitness, blending functional movement with sustainable, realistic nutrition strategies. She understands that training is only half the battle, and works closely with clients to build habits that support recovery, energy levels, and overall wellness.
            </p>
            <p className="text-zinc-400 leading-relaxed text-lg">
              Whether it's helping a client navigate meal prepping or mastering bodyweight mechanics, Leah empowers individuals to take control of their health without feeling restricted or overwhelmed.
            </p>
            <ul className="space-y-3 mt-6">
              {['Functional Fitness', 'Nutrition & Macro Coaching', 'Habit Building & Lifestyle Integration'].map((item, i) => (
                <li key={i} className="flex items-center gap-3 text-zinc-300">
                  <CheckCircle2 className="h-5 w-5 text-orange-500 flex-shrink-0" />
                  {item}
                </li>
              ))}
            </ul>
          </div>
        </div>

      </div>
    </div>
  </div>
);

const BlogPage = () => (
  <div className="bg-zinc-950 min-h-screen py-20 animate-in fade-in duration-500">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="text-center mb-16">
        <h1 className="text-4xl md:text-5xl font-extrabold text-white uppercase tracking-tighter mb-4">
          Training <span className="text-orange-500">Insights</span>
        </h1>
        <p className="text-zinc-400 max-w-2xl mx-auto text-lg">
          Tips, tricks, and science-backed advice from Connor and Leah to help you optimize your training and nutrition.
        </p>
      </div>

      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        {BLOG_POSTS.map((post) => (
          <div key={post.id} className="bg-zinc-900 border border-zinc-800 hover:border-orange-500 transition-colors group cursor-pointer flex flex-col h-full">
            <div className="h-56 overflow-hidden">
              <img 
                src={post.image} 
                alt={post.title} 
                className="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700"
              />
            </div>
            <div className="p-6 flex flex-col flex-grow">
              <div className="flex items-center justify-between text-xs text-orange-500 mb-3 uppercase tracking-wider font-semibold">
                <span>{post.author}</span>
                <span>{post.date}</span>
              </div>
              <h3 className="text-xl font-bold text-white mb-3 leading-tight group-hover:text-orange-500 transition-colors">
                {post.title}
              </h3>
              <p className="text-zinc-400 mb-6 flex-grow">
                {post.excerpt}
              </p>
              <div className="flex items-center text-white font-medium text-sm group-hover:text-orange-500 transition-colors">
                Read Article <ChevronRight className="h-4 w-4 ml-1" />
              </div>
            </div>
          </div>
        ))}
      </div>
    </div>
  </div>
);

const ShopPage = () => (
  <div className="bg-zinc-950 min-h-screen py-20 animate-in fade-in duration-500">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="text-center mb-16">
        <h1 className="text-4xl md:text-5xl font-extrabold text-white uppercase tracking-tighter mb-4">
          Digital <span className="text-orange-500">Programs</span>
        </h1>
        <p className="text-zinc-400 max-w-2xl mx-auto text-lg">
          Downloadable training guides, nutrition templates, and plans designed to accelerate your progress.
        </p>
      </div>

      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        {PRODUCTS.map((product) => (
          <div key={product.id} className="bg-zinc-900 border border-zinc-800 flex flex-col h-full group">
            <div className="relative h-64 overflow-hidden">
              <img 
                src={product.image} 
                alt={product.title} 
                className="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
              />
              <div className="absolute top-4 right-4 bg-orange-500 text-white text-xs font-bold px-3 py-1 uppercase tracking-wider">
                {product.type}
              </div>
            </div>
            <div className="p-6 flex flex-col flex-grow">
              <h3 className="text-lg font-bold text-white mb-2 leading-tight uppercase">
                {product.title}
              </h3>
              <p className="text-zinc-400 text-sm mb-6 flex-grow">
                {product.description}
              </p>
              <div className="flex items-center justify-between mt-auto">
                <span className="text-2xl font-black text-white">
                  ${product.price}
                </span>
                <button 
                  className="bg-zinc-800 hover:bg-orange-500 text-white p-3 transition-colors flex items-center justify-center group/btn"
                  title="Add to cart"
                >
                  <ShoppingCart className="h-5 w-5" />
                </button>
              </div>
            </div>
          </div>
        ))}
      </div>
    </div>
  </div>
);

// --- MAIN APP ---

export default function App() {
  const [currentPage, setCurrentPage] = useState('home');

  const renderPage = () => {
    switch (currentPage) {
      case 'home':
        return <HomePage setCurrentPage={setCurrentPage} />;
      case 'about':
        return <AboutPage />;
      case 'blog':
        return <BlogPage />;
      case 'shop':
        return <ShopPage />;
      default:
        return <HomePage setCurrentPage={setCurrentPage} />;
    }
  };

  return (
    <div className="min-h-screen bg-zinc-950 text-zinc-50 font-sans selection:bg-orange-500 selection:text-white">
      <Navbar currentPage={currentPage} setCurrentPage={setCurrentPage} />
      <main>
        {renderPage()}
      </main>
      <Footer />
    </div>
  );
}
