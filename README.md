import React from 'react';
import { Card, CardContent } from '@/components/ui/card';
import { Button } from '@/components/ui/button';
import { Linkedin, Mail } from 'lucide-react';

const Home = () => {
  return (
    <div className="min-h-screen bg-gray-100 p-6">
      <div className="max-w-3xl mx-auto">
        <Card className="p-6 bg-white rounded-2xl shadow-lg">
          <h1 className="text-4xl font-bold mb-4">Harsh Soni</h1>
          <p className="text-lg mb-4">Data Analyst with 3.8 years of experience in data analytics, data modeling, and business intelligence.</p>
          <div className="flex gap-4 mb-4">
            <Button variant="outline" className="flex items-center gap-2">
              <Linkedin />
              <a href="https://www.linkedin.com/in/harshsoni1735/" target="_blank">LinkedIn</a>
            </Button>
            <Button variant="outline" className="flex items-center gap-2">
              <Mail />
              <a href="mailto:harshsoni1735@example.com">Email</a>
            </Button>
          </div>
          <h2 className="text-2xl font-semibold mb-2">Skills</h2>
          <ul className="list-disc pl-6 mb-4">
            <li>Power BI</li>
            <li>SQL</li>
            <li>Data Modeling</li>
            <li>DAX</li>
            <li>Business Intelligence</li>
          </ul>
          <h2 className="text-2xl font-semibold mb-2">Projects</h2>
          <ul className="list-disc pl-6">
            <li>Sales Analysis Dashboard</li>
            <li>Customer Segmentation Model</li>
            <li>Financial Performance Tracker</li>
          </ul>
        </Card>
      </div>
    </div>
  );
};

export default Home;

