# Choose local vs cloud

## Prefer local when

- privacy and offline operation matter
- the task fits available hardware
- recurring API costs are undesirable
- you need control over the runtime and model

## Prefer cloud when

- the task needs a model that is too large for the device
- the device is too slow for the workload
- you need a managed service
- a provider offers capabilities your local stack does not

## Hybrid is often best

Use a small local model for routine work and route difficult tasks to a stronger model. Keep the routing policy explicit so sensitive data is not sent to a cloud provider accidentally.

A good router can consider task type, latency, cost, context size, privacy requirements, and model reliability.
