1. What Is Observability?
  
            The mathematical definition of observability
            Applying observability to software systems
            Mischaracterizations of observability for software
            Why observability matters now
            Is this really the best way?
            Why are metrics and monitoring not enough?
            Debugging with metrics vs. observability
            The role of cardinality
            Debugging with observability
            Observability is for modern systems
    
2. How Observability Differs From Monitoring
  
            How monitoring data is used
            Troubleshooting behaviors when using dashboards
            The limitations of troubleshooting by intuition
            Traditional monitoring is fundamentally reactive
            How observability is different
    
3. Lessons From Scaling Without Observability
  
            An introduction to Parse
            Scaling at Parse
            The evolution toward modern systems
            The evolution toward modern practices
            Shifting practices at Parse
    
4. How Observability Relates To DevOps, SRE, And Cloud Native
  
            Cloud Native DevOps, and SRE in a nutshell
            Observability: Debugging Then vs. Now
            Observability empowers DevOps and SRE practices

5. Structured Events Are The Building Blocks Of Observability
  
            Debugging with structured events
            The limitations of metrics as a building block
            The limitations of unstructured data as a building block
            Properties of events that are useful in debugging
    
6. Stitching Events Into Traces
  
            Distributed tracing and why it matters now
            The components of tracing
            Instrumenting a trace the hard way
            Adding custom fields into trace spans
            Stitching events into traces
    
7. Analyzing Events To Achieve Observability
  
            Debugging from known conditions
            Debugging from first principles
            The core analysis loop
            Automating the brute force portion of the core analysis loop
            This misleading promise of AIOps
    
8. How Observability And Monitoring Come Together
  
            Where Monitoring Fits
            Infrastructure Considerations vs. Software Considerations
            Assessing Your Organizational Needs
            Exceptions: Infrastructure Monitoring That Can’t Be Ignored
            Real World Examples
    
9. Applying Observability Practices In Your Team
  
            Join a community group
            Start with the biggest pain points
            Buy instead of build
            Flesh out your instrumentation iteratively
            Look for opportunities to leverage existing efforts
            The last push is the hardest to complete
    
10. Observability-Driven Development
  
            Test-driven development
            Observability in the development cycle
            Determining where to debug
            Debugging in the time of microservices
            How instrumentation drives observability
            Shifting observability left

11. Using Service Level Objectives For Reliability
  
            Introduction to Service Level Objectives
            Traditional Monitoring Approaches Create Dangerous Alert Fatigue
            Distributed Systems Exacerbate the Alerting Problem
            Static Thresholds Can’t Reliably Indicate Degraded User Experience
            Reliable Alerting with SLOs
            Changing Culture Toward SLO-Based Alerts: A Case Study
    
12. Using Observability Data To Model Actionable SLOs
  
            Alerting before your error budget is empty
            Framing time as a sliding window
            Forecast models to create a predictive burn alert
            The lookahead window
            The baseline window
            Acting on SLO burn alerts
            Observability data for SLOs vs. time series data
    
13. Cheap And Accurate Enough: Sampling
  
            Sampling to refine your data collection
            Different approaches to sampling
            Constant-probability sampling
            Sampling on recent traffic volume
            Sampling based on event content (keys)
            Combining per-key and historical methods
            Choosing dynamic sampling options
            When to make a sampling decision for traces
            Translating sampling strategies into code
            The base case
            Fixed-rate sampling
            Recording the sample rate
            Consistent sampling
            Target Rate Sampling
            Having more than one static sample rate
            Sampling by key and target rate
            Sampling with dynamic rates on arbitrarily many keys
            Putting it all together: head and tail per-key target rate sampling
    
14. The Business Case For Observability
  
            The reactive approach to introducing change
            The proactive approach to introducing change
            Introducing observability as a practice
            Using the appropriate tools
            Instrumentation
            Data storage and analytics
            Rolling out tools to your teams
            Knowing when you have enough observability
    
15. An Observability Maturity Model
  
            A foreword about maturity models
            Why observability needs a maturity model
            About the Observability Maturity Model
            Capabilities referenced in the OMM
            Respond to system failure with resilience
            Deliver high quality code
            Manage complexity and technical debt
            Release on a predictable cadence
            Understand user behavior
            Using the OMM for your organization