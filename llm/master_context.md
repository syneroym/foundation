“I’m starting a new project. This is the master context. Treat it as canonical.

#Goal#
- Need to build an ecosystem that allows people or organizations to interact and transact with each other directly p2p, via diverse mini apps housed in a covering superapp.

#Constraints#
- Mini-apps can have UI as well as backend logic, need ability to run both. 
- Superapp should provide useful infrastructural support for mini app backends to use. For instance, Networking and Storage abstractions, Metering, Sharding, Search etc.
- Should be cross-platform
- Use state of art technology, even bleeding edge if promising.
- Chat, social networking and ecommerce features are core to the superapp.
- All interactions should be p2p without centralized servers with very few exceptions where completely unavoidable.
- Data sharing ability across core and mini-apps considering tunable Access control
- Highly performant and secure core that mini-apps can also leverage

#Related software to borrow ideas from if needed#
- WeChat: Chat and mini-apps. But unlike wechat, we want p2p
- Iroh: P2P  over QUIC
- Freenet: p2p over UDP, wasm based mini-apps/contracts
- Peertube: Media communication in browser over p2p
- ATProto, ActivityPub, Nostr, SSB: Social networking backbone
- Casbin: RBAC and ABAC

