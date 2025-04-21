import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import Image from "next/image";

export default function ShyannsDaycare() {
  return (
    <div className="p-6 space-y-8">
      <div className="text-center">
        <Image
          src="/shyanns-logo.png"
          alt="Shyann's Daycare Logo"
          width={150}
          height={150}
          className="mx-auto"
        />
        <h1 className="text-4xl font-bold mt-4">Shyann's Daycare</h1>
        <p className="text-lg max-w-2xl mx-auto mt-2">
          A warm, at-home childcare space offering a safe and loving environment
          for children to learn and play. Open from 7 AM to 5 PM, we support
          busy families with full-day care focused on fun, growth, and early
          education.
        </p>
      </div>

      <Card className="max-w-4xl mx-auto">
        <CardContent className="space-y-4 p-6">
          <h2 className="text-2xl font-semibold">Our Program</h2>
          <p>
            Each day is filled with a balance of structured learning time,
            creative play, and hands-on activities that support social,
            emotional, and cognitive development. We enjoy walks to nearby
            parks, and offer cozy nap times for rest and recharge.
          </p>
          <p>
            From ABCs and 123s to arts, music, and movement, we offer a variety
            of educational activities in a homey setting where every child feels
            like family.
          </p>
        </CardContent>
      </Card>

      <Card className="max-w-4xl mx-auto">
        <CardContent className="p-6 space-y-4">
          <h2 className="text-2xl font-semibold">Prices</h2>
          <ul className="list-disc pl-6 space-y-2 text-lg">
            <li>1 Day - $60</li>
            <li>3 Day Package - $170</li>
            <li>5 Day Package - $280</li>
          </ul>
        </CardContent>
      </Card>

      <div className="text-center">
        <a href="/Shyanns_Daycare_Application_250421_144728.pdf" target="_blank">
          <Button className="mt-4">Download Enrollment Application</Button>
        </a>
      </div>
    </div>
  );
}
