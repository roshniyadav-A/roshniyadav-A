export default function Portfolio() {
  return (
    <div className="min-h-screen bg-white text-gray-900 font-sans">

      {/* HERO SECTION */}
      <section className="text-center py-20 px-6 bg-gradient-to-r from-pink-50 to-blue-50">
        <h1 className="text-4xl font-bold">🌸 Roshni Yadav</h1>
        <p className="text-xl mt-3 text-gray-700">
          Business & Data Analyst
        </p>
        <p className="mt-4 max-w-2xl mx-auto text-gray-600">
          Data-driven thinker passionate about turning raw data into meaningful
          business insights and supporting smarter decision-making.
        </p>

        <div className="mt-6 flex justify-center gap-4">
          <span className="px-4 py-2 bg-white shadow rounded-full">Excel</span>
          <span className="px-4 py-2 bg-white shadow rounded-full">Power BI</span>
          <span className="px-4 py-2 bg-white shadow rounded-full">Python</span>
          <span className="px-4 py-2 bg-white shadow rounded-full">SQL</span>
        </div>
      </section>

      {/* ABOUT SECTION */}
      <section className="py-16 px-6 max-w-5xl mx-auto">
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p className="text-gray-700 leading-relaxed">
          I enjoy working at the intersection of business and data analytics.
          My focus is on identifying trends, solving real-world problems, and
          creating clear insights that help in better business decisions.
        </p>
      </section>

      {/* SKILLS SECTION */}
      <section className="py-16 px-6 bg-gray-50">
        <h2 className="text-2xl font-semibold text-center mb-10">Skills</h2>

        <div className="grid md:grid-cols-3 gap-6 max-w-5xl mx-auto">
          <div className="p-6 bg-white shadow rounded-xl">
            <h3 className="font-semibold mb-2">Data Analytics</h3>
            <p className="text-sm text-gray-600">
              Data Cleaning, Data Modeling, Insight Generation
            </p>
          </div>

          <div className="p-6 bg-white shadow rounded-xl">
            <h3 className="font-semibold mb-2">Visualization</h3>
            <p className="text-sm text-gray-600">
              Power BI Dashboards, Matplotlib, Reporting
            </p>
          </div>

          <div className="p-6 bg-white shadow rounded-xl">
            <h3 className="font-semibold mb-2">Business Thinking</h3>
            <p className="text-sm text-gray-600">
              KPI Analysis, Sales Insights, Decision Support
            </p>
          </div>
        </div>
      </section>

      {/* PROJECTS SECTION */}
      <section className="py-16 px-6 max-w-5xl mx-auto">
        <h2 className="text-2xl font-semibold mb-8 text-center">Projects</h2>

        <div className="space-y-6">

          <div className="p-6 border rounded-xl shadow-sm">
            <h3 className="font-semibold">🌸 FNP Sales Analysis (Excel)</h3>
            <p className="text-gray-600 text-sm mt-2">
              Sales performance, customer behavior, and delivery insights using
              Power Query, Pivot Tables, and dashboards.
            </p>
          </div>

          <div className="p-6 border rounded-xl shadow-sm">
            <h3 className="font-semibold">🌍 Airbnb Global Dashboard (Power BI)</h3>
            <p className="text-gray-600 text-sm mt-2">
              Market share, pricing strategy, customer satisfaction, and global
              listing analysis through interactive dashboards.
            </p>
          </div>

        </div>
      </section>

      {/* MINDSET SECTION */}
      <section className="py-16 px-6 bg-gray-50 text-center">
        <h2 className="text-2xl font-semibold mb-4">Mindset</h2>
        <p className="text-gray-700 max-w-2xl mx-auto">
          Curious about patterns, focused on insights, and driven by clarity.
          I believe data tells a story — it just needs the right interpretation.
        </p>
      </section>

      {/* FOOTER */}
      <footer className="py-10 text-center text-gray-600 text-sm">
        <p>Let’s connect and build data-driven solutions together 🚀</p>
        <p className="mt-2">
          © 2026 Roshni Yadav | Business & Data Analyst
        </p>
      </footer>

    </div>
  );
}
