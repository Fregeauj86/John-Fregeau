import React from 'react';


const Portfolio = () => {
  return (
    <div className='min-h-screen bg-gray-100 p-4'>
      <header className='text-center py-10'>
        <h1 className='text-4xl font-bold mb-2'>John Fregeau</h1>
        <p className='text-lg text-gray-600'>Cybersecurity Specialist & IT Support Professional</p>
      </header>

      <section className='max-w-4xl mx-auto mb-10'>
        <h2 className='text-3xl font-bold mb-4'>About Me</h2>
        <p className='text-gray-700 leading-relaxed'>
          I am currently pursuing a Master’s in Cybersecurity and Information Assurance, with plans to continue my journey with a PhD in Cyber Defense. 
          Growing up surrounded by technology, inspired by my grandfather, I developed a passion for understanding how systems work and how to protect them. 
          I am driven to use my education and skills to defend against cyber threats and contribute to a safer digital future.
        </p>
      </section>

      <section className='max-w-4xl mx-auto mb-10'>
        <h2 className='text-3xl font-bold mb-4'>Skills</h2>
        <ul className='list-disc list-inside text-gray-700'>
          <li>Cybersecurity & PenTesting</li>
          <li>SQL, C++, Java, Python</li>
          <li>Technical Troubleshooting & IT Support</li>
          <li>Digital Marketing & Web Design</li>
        </ul>
      </section>

      <section className='max-w-4xl mx-auto mb-10'>
        <h2 className='text-3xl font-bold mb-4'>Projects</h2>
        <div className='bg-white shadow rounded p-4 mb-4'>
            <h3 className='text-2xl font-semibold'>PenTesting on TryHackMe</h3>
            <p className='text-gray-700'>Practiced penetration testing methodologies and enhanced security skills through various challenges.</p>
          </div>
        <div className='bg-white shadow rounded p-4 mb-4'>
            <h3 className='text-2xl font-semibold'>Responsive Web Design</h3>
            <p className='text-gray-700'>Developed responsive websites, showcasing modern design and usability practices.</p>
          </div>
      </section>

      <section className='max-w-4xl mx-auto mb-10'>
        <h2 className='text-3xl font-bold mb-4'>Contact</h2>
        <div className='flex space-x-4'>
          <a href='mailto:[YourEmail]' className='text-blue-500 hover:underline'>Email Me</a>
          <a href='https://www.linkedin.com/in/[YourLinkedIn]' target='_blank' className='text-blue-500 hover:underline'>LinkedIn</a>
        </div>
      </section>
    </div>
  );
};

export default Portfolio;
