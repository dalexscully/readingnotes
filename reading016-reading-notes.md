# Serverless Functions

<hr>

## Links and Resources

- [What is Serverless Computing](https://www.ibm.com/topics/serverless)
- [venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)
- [Vercel - Get Started](https://vercel.com/docs/concepts/get-started/deploy)
- [http.server](https://pymotw.com/3/http.server/index.html)
- [Requests){:target="_blank"}](https://canvas.instructure.com/courses/5755799/assignments/33981353/submissions/35370932)
- [Python & APIs](https://realpython.com/python-api/)
- [What is Serverless?](https://www.youtube.com/watch?v=vxJobGtqKVM)
- [Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)
-[Effective Python Environment](https://vercel.com/docs/concepts/functions/serverless-functions)

<hr>

## Serverless

Serverless is “a cloud computing application development and execution model that enables developers to build and run application code without provisioning or managing servers or backend infrastructure.”

This lets developers focus on the front-end of their application. This application code gets deployed to containers, which are managed by a cloud service provider. The cloud provider handles all routine infrastructure management and maintenance, including security.

Payment is based exclusively on actual execution time and resources.

- serverless can “scale to zero” when program execution stops, so developers don’t get billed for idle time.

Serverless refers to the developer’s perspective of not having to manage a server. All major cloud service providers offer a serverless platform.

“Together serverless computing, microservices and containers form a triumvirate of technologies typically considered to be at the core of cloud-native application development.”

Serverless is based on the FaaS model (function-as-a-service), which is a cloud computing service that allows developers to run code or containers in response to events and requests without having to manage a backend or any infrastructure required to actually run the code.

But serverless has features beyond FaaS, including serverless databases and storage that scale linearly with demand, event streaming and messaging, and API gateways (proxies for web actions).

Compared to PaaS (platform-as-a-service), containers, and virtual machines, serverless has less provisioning time, lower administrative burden, no maintenance, auto-scaling all the way down to zero, no capacity planning requirement, statelessness, high availability and disaster recovery, and resource and billing efficiency.

Kubernetes requires cloud provider-specific software to run serverless apps. Knative is an open source serverless framework for Kubernetes “that enables any container to run as a serverless workload on any cloud platform that runs Kubernetes.” Knative handles network routing, event triggers, and autoscaling for serverless apps.

## Serverless Pros:

- Higher developer productivity
pay for execution only/cost effective
Support many languages
- Streamlines development cycle and DevOps
Provide visibility into system and usage

Serverless Cons:

- Too much latency for certain apps
- Higher costs for stable/predictable workload
- Can make monitoring and debugging more difficult
Vendor lock-in. 

- potentially difficult to migrate to new cloud provider.

<hr>